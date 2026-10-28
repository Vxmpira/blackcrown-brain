# Scribe: Rewrite the complete html document for korvus industries p smt

Date: 2026-10-27
Task: Rewrite the COMPLETE html document for korvus.industries/p/smt-divergence from scratch. The last version failed the executor because the head tag was duplicated
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence for ES, NQ, YM and RTY | Korvus</title>
<meta name="description">
<meta name="description" content="SMT divergence explained for index futures traders: what it is, why it can flag a weak move, and how Korvus Operator surfaces it across ES, NQ, YM and RTY. Education only.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e8e8ee;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6;font-size:17px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:820px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1e1e26;padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;color:#fff;font-weight:600;letter-spacing:.04em}
.brand svg{width:36px;height:33px}
main{padding:40px 0 20px}
h1{font-size:2rem;line-height:1.2;color:#fff;margin-bottom:14px}
h2{font-size:1.3rem;color:#fff;margin:36px 0 12px}
p{margin-bottom:14px}
ul{margin:0 0 14px 22px}
li{margin-bottom:6px}
.lede{font-size:1.1rem;color:#c9c9d4}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:999px;padding:4px 12px;font-size:.85rem}
.figure{background:#111117;border:1px solid #1e1e26;border-radius:10px;padding:18px;margin:22px 0}
.figure svg{width:100%;height:auto;display:block}
.cap{font-size:.85rem;color:#8a8a98;margin-top:10px}
.cta{background:#111117;border:1px solid #ff2d8f;border-radius:10px;padding:26px;margin:36px 0}
.btn{display:inline-block;background:#ff2d8f;color:#0a0a0c;font-weight:700;padding:12px 20px;border-radius:6px;margin-top:6px}
.btn:hover{text-decoration:none;opacity:.9}
.plan{margin:14px 0 6px;color:#fff}
.note{font-size:.9rem;color:#8a8a98}
footer{border-top:1px solid #1e1e26;padding:24px 0 40px;margin-top:40px;font-size:.85rem;color:#8a8a98}
</style>
</head>
<body>
<header>
<div class="wrap">
<div class="brand">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" aria-hidden="true">
<path d="M4 26 L8 10 L14 18 L18 6 L22 18 L28 10 L32 26 Z"/>
<line x1="4" y1="30" x2="32" y2="30"/>
</svg>
<span>KORVUS</span>
</div>
</div>
</header>

<main>
<div class="wrap">
<h1>SMT divergence, explained for index futures traders</h1>
<p class="lede">SMT divergence is a way to compare correlated index futures and check whether they agree. When they stop agreeing at a new extreme, that disagreement can be worth a look. This page explains what it is, why it can flag a weak move, and how Korvus Operator surfaces it across ES, NQ, YM and RTY.</p>

<div class="chips">
<span class="chip">ES</span>
<span class="chip">NQ</span>
<span class="chip">YM</span>
<span class="chip">RTY</span>
<span class="chip">Education only</span>
</div>

<h2>What SMT divergence is</h2>
<p>SMT stands for Smart Money Technique, a term from the ICT community. The idea is simple. Index futures that usually move together, such as E-mini S&amp;P 500 (ES) and E-mini Nasdaq 100 (NQ), often make highs and lows at similar times. A divergence happens when one market sets a new high or low and the other does not confirm it.</p>
<p>The comparison is the point. A single chart can make a new high on its own for many reasons. When correlated markets are measured against each other, the question changes from "did price go higher" to "did the related market go higher too."</p>

<h2>Why it can flag a weak move</h2>
<p>Consider a market that prints a higher high while its correlated partner stops short of the same level. The partner failing to confirm can suggest that the move is narrower than it looks. Traders who use this read often treat it as a prompt to check structure, not as a signal on its own.</p>
<p>The reverse case works too. A lower low in one market without a matching low in the other can point to selling that is not spread across the group.</p>

<div class="figure">
<svg viewBox="0 0 560 220" role="img" aria-label="Illustration of ES making a higher high while NQ fails to confirm">
<rect x="0" y="0" width="560" height="220" fill="#0a0a0c"/>
<line x1="30" y1="40" x2="530" y2="40" stroke="#1e1e26"/>
<line x1="30" y1="110" x2="530" y2="110" stroke="#1e1e26"/>
<line x1="30" y1="180" x2="530" y2="180" stroke="#1e1e26"/>
<polyline points="40,160 100,140 150,150 200,100 250,120 300,60 350,90 400,40 450,70 520,50" fill="none" stroke="#ff2d8f" stroke-width="2.5"/>
<polyline points="40,170 100,150 150,158 200,118 250,132 300,100 350,112 400,96 450,120 520,108" fill="none" stroke="#7a7a88" stroke-width="2.5" stroke-dasharray="6 5"/>
<circle cx="400" cy="40" r="4" fill="#ff2d8f"/>
<circle cx="400" cy="96" r="4" fill="#7a7a88"/>
<text x="412" y="36" fill="#e8e8ee" font-size="12" font-family="system-ui">ES new high</text>
<text x="412" y="112" fill="#c9c9d4" font-size="12" font-family="system-ui">NQ does not confirm</text>
<text x="30" y="210" fill="#8a8a98" font-size="11" font-family="system-ui">Illustration only. Not real market data.</text>
</svg>
<p class="cap">Illustration. Solid line: ES. Dashed line: NQ. The pink high is not matched by the partner.</p>
</div>

<h2>Across ES, NQ, YM and RTY</h2>
<p>The four main US index futures are related but not identical. ES tracks the broad large cap market. NQ leans toward large technology names. YM follows the Dow Jones Industrial Average, a price weighted set of 30 stocks. RTY tracks small caps, which can behave differently in risk on and risk off periods.</p>
<ul>
<li>ES and NQ are often compared first because both are broad and liquid.</li>
<li>YM can diverge from NQ during sector rotation, since its component mix is different.</li>
<li>RTY can diverge from ES when the market favors large or small companies.</li>
</ul>
<p>Correlation changes over time. A pair that agreed for weeks can drift apart. This is why the comparison needs a current read, not a memorized rule.</p>

<h2>How Korvus Operator surfaces it</h2>
<p>Korvus Operator is a 24/7 market intelligence terminal for index futures traders. Its SMT view lines up the four contracts on one screen, marks new highs and lows in each, and flags when one market is not confirmed by its partners. The terminal shows the comparison. It does not tell you what to trade.</p>
<div class="chips">
<span class="chip">Cross index view</span>
<span class="chip">Highs and lows marked</span>
<span class="chip">Confirmation flags</span>
<span class="chip">LodeStone included</span>
</div>
<p>LodeStone, the chart toolkit in the Korvus stack, includes an SMT divergence layer for TradingView. Operator includes LodeStone access.</p>

<div class="cta">
<p class="plan">Operator, annual: 79.99 a year</p>
<p class="note">Listed first because it is the better value. Includes the LodeStone TradingView indicator.</p>
<p style="margin-top:10px">Monthly option: 9.99 a month, also includes LodeStone.</p>
<p><a class="btn" href="https://korvus.industries/signup">Start with Korvus Operator</a></p>
</div>

<h2>Limits to keep in mind</h2>
<p>SMT divergence is one observation among many. Divergences can persist, can fail, and can appear in trends that keep going. Correlation shifts, data can differ between feeds, and no read is guaranteed. Use it as one input to your own process, with your own risk rules.</p>
</div>
</main>

<footer>
<div class="wrap">
<p>Education only. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of results. Trading index futures carries substantial risk of loss. Illustrations are illustrative and are not market data.</p>
<p style="margin-top:10px">BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</footer>
</body>
</html>
