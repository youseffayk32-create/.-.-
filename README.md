<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>القرآن الكريم - Youssef Fayek</title>
<style>
body{margin:0;background:#000;color:#fff;font-family:Arial;text-align:center}
.header{background:#111;padding:15px;border-bottom:2px solid #C9A86A}
.gold{color:#C9A86A}
.search{width:90%;padding:12px;border-radius:20px;border:1px solid #C9A86A;background:#111;color:#fff;margin:15px}
.surah{background:#111;border-right:4px solid #C9A86A;padding:14px;margin:8px 12px;border-radius:12px;text-align:right;cursor:pointer;display:flex;justify-content:space-between}
.quran-page{display:none;background:#0f0f0f;margin:12px;border:1.5px solid #C9A86A;border-radius:15px;padding:20px}
.ayah{font-size:28px;line-height:2.4;padding:12px 0;border-bottom:1px solid #222}
.num{color:#C9A86A;font-size:16px;margin-right:8px;border:1px solid #C9A86A;border-radius:50%;width:34px;height:34px;display:inline-flex;align-items:center;justify-content:center}
.basmala{font-size:30px;color:#C9A86A;margin:15px 0}
.tafsir{font-size:14px;color:#aaa;background:#1a1a1a;padding:10px;border-radius:10px;margin:5px 0 15px;text-align:right;line-height:1.8;display:none}
.btn-small{background:#222;color:#C9A86A;border:1px solid #C9A86A;padding:7px 12px;border-radius:20px;cursor:pointer;font-size:12px;margin:2px}
.admin-btn{display:none}
.exit-btn{position:fixed;bottom:20px;right:20px;background:#222;color:#C9A86A;border:1px solid #C9A86A;padding:12px 18px;border-radius:25px;font-weight:bold;font-size:14px;cursor:pointer;z-index:10}
.modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.9);z-index:100;padding:20px}
.box{background:#111;border:1.5px solid #C9A86A;border-radius:15px;padding:20px;margin-top:50px}
input{padding:10px;border-radius:12px;border:1px solid #C9A86A;background:#000;color:#fff;width:80%;margin:10px}
.btn{background:#C9A86A;color:#000;border:none;padding:12px 24px;border-radius:20px;font-weight:bold;cursor:pointer}
select{padding:7px;border-radius:20px;background:#000;color:#C9A86A;border:1px solid #C9A86A}
#audioBox{display:none;background:#1a1a1a;border:1px solid #C9A86A;border-radius:15px;padding:10px;margin:10px 0}
</style>
</head>
<body>
<div class="header">
<h2 id="secretTitle" class="gold" style="margin:0">القرآن الكريم</h2>
<p style="margin:5px 0 0 0;color:#777;font-size:12px">كامل 114 سورة - </p>
</div>
<input type="text" id="search" class="search" placeholder="ابحث... الفاتحة، البقرة، الكهف...">
<div id="list"></div>
<div id="page" class="quran-page">
<div>
<button class="btn-small" onclick="changeFont(2)">تكبير +</button>
<button class="btn-small" onclick="changeFont(-2)">تصغير -</button>
<button class="btn-small" onclick="toggleTafsir()">تفسير / اخفاء</button>
<button class="btn-small" onclick="playAudio()">تشغيل الصوت - فارس عباد</button>
<button class="btn-small" onclick="stopAudio()">ايقاف</button>
<br><br>
<select id="reciterSelect" onchange="changeReciter()">
<option value="fares" selected>الشيخ فارس عباد</option>
<option value="alafasy">الشيخ مشاري العفاسي</option>
<option value="basit">الشيخ عبد الباسط</option>
<option value="husary">الشيخ محمود الحصري</option>
<option value="minshawi">الشيخ المنشاوي</option>
</select>
</div>
<div id="audioBox">
<p id="audioStatus" style="color:#C9A86A;font-size:13px;margin:5px">جاهز للتشغيل</p>
<audio id="audioPlayer" controls preload="none" style="width:100%"></audio>
</div>
<h3 id="surahTitle" class="gold"></h3>
<p id="meta" style="color:#888;font-size:13px"></p>
<p id="loading" style="color:#C9A86A">جاري تحميل السورة...</p>
<div id="surahText"></div>
<br><button class="btn" onclick="closePage()">رجوع</button>
</div>
<button class="admin-btn" id="openAdmin">👑</button>
<button class="exit-btn" onclick="exitApp()">خروج</button>
<div id="adminModal" class="modal">
<div class="box">
<h3 class="gold">دخول الأدمن</h3>
<div id="loginArea"><input type="password" id="pass" placeholder="الباسورد"><br><button class="btn" id="login">دخول</button></div>
<div id="adminArea" style="display:none;text-align:right"><p>اهلا يا يوسف</p><p>السور المقروءة: <span id="readCount">0</span></p><p>اخر سورة: <span id="lastSurah">-</span></p></div>
<br><button class="btn" style="background:#222;color:#fff" onclick="closeAdmin()">اغلاق</button>
</div>
</div>
<script>
var surahs = ["الفاتحة","البقرة","آل عمران","النساء","المائدة","الأنعام","الأعراف","الأنفال","التوبة","يونس","هود","يوسف","الرعد","إبراهيم","الحجر","النحل","الإسراء","الكهف","مريم","طه","الأنبياء","الحج","المؤمنون","النور","الفرقان","الشعراء","النمل","القصص","العنكبوت","الروم","لقمان","السجدة","الأحزاب","سبأ","فاطر","يس","الصافات","ص","الزمر","غافر","فصلت","الشورى","الزخرف","الدخان","الجاثية","الأحقاف","محمد","الفتح","الحجرات","ق","الذاريات","الطور","النجم","القمر","الرحمن","الواقعة","الحديد","المجادلة","الحشر","الممتحنة","الصف","الجمعة","المنافقون","التغابن","الطلاق","التحريم","الملك","القلم","الحاقة","المعارج","نوح","الجن","المزمل","المدثر","القيامة","الإنسان","المرسلات","النبأ","النازعات","عبس","التكوير","الانفطار","المطففين","الانشقاق","البروج","الطارق","الأعلى","الغاشية","الفجر","البلد","الشمس","الليل","الضحى","الشرح","التين","العلق","القدر","البينة","الزلزلة","العاديات","القارعة","التكاثر","العصر","الهمزة","الفيل","قريش","الماعون","الكوثر","الكافرون","النصر","المسد","الإخلاص","الفلق","الناس"];
var read = 0;
var currentNum = 1;
var fontSize = 28;
var showTafsir = false;
var tafsirData = [];
var audioTry = 0;
var audioList = [];
if(localStorage.getItem("YF_read")){ read = parseInt(localStorage.getItem("YF_read")); }
function pad3(n){ var s = "" + n; while(s.length < 3){ s = "0" + s; } return s; }
function render(f){
  if(!f){ f = ""; }
  var listDiv = document.getElementById("list");
  listDiv.innerHTML = "";
  for(var i=0;i<surahs.length;i++){
    if(f !== "" && surahs[i].indexOf(f) === -1){ continue; }
    var d = document.createElement("div");
    d.className = "surah";
    d.innerHTML = "<span>" + (i+1) + ". سورة " + surahs[i] + "</span><span>📖</span>";
    d.setAttribute("data-num", i+1);
    d.setAttribute("data-name", surahs[i]);
    d.onclick = function(){ openSurah(parseInt(this.getAttribute("data-num")), this.getAttribute("data-name")); };
    listDiv.appendChild(d);
  }
}
render("");
document.getElementById("search").oninput = function(){ render(this.value); };
function openSurah(num, name){
  currentNum = num;
  document.getElementById("list").style.display = "none";
  document.getElementById("search").style.display = "none";
  document.getElementById("page").style.display = "block";
  document.getElementById("surahTitle").innerText = "سورة " + name;
  document.getElementById("surahText").innerHTML = "";
  document.getElementById("loading").style.display = "block";
  document.getElementById("loading").innerText = "جاري تحميل السورة...";
  stopAudioSilent();
  fetch("https://api.alquran.cloud/v1/surah/" + num + "/editions/quran-uthmani,ar.muyassar")
  .then(function(res){ return res.json(); })
  .then(function(data){
    var quranData = data.data[0];
    var tafsirAll = data.data[1];
    tafsirData = [];
    for(var k=0;k<tafsirAll.ayahs.length;k++){ tafsirData.push(tafsirAll.ayahs[k].text); }
    showAyahs(quranData, quranData.ayahs, name);
  })
  .catch(function(){ document.getElementById("loading").innerText = "النت ضعيف - افتح النت وحاول تاني"; });
  window.scrollTo(0,0);
}
function showAyahs(data, ayahs, name){
  var html = "";
  if(currentNum !== 1 && currentNum !== 9){ html += '<div class="basmala">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</div>'; }
  for(var i=0;i<ayahs.length;i++){
    var text = ayahs[i].text;
    if(i===0 && currentNum !== 1){ text = text.replace("بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ","").trim(); }
    html += '<div class="ayah" style="font-size:' + fontSize + 'px">' + text + ' <span class="num">' + ayahs[i].numberInSurah + '</span></div>';
    if(tafsirData[i]){
      var disp = showTafsir ? "block" : "none";
      html += '<div class="tafsir" style="display:' + disp + '">التفسير الميسر: ' + tafsirData[i] + '</div>';
    }
  }
  document.getElementById("surahText").innerHTML = html;
  var type = "مدنية";
  if(data.revelationType === "Meccan"){ type = "مكية"; }
  document.getElementById("meta").innerText = type + " - عدد الآيات: " + data.numberOfAyahs;
  document.getElementById("loading").style.display = "none";
  read = read + 1;
  localStorage.setItem("YF_read", read);
  document.getElementById("readCount").innerText = read;
  document.getElementById("lastSurah").innerText = name;
  localStorage.setItem("YF_last", name);
}
function closePage(){
  document.getElementById("page").style.display = "none";
  document.getElementById("list").style.display = "block";
  document.getElementById("search").style.display = "block";
  stopAudioSilent();
}
function exitApp(){
  closePage();
  document.getElementById("adminModal").style.display = "none";
  document.getElementById("search").value = "";
  render("");
  window.scrollTo(0,0);
}
function closeAdmin(){ document.getElementById("adminModal").style.display = "none"; }
function changeFont(d){
  fontSize = fontSize + d;
  if(fontSize < 18){ fontSize = 18; }
  if(fontSize > 44){ fontSize = 44; }
  var els = document.querySelectorAll(".ayah");
  for(var i=0;i<els.length;i++){ els[i].style.fontSize = fontSize + "px"; }
}
function toggleTafsir(){
  showTafsir = !showTafsir;
  var els = document.querySelectorAll(".tafsir");
  for(var i=0;i<els.length;i++){ els[i].style.display = showTafsir ? "block" : "none"; }
}
function changeReciter(){}
function getAudioList(rec, num){
  var n = pad3(num);
  if(rec === "fares"){
    return [
      "https://server8.mp3quran.net/afs/" + n + ".mp3",
      "https://download.quranicaudio.com/quran/fares_abbad/" + n + ".mp3",
      "https://everyayah.com/data/Fares_Abbad_64/" + n + "001.mp3"
    ];
  }
  if(rec === "alafasy"){
    return [
      "https://cdn.islamic.network/quran/audio-surah/128/ar.alafasy/" + num + ".mp3",
      "https://server8.mp3quran.net/afs/" + n + ".mp3",
      "https://download.quranicaudio.com/quran/mishaari_raashid_al_3afaasee/" + n + ".mp3"
    ];
  }
  if(rec === "basit"){
    return ["https://cdn.islamic.network/quran/audio-surah/128/ar.abdulbasitmurattal/" + num + ".mp3"];
  }
  if(rec === "husary"){
    return ["https://cdn.islamic.network/quran/audio-surah/128/ar.husary/" + num + ".mp3"];
  }
  if(rec === "minshawi"){
    return ["https://cdn.islamic.network/quran/audio-surah/128/ar.minshawi/" + num + ".mp3"];
  }
  return ["https://cdn.islamic.network/quran/audio-surah/128/ar.alafasy/" + num + ".mp3"];
}
function tryPlayNext(){
  var audio = document.getElementById("audioPlayer");
  var status = document.getElementById("audioStatus");
  if(audioTry >= audioList.length){
    status.innerText = "السيرفر مشغول - جرب دوس تشغيل تاني او غير الشيخ";
    return;
  }
  var url = audioList[audioTry];
  status.innerText = "جاري تحميل الصوت... محاولة " + (audioTry + 1);
  audio.src = url;
  audio.load();
  var p = audio.play();
  if(p){ p.catch(function(){ }); }
}
function playAudio(){
  var audio = document.getElementById("audioPlayer");
  var box = document.getElementById("audioBox");
  var rec = document.getElementById("reciterSelect").value;
  box.style.display = "block";
  audio.pause();
  audioTry = 0;
  audioList = getAudioList(rec, currentNum);
  tryPlayNext();
}
function stopAudio(){
  var audio = document.getElementById("audioPlayer");
  audio.pause();
  document.getElementById("audioStatus").innerText = "تم الايقاف";
}
function stopAudioSilent(){
  var audio = document.getElementById("audioPlayer");
  if(audio){ audio.pause(); }
  var box = document.getElementById("audioBox");
  if(box){ box.style.display = "none"; }
}
var secretClicks = 0;
var secretTimer = null;
document.getElementById("secretTitle").onclick = function(){
  secretClicks++;
  if(secretTimer){ clearTimeout(secretTimer); }
  secretTimer = setTimeout(function(){ secretClicks = 0; }, 2000);
  if(secretClicks >= 5){
    secretClicks = 0;
    document.getElementById("adminModal").style.display = "block";
    document.getElementById("readCount").innerText = read;
    var last = localStorage.getItem("YF_last");
    if(!last){ last = "-"; }
    document.getElementById("lastSurah").innerText = last;
  }
};
document.getElementById("login").onclick = function(){
  var realPass = String.fromCharCode(89,111,117,115,115,101,102,35,81,117,114,97,110,95,50,48,50,54,33,57,88,122);
  if(document.getElementById("pass").value === realPass){
    document.getElementById("loginArea").style.display = "none";
    document.getElementById("adminArea").style.display = "block";
  } else { alert("الباسورد غلط"); }
};
document.getElementById("readCount").innerText = read;
var aud = document.getElementById("audioPlayer");
aud.addEventListener("error", function(){
  audioTry = audioTry + 1;
  if(audioTry < audioList.length){ tryPlayNext(); }
});
aud.addEventListener("playing", function(){ document.getElementById("audioStatus").innerText = "شغال الآن - الشيخ فارس عباد"; });
</script>
</body>
</html>
