# Copy: Assemble the complete watcher html document and write it to

Date: 2026-10-30
Task: Assemble the complete Watcher html document and write it to your vault as one file.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watcher, the watcher never sleeps</title>
<meta name="description" content="Korvus watches index futures news and levels around the clock, scoring every headline while you sleep. Built by a working operator. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
:root{--bg:#07080c;--panel:#0d0f16;--line:rgba(255,255,255,.08);--ink:#e8ecf3;--muted:#9aa4b5;--accent:#7c5cff;--gold:#e0b04a;--green:#3ddc97;--red:#ff6b6b}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-2;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(900px 500px at 15% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(800px 500px at 95% 10%,rgba(224,176,74,.12),transparent 60%),radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.7) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{padding:22px 0;border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:.85rem;color:var(--ink);text-decoration:none}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-size:.92rem}
nav a:hover{color:var(--ink)}
main{padding:64px 0 40px}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.14em;font-size:.78rem;font-weight:700;margin:0 0 14px}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.12;margin:0 0 18px;letter-spacing:-.01em;max-width:820px}
h2{font-size:clamp(1.4rem,3vw,1.9rem);line-height:1.2;margin:0 0 14px}
h3{font-size:1.05rem;margin:0 0 8px}
.lede{font-size:clamp(1.02rem,2vw,1.18rem);color:var(--muted);max-width:640px;margin:0 0 28px}
.prose{max-width:640px;color:var(--muted)}
.prose p{margin:0 0 16px}
.cta{display:inline-flex;align-items:center;gap:10px;background:var(--accent);color:#fff;text-decoration:none;font-weight:600;padding:13px 22px;border-radius:10px;margin-right:12px;margin-top:6px}
.cta.ghost{background:transparent;border:1px solid var(--line);color:var(--ink)}
.cta-row{display:flex;flex-wrap:wrap;gap:4px}
section{margin-top:72px}
.feed{background:var(--panel);border:1px solid var(--line);border-radius:16px;overflow:hidden;box-shadow:0 30px 80px rgba(0,0,0,.45)}
.feed-head{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:14px 18px;border-bottom:1px solid var(--line);font-size:.85rem;color:var(--muted);flex-wrap:wrap}
.tag{display:inline-block;font-size:.72rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--gold);border:1px solid rgba(224,176,74,.4);border-radius:999px;padding:3px 10px}
.row{display:grid;grid-template-columns:82px 1fr auto;gap:14px;padding:14px 18px;border-bottom:1px solid var(--line);align-items:center}
.row:last-child{border-bottom:0}
.time{font-family:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;color:var(--muted);font-size:.85rem}
.item strong{display:block;font-size:.95rem;font-weight:600}
.item span{font-size:.84rem;color:var(--muted)}
.chip{font-size:.75rem;font-weight:700;padding:4px 10px;border-radius:999px;white-space:nowrap}
.up{color:var(--green);background:rgba(61,220,151,.1)}
.dn{color:var(--red);background:rgba(255,107,107,.1)}
.neu{color:var(--muted);background:rgba(154,164,181,.1)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{margin:0;color:var(--muted);font-size:.95rem}
.steps{counter-reset:s;display:grid;grid-template-columns:repeat(3,1fr);gap:16px;list-style:none;padding:0;margin:0}
.steps li{counter-increment:s;background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px;color:var(--muted);font-size:.95rem}
.steps li::before{content:counter(s,decimal-leading-zero);display:block;font-family:ui-monospace,Menlo,Consolas,monospace;color:var(--accent);font-weight:700;margin-bottom:8px}
.steps li b{color:var(--ink);display:block;margin-bottom:4px}
.figure{margin:0}
.figure figcaption{font-size:.8rem;color:var(--muted);margin-top:10px}
.disclaimer{font-size:.84rem;color:var(--muted);border-top:1px solid var(--line);margin-top:72px;padding:26px 0 8px}
footer{padding:28px 0 48px;color:var(--muted);font-size:.86rem;border-top:1px solid var(--line)}
footer a{color:var(--muted)}
@media (max-width:700px){
  .grid3,.steps{grid-template-columns:1fr}
  .row{grid-template-columns:1fr;gap:6px}
  .row .chip{justify-self:start}
  main{padding-top:44px}
  section{margin-top:56px}
  nav a{margin-left:0;margin-right:14px}
}
</style>
</head>
<body>
<header>
  <div class="wrap bar">
    <a class="brand" href="https://korvus.industries/">
      <svg viewBox="0 0 64 64" aria-hidden="true" focusable="false">
        <path d="M10 46 L14 24 L24 34 L32 16 L40 34 L50 24 L54 46 Z" fill="none" stroke="#e0b04a" stroke-width="3" stroke-linejoin="round"/>
        <path d="M14 52 H50" stroke="#7c5cff" stroke-width="3" stroke-linecap="round"/>
        <circle cx="32" cy="10" r="2.5" fill="#e0b04a"/>
      </svg>
      Korvus
    </a>
    <nav>
      <a href="https://korvus.industries/lodestone">LodeStone</a>
      <a href="https://korvus.industries/login">Log in</a>
      <a href="https://korvus.industries/signup">Sign up</a>
    </nav>
  </div>
</header>

<main>
  <div class="wrap">
    <p class="eyebrow">Korvus Watcher</p>
    <h1>The watcher never sleeps.</h1>
    <p class="lede">Index futures move while you are offline. Korvus reads the wire around the clock, scores every headline for impact, direction and confidence, and has the read waiting when you sit back down.</p>
    <div class="cta-row">
      <a class="cta" href="https://korvus.industries/signup">Start with the free Observer tier</a>
      <a class="cta ghost" href="https://korvus.industries/lodestone">See the chart toolkit</a>
    </div>

    <section>
      <h2>Overnight, while you were out</h2>
      <p class="prose">Here is what a single night looks like through the Watcher. Every item is scored the moment it lands, so the morning starts from a ranked list instead of a blank screen.</p>
      <figure class="figure" style="margin-top:24px">
        <div class="feed" role="img" aria-label="Illustration of a scored news feed">
          <div class="feed-head">
            <span>Presidential Wire, overnight</span>
            <span class="tag">Illustration</span>
          </div>
          <div class="row">
            <div class="time">02:14</div>
            <div class="item"><strong>Treasury auction draws firm demand</strong><span>Impact high. Confidence 74 percent.</span></div>
            <div class="chip up">Risk on</div>
          </div>
          <div class="row">
            <div class="time">03:41</div>
            <div class="item"><strong>Overseas factory output misses forecast</strong><span>Impact medium. Confidence 61 percent.</span></div>
            <div class="chip dn">Risk off</div>
          </div>
          <div class="row">
            <div class="time">05:02</div>
            <div class="item"><strong>Central bank speaker, no new guidance</strong><span>Impact low. Confidence 55 percent.</span></div>
            <div class="chip neu">Neutral</div>
          </div>
          <div class="row">
            <div class="time">06:30</div>
            <div class="item"><strong>Pre-market levels refreshed for the session</strong><span>Prior day and week levels updated.</span></div>
            <div class="chip neu">Levels</div>
          </div>
        </div>
        <figcaption>Illustration. Sample layout only, not a live market read or a recommendation.</figcaption>
      </figure>
    </section>

    <section>
      <h2>What the Watcher does</h2>
      <div class="grid3">
        <div class="card">
          <h3>Scores the wire</h3>
          <p>Each headline gets an impact rating, a direction and a confidence figure, written so you can judge the read yourself.</p>
        </div>
        <div class="card">
          <h3>Covers the session gaps</h3>
          <p>Overnight, pre-market and the quiet hours between sessions are watched too. Nothing is missed because the desk was closed.</p>
        </div>
        <div class="card">
          <h3>Written, not shouted</h3>
          <p>Every item carries a plain Korvus read. No countdowns, no promises, no guru theater. You decide what the information means.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>How it runs</h2>
      <ol class="steps">
        <li><b>Watch</b>Feeds are read continuously, including the hours you are asleep, flat or away from the screen.</li>
        <li><b>Score</b>Each item is rated for impact, direction and confidence the moment it lands.</li>
        <li><b>Brief</b>The ranked list is waiting when you return, with the levels and context you need to start.</li>
      </ol>
    </section>

    <section>
      <h2>Start watching</h2>
      <p class="prose">The Observer tier is free and open to anyone. Operator adds the full terminal, the LodeStone TradingView indicator and the Watcher feed in full. Annual pricing is listed first on the signup page.</p>
      <div class="cta-row" style="margin-top:20px">
        <a class="cta" href="https://korvus.industries/signup">Create your free account</a>
        <a class="cta ghost" href="https://korvus.industries/">Read the full overview</a>
      </div>
    </section>

    <p class="disclaimer">Korvus is market intelligence and education software. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Index futures carry substantial risk of loss. Figures marked Illustration are sample layouts. Past scoring is not a guide to future results.</p>
  </div>
</main>

<footer>
  <div class="wrap bar">
    <span>BlackCrownVxJ LLC. Your edge while the world sleeps.</span>
    <span><a href="https://korvus.industries/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></span>
  </div>
</footer>
</body>
</html>
