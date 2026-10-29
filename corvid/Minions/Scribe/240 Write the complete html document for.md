# Scribe: Write the complete html document for a new page korvus

Date: 2026-10-28
Task: Write the COMPLETE html document for a new page, korvus:pages/liquidity-sweeps.html, serving at korvus.industries/p/liquidity-sweeps. Title under 60 chars, ONE 
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Liquidity Sweeps Explained for Index Futures</title>
<meta name="description" content="A beginner guide to liquidity sweeps for index futures traders. Resting liquidity, equal highs and lows, and how to review a sweep after the fact. Education only.">
<link rel="canonical" href="https://korvus.industries/p/liquidity-sweeps">
<style>
:root{--bg:#0a0a0c;--panel:#131317;--line:#26262e;--text:#e6e6ea;--muted:#9a9aa6;--gold:#d4af37;--pink:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.65;font-size:17px}
a{color:var(--gold)}
.wrap{max-width:760px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:22px 0}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand span{color:var(--gold)}
h1{font-size:2rem;line-height:1.2;margin:36px 0 12px;color:#fff}
h2{font-size:1.25rem;color:var(--gold);margin:40px 0 10px}
p{margin:0 0 16px}
.lede{color:var(--muted);font-size:1.05rem}
.tag{display:inline-block;font-size:.75rem;letter-spacing:.08em;text-transform:uppercase;color:var(--gold);border:1px solid var(--gold);padding:3px 8px;border-radius:3px;margin-bottom:10px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{background:var(--panel);border:1px solid var(--line);border-radius:999px;padding:5px 12px;font-size:.85rem;color:var(--muted)}
figure{margin:28px 0;background:var(--panel);border:1px solid var(--line);border-radius:6px;padding:18px}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:.85rem;margin-top:10px}
ol,ul{padding-left:22px;margin:0 0 16px}
li{margin-bottom:8px}
.note{border-left:3px solid var(--gold);background:var(--panel);padding:14px 16px;margin:24px 0;color:var(--muted);font-size:.95rem}
.cta{margin:40px 0;padding:22px;background:var(--panel);border:1px solid var(--line);border-radius:6px}
.links{display:grid;gap:10px;margin:18px 0}
.links a{display:block;background:var(--panel);border:1px solid var(--line);border-radius:6px;padding:12px 14px;text-decoration:none;color:var(--text)}
.links a:hover{border-color:var(--gold)}
footer{border-top:1px solid var(--line);margin-top:50px;padding:24px 0;color:var(--muted);font-size:.85rem}
.disclaimer{font-size:.85rem;color:var(--muted);margin-top:30px}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="/">
<svg width="36" height="33" viewBox="0 0 36 33" aria-hidden="true" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" stroke-linecap="round">
<path d="M4 27 L6 11 L13 19 L18 6 L23 19 L30 11 L32 27 Z"/>
<line x1="4" y1="31" x2="32" y2="31"/>
</svg>
<div>Kor<span>vus</span></div>
</a>
</div>
</header>

<main class="wrap">
<span class="tag">Beginner guide</span>
<h1>Liquidity Sweeps, Explained for Index Futures</h1>
<p class="lede">A sweep is a price move through a level where many orders are sitting. This guide covers what that means, why traders watch these levels, and how to review a sweep after it happens. No predictions here. Just the mechanics and a repeatable way to look at them.</p>

<div class="chips">
<span class="chip">Beginner</span>
<span class="chip">ICT framing</span>
<span class="chip">Index futures</span>
<span class="chip">Education only</span>
</div>

<h2>What liquidity means here</h2>
<p>In this context, liquidity is simply orders. A market needs buyers and sellers to trade. Stop orders, limit orders and pending entries tend to cluster at obvious places on a chart. Those clusters are what ICT-style traders call resting liquidity.</p>
<p>Resting liquidity is not a signal by itself. It is a place where orders are known to exist. The question is what price does when it reaches that place.</p>

<h2>Equal highs and lows as resting pools</h2>
<p>When price touches roughly the same high twice, or the same low twice, many traders place stops just beyond that level. Two or more touches create a visible shelf. The stops above equal highs and below equal lows form a pool.</p>
<p>Read more in <a href="/p/equal-highs-and-lows">equal highs and lows</a>, and how the pools form on the chart. For the broader idea, see <a href="/p/resting-liquidity">resting liquidity</a>.</p>

<figure>
<svg viewBox="0 0 560 230" role="img" aria-labelledby="sweepfig sweepcap">
<title id="sweepfig">Illustration of an equal high being swept and price closing back below it</title>
<rect x="0" y="0" width="560" height="230" fill="#0a0a0c"/>
<line x1="40" y1="70" x2="530" y2="70" stroke="#d4af37" stroke-width="1.5" stroke-dasharray="6 5"/>
<text x="46" y="62" fill="#d4af37" font-size="13" font-family="system-ui,sans-serif">Equal highs</text>
<text x="46" y="200" fill="#9a9aa6" font-size="13" font-family="system-ui,sans-serif">Illustration only, not market data</text>
<polyline points="60,150 120,118 180,132 240,92 300,112 340,70 372,56 396,92 430,128 500,140" fill="none" stroke="#e6e6ea" stroke-width="2.5" stroke-linejoin="round"/>
<circle cx="372" cy="56" r="5" fill="#ff2d8f"/>
<text x="382" y="48" fill="#ff2d8f" font-size="13" font-family="system-ui,sans-serif">Sweep wick</text>
<text x="420" y="118" fill="#9a9aa6" font-size="13" font-family="system-ui,sans-serif">Close back below</text>
</svg>
<figcaption id="sweepcap">Illustration. Price trades through the equal highs, then closes back below the level. The wick is the sweep. The close is what gets reviewed.</figcaption>
</figure>

<h2>What a sweep is</h2>
<p>A sweep happens when price trades through a level where resting orders are believed to sit, and takes them out. The wick pokes through. Often the close comes back inside the range.</p>
<p>A sweep is a description of what happened. It does not tell you what happens next. A level can be swept and the market can keep going. Treat every sweep as a fact to review, not a trigger to act on.</p>

<h2>How traders review a sweep after the fact</h2>
<p>Reviewing is where the learning happens. Use the same steps every time so your notes stay comparable.</p>
<ol>
<li>Mark the level. Note which highs or lows were equal, and how many touches formed them.</li>
<li>Note the time and session. Was it during the open, the midday lull, or the close?</li>
<li>Measure the wick. How far did price go beyond the level, and in what time?</li>
<li>Check the close. Did the candle close back through the level, or hold beyond it?</li>
<li>Record what happened over the next session. Write it down without grading it as a win or loss.</li>
<li>Repeat for ten or more examples before drawing any conclusion. One sweep proves nothing.</li>
</ol>

<div class="note">Common misread: treating every wick through a high as a sweep. A sweep needs a level that was visibly relevant before the move. Without that, it is just a wick.</div>

<h2>Keep the frame honest</h2>
<p>Sweeps are a way of describing structure. They are not a reliable prediction tool, and no one should trade them as one. Markets can sweep levels and keep trending, or sweep and reverse, or do neither. Your job in review is to observe, record and learn the pattern of your own reading.</p>

<div class="cta">
<p><strong>Want to practice reviewing structure?</strong> Korvus Observer is free, with no card required, and covers the market terminal layer. Create an account at <a href="https://korvus.industries">korvus.industries</a> when you are ready to look at the tools yourself.</p>
</div>

<div class="links">
<a href="/p/resting-liquidity">Resting liquidity, the foundation</a>
<a href="/p/equal-highs-and-lows">Equal highs and lows, where pools form</a>
</div>

<p class="disclaimer">Education only. Nothing on this page is financial advice, a trading recommendation, or a prediction of future price. Index futures carry substantial risk of loss. Examples are illustrations and are not market data. Past chart patterns do not guarantee future results.</p>
</main>

<footer>
<div class="wrap">
<p>Korvus is a product of BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</footer>
</body>
</html>
