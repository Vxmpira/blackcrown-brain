# Copy: Author the complete watcher page doctype through closing html tag

Date: 2026-10-29
Task: Author the complete watcher page, doctype through closing html tag, saved as one vault note
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watch: Market Intelligence While You Sleep</title>
<meta name="description" content="Korvus watches index futures 24/7 and scores market news while you sleep. Free Observer tier. Operator includes LodeStone. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#06070b;--panel:#0d0f16;--line:#1b1f2b;--text:#e7e9f0;--muted:#9aa1b4;--gold:#d4a84b;--cyan:#4fc3d9;--red:#e05a5a;--green:#4fd18b}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100%}
body{position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(79,195,217,.16),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(212,168,75,.12),transparent 70%),radial-gradient(60% 50% at 50% 100%,rgba(79,209,139,.07),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);box-shadow:inset 0 0 160px 40px rgba(0,0,0,.75)}
a{color:var(--cyan);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{width:min(1060px,100% - 40px);margin:0 auto}
header{padding:22px 0;border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);margin-left:20px;font-size:14px}
nav a:hover{color:var(--text)}
.hero{padding:clamp(56px,9vw,104px) 0 40px}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.16em;font-size:12px;font-weight:700}
h1{font-size:clamp(34px,6vw,60px);line-height:1.08;margin:14px 0 18px;letter-spacing:-.01em;max-width:18ch}
h2{font-size:clamp(24px,3.6vw,34px);line-height:1.15;margin-bottom:12px}
h3{font-size:18px;margin-bottom:8px}
.lead{font-size:clamp(17px,2vw,20px);color:var(--muted);max-width:60ch}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:700;font-size:15px;border:1px solid var(--line);color:var(--text);background:var(--panel)}
.btn.primary{background:linear-gradient(135deg,var(--gold),#b8862e);color:#15110a;border-color:transparent}
.btn:hover{text-decoration:none;filter:brightness(1.08)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:26px}
.chip{font-size:13px;color:var(--text);border:1px solid var(--line);background:rgba(13,15,22,.7);padding:6px 12px;border-radius:999px}
section{padding:40px 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--muted);font-size:15px}
.fig{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px;position:relative}
.fig-label{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:14px;gap:10px;flex-wrap:wrap}
.tag{color:var(--gold);border:1px solid rgba(212,168,75,.45);padding:2px 8px;border-radius:6px;font-size:11px}
.row{display:grid;grid-template-columns:86px 1fr 120px;gap:12px;align-items:center;padding:12px 0;border-top:1px solid var(--line);font-size:14px}
.row:first-of-type{border-top:0}
.t{color:var(--muted);font-variant-numeric:tabular-nums}
.bar-track{height:8px;background:#141826;border-radius:99px;overflow:hidden}
.bar-fill{height:100%;border-radius:99px}
.up{background:var(--green)}.dn{background:var(--red)}.neu{background:var(--cyan)}
.score{text-align:right;font-variant-numeric:tabular-nums;color:var(--text)}
.split{display:grid;grid-template-columns:1fr 1fr;gap:24px;align-items:center}
.split p{color:var(--muted);margin-top:10px}
ul.steps{list-style:none;margin-top:14px}
ul.steps li{padding:10px 0 10px 28px;position:relative;border-top:1px solid var(--line);color:var(--muted);font-size:15px}
ul.steps li::before{content:"";position:absolute;left:0;top:18px;width:10px;height:10px;border-radius:50%;background:var(--gold);box-shadow:0 0 12px rgba(212,168,75,.6)}
ul.steps li strong{color:var(--text)}
.note{font-size:13px;color:var(--muted);border-left:2px solid var(--gold);padding:8px 14px;margin-top:20px;background:rgba(13,15,22,.6)}
.final{text-align:center;padding:64px 0}
.final p{color:var(--muted);max-width:56ch;margin:12px auto 0}
.final .cta{justify-content:center}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--muted);font-size:13px}
footer .bar{justify-content:space-between}
footer a{color:var(--muted)}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  .split{grid-template-columns:1fr}
  nav a{margin-left:14px}
  .row{grid-template-columns:70px 1fr 64px}
  .wrap{width:min(1060px,100% - 28px)}
}
</style>
</head>
<body>
<header>
  <div class="wrap bar">
    <div class="brand">
      <svg viewBox="0 0 40 40" aria-hidden="true">
        <defs><linearGradient id="g" x1="0" x2="1" y1="0" y2="1"><stop offset="0" stop-color="#d4a84b"/><stop offset="1" stop-color="#8f6420"/></linearGradient></defs>
        <path d="M6 30 L4 12 L14 20 L20 8 L26 20 L36 12 L34 30 Z" fill="url(#g)"/>
        <rect x="6" y="32" width="28" height="3" rx="1.5" fill="#d4a84b"/>
      </svg>
      Korvus
    </div>
    <nav>
      <a href="/lodestone">LodeStone</a>
      <a href="/legal">Legal</a>
      <a href="/login">Log in</a>
    </nav>
  </div>
</header>

<main>
  <div class="hero">
    <div class="wrap">
      <div class="eyebrow">24/7 market intelligence for index futures</div>
      <h1>The market never closes. Korvus never stops watching.</h1>
      <p class="lead">While you sleep, Korvus monitors the news wire, scores each headline for impact, direction and confidence, and writes a plain read you can check in seconds. You wake up to a briefing, not a backlog.</p>
      <div class="cta">
        <a class="btn primary" href="/signup">Start with the free Observer tier</a>
        <a class="btn" href="/lodestone">See LodeStone</a>
      </div>
      <div class="chips">
        <span class="chip">Watches around the clock</span>
        <span class="chip">Scored news wire</span>
        <span class="chip">Written Korvus read</span>
        <span class="chip">Operator includes LodeStone</span>
      </div>
    </div>
  </div>

  <section>
    <div class="wrap">
      <div class="fig">
        <div class="fig-label">
          <span>Overnight wire, scored</span>
          <span class="tag">Illustration</span>
        </div>
        <div class="row">
          <span class="t">02:14</span>
          <div><div class="bar-track"><div class="bar-fill up" style="width:78%"></div></div></div>
          <span class="score">Impact 7.8</span>
        </div>
        <div class="row">
          <span class="t">03:40</span>
          <div><div class="bar-track"><div class="bar-fill dn" style="width:56%"></div></div></div>
          <span class="score">Impact 5.6</span>
        </div>
        <div class="row">
          <span class="t">04:05</span>
          <div><div class="bar-track"><div class="bar-fill neu" style="width:32%"></div></div></div>
          <span class="score">Impact 3.2</span>
        </div>
        <div class="row">
          <span class="t">05:31</span>
          <div><div class="bar-track"><div class="bar-fill up" style="width:64%"></div></div></div>
          <span class="score">Impact 6.4</span>
        </div>
        <p class="note">Illustration only. Layout shows how scored entries are presented, not live market data or a signal.</p>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <h2>Three things it does without you</h2>
      <div class="grid" style="margin-top:20px">
        <div class="card">
          <h3>Watches</h3>
          <p>Korvus reads the wire through the night and session by session, so the overnight move never arrives unannounced.</p>
        </div>
        <div class="card">
          <h3>Scores</h3>
          <p>Each item carries an impact figure, a direction and a confidence level, so you can sort noise from news at a glance.</p>
        </div>
        <div class="card">
          <h3>Explains</h3>
          <p>Every scored item gets a written Korvus read in plain language. You decide what it means for your own plan.</p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap split">
      <div>
        <h2>The sequence, start to finish</h2>
        <ul class="steps">
          <li><strong>Overnight:</strong> the wire is monitored continuously across the session gaps.</li>
          <li><strong>On arrival:</strong> each item is scored for impact, direction and confidence.</li>
          <li><strong>In the read:</strong> Korvus writes a short explanation you can verify against the source.</li>
          <li><strong>At the desk:</strong> you open the terminal with the night already organized.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Operator includes LodeStone</h3>
        <p>Operator adds the LodeStone TradingView indicator, a session level toolkit built on ICT concepts for index futures. Standalone access is sold separately, and it is included with Operator at no extra step.</p>
        <p style="margin-top:12px"><a href="/upgrade">Compare tiers</a></p>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <div class="final">
        <h2>Let it watch the night. You keep the decisions.</h2>
        <p>Start free with the Observer tier. Move to Operator when the overnight briefing earns a place in your routine.</p>
        <div class="cta">
          <a class="btn primary" href="/signup">Create a free account</a>
          <a class="btn" href="/">Back to Korvus</a>
        </div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap bar">
    <span>BlackCrownVxJ LLC. Korvus is market information and education, not financial advice. Trading index futures carries risk of loss.</span>
    <span><a href="/legal">Legal</a></span>
  </div>
</footer>
</body>
</html>
