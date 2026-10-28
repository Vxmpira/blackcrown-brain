# Scribe: Write the complete html document for korvus pages smt divergence

Date: 2026-10-28
Task: Write the COMPLETE html document for korvus:pages/smt-divergence.html from scratch as your report, doctype through closing html, nothing else in the note
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Across ES, NQ and YM | Korvus</title>
<meta name="description" content="How SMT divergence works across ES, NQ and YM index futures, how side by side index comparison exposes it, and where traders commonly misread it. Education only.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<meta property="og:type" content="article">
<meta property="og:title" content="SMT Divergence Across ES, NQ and YM">
<meta property="og:description" content="What SMT divergence is, how comparing ES, NQ and YM reveals it, and the common misreads. Education only, not financial advice.">
<meta property="og:url" content="https://korvus.industries/p/smt-divergence">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e8e8ee;font-family:Georgia,"Times New Roman",serif;line-height:1.65;font-size:18px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #22222a;background:#060608}
header svg{width:36px;height:33px;flex-shrink:0}
.brand{font-family:Arial,Helvetica,sans-serif;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:#f4f4f8;font-size:16px}
.brand span{color:#ff2d8f}
nav{margin-left:auto;font-family:Arial,Helvetica,sans-serif;font-size:14px}
nav a{margin-left:18px;color:#9a9aa8}
main{max-width:760px;margin:0 auto;padding:40px 24px 64px}
.kicker{font-family:Arial,Helvetica,sans-serif;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:#ff2d8f;margin-bottom:12px}
h1{font-family:Arial,Helvetica,sans-serif;font-size:34px;line-height:1.2;color:#ffffff;margin-bottom:18px}
h2{font-family:Arial,Helvetica,sans-serif;font-size:22px;color:#ffffff;margin:36px 0 12px}
p{margin-bottom:16px}
ul{margin:0 0 16px 22px}
li{margin-bottom:8px}
.lede{font-size:20px;color:#d4d4de}
.disclaimer{border-left:3px solid #ff2d8f;background:#121216;padding:14px 18px;font-size:15px;color:#b8b8c4;margin:24px 0}
.figure{background:#0f0f14;border:1px solid #22222a;padding:18px;margin:28px 0}
.figure svg{width:100%;height:auto;display:block}
.figure figcaption{font-family:Arial,Helvetica,sans-serif;font-size:13px;color:#8a8a98;margin-top:10px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:12px 0 20px}
.chip{font-family:Arial,Helvetica,sans-serif;font-size:13px;border:1px solid #3a3a46;padding:5px 11px;color:#cfcfda;border-radius:2px}
.chip.hot{border-color:#ff2d8f;color:#ff2d8f}
.misread{background:#121216;border:1px solid #22222a;padding:18px 20px;margin:14px 0}
.misread h3{font-family:Arial,Helvetica,sans-serif;font-size:16px;color:#ffffff;margin-bottom:6px}
.cta{margin-top:44px;border:1px solid #ff2d8f;padding:28px 24px;background:#0d0d11;text-align:center}
.cta h2{margin-top:0}
.btn{display:inline-block;margin-top:10px;font-family:Arial,Helvetica,sans-serif;font-weight:700;letter-spacing:.06em;text-transform:uppercase;background:#ff2d8f;color:#0a0a0c;padding:12px 22px;font-size:14px}
.btn:hover{text-decoration:none;background:#ff5aa5}
.sig{margin-top:40px;font-style:italic;color:#8a8a98;text-align:center;font-size:17px}
footer{border-top:1px solid #22222a;padding:22px 24px;font-family:Arial,Helvetica,sans-serif;font-size:13px;color:#7a7a88;text-align:center}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<div class="brand">Kor<span>vus</span></div>
<nav>
<a href="https://korvus.industries">Home</a>
<a href="https://korvus.industries/lodestone">LodeStone</a>
<a href="https://korvus.industries/signup">Sign up</a>
</nav>
</header>

<main>
<div class="kicker">Education · Index futures</div>
<h1>SMT Divergence Across ES, NQ and YM</h1>

<p class="lede">Three index futures move together most of the time. When they stop agreeing at a high, that disagreement is what traders call SMT divergence. This page explains what it is, how comparing contracts side by side exposes it, and where people get it wrong.</p>

<div class="disclaimer"><strong>Education only. Not financial advice.</strong> Nothing on this page is a recommendation to buy, sell, or hold any instrument. It describes a market concept so you can read charts with more context. Trading futures carries substantial risk of loss.</div>

<div class="chips">
<span class="chip hot">SMT divergence</span>
<span class="chip">ES</span>
<span class="chip">NQ</span>
<span class="chip">YM</span>
<span class="chip">Swing highs</span>
<span class="chip">Cross index comparison</span>
</div>

<h2>What SMT divergence is</h2>
<p>SMT stands for Smart Money Technique, a name traders use for comparing correlated instruments to see whether a move is being confirmed. The core idea is simple. Two indices that usually track each other both push to a new swing high. One of them makes a higher high. The other one stalls below its previous high. That mismatch is the divergence.</p>
<p>It is a comparison, not a prediction. The chart is showing you that the two markets disagree about the move. What that disagreement means depends on context, timeframe, and what else is happening.</p>

<h2>Why ES, NQ and YM are the usual trio</h2>
<p>Each contract tracks a different slice of the US equity market, which is why they are useful together.</p>
<ul>
<li><strong>ES</strong> follows the S&amp;P 500, broad large cap exposure. It is the common benchmark.</li>
<li><strong>NQ</strong> follows the Nasdaq 100, heavier in technology and growth names. It often moves faster than ES.</li>
<li><strong>YM</strong> follows the Dow Jones Industrial Average, a price weighted set of 30 large companies. Its character can differ from both.</li>
</ul>
<p>When all three broad markets are pushing into the same area, agreement is normal. A clean disagreement between them is worth noticing because it is less common.</p>

<h2>How side by side comparison reveals it</h2>
<p>A single chart cannot show divergence. You need the reference points from at least two instruments on the same timeframe and the same session window. Mark each swing high. Then check whether the second index confirmed the first.</p>

<figure class="figure">
<svg viewBox="0 0 600 230" role="img" aria-label="Illustration: ES makes a higher swing high while NQ fails to exceed its prior high">
<rect x="0" y="0" width="600" height="230" fill="#0f0f14"/>
<line x1="20" y1="200" x2="580" y2="200" stroke="#2a2a34" stroke-width="1"/>
<line x1="300" y1="20" x2="300" y2="200" stroke="#2a2a34" stroke-width="1" stroke-dasharray="4 4"/>
<polyline points="30,150 80,130 120,145 170,110 210,128 250,95 300,40 340,80 380,70 420,100 470,88 520,120 580,110" fill="none" stroke="#e8e8ee" stroke-width="2.4" stroke-linejoin="round"/>
<polyline points="30,160 80,140 120,155 170,118 210,136 250,104 300,68 340,96 380,88 420,112 470,104 520,130 580,122" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-dasharray="7 5" stroke-linejoin="round"/>
<circle cx="300" cy="40" r="4" fill="#e8e8ee"/>
<circle cx="300" cy="68" r="4" fill="#ff2d8f"/>
<text x="312" y="36" fill="#e8e8ee" font-family="Arial,Helvetica,sans-serif" font-size="13">ES new high</text>
<text x="312" y="88" fill="#ff2d8f" font-family="Arial,Helvetica,sans-serif" font-size="13">NQ fails to confirm</text>
<text x="30" y="24" fill="#8a8a98" font-family="Arial,Helvetica,sans-serif" font-size="13">Solid: ES   Dashed: NQ</text>
<text x="470" y="222" fill="#8a8a98" font-family="Arial,Helvetica,sans-serif" font-size="12">Illustration</text>
</svg>
<figcaption>Illustration. Not real market data. Two indices reach a swing high at the same moment. One prints a higher high while the other stalls below its prior peak.</figcaption>
</figure>

<p>Read the comparison in this order. First confirm both charts show the same timeframe and session. Second locate the swing high on each. Third note whether the second index made a matching high. If it did not, you have a divergence to study, not a conclusion to act on.</p>

<h2>Where traders misread it</h2>
<div class="misread">
<h3>Treating every divergence as meaningful</h3>
<p>Small disagreements happen constantly, especially between NQ and ES, because NQ runs hotter. Most are noise. A divergence means more when it occurs at a clearly defined level and the timeframe is one you already study.</p>
</div>
<div class="misread">
<h3>Mixing expiries and roll dates</h3>
<p>Front month contracts can roll on different dates and carry different spreads. Comparing a rolled contract against one that has not rolled can create a fake divergence. Check that you are comparing the same contract cycle.</p>
</div>
<div class="misread">
<h3>Ignoring the session</h3>
<p>Overnight and thin liquidity can print highs on one index that the other never tests. Comparing across mismatched session windows produces confusing results. Align the sessions before you read anything into the gap.</p>
</div>
<div class="misread">
<h3>Assuming one index must lead</h3>
<p>Sector news can lift NQ alone for a day. YM can react to specific component earnings. A divergence caused by news is a different question from a divergence caused by structure. Check what moved first.</p>
</div>
<div class="misread">
<h3>Confusing a sweep with a failure</h3>
<p>A brief poke above a high that closes back inside is a liquidity event, not necessarily a failed move. Judging divergence on a single wick without reading the close and the next few bars is a common error.</p>
<p>In each case the fix is the same. Slow down, align the data, and treat the divergence as one input among several.</p>
</div>

<h2>Checklist for reading cross index SMT</h2>
<ul>
<li>Same timeframe and session on every instrument you compare.</li>
<li>Same contract cycle, rolls checked.</li>
<li>Swing highs marked on each index before you compare.</li>
<li>News and sector moves considered before structure.</li>
<li>Close and follow through read, not only the wick.</li>
<li>Written notes on what you observed, not what you expect next.</li>
</ul>

<h2>Keep the comparison live</h2>
<p>Doing this by hand across three indices, several timeframes, and multiple sessions takes attention you may not have while the market moves. Korvus tracks cross index SMT live, so you can see where ES, NQ and YM agree and where they split without rebuilding the comparison every time.</p>
<p>The Observer tier is free. Create an account to see the terminal and decide whether the workflow fits how you read the market.</p>

<div class="cta">
<h2>Korvus tracks cross index SMT live</h2>
<p>Free Observer account. No card needed to start. Education and market intelligence, not financial advice.</p>
<a class="btn" href="https://korvus.industries">Open Korvus</a>
</div>

<p class="sig">A crown is not handed down, it is built.</p>
</main>

<footer>
BlackCrownVxJ LLC · Korvus · Education only, not financial advice · Trading futures involves substantial risk of loss.
</footer>
</body>
</html>
