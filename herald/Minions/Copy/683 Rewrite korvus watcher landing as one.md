# Copy: Rewrite korvus watcher landing as one complete html document

Date: 2026-10-29
Task: Rewrite Korvus watcher landing as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | Korvus, the watcher that never sleeps</title>
<meta name="description" content="Korvus Index Watch scans index futures news around the clock and writes a plain read while you sleep. Operator includes LodeStone. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
:root{--bg:#07080c;--ink:#e9ecf3;--mute:#9aa3b5;--acc:#7c5cff;--acc2:#24d6c0;--line:#1c2030}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:radial-gradient(900px 500px at 15% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(36,214,192,.14),transparent 60%),linear-gradient(180deg,#0a0c12,#06070a);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;pointer-events:none;z-index:0}
body::after{content:"";position:fixed;inset:0;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65));pointer-events:none;z-index:0}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 22px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;gap:16px}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;color:var(--ink);text-decoration:none}
nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:14px}
h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.1;margin:28px 0 14px;letter-spacing:-.01em}
h2{font-size:clamp(1.4rem,3vw,1.9rem);margin:0 0 12px}
.lead{font-size:clamp(1.02rem,1.8vw,1.15rem);color:var(--mute);max-width:62ch}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0}
.chip{border:1px solid var(--line);background:rgba(255,255,255,.03);padding:6px 12px;border-radius:999px;font-size:13px}
.btn{display:inline-block;background:var(--acc);color:#fff;padding:13px 22px;border-radius:10px;text-decoration:none;font-weight:600}
.btn.ghost{background:transparent;border:1px solid var(--line);color:var(--ink);margin-left:10px}
section{margin:64px 0}
.card{border:1px solid var(--line);background:rgba(12,14,22,.7);border-radius:14px;padding:22px}
.fig{border:1px solid var(--line);border-radius:14px;background:rgba(10,12,18,.85);overflow:hidden}
.fig-head{display:flex;justify-content:space-between;gap:12px;padding:12px 16px;border-bottom:1px solid var(--line);font-size:13px;color:var(--mute)}
.row{display:grid;grid-template-columns:70px 90px 1fr 120px;gap:10px;padding:11px 16px;border-bottom:1px solid var(--line);font-size:14px;align-items:center}
.row:last-child{border-bottom:0}
.tag{font-size:12px;padding:3px 8px;border-radius:6px;background:rgba(36,214,192,.12);color:var(--acc2);justify-self:start}
.tag.warn{background:rgba(124,92,255,.16);color:#c3b5ff}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.grid2{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.price{font-size:clamp(1.8rem,4vw,2.4rem);font-weight:700;margin:6px 0}
.muted{color:var(--mute);font-size:14px}
.disc{font-size:13px;color:var(--mute);border-top:1px solid var(--line);padding-top:18px;margin-top:40px}
footer{padding:30px 0 50px;color:var(--mute);font-size:13px}
@media (max-width:700px){
.grid3,.grid2{grid-template-columns:1fr}
nav a{display:none}
.row{grid-template-columns:1fr;gap:4px}
.btn.ghost{margin:10px 0 0 0;display:inline-block}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="https://korvus.industries/">
<svg width="30" height="30" viewBox="0 0 32 32" aria-hidden="true"><path d="M4 22 L7 10 L13 16 L16 7 L19 16 L25 10 L28 22 Z" fill="none" stroke="#7c5cff" stroke-width="2" stroke-linejoin="round"/><rect x="4" y="23" width="24" height="3" rx="1" fill="#24d6c0"/></svg>
<span>KORVUS</span>
</a>
<nav><a href="/lodestone">LodeStone</a><a href="/signup">Sign up</a><a href="/legal">Legal</a></nav>
</header>

<h1>Index Watch runs while you sleep.</h1>
<p class="lead">Korvus watches the news feeds for index futures around the clock, scores each headline for impact, direction and confidence, and writes a plain read you can check in seconds. You decide what it means for your session.</p>
<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Scored headlines</span>
<span class="chip">Written Korvus read</span>
<span class="chip">LodeStone included with Operator</span>
</div>
<a class="btn" href="/signup">Start with the free Observer tier</a>
<a class="btn ghost" href="#pricing">See Operator</a>

<section>
<h2>What the watch looks like</h2>
<p class="muted">Illustration. Layout sample only, not live output and not a signal.</p>
<div class="fig" role="img" aria-label="Illustration of an Index Watch feed">
<div class="fig-head"><span>Index Watch feed</span><span>Illustration</span></div>
<div class="row"><span>03:12</span><span>ES</span><span>Rates auction tails, yields firm into the overnight session</span><span class="tag warn">High impact</span></div>
<div class="row"><span>03:40</span><span>NQ</span><span>Mega-cap earnings guide raised, tech sentiment mixed</span><span class="tag">Lean up, med</span></div>
<div class="row"><span>04:05</span><span>YM</span><span>Industrial order data soft, revision pending</span><span class="tag warn">Lean down, low</span></div>
<div class="row"><span>04:22</span><span>ES</span><span>Central bank speaker repeats prior guidance, no new language</span><span class="tag">Low impact</span></div>
</div>
</section>

<section>
<h2>How it works</h2>
<div class="grid3">
<div class="card"><strong>1. It reads everything</strong><p class="muted">Wire and policy feeds are monitored continuously, including the hours you are offline.</p></div>
<div class="card"><strong>2. It scores each item</strong><p class="muted">Every headline gets an impact level, a direction lean and a confidence rating.</p></div>
<div class="card"><strong>3. It writes the read</strong><p class="muted">A short Korvus read explains the item in plain language so you can judge it yourself.</p></div>
</div>
</section>

<section id="pricing">
<h2>Operator</h2>
<p class="lead">Full Korvus terminal access, with the LodeStone TradingView indicator included.</p>
<div class="grid2" style="margin-top:20px">
<div class="card">
<span class="tag">Annual, listed first</span>
<div class="price">79.99 <span class="muted">a year</span></div>
<p class="muted">Includes LodeStone on TradingView.</p>
<a class="btn" href="/upgrade">Choose annual</a>
</div>
<div class="card">
<span class="tag warn">Monthly</span>
<div class="price">9.99 <span class="muted">a month</span></div>
<p class="muted">Same terminal and LodeStone, billed monthly.</p>
<a class="btn ghost" href="/upgrade">Choose monthly</a>
</div>
</div>
</section>

<section>
<h2>Start free, judge the output yourself</h2>
<p class="lead">The Observer tier is free and open. Read the scored feed, check the reads against what the market does, then decide whether Operator earns a place in your routine.</p>
<p><a class="btn ghost" href="/signup" style="margin-left:0">Create a free account</a></p>
</section>

<p class="disc">Korvus provides market information and education. Nothing on this page is financial advice, a trading recommendation or a promise of results. Index futures trading carries substantial risk of loss. Illustrations are labelled and are not live data.</p>
</div>

<footer>
<div class="wrap">
<span>KORVUS by BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</span>
</div>
</footer>
</body>
</html>
