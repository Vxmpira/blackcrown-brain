# Scribe: Rewrite the complete html document for korvus industries p smt

Date: 2026-10-27
Task: Rewrite the COMPLETE html document for korvus.industries/p/smt-divergence from scratch. Previous notes 108 and 109 both failed: 108 duplicated the head tag, 109
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Explained for ES, NQ, YM and RTY</title>
<meta name="description" content="What SMT divergence is, how it compares ES, NQ, YM and RTY to flag a weak move, and how Korvus Operator surfaces it. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e8e8ec;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.65;font-size:16px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:860px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1e1e24;padding:18px 0;background:#08080a}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;color:#fff;font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
nav a{margin-left:18px;color:#b8b8c2;font-size:14px}
nav a:hover{color:#ff2d8f}
.hero{padding:56px 0 28px}
.kicker{color:#ff2d8f;font-size:13px;text-transform:uppercase;letter-spacing:.12em;font-weight:600}
h1{font-size:40px;line-height:1.15;color:#fff;margin:12px 0 16px;font-weight:800}
h2{font-size:24px;color:#fff;margin:40px 0 12px;font-weight:700}
h3{font-size:17px;color:#ff2d8f;margin:18px 0 6px}
p{margin:0 0 14px;color:#cfcfd8}
.lede{font-size:18px;color:#e2e2ea}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0 6px}
.chip{border:1px solid #2c2c36;background:#121217;color:#ddd;border-radius:999px;padding:5px 12px;font-size:13px}
.chip.pink{border-color:#ff2d8f;color:#ff2d8f}
.panel{background:#101015;border:1px solid #23232c;border-radius:12px;padding:20px;margin:22px 0}
.panel-label{display:inline-block;font-size:12px;color:#ff2d8f;border:1px solid #ff2d8f;border-radius:4px;padding:2px 8px;margin-bottom:12px;letter-spacing:.06em}
.panel svg{width:100%;height:auto;display:block}
.caption{font-size:13px;color:#8d8d99;margin-top:10px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin:18px 0}
.card{background:#101015;border:1px solid #23232c;border-radius:10px;padding:16px}
.card strong{color:#fff;display:block;margin-bottom:4px}
.card span{color:#bdbdc8;font-size:14px}
ul{margin:0 0 14px 20px;color:#cfcfd8}
li{margin-bottom:6px}
.cta{background:#14101a;border:1px solid #ff2d8f;border-radius:14px;padding:28px;margin:36px 0;text-align:center}
.btn{display:inline-block;background:#ff2d8f;color:#0a0a0c;font-weight:700;padding:12px 22px;border-radius:8px;margin-top:10px}
.btn:hover{text-decoration:none;opacity:.92}
.disclaimer{border-left:3px solid #ff2d8f;padding:12px 16px;background:#101015;color:#b8b8c2;font-size:14px;margin:30px 0}
footer{border-top:1px solid #1e1e24;margin-top:40px;padding:22px 0 40px;color:#8d8d99;font-size:14px}
footer a{color:#b8b8c2;margin-right:14px}
@media (max-width:640px){h1{font-size:30px}.grid{grid-template-columns:1fr}nav a{margin-left:12px}}
</style>
</head>
<body>
<header>
<div class="wrap bar">
<a class="brand" href="/" aria-label="Korvus home">
<svg viewBox="0 0 40 40" aria-hidden="true">
<path d="M6 30 L8 14 L15 22 L20 10 L25 22 L32 14 L34 30 Z" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round"/>
<rect x="6" y="30" width="28" height="4" fill="#ff2d8f"/>
<circle cx="20" cy="8" r="2" fill="#ff2d8f"/>
</svg>
<span>KORVUS</span>
</a>
<nav>
<a href="/">Home</a>
<a href="/p/observer">Observer</a>
<a href="/signup">Sign up</a>
</nav>
</div>
</header>

<main class="wrap">
<section class="hero">
<div class="kicker">Education</div>
<h1>SMT Divergence on ES, NQ, YM and RTY</h1>
<p class="lede">SMT divergence is a comparison, not a prediction. When correlated index futures disagree about a new high or a new low, the disagreement is information. This page explains what it is, why it can flag a weak move, and how Korvus Operator surfaces it across the four major index contracts.</p>
<div class="chips">
<span class="chip pink">ES</span>
<span class="chip pink">NQ</span>
<span class="chip pink">YM</span>
<span class="chip pink">RTY</span>
<span class="chip">Index futures</span>
<span class="chip">Education only</span>
</div>
</section>

<section>
<h2>What SMT divergence is</h2>
<p>SMT stands for Smart Money Technique, a term used in ICT style chart reading. The idea is simple. Index futures tend to move together because they track overlapping baskets of stocks. When one contract pushes to a new high or low and a correlated contract fails to do the same at that moment, the two charts no longer agree.</p>
<p>That gap is the divergence. It does not say what happens next. It says the market is not confirming the move across the group, and a trader may want to look closer at why.</p>
</section>

<section>
<div class="panel">
<span class="panel-label">Illustration</span>
<svg viewBox="0 0 640 260" role="img" aria-label="Illustration: ES makes a higher high while NQ fails to confirm">
<rect x="0" y="0" width="640" height="260" fill="#0c0c10"/>
<line x1="40" y1="220" x2="620" y2="220" stroke="#2a2a33" stroke-width="1"/>
<line x1="40" y1="40" x2="40" y2="220" stroke="#2a2a33" stroke-width="1"/>
<polyline points="60,180 120,150 170,168 230,120 290,140 340,96 400,118 450,80" fill="none" stroke="#8d8d99" stroke-width="2.5"/>
<polyline points="60,190 120,160 170,176 230,128 290,150 340,112 400,132 450,104" fill="none" stroke="#ff2d8f" stroke-width="2.5"/>
<line x1="340" y1="60" x2="340" y2="220" stroke="#ff2d8f" stroke-width="1" stroke-dasharray="4 4" opacity="0.5"/>
<circle cx="450" cy="80" r="5" fill="#8d8d99"/>
<circle cx="450" cy="104" r="5" fill="#ff2d8f"/>
<line x1="470" y1="80" x2="470" y2="104" stroke="#fff" stroke-width="1.5"/>
<rect x="480" y="66" width="140" height="52" rx="6" fill="#14141a" stroke="#23232c"/>
<circle cx="494" cy="82" r="4" fill="#8d8d99"/>
<text x="504" y="86" fill="#cfcfd8" font-size="12" font-family="system-ui,sans-serif">Contract A</text>
<circle cx="494" cy="104" r="4" fill="#ff2d8f"/>
<text x="504" y="108" fill="#cfcfd8" font-size="12" font-family="system-ui,sans-serif">Contract B</text>
<text x="48" y="246" fill="#8d8d99" font-size="12" font-family="system-ui,sans-serif">Illustration only. Not market data.</text>
</svg>
<p class="caption">Illustration: contract A prints a higher high while contract B stops short of it at the same moment. The gap between the two is the divergence being described.</p>
</div>
</section>

<section>
<h2>Why it can flag a weak move</h2>
<p>A move that is broad should show up broadly. If ES and NQ both sweep a prior high, a trader reading the pair expects participation from both. When only one of them does, the move may rest on a narrower base than the headline suggests.</p>
<ul>
<li>A failed confirmation can point to a level that was swept without follow through.</li>
<li>It can show that leadership is shifting between groups of stocks.</li>
<li>It gives context to a level, which is different from a signal to act.</li>
</ul>
<p>None of that is guaranteed. Divergences persist, resolve sideways, or get overrun. The point of the tool is to make disagreement visible, so the reader can judge it with their own rules.</p>
</section>

<section>
<h2>Across ES, NQ, YM and RTY</h2>
<div class="grid">
<div class="card"><strong>ES, S&amp;P 500</strong><span>The broad benchmark. Most divergence readings start here as the reference contract.</span></div>
<div class="card"><strong>NQ, Nasdaq 100</strong><span>Tech heavy and often the most sensitive to growth sentiment. Divergences against ES are common reading points.</span></div>
<div class="card"><strong>YM, Dow</strong><span>Price weighted and built differently. A gap between YM and ES can say something about breadth across large caps.</span></div>
<div class="card"><strong>RTY, Russell 2000</strong><span>Small caps. Its behavior against ES can show whether risk appetite is broad or concentrated.</span></div>
</div>
<p>Each pair tells a different story. ES against NQ is the most watched. ES against RTY and YM often adds breadth context. Comparing all four at once is harder by hand, which is where a terminal helps.</p>
</section>

<section>
<h2>How Korvus Operator surfaces it</h2>
<p>Korvus Operator is the paid tier of Korvus, a 24/7 market intelligence terminal for index futures traders. It watches the four contracts together and flags when the group stops agreeing on a new high or low.</p>
<ul>
<li>Cross index readings for ES, NQ, YM and RTY in one view, so a divergence on one pair is not read in isolation.</li>
<li>The LodeStone TradingView indicator is included with Operator. It carries an SMT divergence input for chart work.</li>
<li>Alerts describe the disagreement in plain terms. They do not tell you to trade it.</li>
</ul>
<p>The free Observer tier shows the same market context at a lighter depth. Read <a href="/p/observer">what Observer includes</a> before deciding which view fits how you work.</p>
</section>

<section>
<h2>What this cannot do</h2>
<p>SMT divergence has no fixed timeframe, no guaranteed reversal, and no built in stop. Contracts can diverge for days. Markets can ignore a divergence entirely, especially around scheduled news. Treat every reading as one input among many, and test any approach on your own data before it touches your capital.</p>
</section>

<section class="cta">
<h2 style="margin-top:0">See the four indices side by side</h2>
<p>Create a free Korvus account and explore the terminal. No card needed to start.</p>
<a class="btn" href="/signup">Create a free Korvus account</a>
</section>

<div class="disclaimer">
Education only. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Index futures carry substantial risk of loss. Past chart behavior does not predict future results. Korvus and BlackCrown Intelligence are tools for reading markets, and you make your own decisions.
</div>
</main>

<footer>
<div class="wrap">
<p><a href="/">Korvus home</a><a href="/p/observer">Observer</a><a href="/signup">Create account</a><a href="/legal">Legal</a></p>
<p>BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</footer>
</body>
</html>
