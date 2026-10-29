# Copy: Rewrite watcher landing as one complete html document under 150

Date: 2026-10-29
Task: Rewrite watcher landing as one complete html document, under 150 lines
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | Korvus Market Intelligence</title>
<meta name="description" content="Korvus Index Watch runs overnight while you sleep, scoring market news for index futures traders. Market information and education, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0d1017;--line:#1c2230;--text:#e6e9f0;--muted:#9aa3b5;--accent:#c9a54a;--cool:#4f7cff}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
.bg{position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(900px 500px at 15% -10%,rgba(201,165,74,.16),transparent 60%),
radial-gradient(800px 480px at 95% 10%,rgba(79,124,255,.13),transparent 60%),
linear-gradient(transparent 55px,rgba(255,255,255,.035) 56px),
linear-gradient(90deg,transparent 55px,rgba(255,255,255,.035) 56px),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.75) 100%);
background-size:auto,auto,56px 56px,56px 56px,auto}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header.wrap{display:flex;justify-content:space-between;align-items:center;padding:22px 20px}
.brand{display:flex;align-items:center;gap:10px;color:var(--text);text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:30px;height:30px}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;background:var(--accent);color:#100d05;font-weight:700;text-decoration:none}
.btn.sm{padding:9px 14px;font-size:.92rem}
.btn.ghost{background:transparent;color:var(--text);border:1px solid var(--line)}
.hero{padding:clamp(40px,8vw,90px) 0 30px}
.kicker{color:var(--accent);text-transform:uppercase;letter-spacing:.14em;font-size:.8rem;font-weight:700}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.1;margin:14px 0 18px;max-width:18ch}
h2{font-size:clamp(1.4rem,3vw,2rem);margin-bottom:12px}
h3{font-size:1.1rem;margin-bottom:8px}
.lede{color:var(--muted);font-size:clamp(1rem,2vw,1.15rem);max-width:60ch}
.cta{margin-top:26px;display:flex;flex-wrap:wrap;gap:12px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:22px}
.chip{border:1px solid var(--line);background:var(--panel);padding:6px 12px;border-radius:999px;font-size:.85rem;color:var(--muted)}
.figure{margin:30px 0;background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:18px}
.fig-head{display:flex;justify-content:space-between;align-items:center;color:var(--muted);font-size:.85rem;margin-bottom:10px;flex-wrap:wrap;gap:8px}
.tag{background:#1a1f2b;border:1px solid var(--line);padding:3px 9px;border-radius:6px;color:var(--accent);font-weight:700;font-size:.75rem;text-transform:uppercase;letter-spacing:.08em}
.figure svg{width:100%;height:auto;display:block}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:30px 0}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--muted);font-size:.97rem}
.prose{max-width:68ch;margin:40px 0}
.prose p{color:var(--muted);margin-bottom:14px}
.prose strong{color:var(--text)}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin:30px 0}
.plan{border:1px solid var(--line);background:var(--panel);border-radius:14px;padding:24px}
.plan.hot{border-color:var(--accent)}
.plan ul{list-style:none;margin:14px 0;color:var(--muted)}
.plan li{padding:5px 0;border-bottom:1px solid var(--line)}
.disclaimer{margin:40px 0 20px;padding:18px 20px;border:1px solid var(--line);border-radius:12px;color:var(--muted);font-size:.88rem;background:rgba(13,16,23,.7)}
footer{padding:24px 0 40px;color:var(--muted);font-size:.85rem;border-top:1px solid var(--line);margin-top:30px}
footer a{color:var(--muted)}
@media (max-width:700px){
.grid3,.grid2{grid-template-columns:1fr}
header.wrap{padding:16px}
.cta .btn{width:100%;text-align:center}
}
</style>
</head>
<body>
<div class="bg" aria-hidden="true"></div>

<header class="wrap">
<a class="brand" href="/">
<svg viewBox="0 0 32 32" aria-hidden="true"><path d="M4 24 L4 11 L10 17 L16 7 L22 17 L28 11 L28 24 Z" fill="#c9a54a"/><rect x="4" y="25" width="24" height="3" rx="1" fill="#c9a54a"/></svg>
<span>Korvus</span>
</a>
<a class="btn sm" href="/signup">Start free</a>
</header>

<main class="wrap">

<section class="hero">
<p class="kicker">Index Watch</p>
<h1>The watch runs while you sleep.</h1>
<p class="lede">Index futures move overnight, and most of the news lands before your alarm. Index Watch keeps scanning the wire through every session, scores what matters for index futures, and leaves a written read waiting when you wake up. You decide what to do with it.</p>
<div class="cta">
<a class="btn" href="/signup">Open your free account</a>
<a class="btn ghost" href="/">See current plans</a>
</div>
<div class="chips">
<span class="chip">Runs 24/7</span>
<span class="chip">Scored news</span>
<span class="chip">Written reads</span>
<span class="chip">No card to start</span>
</div>
</section>

<section class="figure" aria-label="Overnight coverage timeline">
<div class="fig-head"><span class="tag">Illustration</span><span>Overnight coverage, sample layout</span></div>
<svg viewBox="0 0 800 220" role="img" aria-label="Illustrative timeline showing continuous watch coverage across sessions">
<rect x="0" y="0" width="800" height="220" fill="#0a0d13"/>
<line x1="40" y1="170" x2="760" y2="170" stroke="#1c2230" stroke-width="2"/>
<rect x="40" y="40" width="200" height="120" fill="#4f7cff" opacity="0.12"/>
<rect x="240" y="40" width="200" height="120" fill="#c9a54a" opacity="0.12"/>
<rect x="440" y="40" width="320" height="120" fill="#4f7cff" opacity="0.10"/>
<text x="140" y="34" fill="#9aa3b5" font-size="14" text-anchor="middle">Asia session</text>
<text x="340" y="34" fill="#9aa3b5" font-size="14" text-anchor="middle">London session</text>
<text x="600" y="34" fill="#9aa3b5" font-size="14" text-anchor="middle">New York session</text>
<line x1="40" y1="60" x2="760" y2="60" stroke="#1c2230" stroke-dasharray="4 6"/>
<circle cx="90" cy="120" r="6" fill="#4f7cff"/>
<circle cx="170" cy="96" r="6" fill="#4f7cff"/>
<circle cx="290" cy="110" r="8" fill="#c9a54a"/>
<circle cx="380" cy="84" r="6" fill="#c9a54a"/>
<circle cx="480" cy="128" r="6" fill="#4f7cff"/>
<circle cx="600" cy="92" r="8" fill="#c9a54a"/>
<circle cx="700" cy="112" r="6" fill="#4f7cff"/>
<text x="40" y="200" fill="#9aa3b5" font-size="13">Scan runs continuously. Markers are sample events, not live data.</text>
</svg>
</section>

<section class="grid3">
<div class="card">
<h3>Overnight coverage</h3>
<p>The scan does not clock out. Headlines from every session get watched, including the hours you are not at the screen.</p>
</div>
<div class="card">
<h3>Scored for index futures</h3>
<p>Each item is weighed for relevance to index futures, so the noise sinks and the items that matter rise.</p>
</div>
<div class="card">
<h3>A written read</h3>
<p>Every flagged item comes with a plain written summary. Read it over coffee, then judge it yourself.</p>
</div>
</section>

<section class="prose">
<h2>Built for the trader who is not at the screen</h2>
<p>Most traders cannot watch the tape around the clock. Index Watch does that job so you do not have to stay awake for it. It is an information layer, not a decision maker. It tells you what arrived and why it was scored the way it was, then steps out of the way.</p>
<p><strong>What it does:</strong> runs through every session, scores incoming news for index futures relevance, and writes a short read on each flagged item.</p>
<p><strong>What it does not do:</strong> place trades, promise outcomes, or tell you what to buy or sell.</p>
</section>

<section class="grid2">
<div class="plan">
<h3>Observer</h3>
<p style="color:var(--muted)">Free, to see the terminal and the wire for yourself.</p>
<ul>
<li>Core market terminal access</li>
<li>Limited wire coverage</li>
<li>No card required</li>
</ul>
<a class="btn ghost" href="/signup">Start as Observer</a>
</div>
<div class="plan hot">
<h3>Operator</h3>
<p style="color:var(--muted)">The full watch, with the LodeStone TradingView indicator included.</p>
<ul>
<li>Index Watch overnight coverage</li>
<li>Full scored wire and written reads</li>
<li>LodeStone TradingView indicator included</li>
</ul>
<a class="btn" href="/signup">Go Operator</a>
</div>
</section>

<section class="disclaimer">
Korvus provides market information and education, not financial advice. Nothing on this page is a recommendation to buy, sell, or hold any instrument, and no profit is promised or implied. Trading index futures carries substantial risk of loss and is not suitable for everyone. Past scoring or coverage does not guarantee future results. Make your own decisions and consult a licensed professional when needed.
</section>

</main>

<footer class="wrap">
<p>BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com. <a href="/legal">Legal</a></p>
</footer>
</body>
</html>
