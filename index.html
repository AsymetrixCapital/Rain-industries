# Rain-industries
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Rain Industries — Deep Dive Research</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{background:#f5f0e8;color:#0f1a14;font-family:Georgia,serif;font-size:16px;line-height:1.75;}

/* NAV */
.nav{background:#0f1a14;position:sticky;top:0;z-index:999;padding:0 24px;}
.nav-inner{max-width:1100px;margin:0 auto;display:flex;align-items:center;flex-wrap:nowrap;overflow-x:auto;gap:2px;}
.nav-logo{color:#f5f0e8;font-size:14px;font-weight:bold;padding:14px 20px 14px 0;white-space:nowrap;flex-shrink:0;border-right:1px solid rgba(255,255,255,0.1);margin-right:8px;}
.nb{background:none;border:none;color:rgba(245,240,232,0.5);font-family:Arial,sans-serif;font-size:11px;font-weight:600;letter-spacing:0.05em;padding:16px 12px;cursor:pointer;white-space:nowrap;border-bottom:2px solid transparent;}
.nb:hover{color:rgba(245,240,232,0.85);}
.nb.on{color:#c8a020;border-bottom-color:#c8a020;}

/* SECTIONS */
.sec{display:none;}
.sec.on{display:block;}

/* HERO */
.hero{background:#0f1a14;padding:60px 32px 52px;}
.hero-in{max-width:900px;margin:0 auto;}
.tag{display:inline-block;font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:#c8a020;border:1px solid #c8a020;padding:4px 13px;margin-bottom:22px;}
.h1{font-size:clamp(34px,5.5vw,62px);color:#f5f0e8;line-height:1.08;margin-bottom:8px;}
.hsub{font-family:Arial,sans-serif;font-size:12px;color:rgba(245,240,232,0.35);letter-spacing:0.12em;text-transform:uppercase;margin-bottom:24px;}
.hq{font-style:italic;font-size:17px;color:rgba(245,240,232,0.70);max-width:640px;line-height:1.65;border-left:3px solid #c8a020;padding-left:18px;margin-bottom:44px;}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:rgba(255,255,255,0.08);border:1px solid rgba(255,255,255,0.08);}
.stat{background:rgba(255,255,255,0.04);padding:20px 16px;text-align:center;}
.sv{display:block;font-size:24px;font-weight:bold;color:#f5f0e8;margin-bottom:4px;}
.sl{display:block;font-family:Arial,sans-serif;font-size:10px;color:rgba(245,240,232,0.32);text-transform:uppercase;letter-spacing:0.08em;line-height:1.35;}

/* BODY */
.wrap{max-width:900px;margin:0 auto;padding:48px 32px 80px;}

/* TYPOGRAPHY */
h2{font-size:24px;color:#0f1a14;margin:48px 0 14px;padding-bottom:10px;border-bottom:2px solid #1a5c38;}
h3{font-size:18px;color:#1a5c38;margin:32px 0 10px;}
h4{font-family:Arial,sans-serif;font-size:14px;font-weight:700;color:#0f1a14;margin:20px 0 7px;}
p{margin-bottom:16px;color:#1a2a1e;line-height:1.75;}
strong{color:#0f1a14;}
.lead{font-style:italic;font-size:18px;line-height:1.65;padding-left:20px;border-left:3px solid #c8a020;margin-bottom:40px;color:#0f1a14;}

/* CALLOUTS */
.co{padding:18px 22px;margin:20px 0;border-left:4px solid;border-radius:2px;}
.co.g{background:#d4edd9;border-color:#1a5c38;}
.co.a{background:#fdf8e1;border-color:#c8a020;}
.co.r{background:#fdecea;border-color:#c8401a;}
.co.dk{background:#0f1a14;border-color:#c8a020;}
.co-lbl{font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;display:block;margin-bottom:7px;}
.co.g .co-lbl{color:#1a5c38;}
.co.a .co-lbl{color:#c8a020;}
.co.r .co-lbl{color:#c8401a;}
.co.dk .co-lbl{color:#c8a020;}
.co p{margin:0;font-size:14px;line-height:1.7;}
.co.g p{color:#0a2010;}
.co.r p{color:#2a0808;}
.co.dk p{color:rgba(245,240,232,0.82);}

/* LISTS */
ul.bl{list-style:none;margin:12px 0 22px;}
ul.bl li{padding:7px 0 7px 24px;position:relative;font-size:15px;color:#1a2a1e;border-bottom:1px solid rgba(208,200,188,0.4);}
ul.bl li:last-child{border-bottom:none;}
ul.bl li::before{content:“▶”;position:absolute;left:0;top:11px;color:#1a5c38;font-size:8px;}

/* TABLES */
.tw{overflow-x:auto;margin:20px 0;}
table{width:100%;border-collapse:collapse;font-family:Arial,sans-serif;font-size:13px;}
th{background:#0f1a14;color:#f5f0e8;padding:10px 13px;text-align:left;font-size:11px;letter-spacing:0.04em;}
td{padding:9px 13px;border-bottom:1px solid #d0c8bc;color:#1a2a1e;vertical-align:top;}
tr:nth-child(even) td{background:#fffdf7;}
.gd{color:#1a5c38;font-weight:700;}
.rd{color:#c8401a;font-weight:700;}
.ad{color:#c8a020;font-weight:700;}

/* STAT GRIDS */
.sg{display:grid;gap:12px;margin:22px 0;}
.sg3{grid-template-columns:repeat(3,1fr);}
.sg4{grid-template-columns:repeat(4,1fr);}
.sg2{grid-template-columns:repeat(2,1fr);}
.sc{background:#fffdf7;border:1px solid #d0c8bc;padding:18px;text-align:center;border-radius:2px;}
.sc.dk{background:#0f1a14;}
.sc-v{display:block;font-size:26px;font-weight:bold;color:#1a5c38;margin-bottom:4px;}
.sc.dk .sc-v{color:#c8a020;}
.sc-l{font-family:Arial,sans-serif;font-size:10px;color:#4a5c52;text-transform:uppercase;letter-spacing:0.08em;line-height:1.4;}
.sc.dk .sc-l{color:rgba(245,240,232,0.36);}

/* THESIS BOX */
.thesis{background:#0f1a14;padding:36px 40px;border-radius:2px;margin-bottom:36px;position:relative;overflow:hidden;}
.thesis::before{content:’”’;font-size:140px;color:rgba(26,92,56,0.12);position:absolute;top:-30px;left:10px;line-height:1;pointer-events:none;}
.t-kick{font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:#c8a020;margin-bottom:10px;display:block;}
.t-body{font-style:italic;font-size:clamp(14px,1.8vw,17px);line-height:1.68;color:rgba(245,240,232,0.86);position:relative;z-index:1;margin-bottom:18px;}
.tags{display:flex;flex-wrap:wrap;gap:7px;}
.tg{font-family:Arial,sans-serif;font-size:10px;font-weight:600;letter-spacing:0.08em;text-transform:uppercase;border:1px solid rgba(245,240,232,0.18);padding:3px 11px;border-radius:18px;color:rgba(245,240,232,0.48);}

/* TIMELINE */
.tl-item{display:flex;gap:16px;margin-bottom:26px;}
.tl-dot{width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;color:#fff;flex-shrink:0;margin-top:2px;}
.tl-dot.g{background:#1a5c38;}
.tl-dot.a{background:#c8a020;}
.tl-yr{font-family:Arial,sans-serif;font-size:10px;font-weight:700;color:#c8a020;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:2px;}
.tl-t{font-size:17px;font-weight:bold;color:#0f1a14;margin-bottom:3px;}
.tl-d{font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;line-height:1.6;}

/* PHASES */
.phases{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin:22px 0;}
.ph{padding:16px 12px;border-radius:2px;text-align:center;}
.ph.done{background:#d4edd9;border:1px solid #1a5c38;}
.ph.now{background:#0f1a14;}
.ph.next{background:#fffdf7;border:1px solid #d0c8bc;opacity:0.7;}
.ph.sell{background:#fdecea;border:1px solid #c8401a;opacity:0.7;}
.ph-n{font-size:24px;font-weight:bold;margin-bottom:3px;}
.ph.done .ph-n{color:#1a5c38;}
.ph.now .ph-n{color:#c8a020;}
.ph.next .ph-n{color:#4a5c52;}
.ph.sell .ph-n{color:#c8401a;}
.ph-name{font-family:Arial,sans-serif;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:0.07em;margin-bottom:3px;}
.ph.done .ph-name{color:#1a5c38;}
.ph.now .ph-name{color:#f5f0e8;}
.ph.next .ph-name{color:#4a5c52;}
.ph.sell .ph-name{color:#c8401a;}
.ph-note{font-family:Arial,sans-serif;font-size:11px;}
.ph.done .ph-note{color:#1a5c38;}
.ph.now .ph-note{color:rgba(245,240,232,0.6);}
.ph.next .ph-note{color:#4a5c52;}
.ph.sell .ph-note{color:#c8401a;}

/* FLOW */
.flow{background:#0f1a14;padding:24px;border-radius:3px;margin:22px 0;}
.flow-t{font-family:Arial,sans-serif;font-size:13px;font-weight:700;color:#f5f0e8;text-align:center;margin-bottom:18px;letter-spacing:0.05em;}
.flow-row{display:flex;align-items:center;gap:6px;flex-wrap:wrap;margin-bottom:10px;}
.fb{background:rgba(255,255,255,0.07);border:1px solid rgba(255,255,255,0.12);padding:10px 13px;text-align:center;flex:1;min-width:90px;border-radius:2px;}
.fb.hl{background:rgba(26,92,56,0.3);border-color:#1a5c38;}
.fb-t{font-family:Arial,sans-serif;font-size:12px;font-weight:700;color:#f5f0e8;margin-bottom:2px;}
.fb-s{font-family:Arial,sans-serif;font-size:10px;color:rgba(245,240,232,0.45);}
.arr{font-size:18px;color:#c8a020;flex-shrink:0;}

/* PENDULUM */
.pend{background:#0f1a14;padding:26px;border-radius:3px;margin:22px 0;}
.pend-t{font-family:Arial,sans-serif;font-size:13px;font-weight:700;color:#f5f0e8;text-align:center;margin-bottom:18px;}
.pend-lbls{display:flex;justify-content:space-between;margin-bottom:5px;}
.pl{font-family:Arial,sans-serif;font-size:11px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;}
.pl.fear{color:#c8401a;}
.pl.greed{color:#1a5c38;}
.pend-track{position:relative;height:12px;border-radius:6px;background:linear-gradient(90deg,#c8401a 0%,#e8d080 50%,#1a5c38 100%);margin-bottom:16px;}
.pend-mark{position:absolute;top:-13px;width:38px;height:38px;background:#fff;border:3px solid #c8a020;border-radius:50%;left:55%;transform:translateX(-50%);box-shadow:0 2px 10px rgba(0,0,0,0.4);}
.pend-mark::after{content:“NOW”;position:absolute;bottom:-20px;left:50%;transform:translateX(-50%);font-family:Arial,sans-serif;font-size:8px;font-weight:700;color:#c8a020;letter-spacing:0.1em;white-space:nowrap;}
.pend-zones{display:grid;grid-template-columns:1fr 1fr 1fr;gap:4px;margin-top:26px;}
.pend-zone{text-align:center;font-family:Arial,sans-serif;font-size:10px;color:rgba(245,240,232,0.4);line-height:1.4;}

/* CHECKLIST */
.ck-item{display:flex;gap:14px;padding:16px 0;border-bottom:1px solid #d0c8bc;}
.ck-item:last-child{border-bottom:none;}
.ck-icon{width:30px;height:30px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:Arial,sans-serif;font-size:12px;font-weight:700;flex-shrink:0;margin-top:2px;}
.ck-icon.pass{background:#d4edd9;color:#1a5c38;}
.ck-icon.warn{background:#fdf8e1;color:#c8a020;}
.ck-icon.fail{background:#fdecea;color:#c8401a;}
.ck-q{font-weight:bold;font-size:14px;color:#0f1a14;margin-bottom:5px;}
.ck-a{font-family:Arial,sans-serif;font-size:13px;color:#1a2a1e;line-height:1.65;}

/* RISK */
.risk{background:#fffdf7;border:1px solid #d0c8bc;border-left:4px solid;padding:18px 22px;border-radius:2px;margin-bottom:12px;}
.risk.h{border-left-color:#c8401a;}
.risk.m{border-left-color:#c8a020;}
.risk.l{border-left-color:#1a5c38;}
.risk-hdr{display:flex;justify-content:space-between;align-items:flex-start;gap:10px;margin-bottom:9px;}
.risk-t{font-size:17px;font-weight:bold;color:#0f1a14;}
.rb{font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;padding:3px 9px;border-radius:2px;flex-shrink:0;}
.rb.h{background:#fdecea;color:#c8401a;}
.rb.m{background:#fdf8e1;color:#c8a020;}
.rb.l{background:#d4edd9;color:#1a5c38;}
.risk-b{font-family:Arial,sans-serif;font-size:13px;color:#1a2a1e;line-height:1.7;}
.risk-sig{margin-top:9px;padding:8px 12px;background:rgba(0,0,0,0.04);border-radius:2px;font-family:Arial,sans-serif;font-size:12px;color:#4a5c52;}

/* PAYOFF */
.payoff{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin:22px 0;}
.pb{padding:20px;border-radius:2px;border:2px solid;}
.pb.bull{border-color:#1a5c38;background:#d4edd9;}
.pb.base{border-color:#2d7a50;background:#eef7f1;}
.pb.bear{border-color:#c8401a;background:#fdecea;}
.pb.tail{border-color:#aaa;background:#f5f5f5;}
.pb-lbl{font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;display:block;margin-bottom:7px;}
.pb.bull .pb-lbl{color:#1a5c38;}
.pb.base .pb-lbl{color:#1a6040;}
.pb.bear .pb-lbl{color:#c8401a;}
.pb.tail .pb-lbl{color:#666;}
.pb-mult{font-size:36px;font-weight:bold;display:block;margin-bottom:7px;}
.pb.bull .pb-mult{color:#1a5c38;}
.pb.base .pb-mult{color:#1a6040;}
.pb.bear .pb-mult{color:#c8401a;}
.pb.tail .pb-mult{color:#888;}
.pb-d{font-family:Arial,sans-serif;font-size:13px;color:#1a2a1e;line-height:1.6;}

/* DASH */
.dash{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:22px 0;}
.dm{background:#fffdf7;border:1px solid #d0c8bc;border-top:3px solid;padding:15px;}
.dm.g{border-top-color:#1a5c38;}
.dm.a{border-top-color:#c8a020;}
.dm.r{border-top-color:#c8401a;}
.dm-l{font-family:Arial,sans-serif;font-size:10px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;color:#4a5c52;margin-bottom:5px;}
.dm-v{font-size:22px;font-weight:bold;margin-bottom:3px;}
.dm.g .dm-v{color:#1a5c38;}
.dm.a .dm-v{color:#c8a020;}
.dm.r .dm-v{color:#c8401a;}
.dm-n{font-family:Arial,sans-serif;font-size:11px;color:#4a5c52;line-height:1.4;}

/* REC BAR */
.rb-row{display:flex;align-items:center;gap:10px;margin-bottom:7px;}
.rb-lbl{font-family:Arial,sans-serif;font-size:12px;font-weight:600;color:#0f1a14;width:72px;flex-shrink:0;}
.rb-track{flex:1;background:#fffdf7;border:1px solid #d0c8bc;border-radius:2px;height:24px;}
.rb-fill{height:100%;border-radius:2px;display:flex;align-items:center;padding:0 8px;}
.rb-fill span{font-family:Arial,sans-serif;font-size:10px;font-weight:700;color:#fff;}
.rb-pct{font-family:Arial,sans-serif;font-size:12px;font-weight:700;width:36px;text-align:right;flex-shrink:0;}

/* PEER */
.peer-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:22px 0;}
.pc{background:#fffdf7;border:1px solid #d0c8bc;border-top:3px solid;padding:18px;border-radius:2px;}
.pc.rain{border-top-color:#1a5c38;}
.pc.alcoa{border-top-color:#2a5fa5;}
.pc.hind{border-top-color:#7b3fa0;}
.pc.phil{border-top-color:#d4700a;}
.pc h4{font-size:16px;margin-bottom:10px;color:#0f1a14;}
.ps{display:flex;justify-content:space-between;padding:5px 0;border-bottom:1px solid #d0c8bc;font-family:Arial,sans-serif;font-size:12px;}
.ps:last-child{border-bottom:none;}
.ps-l{color:#4a5c52;}
.ps-v{font-weight:700;color:#0f1a14;}

/* EXIT */
.exit{background:#fdecea;border:1px solid rgba(200,64,26,0.2);border-left:4px solid #c8401a;padding:14px 18px;margin-bottom:9px;border-radius:2px;}
.exit h4{font-family:Arial,sans-serif;font-size:13px;font-weight:700;color:#c8401a;margin-bottom:4px;}
.exit p{font-family:Arial,sans-serif;font-size:13px;color:#2a0808;margin:0;line-height:1.6;}

/* CATALYST */
.cc-item{display:flex;gap:14px;padding:13px 0;border-bottom:1px solid #d0c8bc;}
.cc-when{font-family:Arial,sans-serif;font-size:11px;font-weight:700;color:#c8a020;text-transform:uppercase;letter-spacing:0.07em;width:76px;flex-shrink:0;padding-top:2px;}
.cc-what{font-family:Arial,sans-serif;font-size:14px;font-weight:700;color:#0f1a14;margin-bottom:3px;}
.cc-why{font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;line-height:1.5;}

/* LYNCH GRID */
.lg{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin:22px 0;}
.lb{background:#fffdf7;border:1px solid #d0c8bc;padding:18px;border-radius:2px;}
.lb.dk{background:#0f1a14;}
.lb h4{font-size:15px;margin-bottom:7px;color:#0f1a14;}
.lb.dk h4{color:#c8a020;}
.lb p{font-family:Arial,sans-serif;font-size:13px;color:#1a2a1e;margin:0;line-height:1.6;}
.lb.dk p{color:rgba(245,240,232,0.7);}

.src{font-family:Arial,sans-serif;font-size:10px;background:rgba(26,92,56,0.1);color:#1a5c38;padding:2px 7px;border-radius:8px;font-weight:700;}
.div{height:1px;background:#d0c8bc;margin:32px 0;}

footer{background:#0f1a14;color:rgba(245,240,232,0.38);text-align:center;padding:28px 24px;font-family:Arial,sans-serif;font-size:11px;line-height:1.8;}
footer strong{color:rgba(245,240,232,0.6);}

@media(max-width:680px){
.stats,.sg4{grid-template-columns:repeat(2,1fr);}
.sg3,.sg2{grid-template-columns:1fr;}
.phases,.payoff,.peer-grid,.lg,.dash{grid-template-columns:1fr 1fr;}
.wrap{padding:32px 18px 60px;}
.hero{padding:44px 18px 40px;}
.thesis{padding:24px 18px;}
}
</style>

</head>
<body>
<!-- NAV -->
<nav class="nav">
 <div class="nav-inner">
  <div class="nav-logo">RAIN Deep Dive</div>
  <button class="nb on" onclick="go('home')">Overview</button>
  <button class="nb" onclick="go('origin')">01 Origin</button>
  <button class="nb" onclick="go('fin')">02 Financials</button>
  <button class="nb" onclick="go('sc')">03 Supply Chain</button>
  <button class="nb" onclick="go('marks')">04 Marks</button>
  <button class="nb" onclick="go('pabrai')">05 Pabrai</button>
  <button class="nb" onclick="go('moat')">06 Moat</button>
  <button class="nb" onclick="go('peers')">07 Peers</button>
  <button class="nb" onclick="go('risks')">08 Risks</button>
  <button class="nb" onclick="go('lynch')">09 Lynch</button>
  <button class="nb" onclick="go('mon')">10 Monitor</button>
 </div>
</nav>

<!-- ======================================================
     HOME
====================================================== -->

<div id="home" class="sec on">
<div class="hero">
 <div class="hero-in">
  <div class="tag">Cycle Turnaround · NSE: RAIN · March 2026 · 18 Source Documents</div>
  <div class="h1">Rain Industries<br>Limited</div>
  <div class="hsub">NSE: RAIN · BSE: 500339 · Hyderabad, India</div>
  <p class="hq">The crowd hunts for AI plays, EV stories, consumption themes. Rain has been converting oil-refinery waste into the backbone of global aluminium for 30 years — and the market prices it as if the business is dying. The business is not dying. The cycle is turning. India's regulatory unlock is permanent. China is capped. That gap between perception and reality is the opportunity.</p>
  <div class="stats">
   <div class="stat"><span class="sv">#1 &amp; #2</span><span class="sl">CTP &amp; CPC Global Rank</span></div>
   <div class="stat"><span class="sv">3.2×</span><span class="sl">Net Debt/EBITDA ↓ from 3.97×</span></div>
   <div class="stat"><span class="sv">₹2,275 Cr</span><span class="sl">CY2025 EBITDA +52% YoY</span></div>
   <div class="stat"><span class="sv">90%+</span><span class="sl">India Plant Utilisation</span></div>
  </div>
 </div>
</div>
<div class="wrap">
 <div class="thesis">
  <span class="t-kick">Core Thesis · March 2026</span>
  <p class="t-body">Rain is the world's largest coal tar pitch producer and second-largest calcined petroleum coke producer — two non-substitutable inputs in every tonne of primary aluminium ever made. A perfect storm of Indian regulatory restriction, commodity cycle collapse, and European energy shock crushed earnings 2022–2024. All three headwinds are now reversing simultaneously. India's plants are back at 90%+ utilisation. EBITDA grew 52% year-on-year. Three consecutive profitable quarters confirmed. And China — the historic swing supplier — is permanently capped at 45 MTPA by government order. The market still prices Rain as a distressed commodity company. The numbers say it is a recovering industrial with irreplaceable global assets and a structural tollbooth on every tonne of non-China aluminium growth for the next decade.</p>
  <div class="tags">
   <span class="tg">Peter Lynch: Cyclical + Turnaround</span>
   <span class="tg">Howard Marks: Stage 2→3 Re-Rating</span>
   <span class="tg">Pabrai: Heads I Win, Tails I Don't Lose Much</span>
   <span class="tg">Asset Play: Replacement Value &gt; Market Cap</span>
   <span class="tg">Munger: Scale + Logistics Moat</span>
  </div>
 </div>

 <h2>All 18 Source Documents</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Document</th><th>Period</th><th>Key Data Extracted</th></tr></thead>
  <tbody>
   <tr><td>Q4 2025 Concall Transcript (×3 copies)</td><td>Mar 2026</td><td>Middle East risk, India CTP update, refinancing, leverage 3.2×, capex US$53Mn</td></tr>
   <tr><td>Q4 2025 Earnings Presentation</td><td>Feb 2026</td><td>Full P&amp;L, segment EBITDA, debt structure, TRIR 0.11, liquidity US$340Mn</td></tr>
   <tr><td>Q3 2025 Concall Transcript</td><td>Nov 2025</td><td>90% India utilisation, cement expansion ₹757 Cr, leverage 3.3×</td></tr>
   <tr><td>Q2 2025 Concall Transcript</td><td>Aug 2025</td><td>Gross debt US$1Bn, refinancing plan, working capital, India CTP timeline</td></tr>
   <tr><td>Q1 2025 Concall Transcript</td><td>May 2025</td><td>GPC spike mechanics, blending strategy revival, working capital build</td></tr>
   <tr><td>Q4 2024 Management Presentation</td><td>Feb 2025</td><td>Trough confirmed, BAM structural shift, VSK ramp, CAQM relief</td></tr>
   <tr><td>Q2 CY2018 Earnings Presentation</td><td>Aug 2018</td><td>Peak margin 18%, EBITDA ₹6.85Bn, EPS ₹8.8, LTM EBITDA US$416Mn</td></tr>
   <tr><td>Q1 CY2018 Earnings Presentation</td><td>May 2018</td><td>HHCR capex US$66Mn, VSK capex US$65Mn, margin 20%</td></tr>
   <tr><td>Q3 CY2017 Earnings Presentation</td><td>Nov 2017</td><td>EBITDA ₹6.74Bn, EPS ₹7.3, margin 22.1%, blending active</td></tr>
   <tr><td>Q2 CY2020 Earnings Presentation</td><td>Jul 2020</td><td>COVID impact, HHCR commercial launch, net debt US$992Mn</td></tr>
   <tr><td>Corporate Presentation Mar 2016</td><td>Mar 2016</td><td>Pre-peak history, CPC blending origins, CTP plant Russia</td></tr>
   <tr><td>Corporate Presentation May 2019</td><td>May 2019</td><td>Post-RÜTGERS integration, petcoke ban, VSK under construction</td></tr>
   <tr><td><strong>Alcoa Q4 2025 Earnings</strong></td><td>Jan 2026</td><td>LME $3,170/t, China 45MTPA cap confirmed, ELYSIS post-2030, US smelter restarts</td></tr>
   <tr><td><strong>Hindalco Q3FY26 Earnings</strong></td><td>Feb 2026</td><td>CPC cost +1% Q4 due to GPC surge, India demand +9% YoY, Aditya expansion</td></tr>
   <tr><td><strong>Phillips 66 Investor Update</strong></td><td>Mar 2026</td><td>~6 MMTPA coke, largest US bottoms upgrading 349 MBD, Permian crude growth</td></tr>
  </tbody>
 </table>
 </div>

 <h2>Investment Framework Summary</h2>
 <div class="sg sg3">
  <div class="sc"><span class="sc-v">2.43×</span><span class="sc-l">Probability-Weighted Expected Return (Pabrai)</span></div>
  <div class="sc"><span class="sc-v">Stage 2→3</span><span class="sc-l">Howard Marks Cycle Position</span></div>
  <div class="sc"><span class="sc-v">7/9</span><span class="sc-l">Peter Lynch Checklist Score</span></div>
 </div>
 <div class="sg sg3">
  <div class="sc dk"><span class="sc-v">US$2.5–3.5Bn</span><span class="sc-l">Replacement Cost of Global Assets</span></div>
  <div class="sc dk"><span class="sc-v">Oct 2028</span><span class="sc-l">Next Major Debt Maturity</span></div>
  <div class="sc dk"><span class="sc-v">US$340Mn</span><span class="sc-l">Current Liquidity Buffer</span></div>
 </div>
 <div class="co a"><span class="co-lbl">How to Navigate This Report</span><p>Use the tabs at the top to switch sections. Start with <strong>01 Origin</strong> for the full story, <strong>02 Financials</strong> for the numbers, <strong>04 Marks / 05 Pabrai</strong> for frameworks, <strong>07 Peers</strong> for Alcoa/Hindalco/Phillips 66 analysis, <strong>09 Lynch</strong> for the checklist, and <strong>10 Monitor</strong> for the live dashboard.</p></div>
</div>
</div>
<!-- ======================================================
     01 ORIGIN
====================================================== -->
<div id="origin" class="sec">
<div class="hero" style="background:#0f2218;">
 <div class="hero-in">
  <div class="tag">01 · Foundation</div>
  <div class="h1">The Tollbooth<br>Nobody Wanted</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">From Hyderabad cement company to the world's #1 CTP producer via two audacious acquisitions. The perfect storm. The three-layer thesis.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Rain is not a great business at a fair price. It is a strategically critical business with irreplaceable global assets built over 50 years that has just survived a perfect storm. The opportunity is the gap between what the market is pricing and what the business is actually doing.</p>

 <div class="sg sg4">
  <div class="sc dk"><span class="sc-v">#2</span><span class="sc-l">Global CPC Producer</span></div>
  <div class="sc dk"><span class="sc-v">#1</span><span class="sc-l">Global CTP Producer</span></div>
  <div class="sc dk"><span class="sc-v">16 Plants</span><span class="sc-l">8 Countries · 3 Continents</span></div>
  <div class="sc dk"><span class="sc-v">50 Years</span><span class="sc-l">Operating History</span></div>
 </div>

 <h2>The Journey — Cement to Carbon Giant</h2>
 <div class="tl-item"><div class="tl-dot g">1</div><div><div class="tl-yr">1974</div><div class="tl-t">Incorporated — Cement Business</div><div class="tl-d">Two integrated cement plants in South India. 'Priya Cement' brand. Pure regional manufacturer for three decades.</div></div></div>
 <div class="tl-item"><div class="tl-dot g">2</div><div><div class="tl-yr">2005</div><div class="tl-t">First CPC Expansion — World's 5th Largest Calciner</div><div class="tl-d">Doubled Visakhapatnam CPC capacity. Nobody was excited about calcined petroleum coke. That was precisely the point.</div></div></div>
 <div class="tl-item"><div class="tl-dot g">3</div><div><div class="tl-yr">2007</div><div class="tl-t">CII Carbon Acquisition — US$619 Million</div><div class="tl-d">World's 2nd largest CPC producer acquired. Six US Gulf Coast plants with deepwater port access. Rain became #2 globally overnight. Revenue tripled. Jagan Nellore led the deal. <span class="src">Q2 CY18 Pres.</span></div></div></div>
 <div class="tl-item"><div class="tl-dot g">4</div><div><div class="tl-yr">2013</div><div class="tl-t">RÜTGERS Acquisition — €702 Million</div><div class="tl-d">World's 2nd largest coal tar distiller. Plants in Belgium, Germany, Canada, Russia. Made Rain the world's #1 CTP producer. Advanced Materials added. CARBORES, NOVARES, PETRORES brands born. <span class="src">Corporate 2019</span></div></div></div>
 <div class="tl-item"><div class="tl-dot g">5</div><div><div class="tl-yr">2017–2022</div><div class="tl-t">Peak Earnings — EPS ₹42.77 (CY2022)</div><div class="tl-d">CY2022: Revenue ₹21,011 Cr, EBITDA ₹3,537 Cr (17% margin), Net Profit ₹1,577 Cr. Margin hit 22.1% in Q3 2017. Peak operational performance. <span class="src">Q3 CY17 Pres.</span></div></div></div>
 <div class="tl-item"><div class="tl-dot a">6</div><div><div class="tl-yr">2018–2024</div><div class="tl-t">The Perfect Storm — Three Simultaneous Hits</div><div class="tl-d">India GPC import ban (Oct 2018), European energy crisis (2022), BAM structural GPC demand squeeze. EBITDA collapsed to ₹933 Cr (2023). Net losses two years running. <span class="src">Q4 2024 Mgmt Pres.</span></div></div></div>
 <div class="tl-item"><div class="tl-dot g">7</div><div><div class="tl-yr">2024–2026</div><div class="tl-t">The Turn — All Three Headwinds Reversing</div><div class="tl-d">India GPC quota expanded + SEZ unlocked (Feb 2024). Both Indian plants at 90%+. EBITDA ₹2,275 Cr (+52% YoY). Three consecutive profitable quarters. Net Debt/EBITDA: 3.97×→3.2×. <span class="src">Q4 2025 Concall</span></div></div></div>

 <h2>The Three-Layer Thesis</h2>
 <div class="co g" style="margin-bottom:12px;"><span class="co-lbl">Layer 1 — Near Term (1–2 Years)</span><p><strong>Cycle Turnaround + P/E Re-Rating.</strong> EBITDA recovering from ₹933 Cr trough toward ₹2,800–3,200 Cr normalised. Three consecutive profitable quarters confirmed. OPM: -15% (Dec 2023) → 14% (Jun–Sep 2025). Market still prices Rain near the trough. As earnings keep improving, P/E re-rating drives near-term returns. This layer is already in motion.</p></div>
 <div class="co a" style="margin-bottom:12px;"><span class="co-lbl">Layer 2 — Medium Term (2–4 Years)</span><p><strong>India Regulatory Unlock + Debt Compression Compounding.</strong> India GPC quota expansion is permanent — not a temporary exemption. Indian plants will continue running at 90%+ regardless of where we are in the aluminium cycle. Adds ₹150–200+ Cr of permanent incremental annual EBITDA. Simultaneously, Debt/EBITDA declining from 3.2× toward 2.5× triggers credit rating upgrade → refinancing at lower rates → dividend resumption → institutional re-entry.</p></div>
 <div class="co dk"><span class="co-lbl">Layer 3 — Long Term (5–10 Years)</span><p><strong>China Cap + Asset Scarcity Tollbooth.</strong> China permanently capped at 45 MTPA by government order. Global aluminium demand growing 3–4% per annum. Every incremental tonne outside China must pass through Rain's kilns or distillation plants. Rain's US Gulf Coast plants cannot be replicated in under 7–10 years. European distillation capacity is SHRINKING. The tollbooth gets more valuable as traffic grows. <em>Alcoa CEO Bill Oplinger (Jan 2026): "China remains near its 45 MMT cap, which we continue to believe will be maintained."</em> <span class="src">Alcoa Q4 2025</span></p></div>

 <h2>The Perfect Storm — Why the Collapse Was NOT Permanent</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Headwind</th><th>Impact</th><th>Status March 2026</th></tr></thead>
  <tbody>
   <tr><td><strong>India GPC Import Ban (Oct 2018)</strong></td><td>Indian plants ran at 30–40% vs 90%+ optimal. VSK plant effectively idle for 6 years.</td><td class="gd">✓ REVERSED — quota expanded Feb 2024, plants at 90%+</td></tr>
   <tr><td><strong>European Energy Crisis (2022)</strong></td><td>Gas €100+/MMBtu. HHCR plant shut Sep 2022. Advanced Materials collapsed.</td><td class="ad">↓ PARTIALLY RECOVERED — gas back to €30–40 vs €10–20 pre-war. Still elevated.</td></tr>
   <tr><td><strong>GPC–CPC Spread Compression</strong></td><td>BAM demand inflated GPC while CPC prices fell. Calcination margins halved.</td><td class="ad">↑ RECOVERING — contract resets flowing through. OPM 14% in Q2–Q3 2025.</td></tr>
   <tr><td><strong>Coal Tar Supply Shortage</strong></td><td>Russian/Ukrainian coal tar inaccessible. BF→EAF reducing supply structurally.</td><td class="ad">ONGOING — alternative materials programme partially offsetting.</td></tr>
  </tbody>
 </table>
 </div>
 <div class="co a"><span class="co-lbl">Critical Nuance</span><p>None of these headwinds destroyed the underlying business. They temporarily destroyed the earnings. Plants kept running. Customer relationships held. Global market position maintained. When headwinds reversed, earnings recovered because the underlying infrastructure was never damaged — it was starved of inputs or volume.</p></div>

 <h2>What the Two Acquisitions Built Together</h2>
 <p>Every tonne of primary aluminium requires ~0.4 tonnes of CPC (the carbon anode body) and ~0.1 tonne of Coal Tar Pitch (the anode binder). After RÜTGERS, Rain produced BOTH at global scale from three continents. No competitor had this combination. No competitor could build it quickly. This is a structural oligopoly position built over 50 years that happens to be in one of the most unglamorous industrial sectors imaginable — which is exactly why the market perpetually misprices it.</p>
</div>
</div>
<!-- ======================================================
     02 FINANCIALS
====================================================== -->
<div id="fin" class="sec">
<div class="hero" style="background:#1c2e22;">
 <div class="hero-in">
  <div class="tag">02 · Financial DNA</div>
  <div class="h1">Trough, Turn<br>&amp; Recovery Map</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Annual P&amp;L from CY2016–2025, quarterly OPM trajectory, leverage journey, balance sheet, debt structure, segment data, normalised earnings scenarios.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Rain's financial story from 2023 to 2025 is one of the cleanest trough-to-recovery patterns in Indian industrials. EBITDA went from ₹933 Cr (trough) to ₹2,275 Cr in two years — a 144% recovery. Net profit went from -₹796 Cr to +₹136 Cr. Debt/EBITDA dropped from 3.97× to 3.2×. These are reported numbers, not forecasts.</p>

 <h2>Annual P&amp;L — Full Historical Picture</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Year</th><th>Revenue (₹ Cr)</th><th>EBITDA (₹ Cr)</th><th>Margin</th><th>Net Profit (₹ Cr)</th><th>EPS (₹)</th></tr></thead>
  <tbody>
   <tr><td>CY2016</td><td>~9,495</td><td>~1,637</td><td class="gd">17.2%</td><td>~291</td><td>~8.7</td></tr>
   <tr><td>CY2017</td><td>11,447</td><td>2,270</td><td class="gd">19.8%</td><td>764</td><td>22.7</td></tr>
   <tr><td>CY2018</td><td>~14,050</td><td>~2,147</td><td class="gd">15.3%</td><td>~730</td><td>21.7</td></tr>
   <tr><td>CY2019</td><td>~12,287</td><td>~1,743</td><td class="ad">14.2%</td><td>~391</td><td>~11.6</td></tr>
   <tr><td>CY2020</td><td>~10,280</td><td>~1,739</td><td class="gd">16.9%</td><td>~266</td><td>~7.9</td></tr>
   <tr><td>CY2022</td><td>21,011</td><td>3,537</td><td class="gd">17.0%</td><td>1,577</td><td class="gd">42.77</td></tr>
   <tr><td>CY2023</td><td>18,141</td><td>933</td><td class="rd">5.0%</td><td class="rd">-796</td><td class="rd">-27.89</td></tr>
   <tr><td>CY2024</td><td>15,374</td><td>1,274</td><td class="ad">8.0%</td><td class="rd">-450</td><td class="rd">-16.78</td></tr>
   <tr><td><strong>CY2025</strong></td><td><strong>16,946</strong></td><td class="gd"><strong>2,275</strong></td><td class="gd"><strong>13.4%</strong></td><td class="gd"><strong>136</strong></td><td class="gd"><strong>1.26</strong></td></tr>
  </tbody>
 </table>
 </div>

 <h2>Quarterly OPM Recovery — Visual</h2>
 <div class="rb-row"><div class="rb-lbl">Dec 2023</div><div class="rb-track"><div class="rb-fill" style="width:4%;background:#c8401a;"><span></span></div></div><div class="rb-pct" style="color:#c8401a;">-15%</div></div>
 <div class="rb-row"><div class="rb-lbl">Mar 2024</div><div class="rb-track"><div class="rb-fill" style="width:28%;background:#c8a020;"><span></span></div></div><div class="rb-pct" style="color:#c8a020;">5%</div></div>
 <div class="rb-row"><div class="rb-lbl">Jun 2024</div><div class="rb-track"><div class="rb-fill" style="width:50%;background:#c8a020;"><span></span></div></div><div class="rb-pct" style="color:#c8a020;">9%</div></div>
 <div class="rb-row"><div class="rb-lbl">Sep 2024</div><div class="rb-track"><div class="rb-fill" style="width:33%;background:#c8a020;"><span></span></div></div><div class="rb-pct" style="color:#c8a020;">6%</div></div>
 <div class="rb-row"><div class="rb-lbl">Dec 2024</div><div class="rb-track"><div class="rb-fill" style="width:50%;background:#c8a020;"><span></span></div></div><div class="rb-pct" style="color:#c8a020;">9%</div></div>
 <div class="rb-row"><div class="rb-lbl">Mar 2025</div><div class="rb-track"><div class="rb-fill" style="width:56%;background:#c8a020;"><span></span></div></div><div class="rb-pct" style="color:#c8a020;">10%</div></div>
 <div class="rb-row"><div class="rb-lbl">Jun 2025</div><div class="rb-track"><div class="rb-fill" style="width:78%;background:#1a5c38;"><span>14%</span></div></div><div class="rb-pct" style="color:#1a5c38;">14%</div></div>
 <div class="rb-row"><div class="rb-lbl">Sep 2025</div><div class="rb-track"><div class="rb-fill" style="width:78%;background:#1a5c38;"><span>14%</span></div></div><div class="rb-pct" style="color:#1a5c38;">14%</div></div>
 <div class="rb-row"><div class="rb-lbl">Dec 2025</div><div class="rb-track"><div class="rb-fill" style="width:67%;background:#1a5c38;"><span>12%</span></div></div><div class="rb-pct" style="color:#1a5c38;">12%</div></div>

 <h2>Leverage Journey</h2>
 <div class="sg sg4">
  <div class="sc"><span class="sc-v" style="color:#c8401a;">4.63×</span><span class="sc-l">Dec 2019</span></div>
  <div class="sc"><span class="sc-v" style="color:#1a5c38;">2.29×</span><span class="sc-l">Dec 2022 (Peak EBITDA)</span></div>
  <div class="sc"><span class="sc-v" style="color:#c8401a;">3.97×</span><span class="sc-l">Dec 2024 (Trough)</span></div>
  <div class="sc"><span class="sc-v" style="color:#c8a020;">3.2×</span><span class="sc-l">Dec 2025 (Now)</span></div>
 </div>

 <h2>Balance Sheet Evolution</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Metric</th><th>Dec 2022</th><th>Dec 2023</th><th>Dec 2024</th><th>Dec 2025</th></tr></thead>
  <tbody>
   <tr><td>Total Assets (₹ Cr)</td><td>21,945</td><td>19,987</td><td>18,935</td><td>20,760</td></tr>
   <tr><td>Fixed Assets (₹ Cr)</td><td>11,977</td><td>11,357</td><td>11,184</td><td>12,543</td></tr>
   <tr><td>Borrowings (₹ Cr)</td><td>9,731</td><td>8,690</td><td>8,494</td><td>9,824</td></tr>
   <tr><td>Reserves (₹ Cr)</td><td>8,360</td><td>7,275</td><td>6,570</td><td>7,382</td></tr>
   <tr><td>ROCE %</td><td class="gd">17%</td><td class="rd">2%</td><td class="ad">4%</td><td class="ad">8%</td></tr>
   <tr><td>Net Debt (US$ Mn)</td><td>~999</td><td>~927</td><td>699</td><td>837</td></tr>
   <tr><td>Liquidity (US$ Mn)</td><td>—</td><td>—</td><td>428</td><td class="gd">340</td></tr>
  </tbody>
 </table>
 </div>

 <h2>Debt Structure — December 2025</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Instrument</th><th>Amount (US$ Mn)</th><th>Maturity</th><th>Rate</th></tr></thead>
  <tbody>
   <tr><td>Euro Senior Secured TLB</td><td>365</td><td>October 2028</td><td>EURIBOR + 300bps</td></tr>
   <tr><td>USD Senior Secured Notes</td><td>445</td><td>September 2029</td><td>~9%+ (callable Mar 2026)</td></tr>
   <tr><td>Other Term Debt</td><td>19</td><td>Various</td><td>Various</td></tr>
   <tr><td>Working Capital Debt</td><td>190</td><td>Revolving</td><td>~7–9%</td></tr>
   <tr><td><strong>Total Gross Debt</strong></td><td><strong>1,007</strong></td><td></td><td>Avg ~9%</td></tr>
   <tr><td>Cash</td><td>(170)</td><td></td><td></td></tr>
   <tr><td><strong>Net Debt</strong></td><td><strong>837</strong></td><td></td><td></td></tr>
  </tbody>
 </table>
 </div>
 <div class="co a"><span class="co-lbl">Working Capital Note</span><p>2025 borrowings rose in ₹ terms due to working capital increase (US$190Mn vs US$96Mn in 2024) and INR depreciation against EUR/USD. Term debt in USD was flat. Working capital build is due to SEZ ramp-up and GPC import quota timing — management guided release in H2 2026. <span class="src">Q4 2025 Concall</span></p></div>

 <h2>CY2025 Segment EBITDA</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Segment</th><th>Revenue (₹ Bn)</th><th>EBITDA (₹ Bn)</th><th>Margin</th><th>YoY EBITDA Change</th></tr></thead>
  <tbody>
   <tr><td><strong>Carbon</strong></td><td>124.98</td><td class="gd">19.97</td><td class="gd">16.0%</td><td class="gd">+62%</td></tr>
   <tr><td>Advanced Materials</td><td>31.62</td><td class="ad">2.20</td><td class="ad">7.0%</td><td class="rd">-14%</td></tr>
   <tr><td>Cement</td><td>11.31</td><td class="ad">0.58</td><td class="ad">5.1%</td><td class="gd">+625%</td></tr>
   <tr><td><strong>Total Consolidated</strong></td><td><strong>167.91</strong></td><td class="gd"><strong>22.75</strong></td><td class="gd"><strong>13.5%</strong></td><td class="gd"><strong>+52%</strong></td></tr>
  </tbody>
 </table>
 </div>

 <h2>Normalised Earnings Scenarios</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Scenario</th><th>Revenue</th><th>EBITDA</th><th>Margin</th><th>Est. EPS (₹)</th><th>Net Debt/EBITDA</th><th>Prob.</th></tr></thead>
  <tbody>
   <tr><td><strong>Bear</strong></td><td>₹16,500 Cr</td><td>₹1,900–2,100 Cr</td><td class="rd">11–12%</td><td class="rd">₹3–6</td><td class="rd">~4×</td><td>20%</td></tr>
   <tr><td><strong>Base</strong></td><td>₹19,000–21,000 Cr</td><td>₹2,600–2,900 Cr</td><td class="ad">13–15%</td><td class="ad">₹12–18</td><td class="ad">~2.8–3×</td><td>55%</td></tr>
   <tr><td><strong>Bull</strong></td><td>₹22,000–24,000 Cr</td><td>₹3,300–3,800 Cr</td><td class="gd">16–18%</td><td class="gd">₹28–40</td><td class="gd">~2–2.3×</td><td>25%</td></tr>
   <tr><td>Historical Peak (2022)</td><td>₹21,011 Cr</td><td>₹3,547 Cr</td><td class="gd">17%</td><td class="gd">₹42.77</td><td class="gd">2.29×</td><td>Ref</td></tr>
  </tbody>
 </table>
 </div>
</div>
</div>
<!-- ======================================================
     03 SUPPLY CHAIN
====================================================== -->
<div id="sc" class="sec">
<div class="hero" style="background:#162438;">
 <div class="hero-in">
  <div class="tag">03 · Operations</div>
  <div class="h1">Supply Chain<br>Anatomy</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">How oil refinery waste and steel by-products become essential aluminium inputs. The global blend strategy. BAM as risk and opportunity. India CTP — first mover.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Rain's business model converts the waste by-products of two major industrial processes into the two non-substitutable inputs every tonne of primary aluminium requires. Capital-intensive, geographically constrained, deeply unglamorous — which is precisely what makes it defensible.</p>

 <h2>The Core Value Chain</h2>
 <div class="flow">
  <div class="flow-t">CPC Calcination — Converting Oil Refinery Waste</div>
  <div class="flow-row">
   <div class="fb"><div class="fb-t">Crude Oil Refining</div><div class="fb-s">By-product: GPC</div></div>
   <div class="arr">→</div>
   <div class="fb hl"><div class="fb-t">Rain: Calcination</div><div class="fb-s">GPC heated to 1,300°C</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">CPC (Anode Body)</div><div class="fb-s">~0.4t per tonne Al</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">Aluminium Smelter</div><div class="fb-s">Electrolytic reduction</div></div>
  </div>
 </div>
 <div class="flow">
  <div class="flow-t">CTP Distillation — Converting Steel By-Product</div>
  <div class="flow-row">
   <div class="fb"><div class="fb-t">Blast Furnace Steel</div><div class="fb-s">By-product: Coal Tar</div></div>
   <div class="arr">→</div>
   <div class="fb hl"><div class="fb-t">Rain: Distillation</div><div class="fb-s">Coal tar → Pitch</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">CTP (Anode Binder)</div><div class="fb-s">~0.1t per tonne Al</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">Same Smelter</div><div class="fb-s">Same anode production</div></div>
  </div>
 </div>
 <div class="co g"><span class="co-lbl">Non-Substitutability</span><p>Every tonne of primary aluminium requires ~0.4t CPC and ~0.1t CTP. No commercially viable substitute exists for either material in the aluminium smelting process at scale. Rain is not serving discretionary buyers — it is supplying a structural engineering requirement. Hindalco explicitly confirmed in Q3FY26 concall: <em>"Expecting costs to be about 1% higher in Q4, largely driven by CP Coke."</em> <span class="src">Hindalco Q3FY26</span></p></div>

 <h2>The Global Blend Strategy — Rain's Hidden Moat</h2>
 <p>This is Rain's most underappreciated competitive advantage. The ability to blend CPC from multiple plants across multiple continents to meet specific smelter specifications at minimum cost is a genuine operational capability that took decades to build and cannot be quickly replicated.</p>
 <ul class="bl">
  <li><strong>US Gulf Coast plants</strong> produce premium CPC from high-quality anode-grade GPC adjacent to ExxonMobil, Valero, Marathon, Phillips 66 refineries — with deepwater port export capability</li>
  <li><strong>India SEZ plant</strong> can import CPC from US plants and blend with locally produced CPC to meet specific density profiles for Asian smelters at lower delivered cost</li>
  <li><strong>Cost optimisation:</strong> blending allows Rain to serve Asian customers at costs no single-region competitor can match — enabling ~5% margin uplift per tonne on blended volumes</li>
  <li><strong>Status:</strong> strategy was SHUT DOWN 2018–2024 due to Indian import restrictions. FULLY REVIVED following the 2024 CAQM order. Scaling through 2025–2026. <span class="src">Q3 2025, Q4 2025 Concalls</span></li>
 </ul>

 <h2>Coal Tar Distillation — The Structural Supply Problem</h2>
 <p>The global shift from blast furnace (BF) to electric arc furnace (EAF) steelmaking is reducing coal tar supply worldwide. As BF capacity declines, coal tar — its by-product — shrinks permanently. This is a secular supply-side headwind that is not going away.</p>
 <ul class="bl">
  <li>Russia-Ukraine war removed Russian and Ukrainian coal tar from the European supply pool entirely <span class="src">Q2 2025 Concall</span></li>
  <li>European BF steel capacity declining for years — closures accelerating post-2022 energy crisis</li>
  <li>Rain's response: importing coal tar from South America and Asia at higher freight cost (partially offset by scale and port location advantages)</li>
  <li>Alternative raw materials programme: petro tar, bio-based pitch precursors — decade-long R&amp;D now showing commercial results</li>
  <li><strong>Key advantage:</strong> Rain's scale and coastal plant locations allow freight arbitrage that smaller European distillers cannot afford — some competitors are now closing, which helps Rain's utilisation</li>
 </ul>

 <h2>Advanced Materials — Product Map</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Product</th><th>End Market</th><th>Position</th><th>2025 Trend</th></tr></thead>
  <tbody>
   <tr><td><strong>NOVARES Resins (incl. eco)</strong></td><td>Tires, adhesives, food packaging</td><td>ISCC-PLUS certified bio-based line differentiates</td><td class="rd">Pressure from Asian imports <span class="src">Q4 2025 Concall</span></td></tr>
   <tr><td><strong>CARBORES / PETRORES</strong></td><td>Graphite electrodes, battery coatings</td><td>Premium specialty; repeat-purchase; EAF electrode demand growing</td><td class="ad">Stable, improving</td></tr>
   <tr><td><strong>LIONCOAT</strong></td><td>Li-ion battery anode coatings</td><td>Proprietary carbon coating IP; selling to Asian BAM producers</td><td class="gd">Growing; Canada R&amp;D scaling</td></tr>
   <tr><td><strong>HHCR (Hydrogenated Resins)</strong></td><td>Food packaging, hygiene</td><td>Ultra-pure water-white; high margin; ramping as European energy normalises</td><td class="gd">Capacity utilisation rising</td></tr>
   <tr><td><strong>BTX Intermediates</strong></td><td>Plastics, solvents, fuels</td><td>Commodity; price taker; crude benzene quotations</td><td class="rd">Benzene fell sharply 2025 — inventory losses <span class="src">Q4 2025 Concall</span></td></tr>
   <tr><td><strong>Phthalic Anhydride (PA)</strong></td><td>Plasticisers, resins</td><td>~10% of AM revenues; benefiting from European competitor exits</td><td class="gd">Improving margins <span class="src">Q1 2025 Concall</span></td></tr>
  </tbody>
 </table>
 </div>

 <h2>India CTP — First Mover in Zero-Competition Market</h2>
 <p>India has <strong>zero</strong> domestic coal tar pitch production. Every kilogram used by NALCO, Hindalco, Vedanta is imported. Rain has secured all regulatory approvals for India's first CTP distillation facility.</p>
 <ul class="bl">
  <li>Phase 1: Coal tar pitch production, targeted start-up Q4 2027 (revised from H2 2026) <span class="src">Q4 2025 Concall</span></li>
  <li>Phase 2: Expand to other carbon products 12–15 months after Phase 1 stabilises</li>
  <li>Domestic CTP will be cheaper for Indian smelters than imported (saves freight + import duties)</li>
  <li>Hindalco's Aditya smelter expansion underway — incremental domestic CTP demand confirmed <span class="src">Hindalco Q3FY26</span></li>
  <li>Revenue contribution: "meaningful" per management from 2027; potential ₹500–700 Cr segment by 2028</li>
 </ul>

 <h2>Global Plant Network</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Location</th><th>Type</th><th>Capacity</th><th>Strategic Advantage</th></tr></thead>
  <tbody>
   <tr><td>Lake Charles + Chalmette, Louisiana</td><td>CPC Calcination + FGD + WHR</td><td>~600k MTPA</td><td>Adjacent to world's largest anode-grade GPC producers; Gulf deepwater ports</td></tr>
   <tr><td>Norco + Gramercy, Louisiana</td><td>CPC Calcination + WHR</td><td>~400k MTPA</td><td>WHR power generation; FGD for high-sulphur GPC processing</td></tr>
   <tr><td>Robinson IL + Purvis MS</td><td>CPC Calcination</td><td>~300k MTPA</td><td>Midcontinent; serving US Midwest smelters</td></tr>
   <tr><td>Visakhapatnam SEZ (India)</td><td>VSK Calcination</td><td>370k MTPA</td><td>Only VSK in India; SEZ export; deepwater port; at 90%+</td></tr>
   <tr><td>Visakhapatnam DTA (India)</td><td>Rotary Calcination</td><td>500k MTPA</td><td>Domestic market; serving Indian aluminium smelters; at 90%+</td></tr>
   <tr><td>Zelzate, Belgium</td><td>Coal Tar Distillation + AM</td><td>~350k MTPA</td><td>European coal tar network; BTX, PA production; inland waterways</td></tr>
   <tr><td>Castrop-Rauxel, Germany</td><td>Coal Tar + Petro Dist. + AM</td><td>~300k MTPA</td><td>HHCR; CARBORES; NOVARES hub; largest advanced materials site</td></tr>
   <tr><td>Hamilton, Canada</td><td>Coal Tar Distillation + R&amp;D</td><td>~263k MTPA</td><td>North American CTP; Technology Innovation Centre for Energy Storage</td></tr>
   <tr><td>Cherepovets, Russia (JV)</td><td>Coal Tar Distillation</td><td>300k MTPA</td><td>JV with PAO Severstal; guaranteed coal tar supply; domestic Russian market only</td></tr>
  </tbody>
 </table>
 </div>
</div>
</div>
<!-- ======================================================
     04 HOWARD MARKS
====================================================== -->
<div id="marks" class="sec">
<div class="hero" style="background:#1a2a3a;">
 <div class="hero-in">
  <div class="tag">04 · Howard Marks Framework</div>
  <div class="h1">Pendulum, Spread<br>Mechanics &amp; Re-Rating</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Where Rain sits on Marks's cycle pendulum. GPC–CPC spread-lag mechanics that create recurring mispricings. The Stage 2→3 re-rating sequence.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Howard Marks says superior investing is not about predicting the future — it is about knowing where you are in the cycle today and acting before the consensus does. Rain's cycle position in March 2026 is unambiguous: the pendulum has swung from maximum pessimism back toward equilibrium. The re-rating has only just begun.</p>

 <h2>The Pendulum — Maximum Pessimism Was Late 2023</h2>
 <div class="pend">
  <div class="pend-t">Rain Industries — Sentiment Pendulum (2022 → 2026)</div>
  <div class="pend-lbls"><span class="pl fear">Maximum Fear</span><span class="pl greed">Maximum Greed</span></div>
  <div class="pend-track"><div class="pend-mark"></div></div>
  <div class="pend-zones">
   <div class="pend-zone">Panic · Dec 2023<br>-15% OPM · -₹1,079 Cr net loss</div>
   <div class="pend-zone"><strong style="color:#c8a020;">← YOU ARE HERE</strong><br>Wall of Worry<br>Early Expansion</div>
   <div class="pend-zone">Peak Optimism<br>2027–2028?<br>Everyone Loves It</div>
  </div>
 </div>
 <p>Maximum fear point identifiable with precision: December 2023. Operating profit was negative ₹612 Crore. Net loss in a single quarter was ₹1,079 Crore. Credit rating outlook cut. FII holding declining. Common analyst verdict: avoid. <strong>This is exactly where Marks says the risk-reward flips.</strong></p>

 <h2>The Four Stages — Where Rain Is Now</h2>
 <div class="phases">
  <div class="ph done"><div class="ph-n">1</div><div class="ph-name">Trough</div><div class="ph-note">✓ Complete<br>Dec 2023</div></div>
  <div class="ph done"><div class="ph-n">2</div><div class="ph-name">Early Recovery</div><div class="ph-note">✓ Confirmed<br>Q2–Q4 2025</div></div>
  <div class="ph now"><div class="ph-n">3</div><div class="ph-name">Expansion</div><div class="ph-note">🚀 Now<br>Underway</div></div>
  <div class="ph sell"><div class="ph-n">4</div><div class="ph-name">Peak</div><div class="ph-note">Not yet<br>2027–28?</div></div>
 </div>
 <div class="co g"><span class="co-lbl">Marks's Second-Level Thinking Applied</span><p>First-level: "Rain had losses in 2023–2024, high debt, uncertain recovery — avoid." Second-level: "Rain had losses because of three simultaneous temporary headwinds, all now reversing. The business is recovering. The market still prices it as if near the trough. That divergence IS the opportunity."</p></div>

 <h2>The Spread-Lag-Contract Mechanics — The Mispricing Engine</h2>
 <p>This creates <em>recurring</em> buying opportunities. The GPC-CPC spread and contract lag dynamics mean that quarterly margin compression often signals future margin expansion — the exact opposite of what most investors infer.</p>
 <h3>How It Works</h3>
 <p>Rain buys GPC (raw material) and sells CPC (finished product). When GPC prices spike suddenly — as happened in Q1 2025 due to Chinese refinery outages and BAM demand — Rain's CPC contracts (set 6–12 months earlier) cannot immediately pass through the higher cost. This creates temporary margin compression that the market reads as business deterioration. In reality, Rain is simultaneously resetting CPC contracts upward to reflect the new cost base.</p>
 <div class="co a"><span class="co-lbl">The Recurring Opportunity</span><p>By Q2 2025, Rain had reset CPC contract prices upward. OPM jumped from 10% to 14% in a single quarter. Gerry Sweeney confirmed Chinese CPC prices "remained above earlier levels by about 100 to 150 US dollars per ton" even after the spike reversed — that residual elevation is the contract reset benefit flowing through. <strong>Investors who understand this buy during the compression phase and profit from the reset. Investors who don't sell during compression and buy back after the reset — too late.</strong> <span class="src">Q2 2025 Concall</span></p></div>

 <h2>Risk Premium Being Systematically Overpriced</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Risk Metric</th><th>Dec 2023 (Trough)</th><th>Dec 2025 (Now)</th><th>Direction</th></tr></thead>
  <tbody>
   <tr><td>Net Debt/EBITDA</td><td class="rd">3.97×</td><td class="ad">3.2×</td><td class="gd">↓ Improving</td></tr>
   <tr><td>Interest Coverage</td><td class="rd">~2.07×</td><td class="ad">~2.5×</td><td class="gd">↑ Improving</td></tr>
   <tr><td>Liquidity (US$ Mn)</td><td class="ad">~$320</td><td class="gd">$340</td><td class="gd">→ Stable</td></tr>
   <tr><td>Next Major Maturity</td><td class="rd">April 2025</td><td class="gd">October 2028</td><td class="gd">✓ Extended</td></tr>
   <tr><td>LTM EBITDA (US$ Mn)</td><td class="rd">~$82</td><td class="gd">$261</td><td class="gd">↑ +218%</td></tr>
   <tr><td>Net Profit</td><td class="rd">-₹796 Cr (CY2023)</td><td class="gd">+₹136 Cr (CY2025)</td><td class="gd">↑ Turned positive</td></tr>
  </tbody>
 </table>
 </div>
 <p>At ₹2,275 Cr EBITDA (2025), the debt is 3.2×. At ₹3,000 Cr (plausible 2026 base case), the SAME debt pile becomes 2.4×. The debt did not change. The risk profile transformed dramatically. The market is still pricing the old 3.97× risk profile.</p>

 <h2>Re-Rating Catalysts — Done vs Pending</h2>
 <div class="sg sg2">
  <div class="sc" style="text-align:left;padding:20px;">
   <div style="font-family:Arial,sans-serif;font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:0.1em;color:#1a5c38;margin-bottom:10px;">✓ Already Triggered</div>
   <ul class="bl" style="margin:0;">
    <li>India GPC quota expanded to 1.9 MTPA (Feb 2024)</li>
    <li>SEZ import unlimited approved</li>
    <li>Both Indian plants at 90%+ utilisation</li>
    <li>2025 USD Notes repaid on schedule (Mar 2025)</li>
    <li>Three consecutive profitable quarters</li>
    <li>US interest deductibility tax change (Jul 2025)</li>
    <li>DII accumulation: 3.16% → 4.87%</li>
   </ul>
  </div>
  <div class="sc" style="text-align:left;padding:20px;">
   <div style="font-family:Arial,sans-serif;font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:0.1em;color:#c8a020;margin-bottom:10px;">○ Pending (Re-Rating Accelerants)</div>
   <ul class="bl" style="margin:0;">
    <li>Net Debt/EBITDA crossing below 3.0×</li>
    <li>Refinancing at sub-8% (callable Mar 2026)</li>
    <li>India CTP Phase 1 revenue (2027)</li>
    <li>Analyst coverage upgrades</li>
    <li>Credit rating upgrade by India Ratings</li>
    <li>Dividend resumption signal</li>
    <li>FII re-entry (declined from 10.82% to 8.54%)</li>
   </ul>
  </div>
 </div>
 <div class="co dk"><span class="co-lbl">The Marks One-Liner on Rain</span><p>"This is a mis-priced cyclical at Stage 2 of recovery. The credit risk has been systematically overpriced since 2023 because the market was anchored to the worst-case scenario. As each quarterly result demonstrates improving leverage, the risk premium in the equity compresses — which IS the re-rating. The investor's task is to be early in recognising the compression, not late in confirming it."</p></div>
</div>
</div>

<!-- ======================================================
     05 PABRAI
====================================================== -->

<div id="pabrai" class="sec">
<div class="hero" style="background:#2a1a08;">
 <div class="hero-in">
  <div class="tag">05 · Pabrai Dhandho</div>
  <div class="h1">Heads I Win,<br>Tails I Don't Lose Much</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Nine-question checklist. Replacement asset floor. Probability-weighted returns. The "bet heavily on the obvious" classification.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Pabrai's Dhandho framework finds situations where the upside is large, the downside is limited by hard assets, and the probability of the favourable outcome is meaningfully higher than the market implies. Rain, at the early expansion stage of a confirmed cyclical recovery with irreplaceable global assets anchoring the downside, fits this precisely.</p>

 <h2>Nine-Question Checklist</h2>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q1: Simple business I can understand?</div><div class="ck-a">Yes. Convert GPC (oil refinery waste) into CPC (aluminium anode material). Convert coal tar (steel by-product) into CTP (anode binder). Every tonne of aluminium needs both. Straightforward converter model. Unglamorous enough that most investors never bother — which is why the mispricing exists.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q2: Durable competitive advantage?</div><div class="ck-a">Partially yes. Scale and logistics moats: 2.4 MTPA calcination (most outside China), strategically located deepwater plants, global blend strategy. 7–10 years minimum to replicate US Gulf plants. Limitation: Rain is a price taker on core CPC and CTP volumes. Moat is defensive logistics and scale, not pricing power. Adequate for Dhandho purposes.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q3: Survived a recent near-death experience?</div><div class="ck-a">Clearly yes. CY2023–2024: negative OPM in Q4 2023 (-15%), net losses of ₹1,246 Cr over two years, interest coverage below 2×, credit outlook cut. Navigated through cost management and successful debt refinancing. Survival itself is a data point — the business is more resilient than trough earnings suggested. <span class="src">Q4 2024 Mgmt Pres.</span></div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q4: Priced well below intrinsic value?</div><div class="ck-a">Yes, on two bases. (1) Replacement cost: US$2.5–3.5 Bn replacement cost of global plants vs current market cap — a significant discount. (2) Earnings basis: normalised base case EBITDA ₹2,800–3,200 Cr represents meaningful earning power well above current trough-anchored pricing.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q5: Management honest and capable?</div><div class="ck-a">Largely yes. Jagan Nellore: 31 years experience, finance background (Citibank Special Situations), no equity dilution through the trough, no distressed asset sales. Family holds 41.19% — completely stable throughout the crisis. One concern: cement represents emotional capital allocation over purely economic returns. Flag but not a deal-breaker.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q6: Multiple independent ways to win?</div><div class="ck-a">Yes — three layers. Layer 1: earnings recovery + P/E re-rating (already in motion). Layer 2: debt reduction → credit upgrade → refinancing savings → dividend resumption. Layer 3: China cap drives non-China aluminium demand, making Rain's scarce assets increasingly valuable. Any one layer provides satisfactory returns. All three compound on each other.</div></div></div>
 <div class="ck-item"><div class="ck-icon warn">!</div><div><div class="ck-q">Q7: Margin of safety large enough?</div><div class="ck-a">Moderate. Safety comes from: (1) replacement asset value as hard floor (US$2.5–3.5 Bn); (2) normalised earnings power significantly above trough-anchored prices. Caveat: normalised EBITDA/tonne depends on BAM-GPC structural question resolving. Pabrai would want more evidence per-tonne margins can return to US$50+ before calling margin of safety "wide." Currently adequate, not wide.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q8: Odds of permanent capital loss low?</div><div class="ck-a">Yes. Even in worst scenario (BAM permanently impairs calcination + coal tar stays scarce), Rain's physical assets retain substantial value. A strategic buyer — Gulf aluminium producer, CPC trader, infrastructure investor — would pay replacement cost for the global plant network. Permanent loss requires both earnings AND asset impairment simultaneously. Lower probability than market implies.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">Q9: Is this in the "too hard" pile?</div><div class="ck-a">No. Business model is simple. Cycle position is clear. Key risk (BAM) is identifiable and monitorable through EBITDA/tonne per quarter. This is not a black box — it is a boring industrial temporarily misunderstood due to three simultaneous headwinds hitting at once.</div></div></div>

 <div class="co a"><span class="co-lbl">Checklist Verdict</span><p>7 clear passes, 1 moderate pass (margin of safety adequate but not wide), 1 conditional pass (management quality good with cement caveat). Pabrai would classify Rain as a "bet heavily on the obvious" — survived near-death, priced below intrinsic value on both asset and earnings bases, multiple independent paths to value creation.</p></div>

 <h2>Replacement Asset Floor — "Tails I Don't Lose Much"</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Asset</th><th>Est. Book</th><th>Replacement Cost</th></tr></thead>
  <tbody>
   <tr><td>6× US Gulf Coast CPC Plants (deepwater ports, FGD, WHR)</td><td>~₹4,000 Cr</td><td class="gd">US$800–1,100 Mn</td></tr>
   <tr><td>Visakhapatnam SEZ VSK + DTA Plants (India)</td><td>~₹1,200 Cr</td><td class="gd">US$150–200 Mn</td></tr>
   <tr><td>Belgium + Germany Distillation + AM Plants</td><td>~₹3,500 Cr</td><td class="gd">US$500–700 Mn</td></tr>
   <tr><td>Canada + Russia Distillation + R&amp;D</td><td>~₹1,500 Cr</td><td class="gd">US$200–300 Mn</td></tr>
   <tr><td>Cement Plants (South India, 4.3 MTPA)</td><td>~₹1,500 Cr</td><td class="gd">₹2,500–3,500 Cr</td></tr>
   <tr><td><strong>Total Portfolio Replacement Cost</strong></td><td>~₹11,700 Cr (book)</td><td class="gd"><strong>US$2.5–3.5 Bn (~₹21,000–29,000 Cr)</strong></td></tr>
  </tbody>
 </table>
 </div>

 <h2>Probability-Weighted Return Matrix</h2>
 <div class="payoff">
  <div class="pb bull"><span class="pb-lbl">🔥 Bull Case · 25%</span><span class="pb-mult">3.5–5×</span><div class="pb-d">EBITDA reaches ₹3,300+ Cr by 2027. Debt/EBITDA below 2.5×. Refinancing at 7%. India CTP revenue starts. Credit upgraded. EPS ₹30–40. Multiple expansion.</div></div>
  <div class="pb base"><span class="pb-lbl">Base Case · 55%</span><span class="pb-mult">1.8–2.5×</span><div class="pb-d">EBITDA reaches ₹2,600–2,900 Cr. Debt/EBITDA approaches 2.8–3×. Moderate P/E re-rating. EPS ₹12–18 in CY2026. Slow, steady deleverage.</div></div>
  <div class="pb bear"><span class="pb-lbl">⚠ Bear Case · 20%</span><span class="pb-mult">0.7–1×</span><div class="pb-d">BAM permanently impairs EBITDA/tonne. Coal tar stays scarce. EBITDA plateaus at ₹1,900–2,200 Cr. Hard asset floor limits losses.</div></div>
  <div class="pb tail"><span class="pb-lbl">Catastrophic · &lt;5%</span><span class="pb-mult">0.3–0.5×</span><div class="pb-d">Debt refinancing failure + distressed asset sale + equity dilution. Requires EBITDA collapse back to 2023 trough AND credit markets seizing simultaneously.</div></div>
 </div>
 <div class="co g"><span class="co-lbl">Expected Return Calculation</span><p>Bull (25% × 4.25×) + Base (55% × 2.15×) + Bear (20% × 0.85×) + Catastrophic (5% × 0.4×) = 1.06 + 1.18 + 0.17 + 0.02 = <strong>~2.43× probability-weighted expected return.</strong> The downside is hard-asset-floored. The upside has three independent catalysts. The math strongly favours participation.</p></div>
</div>
</div>
<!-- ======================================================
     06 MOAT
====================================================== -->
<div id="moat" class="sec">
<div class="hero" style="background:#0f2218;">
 <div class="hero-in">
  <div class="tag">06 · Moat &amp; Asset Play</div>
  <div class="h1">The Tollbooth<br>Economics</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Why Rain is simultaneously a cyclical turnaround AND a multi-decade asset play. China cap. Replacement value. Munger's four moat layers scored.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">The most powerful investment situations arise when a business with irreplaceable physical assets is also experiencing a cyclical earnings recovery. Rain is both simultaneously. The earnings recovery generates near-term returns. The asset scarcity generates long-term returns that compound independently.</p>

 <h2>Munger's Moat Test — Four Real Competitive Advantages</h2>
 <div class="sg sg2">
  <div class="sc" style="text-align:left;padding:20px;border-top:3px solid #1a5c38;">
   <div style="font-size:28px;font-weight:bold;color:#1a5c38;margin-bottom:4px;">9.5/10</div>
   <h4>Logistics &amp; Port Infrastructure</h4>
   <p style="font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;margin:0;line-height:1.6;">US Gulf Coast deepwater ports adjacent to GPC producers. Visakhapatnam SEZ deepwater port. Belgian &amp; German plants with inland waterway access. Hamilton Canada. This network took 50 years to assemble. Cannot be replicated quickly.</p>
  </div>
  <div class="sc" style="text-align:left;padding:20px;border-top:3px solid #1a5c38;">
   <div style="font-size:28px;font-weight:bold;color:#1a5c38;margin-bottom:4px;">9.0/10</div>
   <h4>Scale &amp; Geographic Network</h4>
   <p style="font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;margin:0;line-height:1.6;">2.4 MTPA calcination — most outside China. 1.3 MTPA coal tar distillation across 4 continents. No competitor can replicate this footprint without decades and billions of dollars. Each plant took 3–7 years to permit and build.</p>
  </div>
  <div class="sc" style="text-align:left;padding:20px;border-top:3px solid #c8a020;">
   <div style="font-size:28px;font-weight:bold;color:#c8a020;margin-bottom:4px;">8.5/10</div>
   <h4>Global Blend Strategy</h4>
   <p style="font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;margin:0;line-height:1.6;">Blend CPC from US + India plants to meet specific smelter specifications at minimum cost. No single-region competitor can replicate this. Six years of being unable to execute it showed how uniquely valuable it is when available.</p>
  </div>
  <div class="sc" style="text-align:left;padding:20px;border-top:3px solid #c8a020;">
   <div style="font-size:28px;font-weight:bold;color:#c8a020;margin-bottom:4px;">7.5/10</div>
   <h4>Proprietary Technologies</h4>
   <p style="font-family:Arial,sans-serif;font-size:13px;color:#4a5c52;margin:0;line-height:1.6;">ACP (patented — upgrades lower-grade GPC), LIONCOAT (battery coating IP), CARBORES (specialty electrode pitch), NOVARES-eco (ISCC-PLUS certified bio-resins). Premium-priced, repeat-purchase products in defensible niches.</p>
  </div>
 </div>
 <div class="co r"><span class="co-lbl">Munger's Limitation Warning</span><p><strong>No pricing power on core CPC and CTP volumes.</strong> Rain is a price-taker, not a price-maker. The moats are defensive (location, scale, logistics) — not offensive (brand, IP, switching costs). This makes Rain a "good cyclical with structural floor" rather than a compounder. Munger would own it through the cycle but would not call it a Berkshire-style holding forever.</p></div>

 <h2>The China Cap — The Most Important Macro Fact</h2>
 <div class="co dk"><span class="co-lbl">Alcoa CEO Bill Oplinger · January 22, 2026</span><p>"China remains near its 45 MMT cap, which we continue to believe will be maintained." This is a lollapalooza event — creating multiple independent tailwinds for Rain simultaneously over the next decade. <span class="src">Alcoa Q4 2025</span></p></div>
 <div class="tw">
 <table>
  <thead><tr><th>Factor</th><th>Data Point</th><th>Source</th><th>Rain Impact</th></tr></thead>
  <tbody>
   <tr><td>China production cap</td><td>Hard 45 MTPA — government policy</td><td class="ad">Alcoa Q4 2025</td><td class="gd">All incremental demand goes to non-China smelters. Rain serves them.</td></tr>
   <tr><td>Global Al demand</td><td>~72 MTPA, growing 3–4% per annum</td><td class="ad">Hindalco Q3FY26</td><td class="gd">Each incremental tonne requires Rain's CPC + CTP</td></tr>
   <tr><td>Indonesia expansion</td><td>~700,000 MT new production in 2026</td><td class="ad">Alcoa Q4 2025</td><td class="gd">Rain building customer relationships in Indonesia</td></tr>
   <tr><td>US aluminium renaissance</td><td>Section 232 tariffs; greenfield smelter announced; restarts underway</td><td class="ad">Alcoa Q4 2025</td><td class="gd">Rain's 6 US Gulf plants ideally positioned</td></tr>
   <tr><td>India demand</td><td>+9% YoY demand growth Q3FY26</td><td class="ad">Hindalco Q3FY26</td><td class="gd">India calcination + planned India CTP facility serve growing demand</td></tr>
   <tr><td>ELYSIS NOT near-term</td><td>No groundbreaking until post-2030</td><td class="ad">Alcoa Q4 2025</td><td class="gd">Carbon anodes essential through this entire decade</td></tr>
   <tr><td>LME aluminium price</td><td>~US$3,170/tonne (Feb 2026)</td><td class="ad">Alcoa Q4 2025</td><td class="gd">Strong smelter profitability supports CPC/CTP pricing in contract rounds</td></tr>
  </tbody>
 </table>
 </div>

 <h2>The Tollbooth Compounding Effect</h2>
 <ul class="bl">
  <li>US Gulf Coast plants cannot be replicated in under 7–10 years due to environmental permitting — effective barrier to entry</li>
  <li>European distillation capacity is <strong>SHRINKING</strong>, not growing — smaller distillers closing due to coal tar scarcity and energy costs; Rain gains their market share</li>
  <li>India CTP distillation will be the <strong>FIRST domestic CTP producer in India</strong> — first-mover regulatory approvals take years for any competitor to replicate</li>
  <li>China's domestic calcination is already GPC-deficient for its own smelters — cannot meaningfully export CPC to service non-China demand at scale</li>
  <li>As non-China aluminium production grows from ~30.5 MTPA (2025) toward 35–40 MTPA (2030+), Rain's existing plant utilisation increases from 70% toward 85–90% with minimal additional capex — the tollbooth gets more valuable as traffic grows</li>
 </ul>

 <h2>Phillips 66 — The GPC Supply Context</h2>
 <p>Phillips 66's March 2026 investor update highlights approximately 6 million metric tonnes of annual coke production, with the largest US bottoms upgrading capacity at 349 MBD — higher than any US refining peer. Their heavy crude slate strategy and Permian/Canadian crude growth directly impacts GPC quality and availability at Rain's adjacent US Gulf plants. <span class="src">Phillips 66 Investor Update Mar 2026</span></p>
 <div class="co a"><span class="co-lbl">The Phillips 66 Connection</span><p>Phillips 66 is a key GPC supplier to Rain's US Gulf operations. Their investment in Permian crude processing and 6 MMTPA coke production capacity make them one of Rain's most important upstream partners. Their ongoing heavy crude strategy ensures continued availability of anode-grade GPC at Rain's doorstep — a crucial input for Rain's calcination plants to keep running at high utilisation.</p></div>
</div>
</div>
<!-- ======================================================
     07 PEERS
====================================================== -->
<div id="peers" class="sec">
<div class="hero" style="background:#1a1a2e;">
 <div class="hero-in">
  <div class="tag">07 · Peer Comparison</div>
  <div class="h1">Alcoa · Hindalco<br>Phillips 66</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">What Rain's three upstream peers tell us. Aluminium demand signals from Alcoa. India demand validated by Hindalco. GPC supply chain anchored by Phillips 66.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Rain does not have direct listed peers — no company combines global CPC calcination, coal tar pitch distillation, and advanced materials at this scale. But the three companies in our documents provide critical context: Alcoa as the aluminium demand signal, Hindalco as Indian demand validator, and Phillips 66 as the GPC supply chain anchor.</p>

 <h2>How They Fit in Rain's Value Chain</h2>
 <div class="flow">
  <div class="flow-t">Rain's Position in the Global Aluminium Value Chain</div>
  <div class="flow-row">
   <div class="fb"><div class="fb-t">Phillips 66</div><div class="fb-s">GPC Producer ~6 MMTPA coke</div></div>
   <div class="arr">→</div>
   <div class="fb hl"><div class="fb-t">RAIN INDUSTRIES</div><div class="fb-s">CPC Calcination + CTP Distillation</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">Alcoa / Hindalco</div><div class="fb-s">Aluminium Smelting — Customers</div></div>
   <div class="arr">→</div>
   <div class="fb"><div class="fb-t">Primary Aluminium</div><div class="fb-s">EVs, Packaging, Aerospace</div></div>
  </div>
 </div>

 <h2>Alcoa Q4 2025 — Demand Signal for Rain</h2>
 <p><span class="src">Source: Alcoa Q4 2025 Earnings Call · January 22, 2026</span></p>
 <div class="peer-grid">
  <div class="pc alcoa">
   <h4>Alcoa Financials Q4 2025</h4>
   <div class="ps"><span class="ps-l">Q4 Revenue</span><span class="ps-v">US$3.4 Bn (+15% QoQ)</span></div>
   <div class="ps"><span class="ps-l">Adj. EBITDA</span><span class="ps-v">US$546 Mn</span></div>
   <div class="ps"><span class="ps-l">LME Al Price (Feb 2026)</span><span class="ps-v">US$3,200/tonne</span></div>
   <div class="ps"><span class="ps-l">ROE 2025</span><span class="ps-v">16.4%</span></div>
   <div class="ps"><span class="ps-l">Free Cash Flow 2025</span><span class="ps-v">US$594 Mn</span></div>
   <div class="ps"><span class="ps-l">Net Debt Target</span><span class="ps-v">US$1–1.5 Bn</span></div>
  </div>
  <div class="pc alcoa" style="grid-column:span 2;">
   <h4>Critical Signals for Rain's Thesis</h4>
   <ul class="bl" style="margin:0;">
    <li><strong>China cap confirmed:</strong> "China remains near its 45 MMT cap, which we continue to believe will be maintained." — CEO Bill Oplinger. Validates Rain's Layer 3 thesis directly.</li>
    <li><strong>LME at US$3,200:</strong> Highest levels in years. Strong smelter profitability supports CPC/CTP pricing negotiations in Rain's favour during 2026 contract rounds.</li>
    <li><strong>Indonesia adding 700k MT in 2026:</strong> Rain is building customer relationships in Indonesia — new captive demand for CPC and CTP outside China.</li>
    <li><strong>US smelter restarts confirmed:</strong> Alcoa restarted capacity. Century restarted. Two greenfield US smelters announced. Rain's 6 US Gulf plants ideally positioned to supply all new demand.</li>
    <li><strong>San Ciprián (Spain) restart:</strong> 65% operational end 2025, full restart H1 2026. Direct incremental CTP demand as Spain imports all pitch.</li>
    <li><strong>ELYSIS is NOT a near-term threat:</strong> CEO: "No ELYSIS groundbreaking until post-2030. Still a lot of water to go under the bridge." Carbon anodes essential through this decade and beyond.</li>
    <li><strong>LME inventories at 15-year low year-end 2025:</strong> Tight market supports pricing power for all inputs including CPC and CTP in contract negotiations.</li>
   </ul>
  </div>
 </div>

 <h2>Hindalco Q3FY26 — India Demand Validator</h2>
 <p><span class="src">Source: Hindalco Q3 FY2026 Earnings Call · February 12, 2026</span></p>
 <div class="peer-grid">
  <div class="pc hind">
   <h4>Hindalco India Q3FY26</h4>
   <div class="ps"><span class="ps-l">India Al Demand Growth</span><span class="ps-v">+9% YoY</span></div>
   <div class="ps"><span class="ps-l">Upstream EBITDA/tonne</span><span class="ps-v">US$1,572</span></div>
   <div class="ps"><span class="ps-l">Upstream EBITDA Margin</span><span class="ps-v">45%</span></div>
   <div class="ps"><span class="ps-l">CPC Cost Impact Q4</span><span class="ps-v" style="color:#c8401a;">+1% due to GPC prices</span></div>
   <div class="ps"><span class="ps-l">Net Debt/EBITDA (Consol.)</span><span class="ps-v">1.73×</span></div>
   <div class="ps"><span class="ps-l">Renewable Energy</span><span class="ps-v">418 MW capacity</span></div>
  </div>
  <div class="pc hind" style="grid-column:span 2;">
   <h4>Critical Signals for Rain's Thesis</h4>
   <ul class="bl" style="margin:0;">
    <li><strong>CPC costs rising +1% in Q4:</strong> CFO stated cost of production increasing "largely driven by CP Coke" due to GPC price surge in China. This directly validates Rain's GPC-CPC spread mechanics and contract reset thesis in real-time.</li>
    <li><strong>India aluminium demand +9% YoY:</strong> "Growth remains broad-based, with autos buoyed by GST 2.0 reform, strong momentum in solar." Hindalco is a direct customer for Rain's India calcination plants.</li>
    <li><strong>Aditya upstream expansion in progress:</strong> Hindalco adding significant smelting capacity in India. Each new tonne of Indian aluminium production requires CPC and CTP. Rain's India plants and planned India CTP facility directly benefit.</li>
    <li><strong>LME hedging at US$2,807/tonne for Q4:</strong> Smelters locking in strong profitability — no risk of capacity curtailments that would reduce CPC demand.</li>
    <li><strong>No CBAM concern for Indian aluminium:</strong> "Till power is not included in CBAM, there is no restriction for Indian aluminum imports." Removes a potential risk to Rain's customer base.</li>
   </ul>
  </div>
 </div>

 <h2>Phillips 66 March 2026 — GPC Supply Context</h2>
 <p><span class="src">Source: Phillips 66 Investor Update · March 2026</span></p>
 <div class="peer-grid">
  <div class="pc phil">
   <h4>Phillips 66 Snapshot</h4>
   <div class="ps"><span class="ps-l">Annual Coke Production</span><span class="ps-v">~6 MM MT</span></div>
   <div class="ps"><span class="ps-l">Crude Capacity</span><span class="ps-v">~2 MMBD refining</span></div>
   <div class="ps"><span class="ps-l">Bottoms Upgrading</span><span class="ps-v">349 MBD — #1 US refiner</span></div>
   <div class="ps"><span class="ps-l">2027E Adj. EBITDA</span><span class="ps-v">~US$10 Bn</span></div>
   <div class="ps"><span class="ps-l">Dividend CAGR (since 2012)</span><span class="ps-v">15%</span></div>
  </div>
  <div class="pc phil" style="grid-column:span 2;">
   <h4>What Phillips 66 Tells Us About GPC Supply</h4>
   <ul class="bl" style="margin:0;">
    <li><strong>Largest US bottoms upgrading capacity:</strong> 349 MBD of delayed coking capacity — highest among US refiners. This is the primary GPC production mechanism. Phillips 66's US Gulf operations are directly adjacent to several of Rain's calcination plants.</li>
    <li><strong>Heavy crude strategy:</strong> Phillips 66 explicitly focuses on heavy and medium crude processing — which produces higher-quality anode-grade GPC. Their crude slate strategy directly impacts GPC quality available to Rain.</li>
    <li><strong>Permian and Canadian crude growth:</strong> Both are increasing in production. These crude types when processed produce anode-grade GPC. More Permian/Canadian crude = more GPC at Rain's doorstep.</li>
    <li><strong>~6 MMTPA coke portfolio:</strong> One of the world's largest GPC producers. Their refining investment commitment ensures continued GPC supply at competitive prices for Rain's US operations.</li>
    <li><strong>No BAM conflict from P66 side:</strong> Phillips 66 is a pure GPC supplier — not a BAM competitor. Their production strategy is driven by refining economics. They have no incentive to divert GPC away from calciners.</li>
   </ul>
  </div>
 </div>

 <h2>Rain vs Alcoa vs Hindalco — Comparative Table</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Metric</th><th>Rain Industries</th><th>Alcoa (US)</th><th>Hindalco India Ops</th></tr></thead>
  <tbody>
   <tr><td>Role in Value Chain</td><td>CPC + CTP Producer (Input supplier)</td><td>Alumina + Aluminium (Customer)</td><td>Aluminium Smelter + Downstream (Customer)</td></tr>
   <tr><td>Net Debt/EBITDA</td><td class="ad">3.2× (improving)</td><td class="gd">~1.5× (target range)</td><td class="gd">1.73× consolidated</td></tr>
   <tr><td>EBITDA Margin (2025)</td><td class="ad">13.4%</td><td class="gd">~16%</td><td class="gd">~45% (upstream Al only)</td></tr>
   <tr><td>Recovery Status</td><td class="ad">Stage 2→3 — Early Expansion</td><td class="gd">Stable, strong profitability</td><td class="ad">Strong; Novelis Oswego fire impact</td></tr>
   <tr><td>Beneficiary of China Cap?</td><td class="gd">YES — directly</td><td class="gd">YES — Al price support</td><td class="gd">YES — India smelter growth</td></tr>
   <tr><td>Key Risk</td><td class="rd">BAM GPC structural impairment</td><td class="rd">Alumina price pressure; energy</td><td class="rd">Novelis fire; high capex cycle</td></tr>
   <tr><td>2026 Capex Guidance</td><td class="gd">US$60–65 Mn (disciplined)</td><td class="ad">US$750 Mn</td><td class="ad">~₹10,000 Cr</td></tr>
  </tbody>
 </table>
 </div>
 <div class="co g"><span class="co-lbl">The Key Insight from Peer Analysis</span><p>Both Alcoa and Hindalco are Rain's downstream customers — and both are confirming exactly the demand signals Rain's thesis depends on. Rain is the upstream beneficiary of the macro trends these two well-capitalised companies are capitalising on. As they grow and commission new smelter capacity, they need more of Rain's product. The three source documents provide an integrated, mutually corroborating confirmation of Rain's investment thesis from three different vantage points in the same value chain.</p></div>
</div>
</div>
<!-- ======================================================
     08 RISKS
====================================================== -->
<div id="risks" class="sec">
<div class="hero" style="background:#2a0e0e;">
 <div class="hero-in">
  <div class="tag">08 · Risk Register</div>
  <div class="h1">Five Failure Modes<br>&amp; Exit Triggers</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Every thesis can be wrong. Specific failure modes with probability, severity, monitoring signal, and when to exit immediately.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Intellectual honesty requires mapping failure modes with the same rigour applied to the opportunity. For Rain the risks are real — not manufactured for balance. The leverage is high. The BAM structural shift is genuine. The coal tar supply squeeze is structural. Understanding each precisely is what allows a disciplined investor to hold through volatility rather than capitulate at the wrong moment.</p>

 <div class="risk h">
  <div class="risk-hdr"><div class="risk-t">Risk 1: BAM Permanently Impairs Calcination Economics</div><div class="rb h">HIGH STRUCTURAL</div></div>
  <div class="risk-b">Battery Anode Material producers continue outbidding calciners for premium low-sulfur GPC indefinitely. If this persists, Rain's normalised EBITDA/tonne settles permanently at US$30–40 (vs historical US$60–80), making the investment case far weaker. <strong>Management counter:</strong> BAM players will eventually use lower-grade GPC as battery chemistry evolves; ACP technology allows using grades BAM doesn't want; CPC prices will eventually catch up through contract resets. Evidence of partial normalisation: OPM recovered from -15% to 14%. But per-tonne margins need to reach US$50+ for full validation. <strong>Probability: Medium.</strong></div>
  <div class="risk-sig"><strong>Monitor:</strong> Carbon segment EBITDA/tonne quarterly. Below US$35 for 3+ quarters = thesis at risk. Watch BAM sector GPC purchasing behaviour; needle coke vs GPC pricing spread.</div>
 </div>

 <div class="risk h">
  <div class="risk-hdr"><div class="risk-t">Risk 2: Coal Tar Supply Secular Decline</div><div class="rb h">HIGH STRUCTURAL</div></div>
  <div class="risk-b">The BF-to-EAF steel transition is structural and accelerating. As BF capacity declines, coal tar supply shrinks permanently. European BF closures accelerated in 2022–2025. Russian/Ukrainian coal tar remains inaccessible. Alternative raw materials programme in progress but not yet at scale. <strong>Partial mitigation:</strong> smaller European distillers are closing — improves supply/demand for survivors like Rain. Rain's scale allows freight arbitrage small players cannot afford. <strong>Probability: Medium-High for partial impairment.</strong></div>
  <div class="risk-sig"><strong>Monitor:</strong> Distillation EBITDA/tonne; alternative raw material % in blend; competitor closures. Competitor exits actually help Rain's utilisation and pricing.</div>
 </div>

 <div class="risk m">
  <div class="risk-hdr"><div class="risk-t">Risk 3: Debt Refinancing Failure or Forced Equity</div><div class="rb m">MEDIUM FINANCIAL</div></div>
  <div class="risk-b">Rain must refinance ~US$810 Mn of term debt by 2028–2029. If credit markets deteriorate or EBITDA recovery stalls, refinancing at reasonable rates becomes difficult. A forced refinancing at 11–12%+ adds ~US$20–25 Mn of annual interest. Worst case: equity issuance at dilutive prices. Management committed to no equity issuance. <strong>Current protection:</strong> US$340 Mn liquidity provides 3+ years runway. 2029 Notes callable from March 2026 — refinancing window is open now. <span class="src">Q4 2025 Concall</span> <strong>Probability: Low in base case.</strong></div>
  <div class="risk-sig"><strong>Monitor:</strong> Net Debt/EBITDA — if back above 4.0× for two consecutive quarters, refinancing risk escalates. Any equity issuance announcement = exit signal immediately.</div>
 </div>

 <div class="risk m">
  <div class="risk-hdr"><div class="risk-t">Risk 4: Middle East Geopolitical Escalation</div><div class="rb m">MEDIUM · LIVE Mar 2026</div></div>
  <div class="risk-b">The Q4 2025 concall (March 2026) explicitly flagged that within 24 hours of their initial investor call, Middle East hostilities escalated materially — "several aluminium producers in the region declared force majeure." A sustained conflict could: shut down Middle Eastern aluminium smelter customers; spike European natural gas prices again (pressing Advanced Materials margins); disrupt shipping routes raising freight costs; affect GPC availability if Gulf crude trade flows are redirected. Management stated "only a reduced impact on operations" but monitoring closely. <span class="src">Q4 2025 Concall</span></div>
  <div class="risk-sig"><strong>Monitor:</strong> Middle East escalation news; European natural gas prices (above €50/MMBtu = concern); shipping route disruptions; customer force majeure announcements.</div>
 </div>

 <div class="risk l">
  <div class="risk-hdr"><div class="risk-t">Risk 5: Cement Business — Permanent Capital Drag</div><div class="rb l">LOW-MEDIUM OPERATIONAL</div></div>
  <div class="risk-b">Cement generating 5% EBITDA margin on ₹1,131 Cr revenue (CY2025) — far below cost of capital. Brownfield expansion (₹757 Cr, 1.3→3.8 MTPA) approved in Q3 2025 but deferred in Q4 2025 due to muted demand and intensified competition from pan-India players. If management revives this expansion in a weak environment, it consumes ₹500+ Cr of cash that could service debt. Selling cement could reduce debt by 35–40% and save ₹140–200 Cr annual interest. <span class="src">Q2 2025 Concall</span></div>
  <div class="risk-sig"><strong>Monitor:</strong> Any board announcement to restart cement expansion; cement EBITDA/tonne; South Indian pricing. The deferred expansion decision is correct — watch whether management maintains discipline.</div>
 </div>

 <h2>Exit Triggers — Sell Immediately If:</h2>
 <div class="exit"><h4>⚠ EXIT 1: Net Debt/EBITDA back above 4.0× for two consecutive quarters</h4><p>Recovery stalled and refinancing risk is becoming acute. Reduce or exit immediately.</p></div>
 <div class="exit"><h4>⚠ EXIT 2: Management announces equity issuance at dilutive prices</h4><p>No-equity commitment has broken. Clearest possible signal the thesis is not playing out as planned.</p></div>
 <div class="exit"><h4>⚠ EXIT 3: Carbon EBITDA/tonne confirmed below US$35 for 3+ consecutive quarters</h4><p>BAM has structurally impaired the core calcination business beyond recoverable levels. Re-evaluate the entire framework.</p></div>
 <div class="exit"><h4>⚠ EXIT 4: India GPC quota reduced again OR SEZ exemption revoked</h4><p>The most important regulatory catalyst is undone. Indian plants revert to 30–40% utilisation. Eliminates Layer 2 of the thesis entirely.</p></div>
</div>
</div>

<!-- ======================================================
     09 PETER LYNCH CHECKLIST
====================================================== -->

<div id="lynch" class="sec">
<div class="hero" style="background:#1a1a12;">
 <div class="hero-in">
  <div class="tag">09 · Peter Lynch Checklist</div>
  <div class="h1">The Lynch Checklist<br>— Full Verdict</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">Peter Lynch's complete framework applied to Rain. Category classification. Six criteria. Warning signs. Final score and what it means for the investment.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">Peter Lynch made his reputation finding cyclical turnarounds that the market had given up on. His framework for identifying them — and knowing when to buy and sell — is the most practical template for Rain's specific situation. Let us apply it completely and without mercy.</p>

 <div class="sg sg3">
  <div class="sc dk"><span class="sc-v">Cyclical</span><span class="sc-l">Lynch Category A</span></div>
  <div class="sc dk"><span class="sc-v">Turnaround</span><span class="sc-l">Lynch Category B</span></div>
  <div class="sc dk"><span class="sc-v">7 / 9</span><span class="sc-l">Pabrai Checklist Score</span></div>
 </div>

 <h2>Lynch's Category — Rain Fits TWO Simultaneously</h2>
 <div class="lg">
  <div class="lb dk"><h4>Category A: Cyclical</h4><p>Earnings swing dramatically with the CPC-GPC spread, coal tar prices, aluminium demand, and energy costs. Lynch's advice: buy when the industry is depressed and starting to turn, BEFORE Wall Street discovers the recovery. That moment is Q2 2025. The turn is confirmed. The consensus has not caught up.</p></div>
  <div class="lb dk"><h4>Category B: Turnaround</h4><p>Beaten down by regulatory, macro, and structural headwinds simultaneously. Now emerging with specific verified catalysts. Lynch: "Markets tend to extrapolate bad news well past its expiry date." Two years of losses anchored sentiment. Three quarters of recovery haven't reset that anchor yet.</p></div>
  <div class="lb"><h4>Lynch's Favourite Signal</h4><p>Insider buying or holding. Promoter holding has been completely STABLE at 41.19% through the entire crisis. Not a single share sold. Not a single share pledged. This is the strongest possible confidence signal from people who know the business best. Lynch would note this prominently.</p></div>
  <div class="lb"><h4>Lynch's Key Warning for Cyclicals</h4><p>Cyclicals are dangerous when you buy them at the wrong time. Lynch says SELL when the P/E is at its lowest and everyone is excited. For Rain, that time is NOT now. The P/E is high on trough earnings and few people are excited. This is the BUY signal, not the sell signal — which is precisely what many investors get backwards.</p></div>
 </div>

 <h2>Lynch's Six Criteria Applied</h2>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">1. "The worst is behind them" — Is the cycle definitively turning?</div><div class="ck-a"><strong>YES.</strong> The trough is identifiable with precision (Dec 2023: -15% OPM, -₹1,079 Cr net loss in a single quarter). Recovery confirmed: OPM -15% → 14% over 7 quarters. Three consecutive profitable quarters. EBITDA grew 52% year-on-year. Net Debt/EBITDA fell 3.97×→3.2×. Lynch demands specific, verifiable evidence — not hope. Rain provides it.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">2. "The balance sheet can survive the recovery period"</div><div class="ck-a"><strong>YES.</strong> US$340 Mn liquidity (Dec 2025). No major term debt maturity until October 2028 — 2.5+ years of runway. Annual interest ~US$90 Mn vs CY2025 EBITDA of US$261 Mn. Tight but survivable, and improving every quarter. Lynch demanded companies not run out of cash before the recovery matures. Rain has enough runway.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">3. "Something concrete has changed" — Not just cyclical hope</div><div class="ck-a"><strong>YES — Multiple verified facts:</strong> India GPC quota expanded to 1.9 MTPA (Feb 2024 — DONE). SEZ import unlimited approved (2024 — DONE). Indian plants at 90%+ (verified in Q3 and Q4 2025 concalls — DONE). US$44 Mn notes repaid on schedule (Mar 2025 — DONE). US tax law change improving interest deductibility (Jul 2025 — DONE). Lynch wanted specific verifiable facts not macro speculation. Rain has multiple.</div></div></div>
 <div class="ck-item"><div class="ck-icon warn">!</div><div><div class="ck-q">4. "Inventories declining, orders improving"</div><div class="ck-a"><strong>PARTIALLY.</strong> Carbon segment volumes improving. Capacity utilisation rising to 90%+ at Indian plants. However, inventory days rose to 137 (2025) — elevated. Management explains this as deliberate strategic build for SEZ ramp-up and global blend strategy logistics pipeline, not demand weakness. Working capital release guided for H2 2026. Monitor quarterly.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">5. "Institutional ownership is still low" — Smart money not yet in</div><div class="ck-a"><strong>YES — a strong contrarian signal.</strong> FII holding DECLINED from 10.82% to 8.54% through 2025 as FIIs reduced exposure during the recovery's early stages. DIIs increased from 3.16% to 4.87% — smart domestic money accumulating. This is exactly Lynch's setup: institutions have not yet discovered the recovery. The re-rating happens when they do.</div></div></div>
 <div class="ck-item"><div class="ck-icon pass">✓</div><div><div class="ck-q">6. "What is the normalised EPS?" — Not trough, not peak</div><div class="ck-a"><strong>Clear upside from trough.</strong> Historical peak EPS: ₹42.77 (CY2022). Trough: -₹27.89 (CY2023). CY2025: ₹1.26 (returning positive). Normalised base case EPS (₹2,800 Cr EBITDA): approximately ₹12–18. Bull case (₹3,300+ Cr EBITDA): approximately ₹28–40. Lynch says buy cyclicals when the P/E appears astronomically high on trough earnings. That apparent high P/E IS the signal, not the warning.</div></div></div>

 <h2>Lynch's Warning Signs — Is Rain Guilty?</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Lynch Warning</th><th>Applicable?</th><th>Assessment</th></tr></thead>
  <tbody>
   <tr><td>"Hot stock in a hot industry"</td><td class="gd">NO</td><td>CPC is the definition of boring. Rain is unloved and undiscovered. Exactly where Lynch found his best opportunities.</td></tr>
   <tr><td>"Diversifying into unrelated businesses"</td><td class="ad">PARTIAL</td><td>RÜTGERS and cement are diversifications. No new deals being done now — management focused on operating existing assets.</td></tr>
   <tr><td>"One customer accounts for 25%+ of sales"</td><td class="gd">NO</td><td>42% from aluminium sector spread across many smelters globally. No single customer likely exceeds 10–12% of revenue.</td></tr>
   <tr><td>"Company losing money"</td><td class="gd">RESOLVED</td><td>Net losses in 2023–2024. Three consecutive profitable quarters in 2025. The inflection has occurred.</td></tr>
   <tr><td>"High debt relative to earnings"</td><td class="ad">YES — IMPROVING</td><td>3.2× Net Debt/EBITDA is real and elevated. But declining consistently. At ₹3,000 Cr EBITDA (plausible 2026), same debt = 2.4×. The risk is priced in; the improvement is not.</td></tr>
   <tr><td>"Whispering numbers from analysts"</td><td class="gd">NO</td><td>Limited sell-side coverage means consensus expectations are low and easily beat. Analyst upgrades are a pending re-rating catalyst.</td></tr>
   <tr><td>"P/E above the growth rate"</td><td class="gd">NO</td><td>On normalised earnings (base case ₹12–18 EPS), current P/E is not expensive. The apparent high P/E is on trough earnings — exactly the signal Lynch says to buy, not avoid.</td></tr>
  </tbody>
 </table>
 </div>

 <h2>Final Lynch Scorecard</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Criteria</th><th>Score</th><th>Key Evidence</th></tr></thead>
  <tbody>
   <tr><td>Cycle turning — worst behind?</td><td class="gd">✓ PASS</td><td>OPM -15%→14%; 3 consecutive profitable quarters; EBITDA +52%</td></tr>
   <tr><td>Balance sheet survival</td><td class="gd">✓ PASS</td><td>US$340Mn liquidity; Oct 2028 next maturity; leverage improving quarterly</td></tr>
   <tr><td>Concrete catalysts (not hope)</td><td class="gd">✓ PASS</td><td>GPC quota, SEZ unlock, 90% utilisation, notes repaid — all verified facts</td></tr>
   <tr><td>Volume/inventory normalising</td><td class="ad">~ PARTIAL</td><td>Volumes rising; inventory days 137 — elevated but strategic, watch H2 2026</td></tr>
   <tr><td>Institutional ownership low</td><td class="gd">✓ PASS</td><td>FIIs at 8.54% declining; DIIs accumulating — smart money early</td></tr>
   <tr><td>Normalised EPS attractive</td><td class="gd">✓ PASS</td><td>Base case ₹12–18 EPS; bull case ₹28–40; vs historical peak ₹42.77</td></tr>
   <tr><td>No hot-stock warning signs</td><td class="gd">✓ PASS</td><td>Boring, unloved, undiscovered — exactly where Lynch wanted to be</td></tr>
   <tr><td>Insider/promoter holding stable</td><td class="gd">✓ PASS</td><td>41.19% — zero selling, zero pledging through the entire crisis</td></tr>
   <tr><td>Debt risk manageable?</td><td class="ad">! WATCH</td><td>3.2× leverage is real; refinancing needed by 2028–2029; improving each quarter</td></tr>
  </tbody>
 </table>
 </div>

 <div class="co dk"><span class="co-lbl">The Lynch Final Verdict</span><p>"The person who turns over the most rocks wins." Most investors have not looked carefully enough at Rain to notice: Indian plants at 90%+; global blend strategy revived; three consecutive profitable quarters; Debt/EBITDA improving every quarter; Alcoa and Hindalco both confirming Rain's demand thesis; China cap confirmed; no maturity cliff until 2028. These rocks, once turned over, tell a completely different story than the stock price suggests. Rain is a classic Lynch cyclical turnaround at the early expansion stage. The re-rating has only just begun.</p></div>

 <div class="co r"><span class="co-lbl">Lynch's Hardest Lesson — The Exit Discipline</span><p><strong>Sell when everyone loves the stock.</strong> Rain at its 2022 peak had EPS ₹42.77, EBITDA margin 17%, and interest coverage 7×. That was when Lynch would have sold — when everything looked perfect. The 2023–2024 crash then happened. The discipline to sell at the peak of the narrative is exactly as important as the discipline to buy at the trough. See Section 10 for the specific exit plan.</p></div>
</div>
</div>
<!-- ======================================================
     10 MONITOR
====================================================== -->
<div id="mon" class="sec">
<div class="hero" style="background:#1a2a1a;">
 <div class="hero-in">
  <div class="tag">10 · Live Dashboard</div>
  <div class="h1">Quarterly Monitoring<br>Signal vs Noise</div>
  <p style="font-size:17px;color:rgba(245,240,232,0.6);max-width:640px;line-height:1.65;">The 9 metrics that matter. Green/amber/red thresholds. Phase-based exit plan. Catalyst calendar for 2026. Updated through Q4 2025.</p>
 </div>
</div>
<div class="wrap">
 <p class="lead">The most common mistake in cyclical investing is not buying at the wrong price — it is selling at the wrong time. Capitulating during normal cycle volatility, or holding too long into the cycle peak. This dashboard provides the discipline to avoid both errors.</p>

 <h2>Real-Time Status Dashboard (Q4 2025)</h2>
 <div class="dash">
  <div class="dm g"><div class="dm-l">EBITDA Recovery</div><div class="dm-v">₹2,275 Cr</div><div class="dm-n">+52% YoY. 3 profitable quarters. Target ₹2,800+ Cr</div></div>
  <div class="dm a"><div class="dm-l">Net Debt / EBITDA</div><div class="dm-v">3.2×</div><div class="dm-n">Down from 3.97×. Target below 3.0×. Amber until confirmed.</div></div>
  <div class="dm g"><div class="dm-l">India Utilisation</div><div class="dm-v">90%+</div><div class="dm-n">Both plants at/above 90%. Up from 30–40% two years ago.</div></div>
  <div class="dm a"><div class="dm-l">Inventory Days</div><div class="dm-v">137 days</div><div class="dm-n">Elevated. Watch for release in H2 2026. Strategic build.</div></div>
  <div class="dm g"><div class="dm-l">Liquidity Buffer</div><div class="dm-v">US$340 Mn</div><div class="dm-n">Cash US$170 Mn + undrawn US$170 Mn. Oct 2028 next maturity.</div></div>
  <div class="dm g"><div class="dm-l">Net Profit</div><div class="dm-v">+₹136 Cr</div><div class="dm-n">First positive annual profit since CY2022. Trend positive.</div></div>
  <div class="dm g"><div class="dm-l">Promoter Holding</div><div class="dm-v">41.19%</div><div class="dm-n">Stable. No pledging. No selling. Zero dilution through crisis.</div></div>
  <div class="dm a"><div class="dm-l">FII Holding</div><div class="dm-v">8.54%</div><div class="dm-n">Down from 10.82%. Watch for reversal — that IS the re-rating signal.</div></div>
  <div class="dm g"><div class="dm-l">Safety (TRIR)</div><div class="dm-v">0.11</div><div class="dm-n">Best-ever record. Best-in-class for an industrial operator globally.</div></div>
 </div>

 <h2>Green / Amber / Red Thresholds</h2>
 <div class="tw">
 <table>
  <thead><tr><th>Metric</th><th style="background:#1a5c38;">🟢 Green — On Track</th><th style="background:#8a7010;">🟡 Amber — Watch</th><th style="background:#8a2010;">🔴 Red — Thesis at Risk</th></tr></thead>
  <tbody>
   <tr><td><strong>Carbon EBITDA/Tonne</strong></td><td class="gd">US$45+ and rising</td><td class="ad">US$35–44, flat</td><td class="rd">Below US$35 for 3+ quarters</td></tr>
   <tr><td><strong>Net Debt/EBITDA</strong></td><td class="gd">Below 3.0× declining</td><td class="ad">3.0–3.5× stable</td><td class="rd">Above 3.5× or rising</td></tr>
   <tr><td><strong>India Utilisation</strong></td><td class="gd">Above 88%</td><td class="ad">75–88%</td><td class="rd">Below 75% — quota risk</td></tr>
   <tr><td><strong>Quarterly OPM</strong></td><td class="gd">Above 14%</td><td class="ad">10–14%</td><td class="rd">Below 10% two consecutive quarters</td></tr>
   <tr><td><strong>Inventory Days</strong></td><td class="gd">Declining toward 110–115</td><td class="ad">115–135 stable</td><td class="rd">Above 145, rising into 2026</td></tr>
   <tr><td><strong>Interest Coverage</strong></td><td class="gd">Above 3×</td><td class="ad">2.5–3×</td><td class="rd">Below 2.5× two consecutive quarters</td></tr>
   <tr><td><strong>Promoter Holding</strong></td><td class="gd">Stable or rising</td><td class="ad">Minor decline (&lt;1%)</td><td class="rd">Meaningful decline or pledging</td></tr>
   <tr><td><strong>FII Holding</strong></td><td class="gd">Rising above 10%</td><td class="ad">7–10% stable</td><td class="rd">Below 7% or accelerating sell</td></tr>
   <tr><td><strong>Management Actions</strong></td><td class="gd">No equity; debt paydown; capex discipline</td><td class="ad">Cement expansion revival</td><td class="rd">Equity issuance at dilutive prices</td></tr>
  </tbody>
 </table>
 </div>

 <h2>Phase-Based Exit Plan</h2>
 <div class="phases">
  <div class="ph done"><div class="ph-n">1</div><div class="ph-name">Accumulate</div><div class="ph-note">✓ Done<br>Trough period<br>Max fear</div></div>
  <div class="ph now"><div class="ph-n">2</div><div class="ph-name">Hold / Add</div><div class="ph-note">← NOW<br>OPM 12–16%<br>Debt/EBITDA 3–3.5×</div></div>
  <div class="ph next"><div class="ph-n">3</div><div class="ph-name">Trim 30–50%</div><div class="ph-note">EPS ₹20+<br>Debt/EBITDA &lt;2.5×<br>Analysts upgrading</div></div>
  <div class="ph sell"><div class="ph-n">4</div><div class="ph-name">Exit Majority</div><div class="ph-note">EPS ₹35+<br>Dividend resumed<br>Everyone loves it</div></div>
 </div>

 <h2>Catalyst Calendar — 2026</h2>
 <div class="cc-item"><div class="cc-when">Q1 2026</div><div><div class="cc-what">Refinancing Update on 2029 Notes (Callable Mar 2026)</div><div class="cc-why">Any refinancing at sub-8% would reduce interest cost by US$7–9 Mn annually and signal improved credit access. Strong positive catalyst. Management "actively monitoring market" per Q4 2025 concall.</div></div></div>
 <div class="cc-item"><div class="cc-when">Q1–Q2 2026</div><div><div class="cc-what">Q1 2026 Results — Recovery Continuation</div><div class="cc-why">Most important near-term data point. If OPM remains 12–14%+ and leverage continues declining, Stage 3 re-rating accelerates. Expectation: working capital begins normalising.</div></div></div>
 <div class="cc-item"><div class="cc-when">H2 2026</div><div><div class="cc-what">Working Capital Release</div><div class="cc-why">Management guided release in H2 2026 as GPC import quota timing normalises. A release of ₹800–1,200 Cr improves free cash flow significantly and accelerates deleveraging. <span class="src">Q4 2025 Concall</span></div></div></div>
 <div class="cc-item"><div class="cc-when">2026</div><div><div class="cc-what">India Ratings — Credit Outlook Update</div><div class="cc-why">Current: IND A/Stable. Positive trigger: Net Debt/EBITDA sustained below 3.0×. An upgrade to IND A+ allows institutions with higher rating mandates to re-enter. Significant demand catalyst.</div></div></div>
 <div class="cc-item"><div class="cc-when">2026–2027</div><div><div class="cc-what">Non-China Aluminium Smelter Commissioning</div><div class="cc-why">Indonesia ~700k MT in 2026 (Alcoa). US greenfield smelter announcements. San Ciprián full restart H1 2026. Each new tonne validates the tollbooth thesis. <span class="src">Alcoa Q4 2025</span></div></div></div>
 <div class="cc-item"><div class="cc-when">Q4 2027</div><div><div class="cc-what">India CTP Distillation — Phase 1 Start-Up (Targeted)</div><div class="cc-why">First domestic CTP production in India. Revenue contribution from 2028. India's zero domestic CTP production makes Rain the only local supplier — structural permanent advantage. <span class="src">Q4 2025 Concall</span></div></div></div>

 <h2>What to Ignore — The Noise List</h2>
 <ul class="bl">
  <li><strong>Single-quarter OPM dips</strong> — Quarterly seasonality and inventory timing create noise. Judge on 4-quarter trailing average. Q4 2025's 12% vs Q3's 14% is seasonal, not deterioration.</li>
  <li><strong>GPC price spikes</strong> — Temporarily compress margins but trigger CPC contract price resets. The NEXT quarter typically shows margin improvement. Don't sell during the compression phase.</li>
  <li><strong>Cement segment weakness</strong> — Cement is 7% of revenue. Weak cement quarters are noise unless they signal a capital allocation mistake (expansion revival).</li>
  <li><strong>Borrowings (₹ Cr) rising in 2025</strong> — This reflects INR depreciation inflating USD/EUR debt value, not term debt growth. Always track debt in USD — US$1,007 Mn total, working capital increased from US$96 Mn to US$190 Mn.</li>
  <li><strong>FII selling quarter-to-quarter</strong> — Short-term portfolio rebalancing. Track direction over 2–3 quarters. DII accumulation (3.16%→4.87%) is the more meaningful signal.</li>
  <li><strong>ELYSIS carbon-free smelting news</strong> — Alcoa CEO confirmed no ELYSIS groundbreaking until post-2030. Carbon anodes essential through this entire decade. Not a near-term threat.</li>
  <li><strong>Middle East headlines</strong> — Rain has globally diversified customers. No single region exceeds 20–25% of revenues. Geopolitical risk is real but not binary for Rain.</li>
 </ul>

 <div class="co dk"><span class="co-lbl">The Final Monitoring Discipline</span><p>"The investor who can watch one metric turn red and exit, and watch another metric turn green and add, without being swayed by headlines, analyst commentary, or market price movements — that investor will outperform. For Rain, the thesis lives or dies on three numbers: Carbon EBITDA/tonne, Net Debt/EBITDA, and India plant utilisation. Everything else is context. Monitor the signal. Ignore the noise."</p></div>
</div>
</div>

<!-- FOOTER + JS -->

<footer>
 Rain Industries Deep Dive · March 2026 · 18 Source Documents · Research Only, Not Investment Advice<br>
 Rain Q4 2025, Q3 2025, Q2 2025, Q1 2025 Concalls · Q4 2024 Mgmt Presentation · Q2/Q1 CY2018 · Q3 CY2017 · Q2 CY2020 · Corporate 2016 &amp; 2019 Presentations<br>
 <strong>Alcoa Q4 2025 Earnings · Hindalco Q3FY26 Earnings · Phillips 66 Investor Update Mar 2026</strong><br>
 <strong>This is research only. Consult a qualified financial advisor before making any investment decision.</strong>
</footer>

<script>
function go(id){
 var secs=document.querySelectorAll('.sec');
 for(var i=0;i<secs.length;i++) secs[i].classList.remove('on');
 var nbs=document.querySelectorAll('.nb');
 for(var i=0;i<nbs.length;i++) nbs[i].classList.remove('on');
 document.getElementById(id).classList.add('on');
 var map={home:0,origin:1,fin:2,sc:3,marks:4,pabrai:5,moat:6,peers:7,risks:8,lynch:9,mon:10};
 nbs[map[id]].classList.add('on');
 window.scrollTo(0,0);
}
</script>

</body>
</html>
