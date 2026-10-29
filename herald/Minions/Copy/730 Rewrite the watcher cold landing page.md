# Copy: Rewrite the watcher cold landing page as one complete html

Date: 2026-10-29
Task: Rewrite the Watcher cold landing page as one complete html document, under 40 lines of CSS
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Index Watch: 24/7 Futures Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock, scores the news, and has a written read waiting when you wake. Start on the free Observer tier, no card required.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
:root{--bg:#07080c;--ink:#e9e9f0;--mute:#9a9db0;--acc:#ff2d8f;--line:#20232e}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{min-height:100vh;color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.5;background:radial-gradient(circle at 12% 0%,rgba(255,45,143,.16),transparent 38%),radial-gradient(circle at 92% 18%,rgba(110,90,255,.14),transparent 42%),repeating-linear-gradient(0deg,rgba(255,255,255,.035) 0 1px,transparent 1px 48px),repeating-linear-gradient(90deg,rgba(255,255,255,.035) 0 1px,transparent 1px 48px),var(--bg)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.72))}
a{color:inherit}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
header{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:22px 0}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;font-weight:700;letter-spacing:.08em}
.brand svg{width:36px;height:33px}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;margin:.4em 0 .3em;max-width:18ch}
h2{font-size:clamp(1.4rem,3vw,2rem);margin:0 0 .6em}
.eyebrow{color:var(--acc);text-transform:uppercase;letter-spacing:.14em;font-size:.78rem}
.lede{max-width:62ch;color:var(--mute);font-size:1.08rem;line-height:1.6}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600;margin:6px 8px 6px 0}
.primary{background:var(--acc);color:#0b0b10}
.ghost{border:1px solid var(--line);color:var(--ink)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:22px 0}
.chips span{border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:.85rem;color:var(--mute);background:rgba(255,255,255,.02)}
section{padding:40px 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(14,15,22,.82)}
.mock{border:1px dashed #3a3f55}
.tag{color:var(--acc);font-size:.75rem;text-transform:uppercase;letter-spacing:.12em}
.mockrow{display:flex;justify-content:space-between;gap:10px;font-size:.9rem;color:var(--mute);border-top:1px solid var(--line);padding:8px 0}
.mockrow b{color:var(--ink);font-weight:600}
p{margin:.5em 0}
.muted{color:var(--mute)}
footer{border-top:1px solid var(--line);padding:24px 0;color:var(--mute);font-size:.85rem}
@media(max-width:700px){.grid{grid-template-columns:1fr}.mockrow{flex-direction:column;gap:2px}header{flex-wrap:wrap}}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>KORVUS</span>
</a>
<a class="btn ghost" href="/signup">Start free</a>
</header>

<main>
<section style="padding-top:20px">
<div class="eyebrow">Index futures intelligence</div>
<h1>The market never sleeps. Korvus watches it for you.</h1>
<p class="lede">Korvus keeps a 24/7 watch on index futures, scores every headline that moves price, and has a written read waiting when you wake. Nothing to configure before the first session.</p>
<a class="btn primary" href="/signup">Start on Observer, no card</a>
<a class="btn ghost" href="#how">See how it watches</a>
<div class="chips">
<span>24/7 watch</span>
<span>Scored news</span>
<span>Written read on waking</span>
<span>Free Observer tier</span>
<span>No card required</span>
</div>
</section>

<section id="how">
<div class="grid">
<div class="card"><div class="tag">Step 1</div><h2>It watches, all session</h2><p class="muted">Korvus tracks the index futures wire around the clock, including the hours you are asleep and the hours the desk is closed.</p></div>
<div class="card"><div class="tag">Step 2</div><h2>Every item gets scored</h2><p class="muted">Each story carries an impact rating, a direction, and a confidence level, so you see what matters before you read a word.</p></div>
<div class="card"><div class="tag">Step 3</div><h2>A read is ready at waking</h2><p class="muted">Korvus writes the overnight picture in plain language, so your first minutes go to judgment, not hunting through feeds.</p></div>
</div>
</section>

<section>
<div class="tag">Illustration</div>
<h2>What a scored item looks like</h2>
<div class="card mock">
<div class="mockrow"><span>Headline</span><b>Illustrative: rate expectations shift ahead of data</b></div>
<div class="mockrow"><span>Impact</span><b>High</b></div>
<div class="mockrow"><span>Direction</span><b>Bearish pressure on index futures</b></div>
<div class="mockrow"><span>Confidence</span><b>Moderate</b></div>
<div class="mockrow"><span>Korvus read</span><b>Illustrative sample text, not a live feed</b></div>
</div>
<p class="muted" style="font-size:.85rem">Illustration only. Figures and headlines above are sample data, not a live feed or a forecast.</p>
</section>

<section>
<h2>Start free, upgrade when you want the chart</h2>
<p class="lede">The Observer tier is free with no card. Operator adds the LodeStone TradingView indicator and the full terminal. Current plans are listed on the home page.</p>
<a class="btn primary" href="/signup">Create free account</a>
<a class="btn ghost" href="/#pricing">Compare plans</a>
</section>
</main>

<footer>
<p>Korvus is market information and education, not financial advice. Trading index futures carries substantial risk of loss. Past reads and scores do not predict results.</p>
<p>BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</p>
</footer>
</div>
</body></html>
</body></html>
