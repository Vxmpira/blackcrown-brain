# Copy: Write the index watch landing page as a complete html

Date: 2026-10-28
Task: Write the index-watch landing page as a complete html document into a vault note, under 6000 characters, ending with the closing html tag.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures Watch 24/7 | Korvus</title>
<meta name="description" content="Korvus watches index futures around the clock with scored news and a written read, so you see the overnight move before the open. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080c;color:#e6e8ee;font-family:Helvetica,Arial,sans-serif;line-height:1.6}
a{color:#c9a84c;text-decoration:none}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:20px 0;border-bottom:1px solid #1d2030}
.brand{display:flex;align-items:center;gap:10px;color:#e6e8ee;font-weight:700;letter-spacing:.08em}
.nav a{margin-left:18px;color:#9aa0b4;font-size:14px}
.hero{padding:56px 0 32px}
.eyebrow{color:#c9a84c;font-size:13px;letter-spacing:.14em;text-transform:uppercase}
h1{font-size:40px;line-height:1.15;margin:14px 0 18px;max-width:780px}
.lede{color:#aab0c2;font-size:18px;max-width:700px}
.cta{display:inline-block;margin-top:26px;background:#c9a84c;color:#07080c;padding:13px 22px;border-radius:4px;font-weight:700}
.panel{background:#0d0f16;border:1px solid #1d2030;border-radius:6px;padding:22px;margin:28px 0}
.panel h2{font-size:20px;margin-bottom:10px}
.panel p{color:#aab0c2}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px}
.chip{border:1px solid #2a2f45;border-radius:14px;padding:5px 12px;font-size:13px;color:#c9cfe0}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.tag{color:#7d8399;font-size:12px;letter-spacing:.06em;text-transform:uppercase}
.disc{color:#7d8399;font-size:13px;margin:34px 0 10px;border-top:1px solid #1d2030;padding-top:18px}
footer{padding:24px 0 40px;color:#5d6378;font-size:13px}
@media(max-width:700px){h1{font-size:30px}.grid{grid-template-columns:1fr}.nav{display:none}}
</style>
</head>
<body>
<header class="wrap">
<div class="brand">
<svg width="30" height="30" viewBox="0 0 40 40" aria-hidden="true">
<path d="M6 30 L8 14 L15 22 L20 10 L25 22 L32 14 L34 30 Z" fill="#c9a84c"/>
<rect x="6" y="32" width="28" height="3" fill="#c9a84c"/>
</svg>
KORVUS
</div>
<nav class="nav">
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
</nav>
</header>

<main class="wrap">
<section class="hero">
<div class="eyebrow">Index futures, 24/7</div>
<h1>The market moves at 3 a.m. Korvus watches index futures while you sleep.</h1>
<p class="lede">Korvus scores overnight news by impact, direction, and confidence, then writes a plain read on what it means for the index you trade. You wake up to the work already done.</p>
<a class="cta" href="/signup">Start with the free Observer tier</a>
</section>

<section class="panel">
<div class="tag">Illustration</div>
<h2>Overnight watch, one screen</h2>
<p>A sample of how the overnight session reads when you open it. Figures are illustrative, not live data.</p>
<svg viewBox="0 0 640 200" width="100%" role="img" aria-label="Illustration of overnight index futures movement with scored events" style="margin-top:14px">
<rect x="0" y="0" width="640" height="200" fill="#07080c"/>
<line x1="0" y1="50" x2="640" y2="50" stroke="#1d2030"/>
<line x1="0" y1="100" x2="640" y2="100" stroke="#1d2030"/>
<line x1="0" y1="150" x2="640" y2="150" stroke="#1d2030"/>
<polyline points="20,150 70,138 120,144 170,118 220,126 270,96 320,104 370,78 420,88 470,62 520,70 570,48 620,56" fill="none" stroke="#c9a84c" stroke-width="3"/>
<circle cx="270" cy="96" r="5" fill="#e6e8ee"/>
<circle cx="470" cy="62" r="5" fill="#e6e8ee"/>
<text x="282" y="88" fill="#aab0c2" font-size="13" font-family="Arial">Scored event: high impact</text>
<text x="482" y="54" fill="#aab0c2" font-size="13" font-family="Arial">Read logged</text>
</svg>
<div class="chips">
<span class="chip">Impact scored</span>
<span class="chip">Direction</span>
<span class="chip">Confidence</span>
<span class="chip">Written read</span>
<span class="chip">Session levels</span>
</div>
</section>

<section class="grid">
<div class="panel">
<h2>Watching while you rest</h2>
<p>Korvus runs continuously across the overnight session. When something moves the index, you see what changed, how strong the signal is, and what the read says, in one place.</p>
</div>
<div class="panel">
<h2>Operator, annual plan</h2>
<p>Operator includes Korvus market intelligence and the LodeStone TradingView indicator. The annual plan is listed first, with the savings shown at checkout.</p>
<a href="/signup" style="display:inline-block;margin-top:14px;color:#c9a84c;font-weight:700">See the annual plan</a>
</div>
</section>

<section class="panel">
<h2>Built for the operator, not the pedestal</h2>
<p>Korvus is built by a solo index futures trader for people who trade the same market. No promised returns, no signal calls, no guru theater. Just the watch, the score, and the read.</p>
</section>

<p class="disc">Not financial advice. Korvus provides market information and education only. It does not recommend trades or guarantee outcomes. Trading index futures carries substantial risk of loss.</p>
</main>

<footer class="wrap">
<div>Korvus, a product of BlackCrownVxJ LLC. <a href="/legal">Legal</a></div>
</footer>
</body>
</html>
