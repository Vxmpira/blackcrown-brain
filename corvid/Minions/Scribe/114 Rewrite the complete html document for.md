# Scribe: Rewrite the complete html document for korvus industries p smt

Date: 2026-10-28
Task: Rewrite the COMPLETE html document for korvus.industries/p/smt-divergence. Your entire report is the document itself: doctype through closing html tag, nothing 
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Explained | Korvus</title>
<meta name="description" content="Learn what SMT divergence means on index futures, how traders compare related markets, and how Korvus watches for it. Education only, not advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
:root{--bg:#07070a;--panel:#0e0e14;--line:#22222c;--text:#e8e8ee;--muted:#9a9aa8;--accent:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.65 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:var(--accent)}
header{display:flex;align-items:center;gap:.6rem;padding:1rem 1.25rem;border-bottom:1px solid var(--line)}
header .name{font-weight:700;letter-spacing:.04em;color:var(--text);text-decoration:none}
main{max-width:760px;margin:0 auto;padding:2rem 1.25rem 3rem}
h1{font-size:2rem;line-height:1.2;margin:0 0 .75rem}
h2{font-size:1.25rem;margin:2rem 0 .5rem;color:var(--accent)}
p{margin:0 0 1rem}
.lede{color:var(--muted);font-size:1.05rem}
.chips{display:flex;flex-wrap:wrap;gap:.5rem;margin:1rem 0}
.chip{border:1px solid var(--accent);color:var(--accent);border-radius:999px;padding:.2rem .7rem;font-size:.85rem}
figure{margin:1.5rem 0;background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:1rem}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:.85rem;margin-top:.5rem}
.tag{display:inline-block;background:var(--accent);color:#07070a;font-weight:700;font-size:.75rem;padding:.1rem .45rem;border-radius:4px;margin-right:.4rem}
.cta{background:var(--panel);border:1px solid var(--accent);border-radius:10px;padding:1.25rem;margin:2rem 0}
.btn{display:inline-block;background:var(--accent);color:#07070a;font-weight:700;text-decoration:none;padding:.6rem 1.1rem;border-radius:6px;margin-top:.5rem}
.disclaimer{color:var(--muted);font-size:.85rem;border-top:1px solid var(--line);margin-top:2rem;padding-top:1rem}
footer{max-width:760px;margin:0 auto;padding:0 1.25rem 2rem;color:var(--muted);font-size:.85rem}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 32 24" width="32" height="24" aria-hidden="true"><path d="M2 20 L6 8 L12 14 L16 4 L20 14 L26 8 L30 20 Z" fill="#ff2d8f"/></svg>
<a class="name" href="https://korvus.industries/">KORVUS</a>
</header>

<main>
<h1>SMT Divergence, Explained</h1>
<p class="lede">SMT stands for Smart Money Technique. It is a way of comparing two or more related index futures markets to see whether they agree with each other. This page explains the idea. It does not tell you what to trade.</p>

<div class="chips">
<span class="chip">Index futures</span>
<span class="chip">Intermarket comparison</span>
<span class="chip">Education only</span>
</div>

<h2>What SMT divergence means</h2>
<p>Index futures tend to move together. The S&amp;P 500 (ES), Nasdaq 100 (NQ), Dow (YM) and Russell 2000 (RTY) usually make highs and lows around the same time. When one of them pushes to a new high or low and a related market does not confirm it, traders call that a divergence.</p>
<p>The idea is simple to state. If two markets are supposed to be tracking the same story, a move in one that the other refuses to copy is worth noticing. Noticing it is the whole point. What it means is a separate question, and the answer depends on context you still have to assess yourself.</p>

<h2>How traders compare the pairs</h2>
<p>A common setup compares a primary market against a correlated one. Traders mark the swing highs or lows on each chart and check whether both sets of swings line up. The sections below show the logic with a simplified example.</p>

<figure>
<svg viewBox="0 0 400 170" role="img" aria-label="Illustration: two correlated price lines, one making a higher high while the other fails to confirm">
<line x1="20" y1="150" x2="380" y2="150" stroke="#22222c" stroke-width="1"/>
<line x1="20" y1="20" x2="20" y2="150" stroke="#22222c" stroke-width="1"/>
<polyline points="20,120 60,90 100,100 140,50 180,60 220,28 260,70 300,55 340,90 380,95" fill="none" stroke="#ff2d8f" stroke-width="2.5"/>
<polyline points="20,118 60,92 100,98 140,72 180,80 220,62 260,74 300,66 340,96 380,100" fill="none" stroke="#9a9aa8" stroke-width="2" stroke-dasharray="5 4"/>
<circle cx="220" cy="28" r="4" fill="#ff2d8f"/>
<circle cx="220" cy="62" r="4" fill="#9a9aa8"/>
</svg>
<figcaption><span class="tag">Illustration</span>Solid line: primary market making a new swing high. Dashed line: related market failing to confirm at the same point. Shapes are simplified and not real market data.</figcaption>
</figure>

<h2>What it does not tell you</h2>
<p>A divergence is an observation, not a signal. Correlations shift. Two markets can split for reasons unrelated to each other, such as news that hits one contract more than another, or a session boundary that changes which bars are compared. A divergence can also appear and then resolve without any follow through. Nothing on this page predicts where price will go, and no comparison method guarantees a result.</p>

<h2>Where Korvus fits</h2>
<p>Korvus is a market intelligence terminal for index futures traders. It watches the markets around the clock and surfaces scored news and session context so you can review the conditions yourself. The LodeStone toolkit, which is part of the Korvus stack, includes an SMT divergence layer on TradingView alongside session levels and other chart tools. Operator subscribers get LodeStone included. The Observer tier is free.</p>

<div class="cta">
<p><strong>Watch the markets with Korvus.</strong> Create a free Observer account and look at the terminal on your own time.</p>
<a class="btn" href="https://korvus.industries/signup">Create a free Observer account</a>
</div>

<p class="disclaimer">Education only. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a prediction of future prices. Futures trading involves substantial risk of loss and is not suitable for everyone. Past chart patterns do not guarantee future results. Korvus and BlackCrownVxJ LLC are not registered investment advisers. Do your own research and consider your own circumstances.</p>
</main>

<footer>
<p>Korvus is a product of BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</p>
</footer>
</body>
</html>
