# Copy: Write the complete watcher landing html document into a vault

Date: 2026-10-29
Task: Write the complete watcher landing html document into a vault note, ending in a closing html tag
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- Locked Projects.md lines (Watcher clip caption, Korvus cold hook leader) were not supplied with this task. Swap them in verbatim before filing. -->
<title>Index Watch | Korvus Market Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock, scores market news, and writes a plain read before your session starts. Operator includes LodeStone. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0d1017;--line:#1c2230;--text:#e7eaf2;--muted:#8d96a8;--accent:#7c5cff;--accent2:#3dd6c6;--gold:#e8c46a}
html{background:var(--bg)}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;color:var(--text);line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden;background:var(--bg)}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 500px at 15% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(61,214,198,.14),transparent 60%),radial-gradient(700px 500px at 50% 110%,rgba(232,196,106,.08),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 22px}
a{color:var(--accent2);text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand span{font-size:.95rem}
.brand small{display:block;color:var(--muted);font-weight:400;font-size:.75rem;letter-spacing:.08em;text-transform:uppercase}
nav a{color:var(--muted);margin-left:18px;font-size:.92rem}
nav a.cta{color:#0a0b10;background:var(--accent2);padding:9px 16px;border-radius:999px;font-weight:600;margin-left:18px}
nav a.cta:hover{text-decoration:none;filter:brightness(1.08)}
.hero{padding:56px 0 40px;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.16em;font-size:.78rem;font-weight:700}
h1{font-size:clamp(2rem,4.6vw,3.4rem);line-height:1.1;margin:14px 0 18px;letter-spacing:-.01em}
.lede{color:var(--muted);font-size:clamp(1rem,1.5vw,1.12rem);max-width:58ch}
.ctas{display:flex;gap:12px;flex-wrap:wrap;margin-top:26px}
.btn{display:inline-block;padding:13px 20px;border-radius:10px;font-weight:600;font-size:.98rem}
.btn.primary{background:linear-gradient(135deg,var(--accent),#5b8cff);color:#fff}
.btn.ghost{border:1px solid var(--line);color:var(--text);background:rgba(255,255,255,.02)}
.btn:hover{text-decoration:none;filter:brightness(1.06)}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin-top:22px}
.chip{border:1px solid var(--line);background:var(--panel);color:var(--muted);padding:6px 12px;border-radius:999px;font-size:.82rem}
.panel{background:linear-gradient(180deg,rgba(13,16,23,.96),rgba(9,11,17,.96));border:1px solid var(--line);border-radius:16px;padding:20px;box-shadow:0 20px 60px rgba(0,0,0,.45)}
.panel-head{display:flex;justify-content:space-between;align-items:center;color:var(--muted);font-size:.8rem;margin-bottom:14px;gap:8px}
.live{color:var(--accent2);font-weight:700}
.row{display:grid;grid-template-columns:52px 1fr 64px;gap:10px;align-items:center;padding:10px 0;border-top:1px solid var(--line);font-size:.86rem}
.row:first-of-type{border-top:0}
.time{color:var(--muted);font-variant-numeric:tabular-nums}
.evt{color:var(--text)}
.evt em{display:block;font-style:normal;color:var(--muted);font-size:.78rem}
.bar{height:6px;border-radius:6px;background:#1a2030;overflow:hidden}
.bar i{display:block;height:100%;background:linear-gradient(90deg,var(--accent),var(--accent2))}
.tag{font-size:.7rem;color:var(--gold);text-align:right;letter-spacing:.06em;text-transform:uppercase}
.caption{color:var(--muted);font-size:.76rem;margin-top:12px}
section{padding:44px 0}
h2{font-size:clamp(1.5rem,3vw,2.1rem);line-height:1.2;margin-bottom:14px}
.prose{max-width:66ch;color:var(--muted)}
.prose p+p{margin-top:14px}
.prose strong{color:var(--text)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:26px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card h3{font-size:1.02rem;margin-bottom:8px}
.card p{color:var(--muted);font-size:.93rem}
.price{display:grid;grid-template-columns:1.2fr .8fr;gap:16px;margin-top:26px}
.offer{border:1px solid rgba(124,92,255,.5);background:linear-gradient(160deg,rgba(124,92,255,.14),rgba(13,16,23,.9));border-radius:16px;padding:26px}
.offer .tier{color:var(--gold);font-size:.78rem;letter-spacing:.14em;text-transform:uppercase;font-weight:700}
.offer .amt{font-size:clamp(1.8rem,3.4vw,2.4rem);font-weight:800;margin:8px 0 4px}
.offer .amt small{font-size:.95rem;color:var(--muted);font-weight:500}
.offer ul{list-style:none;margin:16px 0 22px;color:var(--muted);font-size:.95rem}
.offer li{padding:6px 0 6px 22px;position:relative}
.offer li::before{content:"";position:absolute;left:0;top:14px;width:9px;height:9px;border-radius:2px;background:var(--accent2)}
.free{border:1px solid var(--line);background:var(--panel);border-radius:16px;padding:26px}
.free p{color:var(--muted);font-size:.95rem;margin-top:8px}
.free .amt{font-size:1.6rem;font-weight:800}
.disclaimer{border-left:3px solid var(--gold);background:rgba(232,196,106,.05);padding:16px 18px;border-radius:0 10px 10px 0;color:var(--muted);font-size:.9rem;margin-top:30px}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--muted);font-size:.85rem;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
footer a{color:var(--muted)}
@media (max-width:700px){
.hero{grid-template-columns:1fr;padding-top:34px;gap:28px}
.grid3{grid-template-columns:1fr}
.price{grid-template-columns:1fr}
nav a{margin-left:12px;font-size:.85rem}
nav a.cta{padding:8px 13px}
.row{grid-template-columns:44px 1fr 52px}
section{padding:34px 0}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="https://korvus.industries/" aria-label="Korvus home">
<svg width="34" height="34" viewBox="0 0 40 40" aria-hidden="true">
<defs><linearGradient id="cg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#e8c46a"/><stop offset="1" stop-color="#7c5cff"/></linearGradient></defs>
<path d="M6 30 L8 14 L14 22 L20 9 L26 22 L32 14 L34 30 Z" fill="url(#cg)" stroke="#e8c46a" stroke-width="1.2" stroke-linejoin="round"/>
<rect x="6" y="31" width="28" height="4" rx="1" fill="#e8c46a"/>
<circle cx="8" cy="13" r="2" fill="#3dd6c6"/><circle cx="20" cy="8" r="2" fill="#3dd6c6"/><circle cx="32" cy="13" r="2" fill="#3dd6c6"/>
</svg>
<span>KORVUS<small>by BlackCrownVxJ</small></span>
</a>
<nav>
<a href="https://korvus.industries/lodestone">LodeStone</a>
<a href="https://korvus.industries/legal">Legal</a>
<a class="cta" href="https://korvus.industries/signup?utm_source=korvus&amp;utm_medium=page&amp;utm_campaign=index-watch">Get Korvus</a>
</nav>
</header>

<div class="hero">
<div>
<div class="eyebrow">Index Watch</div>
<h1>The index does not sleep. Your watch should not either.</h1>
<p class="lede">Korvus monitors index futures around the clock, scores each market headline for impact, direction and confidence, and writes a plain read you can check before your session opens. Built for traders who work from the arena, not a pedestal.</p>
<div class="ctas">
<a class="btn primary" href="https://korvus.industries/signup?utm_source=korvus&amp;utm_medium=page&amp;utm_campaign=index-watch">Start with Operator</a>
<a class="btn ghost" href="https://korvus.industries/signup?utm_source=korvus&amp;utm_medium=page&amp;utm_campaign=index-watch-free">Try the free Observer tier</a>
</div>
<div class="chips">
<span class="chip">24/7 watch</span>
<span class="chip">Scored news</span>
<span class="chip">LodeStone included with Operator</span>
</div>
</div>

<figure class="panel" aria-label="Illustration of a Korvus watch board">
<div class="panel-head"><span class="live">LIVE WATCH</span><span>Illustration</span></div>
<div class="row"><span class="time">02:14</span><span class="evt">Index futures pre-market headline<em>Scored and filed</em></span><span class="tag">High</span></div>
<div class="row"><span class="time">03:40</span><span class="evt">Macro release queued<em>Agenda entry logged</em></span><span class="tag">Med</span></div>
<div class="row"><span class="time">05:02</span><span class="evt">Sentiment shift across wires<em>Direction: mixed</em></span><span class="tag">Med</span></div>
<div class="row"><span class="time">07:31</span><span class="evt">Pre-open read written<em>Plain language summary</em></span><span class="tag">Read</span></div>
<div class="bar" style="margin-top:14px"><i style="width:72%"></i></div>
<p class="caption">Illustration only. Sample layout, not a live feed or a signal.</p>
</figure>
</div>

<section>
<h2>A watcher that never clocks out</h2>
<div class="prose">
<p>Most traders miss the overnight move because the market moved while they were away. Korvus is the watch that stays on. It reads the wires, scores what matters, and keeps a running log, so the first thing you see at the open is an organized picture instead of a tab full of noise.</p>
<p>Every scored item carries three numbers you can audit: impact, direction and confidence. You decide what they mean for your plan. Korvus gives you the read. You make the call.</p>
</div>
<div class="grid3">
<div class="card"><h3>Scored, not just posted</h3><p>Each headline gets impact, direction and confidence, plus a written read in plain language.</p></div>
<div class="card"><h3>Session ready</h3><p>The watch runs through the overnight hours so the pre-open picture is already built when you arrive.</p></div>
<div class="card"><h3>Your chart, included</h3><p>Operator carries the LodeStone TradingView indicator: session levels built on ICT concepts for index futures, zero repainting.</p></div>
</div>
</section>

<section>
<h2>Operator, annual</h2>
<div class="prose"><p>Annual access is the way in, billed once a year with the full terminal and LodeStone included. Start on the Observer tier if you want to judge the output first.</p></div>
<div class="price">
<div class="offer">
<div class="tier">Operator, annual</div>
<div class="amt">79.99 <small>a year</small></div>
<ul>
<li>Full Korvus terminal and watch</li>
<li>LodeStone TradingView indicator included</li>
<li>Scored news with written reads</li>
<li>Daily USD economic agenda</li>
</ul>
<a class="btn primary" href="https://korvus.industries/signup?utm_source=korvus&amp;utm_medium=page&amp;utm_campaign=index-watch">Get Operator</a>
</div>
<div class="free">
<div class="tier" style="color:var(--accent2);font-size:.78rem;letter-spacing:.14em;text-transform:uppercase;font-weight:700">Observer, free</div>
<div class="amt" style="margin-top:8px">Free</div>
<p>Start with the free tier, see how the watch reads the market, then decide. No trial traps.</p>
<p style="margin-top:18px"><a href="https://korvus.industries/signup?utm_source=korvus&amp;utm_medium=page&amp;utm_campaign=index-watch-free">Create a free account</a></p>
</div>
</div>
<div class="disclaimer">Korvus provides market information and education. It is not financial advice, and nothing on this page is a recommendation to buy or sell any instrument. Futures trading involves substantial risk of loss. Past reads do not predict future results.</div>
</section>

<footer>
<span>Korvus is a product of BlackCrownVxJ LLC.</span>
<span><a href="https://blackcrownvxj.com">blackcrownvxj.com</a> &middot; <a href="https://korvus.industries/legal">Legal</a> &middot; BlackCrownVxJ.LLC@outlook.com</span>
</footer>
</div>
</body>
</html>
