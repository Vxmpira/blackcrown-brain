# Copy: Write watcher landing as one complete html document under 300

Date: 2026-10-29
Task: Write watcher landing as one complete html document under 300 lines
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher That Never Sleeps | Korvus</title>
<meta name="description">
<meta name="description" content="Korvus watches index futures around the clock. Scored news, session levels, and a written read waiting when you wake up.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--ink:#e9e6ef;--mute:#9a95a8;--pink:#ff2d8f;--line:rgba(255,255,255,.08);--card:#14111c}
html{background:#07060b}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;color:var(--ink);line-height:1.6;min-height:100vh;position:relative;background-color:#07060b;background-image:radial-gradient(900px 500px at 15% -5%,rgba(255,45,143,.14),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(120,80,255,.12),transparent 60%),linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.14em;text-transform:uppercase;color:var(--ink);text-decoration:none;font-size:14px}
.brand svg{width:36px;height:33px}
nav a{color:var(--mute);text-decoration:none;font-size:14px;margin-left:18px}
nav a:hover{color:var(--ink)}
.hero{padding:64px 0 40px;display:grid;grid-template-columns:1.1fr .9fr;gap:36px;align-items:center}
.eyebrow{color:var(--pink);font-size:12px;letter-spacing:.2em;text-transform:uppercase;font-weight:700;margin-bottom:14px}
h1{font-size:clamp(30px,5vw,52px);line-height:1.1;letter-spacing:-.02em;margin-bottom:18px}
h2{font-size:clamp(22px,3.2vw,32px);line-height:1.2;margin-bottom:12px}
h3{font-size:17px;margin-bottom:6px}
.lede{color:var(--mute);font-size:clamp(16px,2vw,18px);max-width:560px;margin-bottom:26px}
.cta{display:inline-block;background:var(--pink);color:#0a0609;font-weight:700;padding:14px 26px;border-radius:8px;text-decoration:none;box-shadow:0 0 30px rgba(255,45,143,.35)}
.cta.ghost{background:transparent;color:var(--ink);border:1px solid var(--line);box-shadow:none;margin-left:10px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:26px}
.chip{border:1px solid rgba(255,45,143,.35);color:var(--ink);background:rgba(255,45,143,.07);padding:6px 12px;border-radius:999px;font-size:13px}
.panel{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:20px;box-shadow:0 20px 60px rgba(0,0,0,.5)}
.panel-top{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--mute);margin-bottom:14px;letter-spacing:.06em;text-transform:uppercase}
.tag{color:var(--pink);border:1px solid rgba(255,45,143,.4);padding:2px 8px;border-radius:6px}
.row{display:grid;grid-template-columns:auto 1fr auto;gap:12px;align-items:center;padding:12px 0;border-top:1px solid var(--line);font-size:14px}
.row b{color:var(--ink)}
.dir-up{color:#5fe3a1}
.dir-dn{color:#ff6b8a}
.read{margin-top:14px;padding:12px;border-radius:10px;background:rgba(255,255,255,.03);font-size:13px;color:var(--mute)}
.read strong{color:var(--ink)}
.cap{font-size:11px;color:var(--mute);margin-top:10px;text-align:right}
section{padding:48px 0;border-top:1px solid var(--line)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:22px}
.card{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:20px}
.card p{color:var(--mute);font-size:15px}
.levels{display:grid;grid-template-columns:1fr 1fr;gap:36px;align-items:start}
.levels p{color:var(--mute);margin-bottom:12px}
.lvl{display:flex;justify-content:space-between;padding:10px 14px;border:1px solid var(--line);border-radius:8px;margin-bottom:8px;font-size:14px;background:var(--card)}
.lvl span:last-child{color:var(--pink);font-weight:600}
.steps{counter-reset:s;display:grid;gap:12px;margin-top:20px}
.steps li{list-style:none;padding:14px 16px 14px 56px;position:relative;background:var(--card);border:1px solid var(--line);border-radius:10px;color:var(--mute);font-size:15px}
.steps li::before{counter-increment:s;content:counter(s);position:absolute;left:16px;top:12px;width:28px;height:28px;border-radius:50%;background:rgba(255,45,143,.15);color:var(--pink);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:13px}
.final{text-align:center;padding:56px 0}
.final p{color:var(--mute);max-width:620px;margin:0 auto 26px}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--mute);font-size:12px}
footer p+p{margin-top:8px}
footer a{color:var(--mute)}
@media (max-width:700px){
.hero,.levels{grid-template-columns:1fr}
.grid3{grid-template-columns:1fr}
nav a{margin-left:12px}
header{flex-wrap:wrap}
.cta.ghost{margin-left:0;margin-top:10px;display:inline-block}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>Korvus</span>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
<a href="/signup">Start free</a>
</nav>
</header>

<div class="hero">
<div>
<div class="eyebrow">Index futures intelligence, 24/7</div>
<h1>The market never sleeps. Your watcher doesn't either.</h1>
<p class="lede">Korvus scans the wire around the clock, scores every headline for impact, direction and confidence, tracks your session levels, and leaves a written read waiting when you wake up.</p>
<a class="cta" href="/signup">Start with the free Observer tier</a>
<a class="cta ghost" href="/lodestone">See LodeStone</a>
<div class="chips">
<span class="chip">Presidential Wire</span>
<span class="chip">Session levels</span>
<span class="chip">Written overnight read</span>
<span class="chip">LodeStone included with Operator</span>
</div>
</div>

<div class="panel" aria-label="Illustration data panel">
<div class="panel-top"><span>Presidential Wire</span><span class="tag">Illustration</span></div>
<div class="row"><span class="dir-up">+</span><b>Headline scored overnight</b><span>High</span></div>
<div class="row"><span class="dir-dn">-</span><b>Macro release, revised lower</b><span>Medium</span></div>
<div class="row"><span class="dir-up">+</span><b>Central bank speaker, tone shift</b><span>Medium</span></div>
<div class="read"><strong>Korvus read:</strong> Impact high, direction up, confidence moderate. Prior session low is still holding. Watch the open for a retest before you assume follow through.</div>
<div class="cap">Illustration only. Not a live feed.</div>
</div>
</div>

<section>
<h2>Built for the hours you are not watching</h2>
<p class="lede">Index futures move while you sleep. Korvus does the reading so the morning starts with context, not a scroll.</p>
<div class="grid3">
<div class="card"><h3>Scored news, not noise</h3><p>Each item carries an impact rating, a direction, a confidence level, and a plain written read on what it may mean for the session.</p></div>
<div class="card"><h3>Session levels on the chart</h3><p>Prior day and week levels, the Asia and London ranges, and the levels that matter for the open, kept current as the session runs.</p></div>
<div class="card"><h3>A read when you wake up</h3><p>A written overnight summary covering what changed, what was scored, and what to watch first. Read it in two minutes with coffee.</p></div>
</div>
</section>

<section>
<div class="levels">
<div>
<h2>Your levels, held in one place</h2>
<p>Korvus tracks the reference points traders watch every session and flags when price approaches them, so you see the setup before you open the chart.</p>
<p>LodeStone brings the same session toolkit onto your TradingView chart, and it is included with Operator.</p>
</div>
<div>
<div class="lvl"><span>Prior day high</span><span>Tracked</span></div>
<div class="lvl"><span>Prior day low</span><span>Tracked</span></div>
<div class="lvl"><span>Session open</span><span>Tracked</span></div>
<div class="lvl"><span>Overnight range</span><span>Tracked</span></div>
<div class="lvl"><span>Prior week levels</span><span>Tracked</span></div>
</div>
</div>
</section>

<section>
<h2>How the watcher works</h2>
<ol class="steps">
<li>Korvus monitors the wire and the index futures session without a break.</li>
<li>Every headline is scored for impact, direction, and confidence, with a written read.</li>
<li>Your session levels update as price moves, and the overnight summary is written for you.</li>
<li>You open the terminal, check the read, and decide with the full picture in front of you.</li>
</ol>
</section>

<section class="final">
<h2>Let the watcher take the night shift</h2>
<p>Start on the free Observer tier to see the output for yourself. Move to Operator when you want the full terminal and LodeStone included.</p>
<a class="cta" href="/signup">Start with the free Observer tier</a>
</section>

<footer>
<p>Korvus is an information and education tool for index futures traders. It does not provide financial advice, trading signals, or recommendations to buy or sell any instrument. Trading futures involves substantial risk of loss and is not suitable for every trader. Past reads and scored items do not guarantee future results.</p>
<p>Business contact: BlackCrownVxJ.LLC@outlook.com. <a href="/legal">Legal</a></p>
</footer>
</div>
</body>
</html>
