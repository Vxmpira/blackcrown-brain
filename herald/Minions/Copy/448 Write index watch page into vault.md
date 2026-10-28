# Copy: Write index watch page into vault note complete html document

Date: 2026-10-28
Task: Write index-watch page into vault note, complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch: Korvus 24/7 Market Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock, scoring news and flow while you sleep. Free Observer tier. Operator adds the LodeStone chart toolkit.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
:root{--bg:#07080b;--panel:#0d1017;--line:#1c2230;--text:#e7e9ee;--muted:#8a93a6;--accent:#c9a54a;--ok:#4fb38a;--bad:#d6615b}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
a{color:var(--accent);text-decoration:none}
.wrap{max-width:980px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{display:flex;align-items:center;gap:10px;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);margin-left:18px;font-size:14px}
nav a:hover{color:var(--text)}
.hero{padding:64px 0 36px}
.eyebrow{color:var(--accent);font-size:13px;text-transform:uppercase;letter-spacing:.12em;margin:0 0 12px}
h1{font-size:40px;line-height:1.15;margin:0 0 16px;font-weight:700}
.lede{color:var(--muted);font-size:18px;max-width:700px;margin:0 0 28px}
.btn{display:inline-block;background:var(--accent);color:#14110a;font-weight:700;padding:12px 20px;border-radius:6px;margin-right:12px}
.btn.ghost{background:transparent;color:var(--text);border:1px solid var(--line)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:28px 0 0}
.chip{border:1px solid var(--line);background:var(--panel);color:var(--muted);font-size:13px;padding:6px 12px;border-radius:999px}
section{padding:40px 0}
h2{font-size:26px;margin:0 0 14px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px}
.card h3{margin:0 0 8px;font-size:17px}
.card p{margin:0;color:var(--muted);font-size:15px}
.mock{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px}
.mock-head{display:flex;justify-content:space-between;align-items:center;color:var(--muted);font-size:13px;margin-bottom:12px}
.tag{color:var(--accent);border:1px solid var(--accent);border-radius:4px;padding:2px 8px;font-size:12px}
.feed{margin:0;padding:0;list-style:none}
.feed li{display:flex;justify-content:space-between;gap:12px;border-top:1px solid var(--line);padding:10px 0;font-size:14px}
.feed .up{color:var(--ok)}
.feed .down{color:var(--bad)}
.feed .muted{color:var(--muted)}
.steps{counter-reset:s;margin:0;padding:0;list-style:none}
.steps li{counter-increment:s;padding:12px 0 12px 44px;position:relative;border-top:1px solid var(--line);color:var(--muted)}
.steps li:before{content:counter(s);position:absolute;left:0;top:12px;width:28px;height:28px;border-radius:50%;background:var(--panel);border:1px solid var(--accent);color:var(--accent);display:flex;align-items:center;justify-content:center;font-size:13px}
.cta{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:32px;text-align:left}
.cta p{color:var(--muted);margin:0 0 20px}
footer{border-top:1px solid var(--line);padding:28px 0;color:var(--muted);font-size:13px}
.disclaimer{margin:0 0 12px}
@media (max-width:760px){.grid{grid-template-columns:1fr}h1{font-size:30px}nav{display:none}}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="/" aria-label="Korvus home">
<svg viewBox="0 0 64 64" aria-hidden="true">
<path d="M10 46 L16 24 L24 34 L32 16 L40 34 L48 24 L54 46 Z" fill="none" stroke="#c9a54a" stroke-width="3" stroke-linejoin="round"/>
<circle cx="32" cy="50" r="3" fill="#c9a54a"/>
</svg>
<span>KORVUS</span>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/signup">Observer</a>
<a href="/login">Log in</a>
</nav>
</div>
</header>

<main>
<div class="wrap hero">
<p class="eyebrow">Index Watch</p>
<h1>The market does not close. Your watch should not either.</h1>
<p class="lede">Korvus scans index futures around the clock, scores each headline by impact, direction and confidence, and writes a plain read you can check in seconds. You make the decisions. Korvus keeps the watch.</p>
<a class="btn" href="/signup">Start with Observer, free</a>
<a class="btn ghost" href="/lodestone">See LodeStone</a>
<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Impact scored</span>
<span class="chip">Direction and confidence</span>
<span class="chip">Written Korvus read</span>
<span class="chip">Zero repainting charts</span>
</div>
</div>

<section>
<div class="wrap">
<h2>What the watch covers</h2>
<div class="grid">
<div class="card">
<h3>Scored news wire</h3>
<p>Every relevant release is ranked for likely impact on index futures, with direction and a confidence band attached so you know how hard the read is leaning.</p>
</div>
<div class="card">
<h3>Economic agenda</h3>
<p>The USD calendar for the session, with scheduled times in your timezone and actuals posted as they land, so the overnight gap is no longer a surprise.</p>
</div>
<div class="card">
<h3>Session context</h3>
<p>Asia, London and New York windows tracked on their own, so you see which session owns the tape before you open a position of your own.</p>
</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<h2>Inside the watch</h2>
<div class="mock">
<div class="mock-head">
<span>Korvus wire, sample feed</span>
<span class="tag">Illustration</span>
</div>
<ul class="feed">
<li><span>Headline: rate path repricing, front end</span><span class="up">Impact high, bullish ES, conf 62</span></li>
<li><span>Headline: services data softer than consensus</span><span class="down">Impact medium, bearish NQ, conf 48</span></li>
<li><span>Session: London open, volume building</span><span class="muted">Context, no directional call</span></li>
<li><span>Agenda: USD labor release, 08:30 ET</span><span class="muted">Actual posted on release</span></li>
</ul>
</div>
<p style="color:var(--muted);font-size:13px;margin:12px 0 0">The feed above is an illustrative mock of the layout. It is not live data and not a trading signal.</p>
</div>
</section>

<section>
<div class="wrap">
<h2>How you use it</h2>
<ol class="steps">
<li>Open the Korvus terminal and set your index watch list once.</li>
<li>Scan the scored wire and the session context when you wake up or hand off a position.</li>
<li>Check the written read against your own chart and your own plan.</li>
<li>Go deeper with Operator, which adds the LodeStone TradingView indicator at no extra cost.</li>
</ol>
</div>
</section>

<section>
<div class="wrap">
<div class="cta">
<h2 style="margin-top:0">Run the watch for free</h2>
<p>Observer is free and needs no card. Operator is the full stack for traders who want the chart toolkit and the complete terminal.</p>
<a class="btn" href="/signup">Create Observer account</a>
<a class="btn ghost" href="/upgrade">Compare Operator</a>
</div>
</div>
</section>
</main>

<footer>
<div class="wrap">
<p class="disclaimer">Korvus is market intelligence and education software. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Index futures carry substantial risk of loss. Past reads are not predictions. Trade only capital you can afford to lose.</p>
<p class="disclaimer">BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
<p class="disclaimer"><a href="/legal">Legal</a> &middot; <a href="/terminal">Terminal</a></p>
</div>
</footer>
</body>
</html>
