# Copy: Write the watcher cold landing page as one complete html

Date: 2026-10-29
Task: Write the Watcher cold landing page as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher | Korvus Index Futures Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock, scores breaking news, and keeps a written read ready when you wake. Free Observer tier, no card required.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:#07070b;color:#e8e8ef;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;background:radial-gradient(900px 500px at 15% -10%,rgba(255,79,163,.18),transparent 60%),radial-gradient(800px 500px at 100% 20%,rgba(120,80,255,.14),transparent 60%),linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px) 0 0/44px 44px,linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px) 0 0/44px 44px,#07070b;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 22px;position:relative;z-index:1}
header{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid rgba(255,255,255,.08)}
header b{font-size:1.05rem;letter-spacing:.04em}
header a.nav{margin-left:auto;color:#ff8cc3;text-decoration:none;font-size:.95rem}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:56px 0 18px;max-width:18ch}
h2{font-size:clamp(1.4rem,3vw,2rem);margin:0 0 14px}
p{max-width:70ch;color:#c4c4d0;margin-bottom:14px}
.eyebrow{color:#ff4fa3;text-transform:uppercase;letter-spacing:.14em;font-size:.78rem;margin-bottom:12px}
.btn{display:inline-block;background:#ff4fa3;color:#120812;font-weight:700;padding:14px 24px;border-radius:10px;text-decoration:none;margin:8px 12px 8px 0}
.btn.ghost{background:transparent;color:#ff8cc3;border:1px solid rgba(255,79,163,.5)}
section{padding:52px 0;border-top:1px solid rgba(255,255,255,.06)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:22px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:18px}
.chip{border:1px solid rgba(255,79,163,.35);color:#ffb3d6;border-radius:999px;padding:6px 14px;font-size:.88rem}
.panel{background:rgba(12,12,20,.85);border:1px solid rgba(255,79,163,.25);border-radius:16px;padding:22px;box-shadow:0 0 60px rgba(255,79,163,.12)}
.panel-top{display:flex;justify-content:space-between;align-items:center;font-size:.85rem;color:#9a9ab0;margin-bottom:14px}
.tag{color:#ff8cc3;border:1px solid rgba(255,79,163,.4);border-radius:6px;padding:2px 8px;font-size:.75rem}
.row{display:grid;grid-template-columns:1.4fr 1fr 1fr 1fr;gap:12px;padding:12px 0;border-top:1px solid rgba(255,255,255,.06);font-size:.92rem}
.row.head{color:#9a9ab0;border-top:none;font-size:.78rem;text-transform:uppercase;letter-spacing:.08em}
.read{margin-top:16px;padding:14px;border-radius:10px;background:rgba(255,79,163,.07);font-size:.92rem;color:#d8d8e4}
.steps .card span{color:#ff4fa3;font-weight:700;display:block;margin-bottom:8px}
.tiers{align-items:stretch}
.tiers .card h3{font-size:1.15rem;margin-bottom:6px}
.tiers .price{font-size:.95rem;color:#ffb3d6;margin-bottom:10px}
ul{padding-left:18px;color:#c4c4d0}
li{margin-bottom:6px}
footer{padding:36px 0 56px;border-top:1px solid rgba(255,255,255,.08);color:#8a8a9c;font-size:.85rem}
footer p{color:#8a8a9c;font-size:.85rem}
@media (max-width:700px){
.grid{grid-template-columns:1fr}
.row{grid-template-columns:1fr 1fr}
.row.head{display:none}
header a.nav{display:none}
h1{margin-top:36px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<svg width="34" height="34" viewBox="0 0 48 48" aria-hidden="true"><polygon points="6,36 10,16 18,26 24,10 30,26 38,16 42,36" fill="#ff4fa3"/><rect x="6" y="38" width="36" height="5" rx="2" fill="#ff8cc3"/></svg>
<b>KORVUS</b>
<a class="nav" href="https://korvus.industries/signup">Create free account</a>
</header>

<h1>Index futures, watched while you sleep.</h1>
<p>Korvus monitors the market around the clock, scores breaking news for likely impact, and writes a read you can check the moment you wake. You decide what to do with it. Korvus does the watching.</p>
<div>
<a class="btn" href="https://korvus.industries/signup">Start on the free Observer tier</a>
<a class="btn ghost" href="#preview">See a sample read</a>
</div>
<div class="chips">
<span class="chip">No card required</span>
<span class="chip">Around the clock coverage</span>
<span class="chip">Scored news with direction and confidence</span>
</div>

<section id="preview">
<div class="eyebrow">Sample output</div>
<h2>What a morning looks like</h2>
<p>Every scored item carries an impact level, a direction, a confidence rating, and a short written read. Here is an illustrative panel of the format.</p>
<div class="panel">
<div class="panel-top"><span>Watcher feed, index futures</span><span class="tag">Illustration</span></div>
<div class="row head"><span>Headline</span><span>Impact</span><span>Direction</span><span>Confidence</span></div>
<div class="row"><span>Overnight rate commentary from a regional official</span><span>Medium</span><span>Mixed</span><span>Moderate</span></div>
<div class="row"><span>Revised trade balance release ahead of the open</span><span>High</span><span>Leaning down</span><span>Moderate</span></div>
<div class="row"><span>Large block activity in the e-mini complex</span><span>Low</span><span>Neutral</span><span>Low</span></div>
<div class="read"><b>Written read:</b> Three items scored overnight. The trade balance revision carries the most weight. Confidence is moderate because the source has revised before. Review the full items and your own plan at the open.</div>
</div>
</section>

<section>
<div class="eyebrow">How it works</div>
<h2>Three steps between the news and your morning</h2>
<div class="grid steps">
<div class="card"><span>01</span><b>Watch</b><p style="margin-top:8px">Feeds are monitored continuously for index futures, including overnight sessions and scheduled releases.</p></div>
<div class="card"><span>02</span><b>Score</b><p style="margin-top:8px">Each item gets an impact level, a direction, and a confidence rating, so the loud items do not drown the important ones.</p></div>
<div class="card"><span>03</span><b>Read</b><p style="margin-top:8px">A written summary is ready when you wake, with the reasoning shown so you can check it yourself.</p></div>
</div>
</section>

<section>
<div class="eyebrow">Plans</div>
<h2>Start free, upgrade when the workflow earns it</h2>
<div class="grid tiers">
<div class="card">
<h3>Observer</h3>
<div class="price">Free, no card</div>
<ul>
<li>Live scored news feed</li>
<li>Written reads on the core items</li>
<li>Access to the public terminal views</li>
</ul>
</div>
<div class="card">
<h3>Operator</h3>
<div class="price">Full terminal with the LodeStone indicator included</div>
<ul>
<li>Everything in Observer</li>
<li>Full terminal and forex views</li>
<li>LodeStone TradingView indicator included</li>
</ul>
<p style="margin-top:12px;font-size:.9rem"><a href="https://korvus.industries/upgrade" style="color:#ff8cc3">See current Operator pricing</a></p>
</div>
</div>
</section>

<section>
<div class="eyebrow">Straight talk</div>
<h2>What Korvus is, and what it is not</h2>
<p>Korvus is market intelligence and education. It does not give trading advice, does not promise profits, and does not tell you when to enter or exit a position. Scores and reads are tools for your own analysis. Futures trading carries substantial risk of loss.</p>
<div>
<a class="btn" href="https://korvus.industries/signup">Create your free account</a>
</div>
</section>
</div>

<footer>
<div class="wrap">
<p>BlackCrownVxJ LLC. Korvus is a product of the company. Questions: BlackCrownVxJ.LLC@outlook.com</p>
<p style="margin-top:8px">Nothing on this page is financial advice. Past or illustrative output does not predict future results.</p>
</div>
</footer>
</body></html>
