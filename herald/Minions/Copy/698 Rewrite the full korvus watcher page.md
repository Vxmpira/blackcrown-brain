# Copy: Rewrite the full korvus watcher page with one meta description

Date: 2026-10-29
Task: Rewrite the full Korvus watcher page with one meta description and closing tag
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watcher: 24/7 Index Futures Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock, scoring news with impact, direction and confidence. Information only. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/korvus-watcher">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#06070b;--panel:#0d1019;--line:#1d2232;--text:#e7e9f0;--muted:#9aa3b8;--accent:#7c5cff;--gold:#d9b35c;--ok:#4fd1a5;--warn:#f0a35e}
html,body{background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 500px at 15% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(217,179,92,.12),transparent 60%),radial-gradient(700px 420px at 50% 110%,rgba(79,209,165,.08),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
a{color:var(--gold);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);background:rgba(6,7,11,.7);backdrop-filter:blur(6px)}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:16px 0;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
.brand span small{display:block;font-size:11px;font-weight:500;color:var(--muted);letter-spacing:.08em;text-transform:uppercase}
nav a{color:var(--muted);margin-left:18px;font-size:14px}
nav a:hover{color:var(--text);text-decoration:none}
.hero{padding:72px 0 40px}
.eyebrow{display:inline-block;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--gold);border:1px solid rgba(217,179,92,.35);padding:5px 10px;border-radius:999px}
h1{font-size:clamp(30px,5vw,50px);line-height:1.12;margin:18px 0 16px;letter-spacing:-.01em;max-width:820px}
h2{font-size:clamp(22px,3vw,30px);line-height:1.2;margin:0 0 14px}
h3{font-size:17px;margin:0 0 8px}
.lede{font-size:clamp(16px,2vw,18px);color:var(--muted);max-width:640px}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.btn{display:inline-block;padding:12px 20px;border-radius:10px;font-weight:600;font-size:15px;border:1px solid var(--line);color:var(--text)}
.btn.primary{background:linear-gradient(135deg,var(--accent),#5a3be0);border-color:transparent;color:#fff}
.btn:hover{text-decoration:none;filter:brightness(1.1)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:28px}
.chip{font-size:13px;color:var(--text);background:var(--panel);border:1px solid var(--line);padding:7px 12px;border-radius:8px}
section{padding:44px 0}
.prose{max-width:680px}
.prose p{color:var(--muted);margin-bottom:14px}
.prose p strong{color:var(--text)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--muted);font-size:15px}
.num{font-size:13px;color:var(--gold);font-weight:700;letter-spacing:.08em;margin-bottom:8px}
.figure{background:var(--panel);border:1px solid var(--line);border-radius:14px;overflow:hidden}
.figure-head{display:flex;justify-content:space-between;align-items:center;padding:14px 18px;border-bottom:1px solid var(--line);font-size:13px;color:var(--muted);gap:12px;flex-wrap:wrap}
.tag{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--warn);border:1px solid rgba(240,163,94,.4);padding:3px 8px;border-radius:6px}
.feed{width:100%;border-collapse:collapse;font-size:14px}
.feed th,.feed td{text-align:left;padding:12px 18px;border-bottom:1px solid var(--line);white-space:nowrap}
.feed th{color:var(--muted);font-weight:600;font-size:12px;text-transform:uppercase;letter-spacing:.08em}
.feed td.read{white-space:normal;color:var(--muted);min-width:200px}
.pill{display:inline-block;font-size:12px;font-weight:700;padding:3px 9px;border-radius:999px}
.up{color:var(--ok);background:rgba(79,209,165,.12)}
.dn{color:var(--warn);background:rgba(240,163,94,.12)}
.figure-foot{padding:12px 18px;font-size:12px;color:var(--muted);border-top:1px solid var(--line)}
.steps{counter-reset:s}
.step{display:grid;grid-template-columns:44px 1fr;gap:16px;padding:18px 0;border-bottom:1px solid var(--line)}
.step:last-child{border-bottom:0}
.step .n{width:40px;height:40px;border-radius:50%;display:flex;align-items:center;justify-content:center;background:var(--panel);border:1px solid var(--line);color:var(--gold);font-weight:700}
.step p{color:var(--muted);font-size:15px}
.note{border:1px solid var(--line);background:var(--panel);border-radius:14px;padding:22px;color:var(--muted);font-size:14px}
.note strong{color:var(--text)}
footer{border-top:1px solid var(--line);padding:28px 0 40px;color:var(--muted);font-size:13px}
footer .row{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap}
@media (max-width:700px){
.grid{grid-template-columns:1fr}
nav a{margin-left:12px}
.hero{padding:48px 0 28px}
.feed th,.feed td{padding:10px 12px}
.feed td.read{min-width:0;white-space:normal}
.bar{justify-content:center;text-align:center}
}
</style>
</head>
<body>
<header>
<div class="wrap bar">
<a class="brand" href="/">
<svg viewBox="0 0 48 48" aria-hidden="true" focusable="false">
<path d="M8 36 L8 16 L17 26 L24 12 L31 26 L40 16 L40 36 Z" fill="none" stroke="#d9b35c" stroke-width="2.5" stroke-linejoin="round"/>
<circle cx="24" cy="32" r="2.6" fill="#7c5cff"/>
</svg>
<span>KORVUS<small>BlackCrownVxJ</small></span>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/signup">Sign up</a>
<a href="/login">Log in</a>
</nav>
</div>
</header>

<main>
<div class="wrap hero">
<span class="eyebrow">Korvus Watcher</span>
<h1>The market never sleeps. Korvus watches it for you.</h1>
<p class="lede">Korvus is a 24/7 market intelligence terminal for index futures traders. It scores incoming news for impact, direction and confidence, then writes a plain read you can check against your own plan.</p>
<div class="cta">
<a class="btn primary" href="/signup">Start with the free Observer tier</a>
<a class="btn" href="/lodestone">See LodeStone</a>
</div>
<div class="chips">
<span class="chip">Scored news</span>
<span class="chip">Written Korvus read</span>
<span class="chip">Session levels</span>
<span class="chip">Live USD agenda</span>
</div>
</div>

<section>
<div class="wrap">
<h2>Eyes on the tape while you are off it</h2>
<div class="prose">
<p>Index futures move on headlines at hours nobody can cover manually. Korvus is the watcher that stays on the wire so you do not have to. It reads what lands, weighs it, and shows you where the pressure seems to be coming from.</p>
<p><strong>It is information, not instruction.</strong> Korvus does not tell you what to buy or sell. It gives you a faster, cleaner picture of the environment so your decisions rest on more than a scroll through headlines at 3 a.m.</p>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="figure">
<div class="figure-head">
<span>Watcher feed</span>
<span class="tag">Illustration</span>
</div>
<table class="feed">
<thead>
<tr><th>Time</th><th>Headline</th><th>Impact</th><th>Direction</th><th>Confidence</th><th>Korvus read</th></tr>
</thead>
<tbody>
<tr><td>02:14</td><td>Rates desk flags sticky services inflation</td><td>High</td><td><span class="pill dn">Bearish</span></td><td>Medium</td><td class="read">Tone firmer than the prior print. Watch the open for follow through.</td></tr>
<tr><td>04:37</td><td>Overnight liquidity thins across index pairs</td><td>Medium</td><td><span class="pill up">Supportive</span></td><td>High</td><td class="read">Depth is light. Wider ranges are likely into the London session.</td></tr>
<tr><td>07:02</td><td>Pre-market guidance lifts large caps</td><td>Medium</td><td><span class="pill up">Bullish</span></td><td>Low</td><td class="read">Single source, unconfirmed. Hold the read until volume confirms.</td></tr>
</tbody>
</table>
<div class="figure-foot">Illustration only. Sample layout, not a live feed or a recommendation.</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<h2>What the watcher does</h2>
<div class="grid">
<div class="card">
<div class="num">01</div>
<h3>Scores every headline</h3>
<p>Each item gets an impact rating, a directional tag and a confidence level so you can sort noise from signal fast.</p>
</div>
<div class="card">
<div class="num">02</div>
<h3>Writes the read</h3>
<p>A short Korvus read explains what the item may mean for the session, with the uncertainty stated plainly.</p>
</div>
<div class="card">
<div class="num">03</div>
<h3>Keeps the calendar honest</h3>
<p>The USD economic agenda posts with live actuals, so you see the scheduled risk before it arrives.</p>
</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<h2>How it works</h2>
<div class="prose steps">
<div class="step"><div class="n">1</div><p>Korvus monitors the wire around the clock, including the thin hours when headlines hit hardest.</p></div>
<div class="step"><div class="n">2</div><p>Each item is scored for impact, direction and confidence, and marked as confirmed or single source.</p></div>
<div class="step"><div class="n">3</div><p>You read the Korvus read, check it against your own plan and your own charts, and make your own call.</p></div>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="note">
<p><strong>Plans.</strong> Start on the free Observer tier with no card required. Operator adds the full terminal and includes the LodeStone TradingView indicator. Compare both on the <a href="/signup">signup page</a>.</p>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="note">
<p><strong>Information only, not financial advice.</strong> Korvus publishes market information and education. Nothing on this page is a recommendation to buy, sell or hold any instrument, and no outcome is promised. Futures trading carries substantial risk of loss. Trade only with capital you can afford to lose and decide for yourself.</p>
</div>
</div>
</section>
</main>

<footer>
<div class="wrap row">
<span>BlackCrownVxJ LLC. Korvus is a product of BlackCrownVxJ.</span>
<span><a href="/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></span>
</div>
</footer>
</body>
</html>
