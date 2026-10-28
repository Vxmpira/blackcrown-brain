# Scribe: Write the complete html document for korvus industries p smt

Date: 2026-10-27
Task: Write the COMPLETE html document for korvus.industries/p/smt-divergence, SMT divergence for index futures explained, Korvus Operator as the tool that surfaces i
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence for Index Futures | Korvus</title>
<meta name="description" content="What SMT divergence means for ES, NQ, YM and RTY, why it can flag a weak move, and how Korvus Operator surfaces it. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e8e8ee;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6;font-size:17px}
a{color:#ff2d8f}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #222}
header .brand{font-weight:700;letter-spacing:.04em}
main{max-width:820px;margin:0 auto;padding:32px 24px 64px}
h1{font-size:2rem;line-height:1.2;margin-bottom:12px}
h2{font-size:1.35rem;margin:36px 0 12px;color:#fff}
p{margin-bottom:14px}
.kicker{color:#ff2d8f;text-transform:uppercase;font-size:.8rem;letter-spacing:.12em}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{border:1px solid #ff2d8f;color:#ff2d8f;padding:4px 10px;border-radius:999px;font-size:.85rem}
table{width:100%;border-collapse:collapse;margin:16px 0;font-size:.95rem}
th,td{text-align:left;padding:10px 8px;border-bottom:1px solid #26262c}
th{color:#ff2d8f;font-weight:600}
figure{background:#111116;border:1px solid #26262c;border-radius:10px;padding:18px;margin:24px 0}
figcaption{font-size:.85rem;color:#9a9aa6;margin-top:10px}
.tag{display:inline-block;background:#ff2d8f;color:#0a0a0c;font-size:.75rem;font-weight:700;padding:2px 8px;border-radius:4px;margin-bottom:8px}
.card{background:#111116;border:1px solid #26262c;border-radius:10px;padding:18px;margin:16px 0}
.cta{display:flex;flex-wrap:wrap;gap:12px;margin:24px 0}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600}
.btn-primary{background:#ff2d8f;color:#0a0a0c}
.btn-ghost{border:1px solid #ff2d8f;color:#ff2d8f}
.disclaimer{font-size:.85rem;color:#9a9aa6;border-top:1px solid #222;margin-top:40px;padding-top:16px}
footer{text-align:center;color:#6b6b76;font-size:.85rem;padding:24px}
</style>
</head>
<body>
<header>
<svg width="36" height="33" viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" aria-hidden="true">
<path d="M6 26 L8 12 L13 18 L18 6 L23 18 L28 12 L30 26 Z"/>
<line x1="6" y1="30" x2="30" y2="30"/>
</svg>
<span class="brand">Korvus</span>
</header>

<main>
<p class="kicker">Education</p>
<h1>SMT divergence for index futures, explained</h1>
<p>Index futures move together most of the time. ES, NQ, YM and RTY track large US stock indexes, so they often make highs and lows at about the same moment. When they stop agreeing, that gap can be worth a look. This page explains what that gap is, why traders watch it, and where Korvus Operator fits.</p>

<div class="chips">
<span class="chip">ES</span>
<span class="chip">NQ</span>
<span class="chip">YM</span>
<span class="chip">RTY</span>
<span class="chip">Smart Money Technique</span>
</div>

<h2>What SMT divergence is</h2>
<p>SMT stands for Smart Money Technique. It is a comparison method, not a secret. You take two or more correlated contracts and check whether each one confirms the other's structure.</p>
<p>The basic case is simple. One contract sets a new high. A correlated contract does not. The second contract "fails to confirm." That mismatch is the divergence.</p>
<p>The same logic works for lows. One contract sets a new low while another holds above its prior low. That is a divergence too.</p>
<p>A divergence is a description of what happened. It does not tell you what happens next.</p>

<h2>ES vs NQ vs YM vs RTY</h2>
<p>Each contract represents a different slice of the US equity market. That difference is what makes the comparison useful.</p>
<table>
<thead>
<tr><th>Contract</th><th>Tracks</th><th>What it tends to reflect</th></tr>
</thead>
<tbody>
<tr><td>ES</td><td>S&amp;P 500</td><td>Broad large cap market</td></tr>
<tr><td>NQ</td><td>Nasdaq 100</td><td>Large growth and technology heavy names</td></tr>
<tr><td>YM</td><td>Dow Jones Industrial Average</td><td>Thirty blue chip industrials and others</td></tr>
<tr><td>RTY</td><td>Russell 2000</td><td>Small cap companies, more domestic exposure</td></tr>
</tbody>
</table>
<p>ES and NQ are the most common pair. They usually move together, but NQ can run harder on tech strength. YM and RTY add context. If the broad market rallies and small caps refuse to follow, that is information. If only NQ makes a new high while ES and YM stall, that is also information.</p>

<figure>
<svg viewBox="0 0 520 220" width="100%" role="img" aria-label="Illustration: ES and NQ highs, NQ prints a higher high while ES fails to confirm">
<text x="10" y="18" fill="#ff2d8f" font-size="13" font-family="system-ui,sans-serif">ES</text>
<line x1="10" y1="100" x2="250" y2="100" stroke="#3a3a44" stroke-dasharray="4 4"/>
<polyline points="20,160 70,120 110,140 150,100 190,118 240,100" fill="none" stroke="#e8e8ee" stroke-width="2"/>
<text x="270" y="18" fill="#ff2d8f" font-size="13" font-family="system-ui,sans-serif">NQ</text>
<line x1="270" y1="70" x2="510" y2="70" stroke="#3a3a44" stroke-dasharray="4 4"/>
<polyline points="280,160 330,120 370,140 410,80 450,110 500,60" fill="none" stroke="#ff2d8f" stroke-width="2"/>
<circle cx="500" cy="60" r="4" fill="#ff2d8f"/>
<circle cx="240" cy="100" r="4" fill="#e8e8ee"/>
</svg>
<figcaption><strong>Illustration.</strong> Stylized example only, not real market data. The dashed lines mark prior highs. NQ sets a higher high while ES stops short of its prior high. That mismatch is the divergence.</figcaption>
</figure>

<h2>Why it can flag a weak move</h2>
<p>A move that only one contract makes is narrow. Narrow moves can lack breadth. If the wider group does not join, the push may be less supported.</p>
<p>Traders use divergence as one piece of context. It can help frame whether a level was confirmed across the group. It can also warn that a move needs more evidence before you trust it.</p>
<p>It does not work every time. Divergences can resolve with the lagging contract catching up. Sometimes the leader keeps going. Treat each one as a question to answer, not a result to bet on.</p>

<h2>How Korvus Operator surfaces it</h2>
<p>Korvus Operator is the paid tier of the Korvus market intelligence terminal. It runs 24/7 and watches index futures while you sleep, then puts the context in one place.</p>
<div class="card">
<span class="tag">Operator</span>
<p>The LodeStone TradingView indicator ships with Operator. Its inputs include an SMT divergence layer, so you can see the ES, NQ, YM and RTY comparison directly on your chart.</p>
<p>The terminal and Presidential Wire add the news side. Scored events show impact, direction and confidence, so you can check whether the wider tape is moving with the divergence or against it.</p>
</div>
<p>Observer, the free tier, lets you see the terminal before you decide. Operator adds the indicator and the full feed.</p>

<div class="cta">
<a class="btn btn-primary" href="https://korvus.industries/signup">Start with Korvus</a>
<a class="btn btn-ghost" href="https://korvus.industries/p/observer">Compare the free Observer tier</a>
</div>

<div class="disclaimer">
<p>Education only. Nothing on this page is financial advice, a trade recommendation or a promise of profit. Index futures carry substantial risk and are not suitable for everyone. Divergences are descriptions of price action, not signals to act. Past patterns do not guarantee future results. Illustration marks examples that are not real market data. Korvus and BlackCrown Intelligence are products of BlackCrownVxJ LLC.</p>
</div>
</main>

<footer>BlackCrownVxJ LLC. Korvus, a product of BlackCrown Intelligence. Your edge while the world sleeps.</footer>
</body>
</html>
