# Scribe: Write the complete html document for a new page korvus

Date: 2026-10-28
Task: Write the COMPLETE html document for a new page, korvus:pages/equal-highs-and-lows.html, serving at korvus.industries/p/equal-highs-and-lows. Full doctype throu
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Equal Highs and Lows Explained for Index Futures</title>
<meta name="description">
<meta name="description" content="Equal highs and lows explained plainly for index futures traders. What they are, why stops cluster there, how sweeps resolve them, and where the idea fails.">
<link rel="canonical" href="https://korvus.industries/p/equal-highs-and-lows">
<meta name="robots" content="index, follow">
<meta property="og:title" content="Equal Highs and Lows Explained for Index Futures">
<meta property="og:description" content="What equal highs and lows are, why stops cluster there, and where the idea fails. Education only.">
<meta property="og:type" content="article">
<meta property="og:url" content="https://korvus.industries/p/equal-highs-and-lows">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0f;color:#e6e6ee;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.65;font-size:16px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #1e1e2a;flex-wrap:wrap}
header svg{width:36px;height:33px}
.brand{font-weight:700;font-size:20px;letter-spacing:.5px;color:#fff}
nav{margin-left:auto;display:flex;gap:18px;flex-wrap:wrap}
nav a{color:#b8b8c8;font-size:14px}
main{max-width:820px;margin:0 auto;padding:40px 24px 64px}
h1{font-size:34px;line-height:1.2;color:#fff;margin-bottom:14px}
h2{font-size:22px;color:#fff;margin:40px 0 12px}
p{margin-bottom:16px;color:#d4d4de}
.lede{font-size:18px;color:#f0f0f6}
.panel{background:#12121a;border:1px solid #1e1e2a;border-radius:10px;padding:22px;margin:24px 0}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin:18px 0}
.chip{background:#12121a;border:1px solid #ff2d8f;color:#ff2d8f;border-radius:999px;padding:4px 12px;font-size:13px}
figure{background:#12121a;border:1px solid #1e1e2a;border-radius:10px;padding:18px;margin:24px 0}
figure svg{width:100%;height:auto;display:block}
figcaption{font-size:13px;color:#9a9ab0;margin-top:10px}
ul{margin:0 0 16px 22px;color:#d4d4de}
li{margin-bottom:8px}
.disclaimer{background:#12121a;border-left:3px solid #ff2d8f;padding:18px 20px;border-radius:6px;margin:40px 0 24px;font-size:14px;color:#b8b8c8}
.cta{text-align:center;background:#12121a;border:1px solid #1e1e2a;border-radius:10px;padding:28px 22px;margin-top:32px}
.btn{display:inline-block;background:#ff2d8f;color:#0a0a0f;font-weight:700;padding:12px 26px;border-radius:6px;margin-top:10px}
.btn:hover{text-decoration:none;opacity:.9}
footer{border-top:1px solid #1e1e2a;padding:24px;text-align:center;font-size:13px;color:#8a8a9c}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">Korvus</span>
<nav>
<a href="/">Home</a>
<a href="/lodestone">LodeStone</a>
<a href="/signup">Free Observer</a>
</nav>
</header>

<main>
<p class="chips"><span class="chip">Beginner</span><span class="chip">Index futures</span><span class="chip">Education only</span></p>

<h1>Equal highs and lows, explained plainly</h1>
<p class="lede">Two swing points at nearly the same price. That is the whole pattern. This guide explains what it looks like, why it draws attention, and where the idea breaks down.</p>

<h2>What equal highs and lows are</h2>
<p>A swing high is a peak where price rose, then turned down. A swing low is a trough where price fell, then turned up. When two swing highs sit at roughly the same price, traders call them equal highs. Two swing lows at roughly the same price are equal lows.</p>
<p>"Roughly" matters. Price almost never lands on the exact same tick twice. Most traders treat points within a small band as equal, and that band depends on the instrument and the timeframe you chart.</p>

<figure>
<svg viewBox="0 0 400 220" role="img" aria-label="Illustration of equal highs with a sweep above them">
<rect x="0" y="0" width="400" height="220" fill="#0a0a0f"/>
<line x1="20" y1="60" x2="380" y2="60" stroke="#ff2d8f" stroke-width="1.5" stroke-dasharray="6 5"/>
<polyline points="20,150 70,95 120,60 170,120 220,62 270,130 310,40 350,110 380,95" fill="none" stroke="#e6e6ee" stroke-width="2.2" stroke-linejoin="round"/>
<circle cx="120" cy="60" r="4" fill="#ff2d8f"/>
<circle cx="220" cy="62" r="4" fill="#ff2d8f"/>
<text x="26" y="50" fill="#ff2d8f" font-size="12" font-family="system-ui,sans-serif">Equal highs</text>
<text x="300" y="30" fill="#9a9ab0" font-size="12" font-family="system-ui,sans-serif">Sweep</text>
<text x="10" y="210" fill="#9a9ab0" font-size="11" font-family="system-ui,sans-serif">Illustration. Not real market data.</text>
</svg>
<figcaption>Illustration. Two swing highs sit near the same level. A later spike trades through that level, then price turns back down.</figcaption>
</figure>

<h2>Why stops cluster there</h2>
<p>Many traders place stop orders just beyond obvious levels. A short seller often sets a stop above a recent high. A long buyer often sets a stop below a recent low. When the same level has been tested twice, many of those stops sit in the same zone.</p>
<p>That clustering is the reason traders watch these points. It is a mechanical fact about how orders are placed, not a prediction about what price will do next.</p>

<h2>How this connects to resting liquidity</h2>
<p>Resting orders are orders waiting on the book or in the chart structure. Stop orders become market orders once triggered, so a cluster of them is a pool of fuel. Equal highs and lows mark where that fuel is likely to sit. For a fuller explanation, read the guide on <a href="https://korvus.industries/p/resting-liquidity">resting liquidity</a>.</p>

<div class="panel">
<p><strong>Plain version:</strong> equal highs show where sellers placed stops above. Equal lows show where buyers placed stops below. The level is visible. The orders behind it are not.</p>
</div>

<h2>How sweeps resolve them</h2>
<p>A sweep happens when price trades through an equal high or low, takes out the clustered orders, and then moves back the other way. Traders describe it as a level being "run" or "swept."</p>
<ul>
<li>Price approaches the equal level.</li>
<li>Price trades a little beyond it, often briefly.</li>
<li>Price returns inside the prior range.</li>
<li>Traders watch whether the move holds or continues.</li>
</ul>
<p>Not every touch is a sweep. A sweep is defined by what happens after the level breaks. A clean break and hold is a different event, and the two can look identical for the first few bars.</p>

<h2>Where the idea fails</h2>
<p>This is the part most guides skip. Equal highs and lows fail often, and the failures are instructive.</p>
<ul>
<li><strong>Price breaks and keeps going.</strong> A level can break because the market has genuinely changed direction. Stops are not the only force.</li>
<li><strong>The level was never equal.</strong> Two highs that differ by a noticeable amount are not equal, however much you want them to be.</li>
<li><strong>Too many levels.</strong> On a busy chart, almost every price is near some earlier high or low. A pattern that appears everywhere carries little information.</li>
<li><strong>Timeframe mismatch.</strong> Equal highs on a one-minute chart can sit inside a single equal high on a larger chart. Context changes what the level means.</li>
<li><strong>Confirmation is late.</strong> The sweep is only clear after price has already moved. Anything that looks obvious in hindsight was not obvious in the moment.</li>
</ul>

<h2>Testing the idea yourself</h2>
<p>Mark equal highs and lows on past sessions, then record what happened next. Do not decide ahead of time what the answer should be. Write down the misses as carefully as the hits. A pattern you cannot measure is a story, and stories are cheap.</p>

<p>For a related concept that people often pair with sweeps, read the explainer on <a href="https://korvus.industries/p/what-is-smt-divergence">SMT divergence</a>. It compares how related index futures move at the same highs and lows, which can help you see whether a level is being respected across markets.</p>

<div class="disclaimer">
<strong>Education only. Not trading advice.</strong> This page explains a chart concept. It does not recommend any entry, exit, position size, or instrument, and it does not promise any result. Futures trading carries substantial risk of loss. Past chart behavior does not predict future prices. Korvus is a market intelligence tool, and you make your own decisions.
</div>

<div class="cta">
<p>Want to watch these levels live without staring at charts all day?</p>
<p>Korvus Observer is free. No card needed. See what the terminal reads across the session.</p>
<a class="btn" href="https://korvus.industries/signup">Create your free Observer account</a>
</div>
</main>

<footer>
<p>Korvus by BlackCrownVxJ LLC. <a href="/legal">Legal</a></p>
<p>Your edge while the world sleeps.</p>
</footer>
</body>
</html>
