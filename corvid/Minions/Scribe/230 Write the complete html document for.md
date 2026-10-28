# Scribe: Write the complete html document for a new page korvus

Date: 2026-10-28
Task: Write the COMPLETE html document for a new page, korvus:pages/what-is-smt-divergence.html, serving at korvus.industries/p/what-is-smt-divergence. Doctype throug
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>What Is SMT Divergence? A Plain Guide for Index Futures</title>
<meta name="description">
<meta name="description" content="SMT divergence explained for index futures traders: what it compares, how bullish and bearish versions look, and where it fails. Education only, not advice.">
<link rel="canonical" href="https://korvus.industries/p/what-is-smt-divergence">
<style>
:root{--bg:#0a0a0f;--panel:#12121a;--line:#24242f;--text:#e7e7ee;--muted:#9a9aab;--accent:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.65 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:var(--accent);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:760px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:700;letter-spacing:.02em}
.brand svg{width:36px;height:33px}
.brand span{font-size:18px}
main{padding:36px 0 24px}
h1{font-size:32px;line-height:1.2;margin:0 0 14px}
h2{font-size:22px;margin:34px 0 10px;color:var(--text)}
p{margin:0 0 14px;color:var(--text)}
.lede{font-size:18px;color:var(--muted)}
ul{margin:0 0 14px;padding-left:20px}
li{margin-bottom:6px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:5px 12px;font-size:13px;color:var(--muted)}
.chip b{color:var(--accent);font-weight:600}
figure{margin:26px 0;background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:16px}
figure svg{width:100%;height:auto;display:block}
figcaption{font-size:13px;color:var(--muted);margin-top:10px}
.tag{display:inline-block;font-size:11px;letter-spacing:.08em;text-transform:uppercase;color:var(--accent);border:1px solid var(--accent);border-radius:4px;padding:2px 6px;margin-right:6px}
.box{background:var(--panel);border-left:3px solid var(--accent);padding:14px 16px;border-radius:6px;margin:20px 0}
.cta{margin:30px 0 10px;padding:22px;background:var(--panel);border:1px solid var(--line);border-radius:10px}
.btn{display:inline-block;background:var(--accent);color:#0a0a0f;font-weight:700;padding:10px 18px;border-radius:6px}
.btn:hover{text-decoration:none;opacity:.9}
.disclaimer{font-size:13px;color:var(--muted);border-top:1px solid var(--line);margin-top:30px;padding-top:16px}
footer{border-top:1px solid var(--line);padding:20px 0 40px;font-size:14px;color:var(--muted)}
footer nav a{margin-right:14px}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="/">
<svg viewBox='0 0 36 33' fill='none' stroke='#ff2d8f' stroke-width='2.4' stroke-linejoin='round' stroke-linecap='round' aria-hidden="true"><path d='M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z'/><path d='M8 28 L28 28'/></svg>
<span>Korvus</span>
</a>
</div>
</header>

<main>
<div class="wrap">

<p class="chips">
<span class="chip"><b>Education</b> only</span>
<span class="chip">Index futures</span>
<span class="chip">Reading the chart</span>
</p>

<h1>What is SMT divergence?</h1>
<p class="lede">SMT stands for Smart Money Technique. It is a way of comparing two related index futures at the same moment in time, and noticing when they stop agreeing. Here is what it measures, what the two versions look like, and where it breaks down.</p>

<h2>The short definition</h2>
<p>SMT divergence happens when two correlated markets are moving together, then one of them makes a new swing high or swing low and the other one does not. The market that fails to confirm the move is the divergence.</p>
<p>Common pairs for index futures traders are ES (S&amp;P 500), NQ (Nasdaq 100), YM (Dow) and RTY (Russell 2000). ES and NQ are the pair most people start with, because they usually move in step.</p>

<h2>The two versions</h2>
<ul>
<li><strong>Bearish SMT:</strong> both markets push to a new high. One of them makes the high, the other stalls below its prior high. The one that stalled is showing weakness the other one is not.</li>
<li><strong>Bullish SMT:</strong> both markets push to a new low. One of them breaks the prior low, the other holds above its prior low. The one that held is showing strength the other one is not.</li>
</ul>

<h2>What it looks like on a chart</h2>
<p>The clearest way to see it is two lines drawn side by side, aligned on time. Watch the swing points, not every wiggle in between.</p>

<figure>
<svg viewBox="0 0 480 220" role="img" aria-label="Illustration of bearish SMT divergence between two index futures">
<line x1="20" y1="200" x2="460" y2="200" stroke="#24242f" stroke-width="1"/>
<line x1="20" y1="20" x2="20" y2="200" stroke="#24242f" stroke-width="1"/>
<polyline points="30,170 80,120 130,140 170,60 220,110 260,90 300,35 340,70 380,120" fill="none" stroke="#e7e7ee" stroke-width="2.2" stroke-linejoin="round"/>
<polyline points="30,175 80,125 130,145 170,70 220,115 260,100 300,80 340,95 380,130" fill="none" stroke="#ff2d8f" stroke-width="2.2" stroke-linejoin="round" stroke-dasharray="6 4"/>
<circle cx="170" cy="60" r="4" fill="#e7e7ee"/>
<circle cx="300" cy="35" r="4" fill="#e7e7ee"/>
<circle cx="170" cy="70" r="4" fill="#ff2d8f"/>
<circle cx="300" cy="80" r="4" fill="#ff2d8f"/>
<text x="312" y="34" font-size="12" fill="#e7e7ee">Market A: new high</text>
<text x="312" y="92" font-size="12" fill="#ff2d8f">Market B: fails to confirm</text>
<text x="28" y="212" font-size="11" fill="#9a9aab">Illustration. Not real market data.</text>
</svg>
<figcaption>Illustration. Solid line makes a higher swing high. Dashed line stalls below its earlier high. That gap is the divergence being described.</figcaption>
</figure>

<h2>Why traders look at it</h2>
<p>Index futures are correlated, so when one leads and the other lags, the lag is information. SMT is a way to put a label on that disagreement so you can review it consistently instead of relying on memory.</p>
<p>Many traders use it as context, not as a trigger. It is one observation among several: session levels, structure, volume, and the broader tape.</p>

<h2>Where it fails</h2>
<ul>
<li>Divergences show up often. Many of them lead nowhere.</li>
<li>Different pairs disagree with each other, and that is normal. A divergence on one pair can be absent on another.</li>
<li>Timeframe matters. A divergence on a one minute chart and a divergence on a daily chart are different events.</li>
<li>News and scheduled releases can move one market faster than the other for reasons unrelated to structure.</li>
<li>Defining the swing points is subjective. Two people can mark the same chart differently.</li>
</ul>

<div class="box">
<p><span class="tag">Honest note</span>SMT divergence is a description of a disagreement between two markets. It does not tell you direction, timing, or size. Treat it as a question to answer, not an answer.</p>
</div>

<h2>How Korvus helps you watch for it</h2>
<p>Korvus is a 24/7 market intelligence terminal for index futures traders. It tracks the news, the economic calendar, and the session context so you can review what the markets were doing while you were away. Operator includes the LodeStone TradingView indicator, which carries SMT divergence as one of its inputs, alongside session and level tools. You decide what to do with what you see.</p>

<div class="cta">
<p>Start on the free Observer tier and look at the terminal yourself. Upgrade only if the tools earn it.</p>
<p><a class="btn" href="/signup">Create a free account</a></p>
</div>

<h2>Questions people ask</h2>
<p><strong>Is SMT divergence a buy or sell signal?</strong><br>No. It is a comparison. What you do with it is your decision, and it should sit inside your own plan and risk rules.</p>
<p><strong>Do I need two monitors?</strong><br>Not necessarily. Many traders overlay two symbols on one chart. What matters is that the time axis is aligned.</p>
<p><strong>Does SMT always work?</strong><br>No. Anyone who says a pattern always works is selling something. Track how often your own reads hold up before you rely on them.</p>

<p class="disclaimer">Korvus and BlackCrownVxJ LLC provide market information and education. Nothing on this page is financial advice, a recommendation, or a promise of results. Index futures carry substantial risk of loss. Past chart behavior does not predict future moves. Illustrations are for teaching only and are not real market data.</p>

</div>
</main>

<footer>
<div class="wrap">
<nav>
<a href="/">Korvus</a>
<a href="/lodestone">LodeStone</a>
<a href="/signup">Sign up</a>
<a href="/legal">Legal</a>
</nav>
<p style="margin-top:12px">BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</footer>
</body>
</html>
