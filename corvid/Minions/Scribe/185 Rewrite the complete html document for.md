# Scribe: Rewrite the complete html document for korvus pages smt divergence

Date: 2026-10-28
Task: Rewrite the COMPLETE html document for korvus:pages/smt-divergence.html as a fresh note, doctype through closing html, with EXACTLY ONE head tag, one title, one
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence for Index Futures | Korvus</title>
<meta name="description">
<meta name="description" content="What SMT divergence is, how comparing ES, NQ and YM can expose it, the mistakes beginners make, and how Korvus surfaces it on your charts.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
:root{--bg:#07090d;--panel:#0d1118;--line:#1d2431;--text:#e6e9ef;--muted:#9aa3b2;--gold:#d4a84b;--teal:#3fb8a8;--red:#d46a6a}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.65}
a{color:var(--gold)}
.wrap{max-width:860px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
h1{font-size:2.1rem;line-height:1.2;margin:36px 0 12px}
h2{font-size:1.35rem;margin:40px 0 10px;color:var(--gold)}
p{margin:0 0 14px;color:var(--text)}
.lede{font-size:1.1rem;color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid var(--line);background:var(--panel);padding:6px 12px;border-radius:999px;font-size:.85rem;color:var(--muted)}
.chip b{color:var(--teal);font-weight:600}
figure{margin:26px 0;background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px}
figure svg{width:100%;height:auto;display:block}
figcaption{font-size:.82rem;color:var(--muted);margin-top:10px}
ul{padding-left:20px;margin:0 0 14px}
li{margin-bottom:8px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px;margin:18px 0}
.cta{display:inline-block;margin-top:8px;background:var(--gold);color:#07090d;text-decoration:none;font-weight:700;padding:12px 22px;border-radius:8px}
.disclaimer{font-size:.8rem;color:var(--muted);border-top:1px solid var(--line);margin-top:48px;padding-top:16px}
footer{padding:28px 0 40px;color:var(--muted);font-size:.85rem}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="https://korvus.industries/">
<svg viewBox="0 0 40 40" aria-hidden="true">
<path d="M6 30 L8 14 L15 22 L20 10 L25 22 L32 14 L34 30 Z" fill="none" stroke="#d4a84b" stroke-width="2" stroke-linejoin="round"/>
<rect x="6" y="32" width="28" height="3" fill="#d4a84b"/>
<circle cx="20" cy="7" r="2" fill="#3fb8a8"/>
</svg>
<span>KORVUS</span>
</a>
</div>
</header>

<main class="wrap">
<h1>SMT Divergence on Index Futures: What It Is and Why Comparison Matters</h1>
<p class="lede">Price makes a new high. A related market does not. That mismatch is the whole idea behind SMT divergence, and it is easy to misread if you only watch one chart.</p>

<div class="chips">
<span class="chip"><b>ES</b> S&amp;P 500 futures</span>
<span class="chip"><b>NQ</b> Nasdaq 100 futures</span>
<span class="chip"><b>YM</b> Dow futures</span>
<span class="chip"><b>RTY</b> Russell 2000 futures</span>
</div>

<h2>What SMT divergence is</h2>
<p>SMT stands for Smart Money Technique. It is a comparison tool, not a signal by itself. You take two or more index futures that usually move together, mark their swing highs or swing lows, and check whether they agree.</p>
<p>When one market sets a higher high and a correlated market fails to confirm it, the two have diverged. The divergence says the markets disagree about strength at that moment. It does not say what happens next.</p>

<h2>How cross index comparison reveals it</h2>
<p>A single chart shows you one story. Two charts side by side show whether the story is shared. ES and NQ are the most common pair because they track the same broad risk appetite, but their composition is different, so their swing points do not always line up.</p>
<p>The useful habit is to compare structure, not candles. Ask whether each market took out the prior swing, and whether the other did the same at the same time.</p>

<figure>
<svg viewBox="0 0 640 260" role="img" aria-label="Illustration: two index lines, one making a new high while the other fails to confirm">
<rect x="0" y="0" width="640" height="260" fill="#0d1118"/>
<line x1="30" y1="220" x2="620" y2="220" stroke="#1d2431" stroke-width="1"/>
<line x1="30" y1="60" x2="620" y2="60" stroke="#1d2431" stroke-width="1" stroke-dasharray="4 4"/>
<polyline points="40,170 120,120 180,150 260,80 330,130 420,70" fill="none" stroke="#3fb8a8" stroke-width="3" stroke-linejoin="round"/>
<polyline points="40,180 120,130 180,160 260,100 330,120 420,95" fill="none" stroke="#d46a6a" stroke-width="3" stroke-linejoin="round"/>
<circle cx="420" cy="70" r="5" fill="#3fb8a8"/>
<circle cx="420" cy="95" r="5" fill="#d46a6a"/>
<text x="440" y="66" fill="#3fb8a8" font-size="14" font-family="system-ui,sans-serif">Market A: new high</text>
<text x="440" y="100" fill="#d46a6a" font-size="14" font-family="system-ui,sans-serif">Market B: no confirmation</text>
<text x="30" y="245" fill="#9aa3b2" font-size="13" font-family="system-ui,sans-serif">Illustration. Not real market data.</text>
</svg>
<figcaption>Illustration: Market A extends its high while Market B stalls below its prior swing. This is the shape SMT comparison is built to flag.</figcaption>
</figure>

<h2>Beginner mistakes</h2>
<ul>
<li><strong>Treating every mismatch as a setup.</strong> Divergence is a observation to study, not an entry trigger. Most mismatches resolve without any dramatic move.</li>
<li><strong>Comparing the wrong timeframes.</strong> A divergence on a one minute chart and a divergence on a daily chart describe different things. Mixing them creates false confidence.</li>
<li><strong>Ignoring session and levels.</strong> A swing that forms during a thin overnight session carries less weight than one formed at a major session high or a prior day level.</li>
<li><strong>Skipping the second market.</strong> Looking at ES alone and calling it divergence is just reading a chart. The comparison is the point.</li>
<li><strong>Assuming the pair always agrees.</strong> Correlation shifts. A pair that tracked closely last month can drift apart for reasons unrelated to your analysis.</li>
<li><strong>Backfitting the story.</strong> Once you know a divergence happened, every chart looks like one. Log what you saw before the outcome is known.</li>
</ul>

<h2>How Korvus surfaces it</h2>
<p>Korvus runs a 24/7 market intelligence terminal for index futures traders. Its job is to keep the comparison in front of you while you are busy or asleep, so you are not checking three tabs by hand.</p>
<p>The LodeStone TradingView indicator, included with Korvus Operator and available standalone on TradingView, carries an SMT divergence layer as one of its feature set. It marks cross index mismatches on the chart next to the session and level tools, so the comparison sits in the same view as the context around it.</p>

<div class="chips">
<span class="chip">Cross index comparison</span>
<span class="chip">Session context</span>
<span class="chip">Prior day and week levels</span>
<span class="chip">Zero repainting</span>
</div>

<div class="card">
<p><strong>Start with the free account.</strong> A Korvus Observer account is free and shows you how the terminal reads the market before you decide whether the upgrade fits your process.</p>
<a class="cta" href="https://korvus.industries/signup">Create a free Korvus account</a>
</div>

<p class="disclaimer">Not financial advice. This page explains a charting concept and describes features of Korvus and LodeStone. It does not recommend any trade, instrument, or action. Futures trading carries substantial risk of loss and is not suitable for everyone. Past behavior of any market does not predict future results. Chart examples are illustrations, not real market data. Only trade with capital you can afford to lose and make your own decisions.</p>
</main>

<footer>
<div class="wrap">
<p>Korvus, a product of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
<p><a href="https://korvus.industries/legal">Legal</a></p>
</div>
</footer>
</body>
</html>
