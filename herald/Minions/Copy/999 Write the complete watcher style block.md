# Copy: Write the complete watcher style block as one full html

Date: 2026-10-30
Task: Write the complete Watcher style block as one full html document, closing tag verified
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher Never Sleeps | Korvus</title>
<meta name="description" content="Korvus watches index futures news and the economic calendar around the clock, scores every headline, and has the read ready when you wake up. Information only, not advice.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--ink:#e9e6f0;--mute:#9a95a8;--pink:#ff2d8f;--violet:#7a5cff;--line:rgba(255,255,255,.08);--card:rgba(16,14,26,.72)}
html,body{background:#07060c;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 45vw at 15% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(55vw 50vw at 90% 20%,rgba(122,92,255,.16),transparent 70%),radial-gradient(70vw 60vw at 50% 110%,rgba(255,45,143,.10),transparent 70%),#07060c}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:.85rem}
.brand small{display:block;color:var(--mute);font-weight:500;letter-spacing:.04em;text-transform:none;font-size:.78rem}
nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:.92rem}
nav a:hover{color:var(--ink)}
.hero{padding:72px 0 48px}
.eyebrow{display:inline-block;color:var(--pink);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;font-weight:700;margin-bottom:16px}
h1{font-size:clamp(2.1rem,5.4vw,3.6rem);line-height:1.1;letter-spacing:-.02em;max-width:18ch}
h1 span{background:linear-gradient(90deg,var(--pink),var(--violet));-webkit-background-clip:text;background-clip:text;color:transparent}
h2{font-size:clamp(1.5rem,3.4vw,2.1rem);line-height:1.2;margin-bottom:14px}
h3{font-size:1.1rem;margin-bottom:8px}
.lede{font-size:clamp(1.02rem,2vw,1.2rem);color:var(--mute);max-width:64ch;margin-top:20px}
.actions{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.btn{display:inline-block;padding:12px 20px;border-radius:10px;text-decoration:none;font-weight:600;font-size:.95rem}
.btn-main{background:var(--pink);color:#12040b}
.btn-ghost{border:1px solid var(--line);color:var(--ink);background:rgba(255,255,255,.02)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:26px}
.chip{font-size:.8rem;padding:6px 12px;border-radius:999px;border:1px solid var(--line);color:var(--mute);background:rgba(255,255,255,.03)}
section{padding:56px 0;border-top:1px solid var(--line)}
.prose{max-width:70ch;color:var(--mute)}
.prose p+p{margin-top:14px}
.prose strong{color:var(--ink);font-weight:600}
.panel{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:24px;margin-top:28px}
.panel-head{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;margin-bottom:14px}
.tag{font-size:.72rem;letter-spacing:.12em;text-transform:uppercase;color:var(--violet);border:1px solid rgba(122,92,255,.4);padding:4px 10px;border-radius:6px}
.figure svg{width:100%;height:auto;display:block}
.caption{font-size:.82rem;color:var(--mute);margin-top:12px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:28px}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--mute);font-size:.95rem}
.kv{display:grid;grid-template-columns:1fr auto;gap:10px 16px;font-size:.92rem;margin-top:6px}
.kv div:nth-child(odd){color:var(--mute)}
.kv div:nth-child(even){color:var(--ink);text-align:right;font-variant-numeric:tabular-nums}
.cta{background:linear-gradient(135deg,rgba(255,45,143,.12),rgba(122,92,255,.10));border:1px solid rgba(255,45,143,.25);border-radius:18px;padding:36px}
.cta p{color:var(--mute);max-width:60ch;margin-top:10px}
footer{padding:36px 0 56px;border-top:1px solid var(--line);color:var(--mute);font-size:.84rem}
footer a{color:var(--mute)}
footer p+p{margin-top:10px}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  nav{display:none}
  .hero{padding:48px 0 32px}
  .cta{padding:24px}
  .panel{padding:16px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
  <a class="brand" href="https://korvus.industries/">
    <svg viewBox="0 0 36 33" width="36" height="33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
    <span>Korvus<small>by BlackCrownVxJ</small></span>
  </a>
  <nav>
    <a href="https://korvus.industries/lodestone">LodeStone</a>
    <a href="https://korvus.industries/legal">Legal</a>
    <a href="https://korvus.industries/login">Log in</a>
  </nav>
</header>

<main>
<div class="hero">
  <span class="eyebrow">The overnight watch</span>
  <h1>The market moves at 3 a.m. <span>Korvus is already watching.</span></h1>
  <p class="lede">Korvus keeps a watch on index futures news and the USD economic calendar around the clock. Every headline gets scored for impact, direction, and confidence, with a written read attached. When you wake up, the overnight picture is waiting, already sorted.</p>
  <div class="actions">
    <a class="btn btn-main" href="https://korvus.industries/signup">Start on the free Observer tier</a>
    <a class="btn btn-ghost" href="https://korvus.industries/lodestone">See the LodeStone toolkit</a>
  </div>
  <div class="chips">
    <span class="chip">Scored headlines</span>
    <span class="chip">Daily USD agenda</span>
    <span class="chip">Live actuals</span>
    <span class="chip">Session timeline</span>
    <span class="chip">Runs without you</span>
  </div>
</div>

<section>
  <h2>One watcher. Every session.</h2>
  <div class="prose">
    <p><strong>Markets trade in shifts.</strong> Asia opens while the U.S. closes, London wakes before New York, and the news does not wait for your alarm. Most traders cover one session at most. Korvus is built to cover the handoffs.</p>
    <p>The watch runs as a standing system, not a person on shift. It reads the wire, checks the calendar, and logs what changed, so the record of the night is complete when you open the terminal.</p>
  </div>

  <div class="panel figure" role="img" aria-label="Illustration of 24 hour market coverage across three sessions">
    <div class="panel-head">
      <strong>Coverage across the session day</strong>
      <span class="tag">Illustration</span>
    </div>
    <svg viewBox="0 0 1000 200" fill="none" xmlns="http://www.w3.org/2000/svg">
      <line x1="40" y1="120" x2="960" y2="120" stroke="rgba(255,255,255,.18)" stroke-width="2"/>
      <rect x="40" y="96" width="260" height="48" rx="8" fill="rgba(122,92,255,.22)" stroke="rgba(122,92,255,.6)"/>
      <rect x="300" y="96" width="260" height="48" rx="8" fill="rgba(255,45,143,.16)" stroke="rgba(255,45,143,.55)"/>
      <rect x="560" y="96" width="260" height="48" rx="8" fill="rgba(122,92,255,.22)" stroke="rgba(122,92,255,.6)"/>
      <rect x="820" y="96" width="140" height="48" rx="8" fill="rgba(255,45,143,.16)" stroke="rgba(255,45,143,.55)"/>
      <text x="170" y="84" fill="#e9e6f0" font-size="15" text-anchor="middle">Asia open</text>
      <text x="430" y="84" fill="#e9e6f0" font-size="15" text-anchor="middle">London</text>
      <text x="690" y="84" fill="#e9e6f0" font-size="15" text-anchor="middle">New York</text>
      <text x="890" y="84" fill="#e9e6f0" font-size="15" text-anchor="middle">Close</text>
      <circle cx="300" cy="120" r="6" fill="#ff2d8f"/>
      <circle cx="820" cy="120" r="6" fill="#ff2d8f"/>
      <text x="300" y="160" fill="#9a95a8" font-size="13" text-anchor="middle">Handoff scored</text>
      <text x="820" y="160" fill="#9a95a8" font-size="13" text-anchor="middle">Calendar checkpoint</text>
      <text x="40" y="190" fill="#9a95a8" font-size="13">00:00</text>
      <text x="500" y="190" fill="#9a95a8" font-size="13" text-anchor="middle">12:00</text>
      <text x="960" y="190" fill="#9a95a8" font-size="13" text-anchor="end">24:00</text>
    </svg>
    <p class="caption">Illustration. Sample coverage shape only, not a live feed or a forecast of any session.</p>
  </div>
</section>

<section>
  <h2>What the watch does while you sleep</h2>
  <div class="grid">
    <div class="card">
      <h3>Scores every headline</h3>
      <p>Each item on the Presidential Wire carries an impact score, a direction, a confidence level, and a written Korvus read. The reasoning is shown, so you can check it instead of trusting it.</p>
    </div>
    <div class="card">
      <h3>Tracks the USD calendar</h3>
      <p>The daily USD economic agenda posts before the open, and live actuals are logged as they print. Nothing scheduled gets missed because the screen was off.</p>
    </div>
    <div class="card">
      <h3>Waits for your return</h3>
      <p>Overnight events are gathered into one clean record. You read the picture in minutes, then decide what your own plan says to do.</p>
    </div>
  </div>
</section>

<section>
  <h2>Built to be checked, not believed</h2>
  <div class="prose">
    <p>A watcher is only useful if you can audit it. Every score shows its inputs, and every read says what it is based on. If a call looks wrong to you, that is a fair reason to discount it.</p>
    <p>Korvus delivers market information and education. It does not tell you what to trade, and it does not promise results. Use it as one input in your own process.</p>
  </div>
  <div class="panel">
    <div class="panel-head">
      <strong>How a headline moves through the watch</strong>
      <span class="tag">Illustration</span>
    </div>
    <div class="kv">
      <div>1. Headline arrives</div><div>Logged with timestamp</div>
      <div>2. Impact scored</div><div>Low to high</div>
      <div>3. Direction stated</div><div>Stated, not implied</div>
      <div>4. Confidence attached</div><div>Shown with the read</div>
      <div>5. Posted for review</div><div>Eclipse-X and terminal</div>
    </div>
    <p class="caption">Illustration. Sample pipeline steps, not a record of any real headline.</p>
  </div>
</section>

<section>
  <div class="cta">
    <h2>Let the watch run tonight.</h2>
    <p>Start on the free Observer tier to see how the overnight record reads. Operator adds the full terminal and includes the LodeStone TradingView indicator. Annual billing is listed first with the savings shown.</p>
    <div class="actions">
      <a class="btn btn-main" href="https://korvus.industries/signup">Create a free account</a>
      <a class="btn btn-ghost" href="https://korvus.industries/upgrade">Compare Operator</a>
    </div>
  </div>
</section>
</main>

<footer>
  <p>Korvus is market intelligence and education for index futures traders. Nothing on this page is financial advice, a recommendation to buy or sell, or a promise of profit. Trading involves risk of loss.</p>
  <p>Korvus is a product of BlackCrownVxJ LLC. <a href="https://blackcrownvxj.com/">blackcrownvxj.com</a> &middot; <a href="https://korvus.industries/legal">Legal</a> &middot; BlackCrownVxJ.LLC@outlook.com</p>
</footer>
</div>
</body>
</html>
