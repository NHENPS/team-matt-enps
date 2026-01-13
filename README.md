# team-matt-enps
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Team Matt eNPS</title>

<style>
body {
font-family: "Segoe UI", Arial, sans-serif;
background: #f5f7fa;
margin: 0;
padding: 20px;
color: #333;
}
h1 { color:#0057B8; margin-bottom:12px; }
.container {
display:grid;
grid-template-columns:2fr 1fr;
gap:20px;
}
.card {
background:#fff;
border-radius:10px;
padding:16px;
box-shadow:0 4px 12px rgba(0,0,0,0.08);
}
input {
width:100%;
padding:10px;
margin-bottom:12px;
border-radius:6px;
border:1px solid #ccc;
font-size:14px;
}
.advocate-list {
max-height:540px;
overflow-y:auto;
}
.advocate {
padding:10px;
border-bottom:1px solid #eee;
}
.score { font-weight:bold; color:#FF6A00; }
.name { font-weight:bold; color:#0057B8; }
.comment { font-size:13px; margin-top:4px; }
ol { padding-left:20px; }
li { margin-bottom:6px; font-weight:600; }
</style>
</head>

<body>

<h1>Team Matt eNPS</h1>

<div class="container">

<!-- LEFT -->
<div class="card">
<input type="text" id="search" placeholder="Search by agent name…" onkeyup="filterAgents()">

<div class="advocate-list">

<!-- ===== ALL 41 ADVOCATES ===== -->

<!-- Faiaz Shihan (4) -->
<div class="advocate" data-name="Faiaz Shihan" data-score="10"><div class="score">10</div><div class="name">Faiaz Shihan</div><div class="comment">Telstra has also been able to provide me with excellent service so I’m so happy with Telstra for being there for me when I don’t understand.</div></div>
<div class="advocate" data-name="Faiaz Shihan" data-score="10"><div class="score">10</div><div class="name">Faiaz Shihan</div><div class="comment">Always excellent, efficient service.</div></div>
<div class="advocate" data-name="Faiaz Shihan" data-score="10"><div class="score">10</div><div class="name">Faiaz Shihan</div><div class="comment">Very prompt and efficient service.</div></div>
<div class="advocate" data-name="Faiaz Shihan" data-score="10"><div class="score">10</div><div class="name">Faiaz Shihan</div><div class="comment">Excellent service.</div></div>

<!-- Kerri Gauld (2) -->
<div class="advocate" data-name="Kerri Gauld" data-score="10"><div class="score">10</div><div class="name">Kerri Gauld</div><div class="comment">I was guided through the problem with professional advice and felt very reassured.</div></div>
<div class="advocate" data-name="Kerri Gauld" data-score="10"><div class="score">10</div><div class="name">Kerri Gauld</div><div class="comment">She was wonderful and very patient.</div></div>

<!-- Ashna Dilnaz (4) -->
<div class="advocate" data-name="Ashna Dilnaz" data-score="10"><div class="score">10</div><div class="name">Ashna Dilnaz</div><div class="comment">Staff were very understanding as I wear hearing aids.</div></div>
<div class="advocate" data-name="Ashna Dilnaz" data-score="10"><div class="score">10</div><div class="name">Ashna Dilnaz</div><div class="comment">Internet was restored quickly.</div></div>
<div class="advocate" data-name="Ashna Dilnaz" data-score="10"><div class="score">10</div><div class="name">Ashna Dilnaz</div><div class="comment">So much patience with my elderly parents.</div></div>
<div class="advocate" data-name="Ashna Dilnaz" data-score="10"><div class="score">10</div><div class="name">Ashna Dilnaz</div><div class="comment">Fixed the problem end-to-end with one person.</div></div>

<!-- Maryam Munib (8) -->
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">They were all very helpful.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="9"><div class="score">9</div><div class="name">Maryam Munib</div><div class="comment">Eager to help each time I rang.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">Internet resolved within a few hours.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">Very helpful and professional staff.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">The man who dealt with the problem was excellent.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">Excellent support from the team.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="10"><div class="score">10</div><div class="name">Maryam Munib</div><div class="comment">Very patient and reassuring.</div></div>
<div class="advocate" data-name="Maryam Munib" data-score="9"><div class="score">9</div><div class="name">Maryam Munib</div><div class="comment">Prompt professional service.</div></div>

<!-- Sudhir Patel (8) -->
<div class="advocate" data-name="Sudhir Patel" data-score="10"><div class="score">10</div><div class="name">Sudhir Patel</div><div class="comment">The team members were very helpful.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="9"><div class="score">9</div><div class="name">Sudhir Patel</div><div class="comment">Service was good and clear.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="9"><div class="score">9</div><div class="name">Sudhir Patel</div><div class="comment">Issue fixed quickly.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="10"><div class="score">10</div><div class="name">Sudhir Patel</div><div class="comment">Help when needed.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="10"><div class="score">10</div><div class="name">Sudhir Patel</div><div class="comment">Prompt service and great attitude.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="10"><div class="score">10</div><div class="name">Sudhir Patel</div><div class="comment">Courtesy and professionalism.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="9"><div class="score">9</div><div class="name">Sudhir Patel</div><div class="comment">Helpful and patient.</div></div>
<div class="advocate" data-name="Sudhir Patel" data-score="10"><div class="score">10</div><div class="name">Sudhir Patel</div><div class="comment">Excellent resolution.</div></div>

<!-- Remaining agents -->
<div class="advocate" data-name="Rita Feng" data-score="9"><div class="score">9</div><div class="name">Rita Feng</div><div class="comment">Patient and obliging.</div></div>
<div class="advocate" data-name="Rita Feng" data-score="10"><div class="score">10</div><div class="name">Rita Feng</div><div class="comment">Staff were incredibly supportive.</div></div>
<div class="advocate" data-name="Rita Feng" data-score="10"><div class="score">10</div><div class="name">Rita Feng</div><div class="comment">Understanding and clear communication.</div></div>

<div class="advocate" data-name="Vincent Padlan" data-score="9"><div class="score">9</div><div class="name">Vincent Padlan</div><div class="comment">Quick and excellent service.</div></div>
<div class="advocate" data-name="Vincent Padlan" data-score="10"><div class="score">10</div><div class="name">Vincent Padlan</div><div class="comment">Very impressed with the staff.</div></div>
<div class="advocate" data-name="Vincent Padlan" data-score="10"><div class="score">10</div><div class="name">Vincent Padlan</div><div class="comment">Excellent explanation and support.</div></div>

<div class="advocate" data-name="Nicholas Halta" data-score="10"><div class="score">10</div><div class="name">Nicholas Halta</div><div class="comment">Team was very supportive.</div></div>
<div class="advocate" data-name="Nicholas Halta" data-score="10"><div class="score">10</div><div class="name">Nicholas Halta</div><div class="comment">No problem with the service.</div></div>
<div class="advocate" data-name="Nicholas Halta" data-score="9"><div class="score">9</div><div class="name">Nicholas Halta</div><div class="comment">Good support overall.</div></div>

<div class="advocate" data-name="Nirali Patel" data-score="10"><div class="score">10</div><div class="name">Nirali Patel</div><div class="comment">Informative and patient.</div></div>

<div class="advocate" data-name="Kylie Husmann" data-score="10"><div class="score">10</div><div class="name">Kylie Husmann</div><div class="comment">Resolved promptly.</div></div>
<div class="advocate" data-name="Kylie Husmann" data-score="10"><div class="score">10</div><div class="name">Kylie Husmann</div><div class="comment">Problem fixed immediately.</div></div>
<div class="advocate" data-name="Kylie Husmann" data-score="9"><div class="score">9</div><div class="name">Kylie Husmann</div><div class="comment">Very efficient service.</div></div>
<div class="advocate" data-name="Kylie Husmann" data-score="10"><div class="score">10</div><div class="name">Kylie Husmann</div><div class="comment">Good customer service.</div></div>
<div class="advocate" data-name="Kylie Husmann" data-score="10"><div class="score">10</div><div class="name">Kylie Husmann</div><div class="comment">Great experience.</div></div>

<div class="advocate" data-name="Rohan Silver" data-score="10"><div class="score">10</div><div class="name">Rohan Silver</div><div class="comment">Loyal customer since 1990.</div></div>
<div class="advocate" data-name="Rohan Silver" data-score="10"><div class="score">10</div><div class="name">Rohan Silver</div><div class="comment">Patient.</div></div>
<div class="advocate" data-name="Rohan Silver" data-score="10"><div class="score">10</div><div class="name">Rohan Silver</div><div class="comment">Very helpful service.</div></div>

<div class="advocate" data-name="Lakshmi Jagarlamudi" data-score="9"><div class="score">9</div><div class="name">Lakshmi Jagarlamudi</div><div class="comment">Telstra team very helpful.</div></div>
<div class="advocate" data-name="Lakshmi Jagarlamudi" data-score="10"><div class="score">10</div><div class="name">Lakshmi Jagarlamudi</div><div class="comment">Friendly and caring support.</div></div>

<div class="advocate" data-name="Sera Debono" data-score="10"><div class="score">10</div><div class="name">Sera Debono</div><div class="comment">Telstra always fixed technical problems.</div></div>

<div class="advocate" data-name="Alice Iosefo" data-score="10"><div class="score">10</div><div class="name">Alice Iosefo</div><div class="comment">Very patient, kind, and resolved my issue fast.</div></div>

</div>
</div>

<!-- RIGHT -->
<div style="align-self:flex-start;">
<div class="card">
<h3 style="color:#FF6A00; margin-top:0;">Leaderboard</h3>
<ol id="leaderboard"></ol>
</div>
</div>

<script>
function filterAgents(){
const v=document.getElementById("search").value.toLowerCase();
document.querySelectorAll(".advocate").forEach(a=>{
a.style.display=a.dataset.name.toLowerCase().includes(v)?"":"none";
});
}
function buildLeaderboard(){
const c={};
document.querySelectorAll(".advocate").forEach(a=>{
const n=a.dataset.name;
c[n]=(c[n]||0)+1;
});
const l=document.getElementById("leaderboard");
l.innerHTML="";
Object.entries(c).sort((a,b)=>b[1]-a[1]).forEach(([n,v])=>{
const li=document.createElement("li");
li.textContent=`${n} — ${v}`;
l.appendChild(li);
});
}
buildLeaderboard();

  <div class="card" style="margin-top:16px;">
<h3 style="color:#FF6A00; margin-top:0;">Detractor Insight & Fix</h3>

<div class="insight">
<strong>What drives 0–6 scores</strong><br>
Customers score low when their issue is not resolved on first contact and
requires repeated effort, follow-ups, or self-resolution — even when staff
are polite and professional.
</div>

<div class="insight" style="margin-top:12px;">
<strong>How we fix this</strong>
<ul style="margin-top:6px; padding-left:18px;">
<li>Strengthen first-contact ownership end to end</li>
<li>Reduce handoffs and repeat explanations</li>
<li>Set clear resolution expectations and next steps</li>
<li>Confirm resolution before case closure</li>
</ul>
</div>
</div>
</script>

</body>
</html>
