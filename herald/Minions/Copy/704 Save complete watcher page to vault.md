# Copy: Save complete watcher page to vault note watcher page md

Date: 2026-10-29
Task: Save complete watcher page to vault note Watcher-page.md
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher | Korvus 24/7 Market Intelligence</title>
<meta name="description" content="Korvus Watcher monitors index futures news around the clock and scores each event by impact, direction, and confidence while you sleep. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0d1017;--line:#1c2230;--text:#e7eaf2;--mute:#8f98ab;--gold:#d8b45a;--cyan:#4fc3d9;--red:#e06c6c;--green:#6fd08c}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 45% at 85% 0%,rgba(79,195,217,.13),transparent 70%),radial-gradient(50% 40% at 0% 30%,rgba(216,180,90,.10),transparent 70%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
a{color:var(--cyan);text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand span{color:var(--mute);font-weight:500;font-size:.85rem;display:block;letter-spacing:.02em}
nav a{color:var(--mute);margin-left:18px;font-size:.92rem}
nav a:hover{color:var(--text);text-decoration:none}
.hero{padding:72px 0 56px;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.18em;font-size:.78rem;font-weight:700}
h1{font-size:clamp(2rem,4.6vw,3.4rem);line-height:1.1;margin:14px 0 18px;letter-spacing:-.01em}
h2{font-size:clamp(1.4rem,2.8vw,2rem);margin-bottom:12px}
h3{font-size:1.05rem;margin-bottom:6px}
.lead{color:var(--mute);font-size:1.08rem;max-width:58ch}
.cta{display:inline-block;margin-top:26px;background:var(--gold);color:#120e04;font-weight:700;padding:14px 22px;border-radius:8px}
.cta:hover{text-decoration:none;filter:brightness(1.08)}
.ghost{display:inline-block;margin:26px 0 0 12px;color:var(--text);padding:14px 4px;font-weight:600}
.note{color:var(--mute);font-size:.85rem;margin-top:14px}
.panel{background:linear-gradient(180deg,var(--panel),#090c12);border:1px solid var(--line);border-radius:14px;padding:20px;box-shadow:0 20px 60px rgba(0,0,0,.45)}
.panel-head{display:flex;justify-content:space-between;align-items:center;font-size:.8rem;color:var(--mute);margin-bottom:12px}
.tag{font-size:.7rem;letter-spacing:.12em;text-transform:uppercase;color:var(--gold);border:1px solid rgba(216,180,90,.4);padding:3px 8px;border-radius:999px}
.feed{list-style:none;display:grid;gap:10px}
.feed li{display:grid;grid-template-columns:64px 1fr auto;gap:12px;align-items:center;padding:10px 12px;background:rgba(255,255,255,.02);border:1px solid var(--line);border-radius:10px;font-size:.9rem}
.time{color:var(--mute);font-variant-numeric:tabular-nums}
.dir{font-weight:700;font-size:.78rem;letter-spacing:.06em}
.up{color:var(--green)} .down{color:var(--red)} .flat{color:var(--mute)}
.score{font-variant-numeric:tabular-nums;color:var(--text);font-size:.82rem}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:8px 0 0}
.chip{border:1px solid var(--line);background:rgba(255,255,255,.02);padding:8px 14px;border-radius:999px;font-size:.88rem;color:var(--text)}
section{padding:56px 0;border-top:1px solid var(--line)}
.lede{color:var(--mute);max-width:64ch;margin-bottom:26px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:20px}
.card p{color:var(--mute);font-size:.94rem}
.num{color:var(--cyan);font-weight:700;font-size:.85rem;letter-spacing:.1em;margin-bottom:10px;display:block}
.table-wrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px}
table{width:100%;border-collapse:collapse;font-size:.92rem;min-width:520px}
th,td{text-align:left;padding:12px 14px;border-bottom:1px solid var(--line)}
th{color:var(--mute);font-weight:600;font-size:.8rem;text-transform:uppercase;letter-spacing:.08em;background:rgba(255,255,255,.02)}
tr:last-child td{border-bottom:none}
.figure-cap{color:var(--mute);font-size:.82rem;margin-top:10px}
.prose{max-width:66ch}
.prose p{color:var(--mute);margin-bottom:14px}
.prose p strong{color:var(--text)}
.final{text-align:center;padding:64px 0}
.final p{color:var(--mute);margin:14px auto 0;max-width:56ch}
.disc{color:var(--mute);font-size:.82rem;max-width:72ch;margin:0 auto}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--mute);font-size:.85rem}
footer .row{display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
@media (max-width:700px){
.hero{grid-template-columns:1fr;padding:44px 0 36px;gap:28px}
.grid{grid-template-columns:1fr}
nav a{margin-left:12px;font-size:.85rem}
header{flex-wrap:wrap;gap:12px}
.ghost{margin:14px 0 0 0;display:block}
.feed li{grid-template-columns:52px 1fr}
.feed li .score{grid-column:2}
section{padding:40px 0}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg width="34" height="34" viewBox="0 0 48 48" aria-hidden="true">
<path d="M8 34 L8 16 L16 24 L24 10 L32 24 L40 16 L40 34 Z" fill="none" stroke="#d8b45a" stroke-width="2.5" stroke-linejoin="round"/>
<rect x="8" y="36" width="32" height="3" rx="1" fill="#d8b45a"/>
<circle cx="24" cy="26" r="2.4" fill="#4fc3d9"/>
</svg>
<div>KORVUS<span>by BlackCrownVxJ</span></div>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/signup">Sign up</a>
<a href="/login">Log in</a>
</nav>
</header>

<div class="hero">
<div>
<div class="eyebrow">Korvus Watcher</div>
<h1>The market never sleeps. The Watcher doesn't either.</h1>
<p class="lead">Index futures move while you are off the screen. Korvus Watcher scans the news wire around the clock, scores each event by impact, direction, and confidence, and writes a plain Korvus read you can check in seconds. You decide what it means for your session.</p>
<a class="cta" href="/signup">Start free</a>
<a class="ghost" href="/legal">Read the terms</a>
<p class="note">Information and education only. Not financial advice. Trading involves risk.</p>
</div>
<div class="panel" aria-label="Watcher feed preview">
<div class="panel-head"><span>Live wire, scored</span><span class="tag">Illustration</span></div>
<ul class="feed">
<li><span class="time">02:14</span><span>Treasury auction draws firm demand</span><span class="score"><span class="dir up">UP</span> 6 / 9 · 72%</span></li>
<li><span class="time">03:41</span><span>Overnight headline on energy supply</span><span class="score"><span class="dir flat">MIXED</span> 4 / 9 · 48%</span></li>
<li><span class="time">05:02</span><span>Services data prints below forecast</span><span class="score"><span class="dir down">DOWN</span> 5 / 9 · 64%</span></li>
<li><span class="time">07:30</span><span>Pre-open agenda loaded with live actuals</span><span class="score"><span class="dir flat">INFO</span> 3 / 9 · 90%</span></li>
</ul>
<p class="figure-cap">Illustration: sample rows for layout only. Not a recommendation and not live market output.</p>
</div>
</div>
</div>

<section>
<div class="wrap" style="padding:0">
<div class="eyebrow">How it works</div>
<h2 style="margin-top:10px">Three steps, every event, no noise</h2>
<p class="lede">The Watcher is built for traders who already have a process. It removes the scanning so you can spend your attention on the decision.</p>
<div class="grid">
<div class="card"><span class="num">01 · SCAN</span><h3>Watch the wire</h3><p>Headlines and scheduled releases are collected continuously, including the hours when you are asleep or away from the desk.</p></div>
<div class="card"><span class="num">02 · SCORE</span><h3>Rate each event</h3><p>Every item gets an impact rating, a direction, and a confidence level, so the loudest headline does not automatically rank first.</p></div>
<div class="card"><span class="num">03 · READ</span><h3>Get the Korvus read</h3><p>A short written summary explains what the event is and why it was scored that way. Verify it yourself before you act on anything.</p></div>
</div>
</div>
</section>

<section>
<div class="wrap" style="padding:0">
<div class="eyebrow">What you get</div>
<h2 style="margin-top:10px">Built for index futures traders</h2>
<div class="chips">
<span class="chip">24/7 news monitoring</span>
<span class="chip">Impact, direction, confidence</span>
<span class="chip">Written Korvus read</span>
<span class="chip">Economic agenda with live actuals</span>
<span class="chip">Free Observer tier</span>
<span class="chip">Operator includes LodeStone</span>
</div>
</div>
</section>

<section>
<div class="wrap" style="padding:0">
<div class="eyebrow">Sample scoring table</div>
<h2 style="margin-top:10px">What a scored event looks like</h2>
<p class="lede">Each row shows the fields the Watcher records. The values below are illustrative only.</p>
<div class="table-wrap">
<table>
<thead><tr><th>Event</th><th>Impact</th><th>Direction</th><th>Confidence</th></tr></thead>
<tbody>
<tr><td>Labor report release</td><td>High</td><td>Up</td><td>Medium</td></tr>
<tr><td>Central bank speaker remarks</td><td>Medium</td><td>Mixed</td><td>Low</td></tr>
<tr><td>Corporate guidance update</td><td>Low</td><td>Flat</td><td>High</td></tr>
</tbody>
</table>
</div>
<p class="figure-cap">Illustration: sample data for layout only.</p>
</div>
</section>

<section>
<div class="wrap" style="padding:0">
<div class="eyebrow">Why Korvus</div>
<h2 style="margin-top:10px">Your edge while the world sleeps</h2>
<div class="prose">
<p><strong>The Watcher does one job.</strong> It watches, scores, and reports. It does not place trades, promise outcomes, or tell you what to buy or sell.</p>
<p>Korvus is a market intelligence terminal built by a solo operator who trades index futures himself. Every feature is something that operator wanted during his own sessions, and every claim is written to be checked.</p>
<p>Start on the free Observer tier to see the output for yourself. Upgrade only if the reads earn a place in your routine.</p>
</div>
</div>
</section>

<section class="final">
<div class="wrap" style="padding:0">
<h2>Put the Watcher on your watch list</h2>
<p>Create a free account and see how the scoring reads against the session you actually traded.</p>
<a class="cta" href="/signup">Start free</a>
<p class="disc" style="margin-top:28px">Korvus provides market information and education. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Trading futures involves substantial risk of loss and is not suitable for every person.</p>
</div>
</section>
</div>

<footer>
<div class="wrap">
<div class="row">
<span>Korvus is a product of BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</span>
<span><a href="/legal">Legal</a> · <a href="https://blackcrownvxj.com">blackcrownvxj.com</a></span>
</div>
</div>
</footer>
</body>
</html>
