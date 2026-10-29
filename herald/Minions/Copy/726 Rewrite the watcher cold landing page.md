# Copy: Rewrite the watcher cold landing page as one complete compact

Date: 2026-10-29
Task: Rewrite the Watcher cold landing page as one complete compact html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher That Never Sleeps | Korvus</title>
<meta name="description" content="Korvus watches index futures around the clock, scores breaking news, and keeps a written read ready when you wake. Free to start, no card required.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
:root{--bg:#07070b;--ink:#ecebf3;--mute:#9a98ab;--acc:#ff2d8f;--line:#2a2736;--card:#0e0d14}
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%),radial-gradient(900px 500px at 12% -8%,rgba(255,45,143,.2),transparent 60%),radial-gradient(800px 460px at 96% 12%,rgba(120,80,255,.14),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;opacity:.16;background-image:linear-gradient(var(--line) 1px,transparent 1px),linear-gradient(90deg,var(--line) 1px,transparent 1px);background-size:56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.bar{display:flex;justify-content:space-between;align-items:center;padding:18px 20px}
.brand{display:flex;align-items:center;gap:10px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:28px;height:26px}
.hero{padding:64px 20px 36px}
.eyebrow{color:var(--acc);text-transform:uppercase;letter-spacing:.14em;font-size:.78rem;font-weight:700}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;max-width:18ch;margin:14px 0 18px}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin-bottom:12px}
p{max-width:68ch}
.lede{color:var(--mute);font-size:1.1rem}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:24px}
.btn{background:var(--acc);color:#0b0508;padding:12px 22px;border-radius:8px;font-weight:700;text-decoration:none}
.ghost{border:1px solid var(--line);color:var(--ink);padding:12px 22px;border-radius:8px;text-decoration:none}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:26px}
.chips span{border:1px solid var(--line);background:rgba(255,255,255,.03);padding:6px 12px;border-radius:999px;font-size:.85rem;color:var(--mute)}
section.wrap{padding:36px 20px}
.panel{border:1px solid var(--line);background:rgba(14,13,20,.88);border-radius:14px;padding:22px}
.panel-head{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;border-bottom:1px solid var(--line);padding-bottom:12px;margin-bottom:16px}
.tag{font-size:.72rem;letter-spacing:.12em;text-transform:uppercase;color:var(--acc);border:1px solid var(--acc);padding:3px 8px;border-radius:6px}
.rows{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
.cell{border:1px solid var(--line);border-radius:10px;padding:14px;background:#0c0b12}
.cell b{display:block;font-size:.72rem;color:var(--mute);text-transform:uppercase;letter-spacing:.1em;font-weight:600;margin-bottom:6px}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(14,13,20,.6)}
.card p{color:var(--mute);font-size:.95rem}
.card h3{font-size:1.05rem;margin-bottom:8px}
.final{text-align:left}
footer{border-top:1px solid var(--line);padding:26px 20px;color:var(--mute);font-size:.85rem}
footer p{margin-bottom:8px}
@media (max-width:700px){.rows,.grid3{grid-template-columns:1fr}.hero{padding-top:44px}}
</style>
</head>
<body>
<header class="wrap bar">
<a class="brand" href="/"><svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>Korvus</a>
<a class="btn" href="/signup">Start free</a>
</header>

<main>
<section class="hero wrap">
<p class="eyebrow">Korvus Observer, free to start</p>
<h1>The market never closes. Your watch shouldn't either.</h1>
<p class="lede">Korvus keeps eyes on index futures around the clock, scores the news as it breaks, and has a written read waiting when you wake up. No card. No countdown. The watch runs while you sleep.</p>
<div class="cta">
<a class="btn" href="/signup">Start free</a>
<a class="ghost" href="#watch">See the overnight watch</a>
</div>
<div class="chips">
<span>24/7 coverage</span>
<span>Scored news wire</span>
<span>Session awareness</span>
<span>No card to start</span>
</div>
</section>

<section class="wrap" id="watch">
<figure class="panel">
<div class="panel-head">
<h2 style="margin:0;font-size:1.1rem">Overnight watch</h2>
<span class="tag">Illustration</span>
</div>
<div class="rows">
<div class="cell"><b>Session</b><span>Asia open, tape steady</span></div>
<div class="cell"><b>Wire scored</b><span>High impact, moderate confidence</span></div>
<div class="cell"><b>Lean</b><span>Mixed, awaiting London</span></div>
<div class="cell"><b>Levels logged</b><span>Prior day and week marked</span></div>
<div class="cell"><b>Events</b><span>Two releases ahead of the open</span></div>
<div class="cell"><b>Morning brief</b><span>Written read ready on wake</span></div>
</div>
</figure>
</section>

<section class="wrap">
<h2>One watcher. Every hour the market is open.</h2>
<p style="color:var(--mute)">Most of the moves that matter on index futures happen when you are not at the screen. Korvus does not replace your judgment. It removes the blind hours, so the context you need is already written down when you sit back down.</p>
<div class="grid3" style="margin-top:24px">
<div class="card"><h3>It never looks away</h3><p>Coverage runs through the overnight sessions, the handoffs between them, and the quiet stretches in between.</p></div>
<div class="card"><h3>News arrives scored</h3><p>Each headline is weighed for impact, direction, and confidence, then paired with a plain written read.</p></div>
<div class="card"><h3>You decide what it means</h3><p>Korvus shows the market as it is. Every call stays with you, made on your own plan and your own risk.</p></div>
</div>
</section>

<section class="wrap">
<h2>Start with the free tier.</h2>
<p style="color:var(--mute)">Observer is free to start with no card. Watch how the terminal reads a session, then decide whether it earns a place in your routine. Upgrades are always optional.</p>
<div class="cta">
<a class="btn" href="/signup">Start free</a>
<a class="ghost" href="/lodestone">Explore LodeStone</a>
</div>
</section>
</main>

<footer>
<p>Korvus is market intelligence and education, not financial advice. Trading index futures involves substantial risk of loss and is not suitable for everyone. Past behavior of any market or tool does not guarantee future results.</p>
<p>BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
</footer>
</body></html>
