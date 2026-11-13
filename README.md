<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YF SolveX - منهج أولى ثانوي كامل</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0;font-family:'Cairo',sans-serif}
body{background:#0f172a;color:#fff;min-height:100vh;padding-bottom:40px}
header{position:fixed;top:0;right:0;left:0;background:#0f172a;border-bottom:1px solid #1e293b;padding:10px 16px;z-index:100;text-align:center}
header b{font-size:20px} header b span{color:#22d3ee}
header small{display:block;color:#94a3b8;font-size:12px;margin-top:2px}
header small b{color:#fde047;font-size:12px}
.top{padding:110px 14px 20px;max-width:750px;margin:0 auto}
.hero{background:linear-gradient(135deg,#0ea5e9,#7c3aed,#ec4899);border-radius:24px;padding:18px;text-align:center}
.hero h2{font-size:21px;line-height:1.5} .hero p{color:#e0f2fe;font-size:13px;margin-top:5px}
.creator{background:#1e293b;border:1px solid #22d3ee;border-radius:14px;padding:12px;text-align:center;margin:12px 0;line-height:1.8}
.creator b{color:#22d3ee} .creator span{color:#fde047}
.lang-box{background:#1e293b;border:1px solid #22d3ee;border-radius:20px;padding:16px;margin-top:12px}
.lang-box h3{color:#22d3ee;margin-bottom:10px}
.lang-row{display:flex;align-items:center;gap:12px;margin-bottom:12px;background:#0f172a;border:1px solid #334155;border-radius:16px;padding:12px}
.lang-img{width:58px;height:58px;border-radius:14px;display:grid;place-items:center;font-size:26px;font-weight:900;flex-shrink:0}
.lang-info{flex:1} .bar{height:12px;background:#1e293b;border-radius:20px;overflow:hidden;margin-top:5px} .bar div{height:100%;border-radius:20px}
.lang-pct{font-size:18px;font-weight:900;color:#fde047}
.tabs{display:flex;gap:8px;margin-top:12px;flex-wrap:wrap}
.tabs button{flex:1;padding:12px;border:none;border-radius:14px;font-weight:900;cursor:pointer;background:#1e293b;color:#cbd5e1;border:1px solid #334155;min-width:100px}
.tabs button.active{background:#22d3ee;color:#0f172a}
.card{background:#1e293b;border:1px solid #334155;border-radius:20px;padding:16px;margin-top:14px}
.card h3{color:#22d3ee;margin-bottom:4px} .card p{color:#94a3b8;font-size:12px;margin-bottom:12px}
.row{display:flex;gap:8px;margin-bottom:10px;align-items:center}
.row label{font-size:13px;font-weight:700;min-width:78px;color:#cbd5e1}
.row input{flex:1;padding:12px;border-radius:12px;border:1px solid #334155;background:#0f172a;color:#fff;font-size:16px;outline:none;min-width:0}
.row select{width:112px;padding:12px;border-radius:12px;border:1px solid #22d3ee;background:#0f172a;color:#fff;font-weight:700;outline:none;flex-shrink:0}
.btn{width:100%;padding:13px;border:none;border-radius:12px;background:#22d3ee;color:#0f172a;font-weight:900;font-size:16px;cursor:pointer}
.btn2{background:#a78bfa}
.btn-orange{background:#f97316;color:#fff}
.btn-red{background:#ef4444;color:#fff}
.result{background:#0f172a;border:1px solid #22d3ee;border-radius:14px;padding:12px;margin-top:12px;font-size:16px;line-height:1.8;color:#a5f3fc;display:none}
.result b{color:#fde047}
.table{width:100%;border-collapse:collapse;font-size:13px;margin-top:8px}
.table td{border:1px solid #334155;padding:8px;text-align:center}
.table tr:first-child td{background:#0ea5e9;color:#fff;font-weight:900}
.foot{text-align:center;color:#94a3b8;font-size:12px;padding:18px;line-height:1.8}
.foot b{color:#22d3ee}
#adminDot{width:14px;height:14px;background:#ec4899;border-radius:50%;margin:18px auto 0;box-shadow:0 0 12px #ec4899;cursor:pointer}
#adminModal{position:fixed;inset:0;background:rgba(0,0,0,.8);display:none;place-items:center;z-index:200;padding:16px}
#adminBox{background:#1e293b;border:1px solid #22d3ee;border-radius:20px;padding:20px;width:100%;max-width:400px;text-align:center}
#adminBox h3{color:#22d3ee} #adminBox p{margin:10px 0;color:#cbd5e1}
#adminBox button{width:100%;padding:12px;border:none;border-radius:12px;background:#22d3ee;font-weight:900;margin-top:8px;cursor:pointer}
</style>
</head>
<body>
<header><div><b>YF <span>SolveX</span></b></div><small>تم إنشاء هذا الموقع من قبل الطالب <b>يوسف فايق</b> 👨‍🎓 | تحت إشراف مستر <b>أحمد حسن</b> 👨‍🏫</small></header>

<div class="top">
<div class="hero"><h2>منهج أولى ثانوي كامل 🚀</h2><p>تحويلات + قوانين فيزيا ورياضة - اكتب أي خانتين وهو يجيب التالتة</p></div>

<div class="creator">✨ تم إنشاء هذا الموقع من قبل الطالب <b>يوسف فايق</b> 👨‍🎓<br>تحت إشراف مستر <span>أحمد حسن</span> 👨‍🏫 ✨</div>

<div class="lang-box"><h3>👨‍💻 اللغات المستخدمة في بناء الموقع 💻</h3>
<div class="lang-row"><div class="lang-img" style="background:#f97316;color:#fff">html</div><div class="lang-info"><b>HTML - هيكل الموقع 🧱</b><div class="bar"><div style="width:38%;background:#f97316"></div></div></div><div class="lang-pct">38%</div></div>
<div class="lang-row"><div class="lang-img" style="background:#2563eb;color:#fff">css</div><div class="lang-info"><b>CSS - التصميم والألوان والجرافيك 🎨</b><div class="bar"><div style="width:27%;background:#22d3ee"></div></div></div><div class="lang-pct">27%</div></div>
<div class="lang-row"><div class="lang-img" style="background:#fde047;color:#000">jv</div><div class="lang-info"><b>JavaScript - الحل الذكي والتحويلات 🧠⚡</b><div class="bar"><div style="width:35%;background:#fde047"></div></div></div><div class="lang-pct">35%</div></div>
</div>

<div class="tabs">
<button id="tConv" class="active" onclick="showSec('conv')">🔄 التحويلات</button>
<button id="tPhys" onclick="showSec('phys')">⚡ فيزياء</button>
<button id="tMath" onclick="showSec('math')">📐 رياضة</button>
</div>

<!-- ============ التحويلات ============ -->
<div id="sec-conv">
<div class="card"><h3>🔄 محول شامل - تحويلات أولى ثانوي</h3><p>اكتب الرقم واختار من وحدة لـ وحدة، وهو يحول لوحده</p>
<div class="row"><label>الرقم</label><input id="c_val" type="number" placeholder="مثال: 72"></div>
<div class="row"><label>نوع التحويل</label><select id="c_type" style="flex:1" onchange="updateUnits()"><option value="length">📏 طول</option><option value="mass">⚖️ كتلة</option><option value="time">⏱️ زمن</option><option value="area">🟦 مساحة</option><option value="volume">🧊 حجم</option><option value="speed">🚀 سرعة</option><option value="force">💪 قوة</option><option value="energy">⚡ طاقة / شغل</option><option value="pressure">💧 ضغط</option></select></div>
<div class="row"><label>من</label><select id="c_from" style="flex:1"></select></div>
<div class="row"><label>إلى</label><select id="c_to" style="flex:1"></select></div>
<button class="btn btn2" onclick="doConvert()">حوّل الآن ✨</button><div class="result" id="rc"></div>
<table class="table">
<tr><td colspan="2">📚 جدول التحويلات المهمة في أولى ثانوي</td></tr>
<tr><td>1 كم = 1000 م</td><td>1 م = 100 سم = 1000 مم</td></tr>
<tr><td>1 ساعة = 60 د = 3600 ث</td><td>1 دقيقة = 60 ث</td></tr>
<tr><td>1 كجم = 1000 جم</td><td>1 طن = 1000 كجم</td></tr>
<tr><td>1 م² = 10000 سم²</td><td>1 م³ = 1000000 سم³ = 1000 لتر</td></tr>
<tr><td>1 كم/س = 0.277 م/ث</td><td>1 م/ث = 3.6 كم/س</td></tr>
<tr><td>1 نيوتن = كجم . م/ث²</td><td>1 جول = 1 نيوتن . متر</td></tr>
<tr><td>كثافة الماء = 1000 كجم/م³ = 1 جم/سم³</td><td>الحرارة النوعية للماء = 4186 جول/كجم.م°</td></tr>
</table>
</div>
</div>

<!-- ============ فيزياء ============ -->
<div id="sec-phys" style="display:none">

<!-- 1- الضغط -->
<div class="card"><h3>💧 1- الضغط والقوة والمساحة P = F ÷ A</h3><p>اكتب أي خانتين وهو يجيب التالتة</p>
<div class="row"><label>الضغط P</label><input id="p6_p" type="number" placeholder="فاضية = هتتحسب"><select id="p6_p_u"><option value="Pa" selected>باسكال</option><option value="kPa">كيلو باسكال</option></select></div>
<div class="row"><label>القوة F</label><input id="p6_f" type="number" placeholder="فاضية = هتتحسب"><select id="p6_f_u"><option value="N" selected>نيوتن</option><option value="kN">كيلو نيوتن</option></select></div>
<div class="row"><label>المساحة A</label><input id="p6_a" type="number" placeholder="فاضية = هتتحسب"><select id="p6_a_u"><option value="m2" selected>م²</option><option value="cm2">سم²</option></select></div>
<button class="btn" onclick="solve6()">احسب الناقص ✨</button><div class="result" id="r6"></div></div>

<!-- 2- الكثافة - اتنقلت بعد الضغط -->
<div class="card" style="border-color:#f97316"><h3>🧱 2- الكثافة ρ = m ÷ V</h3><p>اكتب أي خانتين وهو يجيب التالتة - كثافة المادة</p>
<div class="row"><label>الكثافة ρ</label><input id="p5_r" type="number" placeholder="فاضية = هتتحسب"><select id="p5_r_u"><option value="kgm3" selected>كجم/م³</option><option value="gcm3">جم/سم³</option></select></div>
<div class="row"><label>الكتلة m</label><input id="p5_m" type="number" placeholder="فاضية = هتتحسب"><select id="p5_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>الحجم V</label><input id="p5_v" type="number" placeholder="فاضية = هتتحسب"><select id="p5_v_u"><option value="m3" selected>م³</option><option value="cm3">سم³</option><option value="L">لتر</option></select></div>
<button class="btn" onclick="solve5()">احسب الناقص ✨</button><div class="result" id="r5"></div></div>

<!-- 3- كمية الحرارة -->
<div class="card" style="border-color:#f97316"><h3>🌡️ 3- كمية الحرارة Q = m × c × ΔT</h3><p>اكتب 3 خانات وسيب الرابعة فاضية</p>
<div class="row"><label>كمية الحرارة Q</label><input id="heat_q" type="number" placeholder="فاضية = هتتحسب"><select id="heat_q_u"><option value="J" selected>جول</option><option value="kJ">كيلو جول</option><option value="cal">كالوري</option></select></div>
<div class="row"><label>الكتلة m</label><input id="heat_m" type="number" placeholder="كجم"><select id="heat_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>الحرارة النوعية c</label><input id="heat_c" type="number" placeholder="جول/كجم.م°"><select><option>جول/كجم.م°</option></select></div>
<div class="row"><label>فرق الحرارة ΔT</label><input id="heat_dt" type="number" placeholder="م° - مثال: 20"><select><option>م° / كلفن</option></select></div>
<button class="btn btn-orange" onclick="solveHeat()">احسب الناقص 🔥</button><div class="result" id="rheat"></div>
<p style="margin-top:8px">مثال: ماء كتلته 2 كجم، حرارته النوعية 4186، سخن من 20° لـ 40° (ΔT = 20) يبقى Q = 167440 جول</p></div>

<!-- 4- الحرارة النوعية -->
<div class="card" style="border-color:#f97316"><h3>🧪 4- الحرارة النوعية c = Q ÷ (m × ΔT)</h3><p>اكتب Q و m و ΔT وهو يجيب c</p>
<div class="row"><label>الحرارة النوعية c</label><input id="sh_c" type="number" placeholder="فاضية = هتتحسب"><select><option>جول/كجم.م°</option></select></div>
<div class="row"><label>كمية الحرارة Q</label><input id="sh_q" type="number" placeholder="جول"><select id="sh_q_u"><option value="J" selected>جول</option><option value="kJ">كيلو جول</option><option value="cal">كالوري</option></select></div>
<div class="row"><label>الكتلة m</label><input id="sh_m" type="number" placeholder="كجم"><select id="sh_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>فرق الحرارة ΔT</label><input id="sh_dt" type="number" placeholder="م°"><select><option>م°</option></select></div>
<button class="btn btn-orange" onclick="solveSpecificHeat()">احسب الحرارة النوعية ✨</button><div class="result" id="rsh"></div>
<p style="margin-top:8px">خلي بالك: الحرارة النوعية للماء 4186، للحديد 450، للألومنيوم 900، للنحاس 385</p></div>

<!-- 5- الكثافة النوعية -->
<div class="card" style="border-color:#f97316"><h3>⚖️ 5- الكثافة النوعية = كثافة المادة ÷ كثافة الماء</h3><p>ملهاش وحدة - رقم بس - كثافة الماء = 1000 كجم/م³ = 1 جم/سم³</p>
<div class="row"><label>كثافة المادة</label><input id="rel_rho" type="number" placeholder="كجم/م³"><select id="rel_rho_u"><option value="kgm3" selected>كجم/م³</option><option value="gcm3">جم/سم³</option></select></div>
<div class="row"><label>كثافة الماء</label><input id="rel_water" type="number" placeholder="1000" value="1000"><select id="rel_water_u"><option value="kgm3" selected>كجم/م³</option><option value="gcm3">جم/سم³</option></select></div>
<div class="row"><label>الكثافة النوعية</label><input id="rel_result" type="number" placeholder="فاضية = هتتحسب"><select><option>بدون وحدة</option></select></div>
<button class="btn btn-orange" onclick="solveRelativeDensity()">احسب الكثافة النوعية ✨</button><div class="result" id="rrel"></div>
<p style="margin-top:8px">مثال: الحديد كثافته 7800، يبقى النوعية = 7800 ÷ 1000 = 7.8 - يعني أتقل من الماية 7.8 مرة وهيغرق</p></div>

<!-- 6- تحويلات الحرارة بالكامل - جديد -->
<div class="card" style="border-color:#ef4444"><h3>🔥 6- تحويلات الحرارة بالكامل</h3><p>مئوية °C - فهرنهايت °F - كلفن K - اكتب رقم واحد وهو يحول للباقي كله</p>
<div class="row"><label>الدرجة</label><input id="temp_val" type="number" placeholder="مثال: 100"></div>
<div class="row"><label>من وحدة</label><select id="temp_from" style="flex:1"><option value="C" selected>مئوية °C</option><option value="F">فهرنهايت °F</option><option value="K">كلفن K</option></select></div>
<button class="btn btn-red" onclick="convertTemp()">حوّل الحرارة 🔥</button><div class="result" id="rtemp"></div>
<table class="table">
<tr><td colspan="2">📚 قوانين تحويل الحرارة - احفظهم صم</td></tr>
<tr><td>من مئوية لـ فهرنهايت</td><td>°F = (°C × 9 ÷ 5) + 32</td></tr>
<tr><td>من فهرنهايت لـ مئوية</td><td>°C = (°F - 32) × 5 ÷ 9</td></tr>
<tr><td>من مئوية لـ كلفن</td><td>K = °C + 273.15</td></tr>
<tr><td>من كلفن لـ مئوية</td><td>°C = K - 273.15</td></tr>
<tr><td>من فهرنهايت لـ كلفن</td><td>K = (°F - 32) × 5 ÷ 9 + 273.15</td></tr>
<tr><td>من كلفن لـ فهرنهايت</td><td>°F = (K - 273.15) × 9 ÷ 5 + 32</td></tr>
<tr><td>الماء بيغلي عند</td><td>100°C = 212°F = 373.15K</td></tr>
<tr><td>الماء بيتجمد عند</td><td>0°C = 32°F = 273.15K</td></tr>
</table>
</div>

<!-- 7- تحويلات الضغط بالكامل - جديد -->
<div class="card" style="border-color:#ef4444"><h3>💨 7- تحويلات الضغط بالكامل</h3><p>باسكال - كيلو باسكال - بار - ضغط جوي - مم زئبق - اكتب رقم واحد وهو يحول للباقي كله</p>
<div class="row"><label>الضغط</label><input id="press_val" type="number" placeholder="مثال: 101325"></div>
<div class="row"><label>من وحدة</label><select id="press_from" style="flex:1"><option value="Pa" selected>باسكال Pa</option><option value="kPa">كيلو باسكال kPa</option><option value="bar">بار bar</option><option value="atm">ضغط جوي atm</option><option value="mmHg">مم زئبق mmHg</option><option value="psi">رطل/بوصة psi</option></select></div>
<button class="btn btn-red" onclick="convertPressure()">حوّل الضغط 💨</button><div class="result" id="rpress"></div>
<table class="table">
<tr><td colspan="2">📚 جدول تحويلات الضغط بالكامل</td></tr>
<tr><td>1 ضغط جوي atm</td><td>= 101325 باسكال = 101.325 كيلو باسكال</td></tr>
<tr><td>1 ضغط جوي atm</td><td>= 1.013 بار = 760 مم زئبق = 14.7 psi</td></tr>
<tr><td>1 بار bar</td><td>= 100000 باسكال = 100 كيلو باسكال</td></tr>
<tr><td>1 كيلو باسكال kPa</td><td>= 1000 باسكال</td></tr>
<tr><td>1 مم زئبق mmHg</td><td>= 133.322 باسكال</td></tr>
<tr><td>1 psi</td><td>= 6894.76 باسكال</td></tr>
</table>
</div>

<!-- باقي القوانين زي ما هي -->
<div class="card"><h3>🚀 8- السرعة والمسافة والزمن</h3><p>السرعة = المسافة ÷ الزمن - اكتب أي 2</p>
<div class="row"><label>المسافة</label><input id="p1_d" type="number" placeholder="فاضية = هتتحسب"><select id="p1_d_u"><option value="m">متر</option><option value="km" selected>كم</option><option value="cm">سم</option><option value="mm">مم</option></select></div>
<div class="row"><label>الزمن</label><input id="p1_t" type="number" placeholder="فاضية = هتتحسب"><select id="p1_t_u"><option value="s">ثانية</option><option value="min">دقيقة</option><option value="h" selected>ساعة</option></select></div>
<div class="row"><label>السرعة</label><input id="p1_v" type="number" placeholder="فاضية = هتتحسب"><select id="p1_v_u"><option value="ms">م/ث</option><option value="kmh" selected>كم/س</option></select></div>
<button class="btn" onclick="solve1()">احسب الناقص ✨</button><div class="result" id="r1"></div></div>

<div class="card"><h3>🏎️ 9- العجلة a = (ع2 - ع1) ÷ ز</h3>
<div class="row"><label>ع1 البداية</label><input id="a_v1" type="number" placeholder="م/ث"><select><option>م/ث</option></select></div>
<div class="row"><label>ع2 النهاية</label><input id="a_v2" type="number" placeholder="م/ث"><select><option>م/ث</option></select></div>
<div class="row"><label>الزمن ز</label><input id="a_t" type="number" placeholder="ثانية"><select id="a_t_u"><option value="s" selected>ثانية</option><option value="min">دقيقة</option><option value="h">ساعة</option></select></div>
<div class="row"><label>العجلة a</label><input id="a_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م/ث²</option></select></div>
<button class="btn" onclick="solveAccel()">احسب الناقص ✨</button><div class="result" id="ra"></div></div>

<div class="card"><h3>📐 10- معادلات الحركة - ع = ع0 + أ ز</h3>
<div class="row"><label>ع0 البداية</label><input id="mo_v0" type="number" placeholder="م/ث"></div>
<div class="row"><label>ع النهائية</label><input id="mo_v" type="number" placeholder="فاضية = هتتحسب"></div>
<div class="row"><label>العجلة أ</label><input id="mo_a" type="number" placeholder="م/ث²"></div>
<div class="row"><label>الزمن ز</label><input id="mo_t" type="number" placeholder="ث"></div>
<button class="btn" onclick="solveMotion1()">احسب من المعادلة الأولى ✨</button><div class="result" id="rmo1"></div></div>

<div class="card"><h3>📐 11- المسافة ف = ع0 ز + ½ أ ز²</h3>
<div class="row"><label>ع0</label><input id="mo2_v0" type="number" placeholder="م/ث"></div>
<div class="row"><label>أ</label><input id="mo2_a" type="number" placeholder="م/ث²"></div>
<div class="row"><label>ز</label><input id="mo2_t" type="number" placeholder="ث"></div>
<div class="row"><label>ف المسافة</label><input id="mo2_d" type="number" placeholder="فاضية = هتتحسب"></div>
<button class="btn" onclick="solveMotion2()">احسب المسافة ✨</button><div class="result" id="rmo2"></div></div>

<div class="card"><h3>📐 12- ع² = ع0² + 2 أ ف</h3>
<div class="row"><label>ع0</label><input id="mo3_v0" type="number" placeholder="م/ث"></div>
<div class="row"><label>ع</label><input id="mo3_v" type="number" placeholder="م/ث"></div>
<div class="row"><label>أ</label><input id="mo3_a" type="number" placeholder="م/ث²"></div>
<div class="row"><label>ف</label><input id="mo3_d" type="number" placeholder="فاضية = هتتحسب"></div>
<button class="btn" onclick="solveMotion3()">احسب الناقص ✨</button><div class="result" id="rmo3"></div></div>

<div class="card"><h3>💪 13- القوة والكتلة والعجلة F = m × a</h3>
<div class="row"><label>القوة F</label><input id="p2_f" type="number" placeholder="فاضية = هتتحسب"><select id="p2_f_u"><option value="N" selected>نيوتن</option><option value="kN">كيلو نيوتن</option></select></div>
<div class="row"><label>الكتلة m</label><input id="p2_m" type="number" placeholder="فاضية = هتتحسب"><select id="p2_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option><option value="ton">طن</option></select></div>
<div class="row"><label>العجلة a</label><input id="p2_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م/ث²</option></select></div>
<button class="btn" onclick="solve2()">احسب الناقص ✨</button><div class="result" id="r2"></div></div>

<div class="card"><h3>🌍 14- الوزن W = m × g</h3>
<div class="row"><label>الكتلة m</label><input id="w_m" type="number" placeholder="كجم"><select id="w_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>عجلة الجاذبية g</label><input id="w_g" type="number" placeholder="9.8" value="9.8"><select><option>م/ث²</option></select></div>
<div class="row"><label>الوزن W</label><input id="w_w" type="number" placeholder="فاضية = هتتحسب"><select><option>نيوتن</option></select></div>
<button class="btn" onclick="solveWeight()">احسب الناقص ✨</button><div class="result" id="rw"></div></div>

<div class="card"><h3>⚡ 15- الشغل والقوة والمسافة W = F × d</h3>
<div class="row"><label>الشغل W</label><input id="p3_w" type="number" placeholder="فاضية = هتتحسب"><select id="p3_w_u"><option value="J" selected>جول</option><option value="kJ">كيلو جول</option></select></div>
<div class="row"><label>القوة F</label><input id="p3_f" type="number" placeholder="فاضية = هتتحسب"><select id="p3_f_u"><option value="N" selected>نيوتن</option><option value="kN">كيلو نيوتن</option></select></div>
<div class="row"><label>المسافة d</label><input id="p3_d" type="number" placeholder="فاضية = هتتحسب"><select id="p3_d_u"><option value="m" selected>متر</option><option value="km">كم</option><option value="cm">سم</option></select></div>
<button class="btn" onclick="solve3()">احسب الناقص ✨</button><div class="result" id="r3"></div></div>

<div class="card"><h3>🔥 16- طاقة الحركة KE = ½ m v²</h3>
<div class="row"><label>الكتلة m</label><input id="ke_m" type="number" placeholder="كجم"><select id="ke_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>السرعة v</label><input id="ke_v" type="number" placeholder="م/ث"><select id="ke_v_u"><option value="ms" selected>م/ث</option><option value="kmh">كم/س</option></select></div>
<div class="row"><label>الطاقة KE</label><input id="ke_e" type="number" placeholder="فاضية = هتتحسب"><select><option>جول</option></select></div>
<button class="btn" onclick="solveKE()">احسب الناقص ✨</button><div class="result" id="rke"></div></div>

<div class="card"><h3>🏔️ 17- طاقة الوضع PE = m g h</h3>
<div class="row"><label>الكتلة m</label><input id="pe_m" type="number" placeholder="كجم"><select id="pe_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>الارتفاع h</label><input id="pe_h" type="number" placeholder="متر"><select id="pe_h_u"><option value="m" selected>متر</option><option value="cm">سم</option><option value="km">كم</option></select></div>
<div class="row"><label>الطاقة PE</label><input id="pe_e" type="number" placeholder="فاضية = هتتحسب"><select><option>جول</option></select></div>
<button class="btn" onclick="solvePE()">احسب الناقص ✨</button><div class="result" id="rpe"></div></div>

<div class="card"><h3>🔋 18- القدرة والشغل والزمن P = W ÷ t</h3>
<div class="row"><label>القدرة P</label><input id="p4_p" type="number" placeholder="فاضية = هتتحسب"><select id="p4_p_u"><option value="W" selected>وات</option><option value="kW">كيلو وات</option></select></div>
<div class="row"><label>الشغل W</label><input id="p4_w" type="number" placeholder="فاضية = هتتحسب"><select id="p4_w_u"><option value="J" selected>جول</option><option value="kJ">كيلو جول</option></select></div>
<div class="row"><label>الزمن t</label><input id="p4_t" type="number" placeholder="فاضية = هتتحسب"><select id="p4_t_u"><option value="s" selected>ثانية</option><option value="min">دقيقة</option><option value="h">ساعة</option></select></div>
<button class="btn" onclick="solve4()">احسب الناقص ✨</button><div class="result" id="r4"></div></div>

<div class="card"><h3>🎱 19- كمية الحركة p = m × v</h3>
<div class="row"><label>كمية الحركة p</label><input id="mom_p" type="number" placeholder="فاضية = هتتحسب"><select><option>كجم.م/ث</option></select></div>
<div class="row"><label>الكتلة m</label><input id="mom_m" type="number" placeholder="كجم"><select id="mom_m_u"><option value="kg" selected>كجم</option><option value="g">جرام</option></select></div>
<div class="row"><label>السرعة v</label><input id="mom_v" type="number" placeholder="م/ث"><select id="mom_v_u"><option value="ms" selected>م/ث</option><option value="kmh">كم/س</option></select></div>
<button class="btn" onclick="solveMom()">احسب الناقص ✨</button><div class="result" id="rmom"></div></div>

<div class="card"><h3>🔌 20- الكهرباء V = I × R</h3>
<div class="row"><label>الجهد V</label><input id="p7_v" type="number" placeholder="فاضية = هتتحسب"><select id="p7_v_u"><option value="V" selected>فولت</option><option value="mV">ملي فولت</option></select></div>
<div class="row"><label>التيار I</label><input id="p7_i" type="number" placeholder="فاضية = هتتحسب"><select id="p7_i_u"><option value="A" selected>أمبير</option><option value="mA">ملي أمبير</option></select></div>
<div class="row"><label>المقاومة R</label><input id="p7_r" type="number" placeholder="فاضية = هتتحسب"><select id="p7_r_u"><option value="ohm" selected>أوم</option><option value="kohm">كيلو أوم</option></select></div>
<button class="btn" onclick="solve7()">احسب الناقص ✨</button><div class="result" id="r7"></div></div>
</div>

<!-- ============ رياضة ============ -->
<div id="sec-math" style="display:none">
<div class="card"><h3>🟦 المربع: الضلع والمساحة والمحيط</h3>
<div class="row"><label>الضلع</label><input id="m1_s" type="number" placeholder="فاضية = هتتحسب"><select id="m1_s_u"><option value="m" selected>متر</option><option value="cm">سم</option><option value="km">كم</option></select></div>
<div class="row"><label>المساحة</label><input id="m1_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م²</option></select></div>
<div class="row"><label>المحيط</label><input id="m1_p" type="number" placeholder="فاضية = هتتحسب"><select><option>متر</option></select></div>
<button class="btn" onclick="solveM1()">احسب الناقص ✨</button><div class="result" id="rm1"></div></div>

<div class="card"><h3>▭ المستطيل: الطول والعرض والمساحة</h3>
<div class="row"><label>الطول</label><input id="m2_l" type="number" placeholder="فاضية = هتتحسب"><select id="m2_l_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>العرض</label><input id="m2_w" type="number" placeholder="فاضية = هتتحسب"><select id="m2_w_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>المساحة</label><input id="m2_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م²</option></select></div>
<button class="btn" onclick="solveM2()">احسب الناقص ✨</button><div class="result" id="rm2"></div></div>

<div class="card"><h3>🔵 الدائرة: نصف القطر والمساحة والمحيط</h3>
<div class="row"><label>نصف القطر</label><input id="m3_r" type="number" placeholder="فاضية = هتتحسب"><select id="m3_r_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>المساحة</label><input id="m3_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م²</option></select></div>
<div class="row"><label>المحيط</label><input id="m3_p" type="number" placeholder="فاضية = هتتحسب"><select><option>متر</option></select></div>
<button class="btn" onclick="solveM3()">احسب الناقص ✨</button><div class="result" id="rm3"></div></div>

<div class="card"><h3>🔺 المثلث: القاعدة والارتفاع والمساحة</h3>
<div class="row"><label>القاعدة</label><input id="tri_b" type="number" placeholder="متر"><select id="tri_b_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>الارتفاع</label><input id="tri_h" type="number" placeholder="متر"><select id="tri_h_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>المساحة</label><input id="tri_a" type="number" placeholder="فاضية = هتتحسب"><select><option>م²</option></select></div>
<button class="btn" onclick="solveTri()">احسب الناقص ✨</button><div class="result" id="rtri"></div></div>

<div class="card"><h3>📐 فيثاغورس: أ و ب والوتر</h3>
<div class="row"><label>الضلع أ</label><input id="m4_a" type="number" placeholder="فاضية = هتتحسب"><select id="m4_a_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>الضلع ب</label><input id="m4_b" type="number" placeholder="فاضية = هتتحسب"><select id="m4_b_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>الوتر جـ</label><input id="m4_c" type="number" placeholder="فاضية = هتتحسب"><select id="m4_c_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<button class="btn" onclick="solveM4()">احسب الناقص ✨</button><div class="result" id="rm4"></div></div>

<div class="card"><h3>🧊 حجم المكعب والمتوازي</h3>
<div class="row"><label>الطول</label><input id="vol_l" type="number" placeholder="متر"><select id="vol_l_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>العرض</label><input id="vol_w" type="number" placeholder="متر"><select id="vol_w_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<div class="row"><label>الارتفاع</label><input id="vol_h" type="number" placeholder="متر"><select id="vol_h_u"><option value="m" selected>متر</option><option value="cm">سم</option></select></div>
<button class="btn" onclick="solveVol()">احسب الحجم ✨</button><div class="result" id="rvol"></div></div>
</div>

<div class="creator" style="margin-top:14px">✨ تم إنشاء هذا الموقع من قبل الطالب <b>يوسف فايق</b> 👨‍🎓<br>تحت إشراف مستر <span>أحمد حسن</span> 👨‍🏫 ✨</div>
<div id="adminDot" onclick="dotClick()"></div>
</div>

<div id="adminModal"><div id="adminBox"><h3>🔐 لوحة الأدمن - YF SolveX</h3><p id="adminInfo">...</p><button onclick="closeAdmin()">قفل</button><button onclick="resetCount()" style="background:#ef4444;color:#fff">تصفير العداد</button></div></div>

<script>
function showSec(s){
  document.getElementById('sec-conv').style.display=s=='conv'?'block':'none';
  document.getElementById('sec-phys').style.display=s=='phys'?'block':'none';
  document.getElementById('sec-math').style.display=s=='math'?'block':'none';
  document.getElementById('tConv').className=s=='conv'?'active':'';
  document.getElementById('tPhys').className=s=='phys'?'active':'';
  document.getElementById('tMath').className=s=='math'?'active':'';
}
function toM(v,u){ if(u=='km')return v*1000; if(u=='cm')return v/100; if(u=='mm')return v/1000; return v; }
function toSec(v,u){ if(u=='min')return v*60; if(u=='h')return v*3600; return v; }
function toKg(v,u){ if(u=='g')return v/1000; if(u=='ton')return v*1000; return v; }
function toN(v,u){ if(u=='kN')return v*1000; return v; }
function toJ(v,u){ if(u=='kJ')return v*1000; if(u=='cal')return v*4.186; return v; }
function toM3(v,u){ if(u=='cm3')return v/1000000; if(u=='L')return v/1000; return v; }
function toM2(v,u){ if(u=='cm2')return v/10000; return v; }
function toRho(v,u){ if(u=='gcm3')return v*1000; return v; }
function val(id){ let v=parseFloat(document.getElementById(id).value); return isNaN(v)?null:v; }
function show(id,h){ let e=document.getElementById(id); e.style.display='block'; e.innerHTML=h; }
function countSolve(){ let c=parseInt(localStorage.getItem('yf_solves')||'0')+1; localStorage.setItem('yf_solves',c); }
function need2(a,b,c){ let n=(a!=null)+(b!=null)+(c!=null); if(n<2){ alert('اكتب خانتين على الأقل يا يوسف 😅 وسيب التالتة فاضية'); return false; } if(n==3){ alert('انت كاتب التلاتة، سيب واحدة فاضية عشان احسبها'); return false; } return true; }

// --- التحويلات ---
const unitsMap={
 length:[['متر','m',1],['كيلو متر','km',1000],['سم','cm',0.01],['مم','mm',0.001]],
 mass:[['كجم','kg',1],['جرام','g',0.001],['طن','ton',1000]],
 time:[['ثانية','s',1],['دقيقة','min',60],['ساعة','h',3600]],
 area:[['م²','m2',1],['سم²','cm2',0.0001],['كم²','km2',1000000]],
 volume:[['م³','m3',1],['سم³','cm3',0.000001],['لتر','L',0.001]],
 speed:[['م/ث','ms',1],['كم/س','kmh',0.277777]],
 force:[['نيوتن','N',1],['كيلو نيوتن','kN',1000]],
 energy:[['جول','J',1],['كيلو جول','kJ',1000]],
 pressure:[['باسكال','Pa',1],['كيلو باسكال','kPa',1000]]
};
function updateUnits(){ let t=document.getElementById('c_type').value; let arr=unitsMap[t]; let f=document.getElementById('c_from'), to=document.getElementById('c_to'); f.innerHTML=''; to.innerHTML=''; arr.forEach(u=>{ f.innerHTML+=`<option value="${u[2]}">${u[0]}</option>`; to.innerHTML+=`<option value="${u[2]}">${u[0]}</option>`; }); to.selectedIndex=1; }
updateUnits();
function doConvert(){ let v=val('c_val'); if(v==null) return alert('اكتب الرقم الأول'); let f=parseFloat(document.getElementById('c_from').value), t=parseFloat(document.getElementById('c_to').value); let base=v*f; let res=base/t; let fromName=document.getElementById('c_from').selectedOptions[0].text; let toName=document.getElementById('c_to').selectedOptions[0].text; show('rc',`${v} ${fromName} = <b>${res.toFixed(4)} ${toName}</b> 🔄`); countSolve(); }

// --- فيزيا ---
function solve1(){ let d=val('p1_d'), t=val('p1_t'), v=val('p1_v'); if(!need2(d,t,v)) return; let dm=d!=null?toM(d,document.getElementById('p1_d_u').value):null; let ts=t!=null?toSec(t,document.getElementById('p1_t_u').value):null; let vms=v!=null?(document.getElementById('p1_v_u').value=='kmh'?v/3.6:v):null; if(v==null){ let res=dm/ts; show('r1',`السرعة = ${dm} ÷ ${ts} = <b>${res.toFixed(2)} م/ث = ${(res*3.6).toFixed(2)} كم/س</b> 🚀`); } else if(d==null){ let resM=vms*ts; show('r1',`المسافة = <b>${resM.toFixed(2)} م = ${(resM/1000).toFixed(2)} كم</b> 📏`); } else { let resS=dm/vms; show('r1',`الزمن = <b>${resS.toFixed(2)} ث = ${(resS/3600).toFixed(2)} ساعة</b> ⏱️`); } countSolve(); }
function solveAccel(){ let v1=val('a_v1'), v2=val('a_v2'), t=val('a_t'), a=val('a_a'); let ts=t!=null?toSec(t,document.getElementById('a_t_u').value):null; if(v1==null && a!=null && v2!=null && ts!=null) show('ra',`ع1 = ${v2} - (${a} × ${ts}) = <b>${(v2-a*ts).toFixed(2)} م/ث</b>`); else if(v2==null && v1!=null) show('ra',`ع2 = ${v1} + (${a||0} × ${ts}) = <b>${(v1+(a||0)*ts).toFixed(2)} م/ث</b>`); else if(t==null && v1!=null && v2!=null && a!=null) show('ra',`الزمن = (${v2} - ${v1}) ÷ ${a} = <b>${((v2-v1)/a).toFixed(2)} ث</b>`); else if(a==null && v1!=null && v2!=null && ts!=null) show('ra',`العجلة = (${v2} - ${v1}) ÷ ${ts} = <b>${((v2-v1)/ts).toFixed(2)} م/ث²</b> 🏎️`); else alert('اكتب 3 خانات وسيب واحدة فاضية'); countSolve(); }
function solveMotion1(){ let v0=val('mo_v0'), v=val('mo_v'), a=val('mo_a'), t=val('mo_t'); if(v==null && v0!=null && a!=null && t!=null) show('rmo1',`ع = ${v0} + ${a} × ${t} = <b>${(v0+a*t).toFixed(2)} م/ث</b>`); else if(v0==null && v!=null) show('rmo1',`ع0 = ${v} - ${a} × ${t} = <b>${(v-a*t).toFixed(2)} م/ث</b>`); else if(a==null && v0!=null && v!=null && t!=null) show('rmo1',`أ = (${v} - ${v0}) ÷ ${t} = <b>${((v-v0)/t).toFixed(2)} م/ث²</b>`); else if(t==null) show('rmo1',`ز = (${v} - ${v0}) ÷ ${a} = <b>${((v-v0)/a).toFixed(2)} ث</b>`); else alert('اكتب 3 وسيب واحدة فاضية'); countSolve(); }
function solveMotion2(){ let v0=val('mo2_v0'), a=val('mo2_a'), t=val('mo2_t'), d=val('mo2_d'); if(d==null) show('rmo2',`ف = ${v0}×${t} + ½×${a}×${t}² = <b>${(v0*t+0.5*a*t*t).toFixed(2)} م</b> 📏`); else show('rmo2',`انت كاتب المسافة، سيبها فاضية عشان احسبها`); countSolve(); }
function solveMotion3(){ let v0=val('mo3_v0'), v=val('mo3_v'), a=val('mo3_a'), d=val('mo3_d'); if(d==null && v!=null && v0!=null && a!=null) show('rmo3',`ف = (${v}² - ${v0}²) ÷ (2×${a}) = <b>${((v*v-v0*v0)/(2*a)).toFixed(2)} م</b>`); else if(a==null) show('rmo3',`أ = (${v}² - ${v0}²) ÷ (2×${d}) = <b>${((v*v-v0*v0)/(2*d)).toFixed(2)} م/ث²</b>`); else if(v==null) show('rmo3',`ع = جذر(${v0}² + 2×${a}×${d}) = <b>${Math.sqrt(v0*v0+2*a*d).toFixed(2)} م/ث</b>`); else alert('سيب خانة واحدة فاضية'); countSolve(); }
function solve2(){ let F=val('p2_f'), m=val('p2_m'), a=val('p2_a'); if(!need2(F,m,a)) return; let Fn=F!=null?toN(F,document.getElementById('p2_f_u').value):null; let kg=m!=null?toKg(m,document.getElementById('p2_m_u').value):null; if(F==null) show('r2',`القوة = ${kg} × ${a} = <b>${(kg*a).toFixed(2)} نيوتن</b> 💪`); else if(m==null) show('r2',`الكتلة = ${Fn} ÷ ${a} = <b>${(Fn/a).toFixed(2)} كجم</b>`); else show('r2',`العجلة = ${Fn} ÷ ${kg} = <b>${(Fn/kg).toFixed(2)} م/ث²</b>`); countSolve(); }
function solveWeight(){ let m=val('w_m'), g=val('w_g'), w=val('w_w'); let kg=m!=null?toKg(m,document.getElementById('w_m_u').value):null; if(w==null && kg!=null && g!=null) show('rw',`الوزن = ${kg} × ${g} = <b>${(kg*g).toFixed(2)} نيوتن</b> 🌍`); else if(m==null && w!=null) show('rw',`الكتلة = ${w} ÷ ${g} = <b>${(w/g).toFixed(2)} كجم</b>`); else alert('اكتب خانتين وسيب واحدة فاضية'); countSolve(); }
function solve3(){ let W=val('p3_w'), F=val('p3_f'), d=val('p3_d'); if(!need2(W,F,d)) return; let J=W!=null?toJ(W,document.getElementById('p3_w_u').value):null; let Fn=F!=null?toN(F,document.getElementById('p3_f_u').value):null; let dm=d!=null?toM(d,document.getElementById('p3_d_u').value):null; if(W==null) show('r3',`الشغل = ${Fn} × ${dm} = <b>${(Fn*dm).toFixed(2)} جول</b> ⚡`); else if(F==null) show('r3',`القوة = ${J} ÷ ${dm} = <b>${(J/dm).toFixed(2)} نيوتن</b>`); else show('r3',`المسافة = ${J} ÷ ${Fn} = <b>${(J/Fn).toFixed(2)} م</b>`); countSolve(); }
function solveKE(){ let m=val('ke_m'), v=val('ke_v'), e=val('ke_e'); let kg=m!=null?toKg(m,document.getElementById('ke_m_u').value):null; let vms=v!=null?(document.getElementById('ke_v_u').value=='kmh'?v/3.6:v):null; if(e==null && kg!=null && vms!=null) show('rke',`KE = ½ × ${kg} × ${vms}² = <b>${(0.5*kg*vms*vms).toFixed(2)} جول</b> 🔥`); else if(v==null && e!=null) show('rke',`السرعة = جذر(2×${e} ÷ ${kg}) = <b>${Math.sqrt(2*e/kg).toFixed(2)} م/ث</b>`); else if(m==null) show('rke',`الكتلة = 2×${e} ÷ ${vms}² = <b>${(2*e/(vms*vms)).toFixed(2)} كجم</b>`); else alert('اكتب خانتين وسيب واحدة فاضية'); countSolve(); }
function solvePE(){ let m=val('pe_m'), h=val('pe_h'), e=val('pe_e'); let kg=m!=null?toKg(m,document.getElementById('pe_m_u').value):null; let hm=h!=null?toM(h,document.getElementById('pe_h_u').value):null; if(e==null && kg!=null && hm!=null) show('rpe',`PE = ${kg} × 9.8 × ${hm} = <b>${(kg*9.8*hm).toFixed(2)} جول</b> 🏔️`); else if(h==null && e!=null) show('rpe',`الارتفاع = ${e} ÷ (${kg}×9.8) = <b>${(e/(kg*9.8)).toFixed(2)} م</b>`); else if(m==null) show('rpe',`الكتلة = ${e} ÷ (9.8×${hm}) = <b>${(e/(9.8*hm)).toFixed(2)} كجم</b>`); else alert('اكتب خانتين وسيب واحدة فاضية'); countSolve(); }
function solve4(){ let P=val('p4_p'), W=val('p4_w'), t=val('p4_t'); if(!need2(P,W,t)) return; let Pw=P!=null?(document.getElementById('p4_p_u').value=='kW'?P*1000:P):null; let J=W!=null?toJ(W,document.getElementById('p4_w_u').value):null; let ts=t!=null?toSec(t,document.getElementById('p4_t_u').value):null; if(P==null) show('r4',`القدرة = ${J} ÷ ${ts} = <b>${(J/ts).toFixed(2)} وات</b> 🔋`); else if(W==null) show('r4',`الشغل = ${Pw} × ${ts} = <b>${(Pw*ts).toFixed(2)} جول</b>`); else show('r4',`الزمن = ${J} ÷ ${Pw} = <b>${(J/Pw).toFixed(2)} ث</b>`); countSolve(); }

// --- القوانين اللي بعد الضغط ---
function solve5(){ let r=val('p5_r'), m=val('p5_m'), v=val('p5_v'); if(!need2(r,m,v)) return; let rho=r!=null?toRho(r,document.getElementById('p5_r_u').value):null; let kg=m!=null?toKg(m,document.getElementById('p5_m_u').value):null; let m3=v!=null?toM3(v,document.getElementById('p5_v_u').value):null; if(r==null) show('r5',`الكثافة = ${kg} ÷ ${m3} = <b>${(kg/m3).toFixed(2)} كجم/م³ = ${(kg/m3/1000).toFixed(3)} جم/سم³</b> 🧱`); else if(m==null) show('r5',`الكتلة = ${rho} × ${m3} = <b>${(rho*m3).toFixed(2)} كجم</b>`); else show('r5',`الحجم = ${kg} ÷ ${rho} = <b>${(kg/rho).toFixed(4)} م³ = ${((kg/rho)*1000000).toFixed(1)} سم³</b>`); countSolve(); }
function solveHeat(){
  let Q=val('heat_q'), m=val('heat_m'), c=val('heat_c'), dt=val('heat_dt');
  let kg=m!=null?toKg(m,document.getElementById('heat_m_u').value):null;
  let Qj=Q!=null?toJ(Q,document.getElementById('heat_q_u').value):null;
  let count=(Q!=null)+(m!=null)+(c!=null)+(dt!=null);
  if(count<3) return alert('اكتب 3 خانات وسيب واحدة فاضية يا يوسف 😅');
  if(Q==null) show('rheat',`Q = ${kg} × ${c} × ${dt} = <b>${(kg*c*dt).toFixed(2)} جول = ${((kg*c*dt)/1000).toFixed(2)} كيلو جول = ${((kg*c*dt)/4.186).toFixed(1)} كالوري</b> 🔥`);
  else if(m==null) show('rheat',`m = ${Qj} ÷ (${c} × ${dt}) = <b>${(Qj/(c*dt)).toFixed(3)} كجم = ${(Qj/(c*dt)*1000).toFixed(1)} جم</b> ⚖️`);
  else if(c==null) show('rheat',`c = ${Qj} ÷ (${kg} × ${dt}) = <b>${(Qj/(kg*dt)).toFixed(2)} جول/كجم.م°</b> 🧪`);
  else if(dt==null) show('rheat',`ΔT = ${Qj} ÷ (${kg} × ${c}) = <b>${(Qj/(kg*c)).toFixed(2)} م°</b> 🌡️`);
  countSolve();
}
function solveSpecificHeat(){
  let c=val('sh_c'), Q=val('sh_q'), m=val('sh_m'), dt=val('sh_dt');
  let kg=m!=null?toKg(m,document.getElementById('sh_m_u').value):null;
  let Qj=Q!=null?toJ(Q,document.getElementById('sh_q_u').value):null;
  let count=(c!=null)+(Q!=null)+(m!=null)+(dt!=null);
  if(count<3) return alert('اكتب 3 خانات وسيب واحدة فاضية');
  if(c==null) show('rsh',`c = ${Qj} ÷ (${kg} × ${dt}) = <b>${(Qj/(kg*dt)).toFixed(2)} جول/كجم.م°</b> 🧪`);
  else if(Q==null) show('rsh',`Q = ${kg} × ${c} × ${dt} = <b>${(kg*c*dt).toFixed(2)} جول</b> 🔥`);
  else if(m==null) show('rsh',`m = ${Qj} ÷ (${c} × ${dt}) = <b>${(Qj/(c*dt)).toFixed(3)} كجم</b>`);
  else if(dt==null) show('rsh',`ΔT = ${Qj} ÷ (${kg} × ${c}) = <b>${(Qj/(kg*c)).toFixed(2)} م°</b>`);
  countSolve();
}
function solveRelativeDensity(){
  let rho=val('rel_rho'), water=val('rel_water'), res=val('rel_result');
  let rhoKg=rho!=null?toRho(rho,document.getElementById('rel_rho_u').value):null;
  let waterKg=water!=null?toRho(water,document.getElementById('rel_water_u').value):null;
  if(res==null && rhoKg!=null && waterKg!=null){
    let r=rhoKg/waterKg;
    let msg=r>1 ? 'أتقل من الماية وهيغرق ⬇️' : r<1 ? 'أخف من الماية وهيطفو ⬆️' : 'قد الماية بالظبط';
    show('rrel',`الكثافة النوعية = ${rhoKg} ÷ ${waterKg} = <b>${r.toFixed(3)}</b> (بدون وحدة)<br>${msg} ⚖️`);
  } else if(rho==null && res!=null && waterKg!=null){
    show('rrel',`كثافة المادة = ${res} × ${waterKg} = <b>${(res*waterKg).toFixed(2)} كجم/م³ = ${(res*waterKg/1000).toFixed(3)} جم/سم³</b> 🧱`);
  } else if(water==null && res!=null && rhoKg!=null){
    show('rrel',`كثافة الماء = ${rhoKg} ÷ ${res} = <b>${(rhoKg/res).toFixed(2)} كجم/م³</b>`);
  } else alert('اكتب خانتين وسيب التالتة فاضية');
  countSolve();
}

// --- الجديد: تحويلات الحرارة والضغط ---
function convertTemp(){
  let v=val('temp_val'); if(v==null) return alert('اكتب الدرجة الأول');
  let from=document.getElementById('temp_from').value;
  let C, F, K;
  if(from=='C'){ C=v; F=(C*9/5)+32; K=C+273.15; }
  if(from=='F'){ F=v; C=(F-32)*5/9; K=C+273.15; }
  if(from=='K'){ K=v; C=K-273.15; F=(C*9/5)+32; }
  show('rtemp',`${v} ${from=='C'?'مئوية':from=='F'?'فهرنهايت':'كلفن'} = <br><b>${C.toFixed(2)} °C مئوية</b><br><b>${F.toFixed(2)} °F فهرنهايت</b><br><b>${K.toFixed(2)} K كلفن</b> 🔥`);
  countSolve();
}
function convertPressure(){
  let v=val('press_val'); if(v==null) return alert('اكتب الضغط الأول');
  let from=document.getElementById('press_from').value;
  let Pa=0;
  if(from=='Pa') Pa=v;
  if(from=='kPa') Pa=v*1000;
  if(from=='bar') Pa=v*100000;
  if(from=='atm') Pa=v*101325;
  if(from=='mmHg') Pa=v*133.322;
  if(from=='psi') Pa=v*6894.76;
  show('rpress',`${v} ${from} = <br><b>${Pa.toFixed(2)} باسكال Pa</b><br><b>${(Pa/1000).toFixed(3)} كيلو باسكال kPa</b><br><b>${(Pa/100000).toFixed(4)} بار bar</b><br><b>${(Pa/101325).toFixed(4)} ضغط جوي atm</b><br><b>${(Pa/133.322).toFixed(2)} مم زئبق mmHg</b><br><b>${(Pa/6894.76).toFixed(3)} psi</b> 💨`);
  countSolve();
}

function solve6(){ let P=val('p6_p'), F=val('p6_f'), A=val('p6_a'); if(!need2(P,F,A)) return; let Pa=P!=null?(document.getElementById('p6_p_u').value=='kPa'?P*1000:P):null; let Fn=F!=null?toN(F,document.getElementById('p6_f_u').value):null; let m2=A!=null?toM2(A,document.getElementById('p6_a_u').value):null; if(P==null) show('r6',`الضغط = ${Fn} ÷ ${m2} = <b>${(Fn/m2).toFixed(2)} باسكال</b> 💧`); else if(F==null) show('r6',`القوة = ${Pa} × ${m2} = <b>${(Pa*m2).toFixed(2)} نيوتن</b>`); else show('r6',`المساحة = ${Fn} ÷ ${Pa} = <b>${(Fn/Pa).toFixed(4)} م²</b>`); countSolve(); }
function solveMom(){ let p=val('mom_p'), m=val('mom_m'), v=val('mom_v'); let kg=m!=null?toKg(m,document.getElementById('mom_m_u').value):null; let vms=v!=null?(document.getElementById('mom_v_u').value=='kmh'?v/3.6:v):null; if(p==null && kg!=null && vms!=null) show('rmom',`كمية الحركة = ${kg} × ${vms} = <b>${(kg*vms).toFixed(2)} كجم.م/ث</b> 🎱`); else if(m==null && p!=null) show('rmom',`الكتلة = ${p} ÷ ${vms} = <b>${(p/vms).toFixed(2)} كجم</b>`); else if(v==null) show('rmom',`السرعة = ${p} ÷ ${kg} = <b>${(p/kg).toFixed(2)} م/ث</b>`); else alert('اكتب خانتين وسيب واحدة فاضية'); countSolve(); }
function solve7(){ let V=val('p7_v'), I=val('p7_i'), R=val('p7_r'); if(!need2(V,I,R)) return; let Volt=V!=null?(document.getElementById('p7_v_u').value=='mV'?V/1000:V):null; let Amp=I!=null?(document.getElementById('p7_i_u').value=='mA'?I/1000:I):null; let Ohm=R!=null?(document.getElementById('p7_r_u').value=='kohm'?R*1000:R):null; if(V==null) show('r7',`الجهد = ${Amp} × ${Ohm} = <b>${(Amp*Ohm).toFixed(2)} فولت</b> 🔌`); else if(I==null) show('r7',`التيار = ${Volt} ÷ ${Ohm} = <b>${(Volt/Ohm).toFixed(2)} أمبير</b>`); else show('r7',`المقاومة = ${Volt} ÷ ${Amp} = <b>${(Volt/Amp).toFixed(2)} أوم</b>`); countSolve(); }

// رياضة
function solveM1(){ let s=val('m1_s'), a=val('m1_a'), p=val('m1_p'); if(!need2(s,a,p)) return; let sm=s!=null?toM(s,document.getElementById('m1_s_u').value):null; if(s==null){ if(a!=null) sm=Math.sqrt(a); else sm=p/4; } show('rm1',`الضلع = <b>${sm.toFixed(2)} م</b><br>المساحة = <b>${(sm*sm).toFixed(2)} م²</b><br>المحيط = <b>${(4*sm).toFixed(2)} م</b> 🟦`); countSolve(); }
function solveM2(){ let L=val('m2_l'), W=val('m2_w'), A=val('m2_a'); if(!need2(L,W,A)) return; let lm=L!=null?toM(L,document.getElementById('m2_l_u').value):null; let wm=W!=null?toM(W,document.getElementById('m2_w_u').value):null; if(A==null) show('rm2',`المساحة = ${lm} × ${wm} = <b>${(lm*wm).toFixed(2)} م²</b> ▭`); else if(L==null) show('rm2',`الطول = ${A} ÷ ${wm} = <b>${(A/wm).toFixed(2)} م</b>`); else show('rm2',`العرض = ${A} ÷ ${lm} = <b>${(A/lm).toFixed(2)} م</b>`); countSolve(); }
function solveM3(){ let r=val('m3_r'), a=val('m3_a'), p=val('m3_p'); if(!need2(r,a,p)) return; let rm=r!=null?toM(r,document.getElementById('m3_r_u').value):null; if(r==null){ if(a!=null) rm=Math.sqrt(a/Math.PI); else rm=p/(2*Math.PI); } show('rm3',`نصف القطر = <b>${rm.toFixed(2)} م</b><br>المساحة = <b>${(Math.PI*rm*rm).toFixed(2)} م²</b><br>المحيط = <b>${(2*Math.PI*rm).toFixed(2)} م</b> 🔵`); countSolve(); }
function solveTri(){ let b=val('tri_b'), h=val('tri_h'), a=val('tri_a'); let bm=b!=null?toM(b,document.getElementById('tri_b_u').value):null; let hm=h!=null?toM(h,document.getElementById('tri_h_u').value):null; if(a==null && bm!=null && hm!=null) show('rtri',`المساحة = ½ × ${bm} × ${hm} = <b>${(0.5*bm*hm).toFixed(2)} م²</b> 🔺`); else if(b==null && a!=null) show('rtri',`القاعدة = 2×${a} ÷ ${hm} = <b>${(2*a/hm).toFixed(2)} م</b>`); else if(h==null) show('rtri',`الارتفاع = 2×${a} ÷ ${bm} = <b>${(2*a/bm).toFixed(2)} م</b>`); else alert('اكتب خانتين وسيب واحدة فاضية'); countSolve(); }
function solveM4(){ let a=val('m4_a'), b=val('m4_b'), c=val('m4_c'); if(!need2(a,b,c)) return; let am=a!=null?toM(a,document.getElementById('m4_a_u').value):null; let bm=b!=null?toM(b,document.getElementById('m4_b_u').value):null; let cm=c!=null?toM(c,document.getElementById('m4_c_u').value):null; if(c==null) show('rm4',`الوتر = جذر (${am}² + ${bm}²) = <b>${Math.sqrt(am*am+bm*bm).toFixed(2)} م</b> 📐`); else if(a==null) show('rm4',`الضلع أ = جذر (${cm}² - ${bm}²) = <b>${Math.sqrt(cm*cm-bm*bm).toFixed(2)} م</b>`); else show('rm4',`الضلع ب = جذر (${cm}² - ${am}²) = <b>${Math.sqrt(cm*cm-am*am).toFixed(2)} م</b>`); countSolve(); }
function solveVol(){ let L=val('vol_l'), W=val('vol_w'), H=val('vol_h'); if(!L||!W||!H) return alert('اكتب الطول والعرض والارتفاع'); let lm=toM(L,document.getElementById('vol_l_u').value), wm=toM(W,document.getElementById('vol_w_u').value), hm=toM(H,document.getElementById('vol_h_u').value); show('rvol',`الحجم = ${lm} × ${wm} × ${hm} = <b>${(lm*wm*hm).toFixed(2)} م³ = ${(lm*wm*hm*1000).toFixed(2)} لتر</b> 🧊`); countSolve(); }

let visits=parseInt(localStorage.getItem('yf_visits')||'0')+1; localStorage.setItem('yf_visits',visits); localStorage.setItem('yf_last',new Date().toLocaleString('ar-EG'));
let dotCount=0, lastDot=0;
function dotClick(){ let now=Date.now(); if(now-lastDot>2000) dotCount=0; lastDot=now; dotCount++; if(dotCount>=5){ dotCount=0; let pass=prompt('اكتب باسورد الأدمن:'); if(pass==='YF2026'){ let solves=localStorage.getItem('yf_solves')||'0'; let last=localStorage.getItem('yf_last')||'---'; document.getElementById('adminInfo').innerHTML=`أهلا يوسف 👨‍🎓<br><br>عدد الزيارات: <b>${visits}</b><br>عدد المسائل اللي اتحلت: <b>${solves}</b><br>آخر ظهور: <b>${last}</b><br><br>تم إنشاء هذا الموقع من قبل الطالب يوسف فايق - تحت إشراف مستر أحمد حسن`; document.getElementById('adminModal').style.display='grid'; } else if(pass!=null) alert('الباسورد غلط ❌'); } }
function closeAdmin(){ document.getElementById('adminModal').style.display='none'; }
function resetCount(){ if(confirm('تصفر العداد؟')){ localStorage.setItem('yf_visits','0'); localStorage.setItem('yf_solves','0'); alert('اتصفر ✅'); closeAdmin(); } }
</script>
</body>
</html>
