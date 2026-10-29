# Copy: Rewrite the watcher cold landing page as one complete html

Date: 2026-10-29
Task: Rewrite the Watcher cold landing page as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher: Market Surveillance While You Sleep</title>
<meta name="description" content="Korvus watches the index futures tape around the clock, scores the news as it lands, and keeps the session context in one terminal. Free to start, no card required.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<meta name="robots" content="index, follow">
<style>
:root{--bg:#07080c;--panel:#0d1017;--line:#1c2230;--ink:#e7eaf2;--mute:#8d96a8;--accent:#c9a54a;--cool:#4f8cff;--ok:#3ecf8e}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(201,165,74,.14),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(79,140,255,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 80%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 80%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
nav a{color:var(--mute);text-decoration:none;margin-left:20px;font-size:14px}
nav a:hover{color:var(--ink)}
.hero{display:grid;grid-template-columns:1.05fr .95fr;gap:40px;align-items:center;padding:64px 0 40px}
.eyebrow{color:var(--accent);text-transform:uppercase;letter-spacing:.14em;font-size:12px;font-weight:700;margin:0 0 14px}
h1{font-size:clamp(30px,4.6vw,52px);line-height:1.1;margin:0 0 18px;letter-spacing:-.01em}
.lede{font-size:clamp(16px,1.6vw,19px);color:#c5cbd8;max-width:36em;margin:0 0 26px}
.cta{display:flex;flex-wrap:wrap;gap:12px;align-items:center}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:700;text-decoration:none;font-size:15px}
.btn-main{background:var(--accent);color:#14110a}
.btn-ghost{border:1px solid var(--line);color:var(--ink)}
.note{color:var(--mute);font-size:13px;margin-top:14px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:26px 0 0;padding:0;list-style:none}
.chips li{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:6px 12px;font-size:13px;color:#c5cbd8}
.figure{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:18px;box-shadow:0 20px 60px rgba(0,0,0,.45)}
.figure-head{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--mute);margin-bottom:12px}
.tag{color:var(--ok);font-weight:700}
.figure svg{width:100%;height:auto;display:block}
.caption{font-size:12px;color:var(--mute);margin-top:10px}
section{padding:40px 0;border-top:1px solid var(--line)}
h2{font-size:clamp(22px,2.8vw,30px);margin:0 0 14px;letter-spacing:-.005em}
.prose{max-width:66ch;color:#c5cbd8}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:22px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.card h3{margin:0 0 8px;font-size:17px}
.card p{margin:0;color:#b4bbca;font-size:15px}
.num{display:inline-block;color:var(--accent);font-weight:700;font-size:13px;margin-bottom:8px}
.table{width:100%;border-collapse:collapse;margin-top:18px;font-size:15px;background:var(--panel);border:1px solid var(--line);border-radius:12px;overflow:hidden}
.table th,.table td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line)}
.table th{color:var(--mute);font-weight:600;font-size:13px;text-transform:uppercase;letter-spacing:.08em}
.table tr:last-child td{border-bottom:0}
.final{text-align:left;padding:48px 0;border-top:1px solid var(--line)}
.disclaimer{font-size:13px;color:var(--mute);max-width:70ch;margin-top:26px}
footer{padding:28px 0 40px;border-top:1px solid var(--line);color:var(--mute);font-size:13px;display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}
footer a{color:var(--mute)}
@media (max-width:700px){
  .hero{grid-template-columns:1fr;padding-top:40px;gap:28px}
  .grid{grid-template-columns:1fr}
  nav a{margin-left:14px}
  .table th:nth-child(3),.table td:nth-child(3){display:none}
}
</style>
</head>
<body>
<div class="wrap">
<header>
  <a class="brand" href="/">
    <svg viewBox="0 0 40 40" aria-hidden="true" focusable="false">
      <path d="M6 30 L8 14 L14 22 L20 9 L26 22 L32 14 L34 30 Z" fill="#c9a54a" stroke="#c9a54a" stroke-width="1.5" stroke-linejoin="round"/>
      <rect x="6" y="31" width="28" height="3.5" rx="1" fill="#c9a54a"/>
      <circle cx="20" cy="22" r="2.2" fill="#07080c"/>
    </svg>
    <span>KORVUS</span>
  </a>
  <nav>
    <a href="/lodestone">LodeStone</a>
    <a href="/login">Log in</a>
  </nav>
</header>

<div class="hero">
  <div>
    <p class="eyebrow">The Watcher</p>
    <h1>The market never closes. Your watch shouldn't either.</h1>
    <p class="lede">Korvus keeps the index futures tape under constant watch. It scores the news as it lands, tracks the session context, and puts one clean read in front of you before the open, while you sleep.</p>
    <div class="cta">
      <a class="btn btn-main" href="/signup">Start free</a>
      <a class="btn btn-ghost" href="#how">See how it watches</a>
    </div>
    <p class="note">Free Observer tier. No card required.</p>
    <ul class="chips">
      <li>24/7 coverage</li>
      <li>Scored news</li>
      <li>Session context</li>
      <li>No repainting charts</li>
    </ul>
  </div>

  <figure class="figure" aria-label="Illustration of the Korvus watch feed">
    <div class="figure-head">
      <span>Watch feed</span>
      <span class="tag">Illustration</span>
    </div>
    <svg viewBox="0 0 400 220" role="img" aria-label="Illustrative chart with session bands and scored news markers">
      <g stroke="#1c2230" stroke-width="1">
        <line x1="0" y1="55" x2="400" y2="55"/>
        <line x1="0" y1="110" x2="400" y2="110"/>
        <line x1="0" y1="165" x2="400" y2="165"/>
      </g>
      <rect x="0" y="0" width="120" height="220" fill="#4f8cff" opacity="0.07"/>
      <rect x="120" y="0" width="140" height="220" fill="#c9a54a" opacity="0.07"/>
      <rect x="260" y="0" width="140" height="220" fill="#3ecf8e" opacity="0.06"/>
      <polyline fill="none" stroke="#e7eaf2" stroke-width="2" points="10,150 40,138 70,146 95,120 125,128 155,96 185,104 215,78 245,90 275,62 305,70 335,48 365,58 390,40"/>
      <circle cx="155" cy="96" r="5" fill="#3ecf8e"/>
      <circle cx="275" cy="62" r="5" fill="#c9a54a"/>
      <circle cx="335" cy="48" r="5" fill="#4f8cff"/>
      <g font-size="10" fill="#8d96a8" font-family="system-ui,sans-serif">
        <text x="12" y="18">Overnight</text>
        <text x="132" y="18">London</text>
        <text x="272" y="18">New York</text>
      </g>
    </svg>
    <p class="caption">Illustration only. Not a live chart and not a signal.</p>
  </figure>
</div>

<section id="how">
  <h2>What the watch does while you are away</h2>
  <p class="prose">Watching a market around the clock is a job for software, not a second screen you have to remember to check. Korvus runs the same checks at 3 a.m. as it does at the open, and it files what matters in one place.</p>
  <div class="grid">
    <article class="card">
      <span class="num">01</span>
      <h3>Scans the tape continuously</h3>
      <p>Index futures are watched through every session, including the quiet hours when most traders are offline.</p>
    </article>
    <article class="card">
      <span class="num">02</span>
      <h3>Scores each news event</h3>
      <p>Each headline is rated for likely impact, direction, and confidence, with a short written read you can scan in seconds.</p>
    </article>
    <article class="card">
      <span class="num">03</span>
      <h3>Keeps the session in view</h3>
      <p>Overnight, London, and New York context stays in one terminal, so you start the day knowing where things stand.</p>
    </article>
  </div>
</section>

<section>
  <h2>Start free, upgrade when the watch earns it</h2>
  <p class="prose">The Observer tier gives you the terminal and the core feed at no cost. Operator adds the full scored wire, the LodeStone TradingView indicator, and the complete session toolkit. Compare the tiers on the pricing section of the landing page before you decide.</p>
  <table class="table">
    <thead>
      <tr><th>Feature</th><th>Observer</th><th>Operator</th></tr>
    </thead>
    <tbody>
      <tr><td>Core market feed</td><td>Included</td><td>Included</td></tr>
      <tr><td>Scored news wire</td><td>Limited</td><td>Full</td></tr>
      <tr><td>LodeStone TradingView indicator</td><td>Not included</td><td>Included</td></tr>
    </tbody>
  </table>
</section>

<section class="final">
  <h2>Put the watch on your side of the clock</h2>
  <p class="prose">Create a free account and see what the feed looks like before you spend a cent. Judge the output yourself.</p>
  <div class="cta" style="margin-top:20px">
    <a class="btn btn-main" href="/signup">Start free</a>
    <a class="btn btn-ghost" href="/lodestone">Explore LodeStone</a>
  </div>
  <p class="disclaimer">Korvus is market intelligence and education software. It is not financial advice, does not recommend trades, and does not promise profits. Index futures carry substantial risk of loss. Past readings and illustrations do not predict future results. Trade only with capital you can afford to lose.</p>
</section>
</div>

<footer class="wrap">
  <span>BlackCrownVxJ LLC. Korvus is a product of BlackCrownVxJ LLC.</span>
  <span><a href="/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></span>
</footer>
</body>
</html>
