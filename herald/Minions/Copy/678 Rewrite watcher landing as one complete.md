# Copy: Rewrite watcher landing as one complete html document under 240

Date: 2026-10-29
Task: Rewrite watcher landing as one complete html document, under 240 lines
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watch: Overnight Index Futures Intelligence</title>
<meta name="description">
<meta name="description" content="Korvus runs 24/7 market intelligence for index futures traders. Scored news, session levels and an overnight watch, with no advice and no promises.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#06070b;--panel:#0d1017;--line:#1c2230;--text:#e7ebf3;--muted:#8d97ab;--gold:#d9b35b;--cyan:#4fd1e0;--red:#ff6b6b;--green:#5fd39a}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100%}
body{position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(79,209,224,.16),transparent 70%),radial-gradient(50% 40% at 90% 20%,rgba(217,179,91,.12),transparent 70%),radial-gradient(60% 50% at 50% 100%,rgba(95,211,154,.08),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.vignette{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%)}
.wrap{width:min(1060px,92vw);margin:0 auto}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);text-decoration:none;font-weight:700;letter-spacing:.12em;text-transform:uppercase;font-size:13px}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);text-decoration:none;font-size:14px;margin-left:20px}
nav a:hover{color:var(--text)}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center;padding:64px 0 48px}
.eyebrow{color:var(--cyan);font-size:12px;letter-spacing:.16em;text-transform:uppercase;font-weight:700}
h1{font-size:clamp(30px,4.6vw,52px);line-height:1.1;margin:14px 0 18px;letter-spacing:-.01em}
h2{font-size:clamp(22px,3vw,30px);line-height:1.2;margin-bottom:12px}
.lede{color:var(--muted);font-size:17px;max-width:60ch}
.caption{margin-top:22px;padding:16px 18px;border-left:3px solid var(--gold);background:rgba(217,179,91,.06);font-size:17px;font-weight:600;max-width:60ch}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:700;text-decoration:none;font-size:15px}
.btn-primary{background:var(--gold);color:#120e04}
.btn-ghost{border:1px solid var(--line);color:var(--text)}
.panel{background:linear-gradient(180deg,rgba(255,255,255,.03),transparent),var(--panel);border:1px solid var(--line);border-radius:16px;padding:20px;box-shadow:0 30px 60px -30px rgba(0,0,0,.8)}
.panel-head{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--muted);letter-spacing:.08em;text-transform:uppercase;margin-bottom:14px}
.tag{font-size:11px;border:1px solid var(--gold);color:var(--gold);padding:2px 8px;border-radius:999px;letter-spacing:.1em}
.feed{list-style:none;display:grid;gap:10px}
.feed li{display:grid;grid-template-columns:62px 1fr auto;gap:10px;align-items:center;padding:10px 12px;border:1px solid var(--line);border-radius:10px;background:rgba(255,255,255,.015);font-size:14px}
.time{color:var(--muted);font-variant-numeric:tabular-nums;font-size:13px}
.chip{font-size:11px;padding:3px 8px;border-radius:999px;font-weight:700;letter-spacing:.06em}
.c-up{background:rgba(95,211,154,.14);color:var(--green)}
.c-dn{background:rgba(255,107,107,.14);color:var(--red)}
.c-neu{background:rgba(79,209,224,.14);color:var(--cyan)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.chips span{font-size:12px;color:var(--muted);border:1px solid var(--line);padding:5px 10px;border-radius:999px}
.section{padding:56px 0;border-top:1px solid var(--line)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:26px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--muted);font-size:15px}
.num{color:var(--gold);font-weight:700;font-size:13px;letter-spacing:.12em}
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:0;margin-top:26px;border:1px solid var(--line);border-radius:14px;overflow:hidden}
.steps div{padding:20px;border-right:1px solid var(--line);font-size:14px;color:var(--muted)}
.steps div:last-child{border-right:0}
.steps strong{display:block;color:var(--text);margin-bottom:6px;font-size:15px}
.figure{margin-top:26px;border:1px solid var(--line);border-radius:14px;background:var(--panel);padding:20px}
.figure svg{width:100%;height:auto;display:block}
.figure figcaption{color:var(--muted);font-size:12px;margin-top:10px;letter-spacing:.06em}
.final{text-align:center;padding:64px 0}
.final p{color:var(--muted);max-width:60ch;margin:14px auto 0}
footer{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--muted);font-size:13px}
footer a{color:var(--muted);margin-right:16px}
.disclaimer{margin-top:12px;font-size:12px;opacity:.8}
@media (max-width:700px){
.hero{grid-template-columns:1fr;padding:40px 0 32px;gap:28px}
.grid3{grid-template-columns:1fr}
.steps{grid-template-columns:1fr 1fr}
.steps div{border-right:0;border-bottom:1px solid var(--line)}
.feed li{grid-template-columns:52px 1fr}
.feed li .chip{grid-column:2;justify-self:start}
nav a{margin-left:12px;font-size:13px}
.brand{font-size:11px}
}
</style>
</head>
<body>
<div class="vignette"></div>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 40 40" aria-hidden="true"><path d="M6 30 L8 14 L15 22 L20 8 L25 22 L32 14 L34 30 Z" fill="none" stroke="#d9b35b" stroke-width="2" stroke-linejoin="round"/><rect x="6" y="31" width="28" height="3" fill="#d9b35b"/><circle cx="20" cy="6" r="2" fill="#4fd1e0"/></svg>
Korvus
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
<a href="/signup">Sign up</a>
</nav>
</header>

<section class="hero">
<div>
<div class="eyebrow">Overnight watch</div>
<h1>Your market terminal, awake while you are not.</h1>
<p class="lede">Korvus scores market-moving news as it breaks, tracks the session levels that matter for index futures, and logs everything that happened while you were offline. Built by a trader, for traders who run their own process.</p>
<p class="caption">Index futures do not stop at 3 a.m. Korvus Operator keeps watch while you sleep.</p>
<div class="cta">
<a class="btn btn-primary" href="/signup">Start with the free Observer tier</a>
<a class="btn btn-ghost" href="/lodestone">See LodeStone</a>
</div>
</div>

<aside class="panel" aria-label="Overnight watch preview">
<div class="panel-head"><span>Overnight log</span><span class="tag">Illustration</span></div>
<ul class="feed">
<li><span class="time">02:14</span><span>Central bank speaker, tone shifts hawkish</span><span class="chip c-dn">BEARISH</span></li>
<li><span class="time">03:40</span><span>Overnight range tested prior day high</span><span class="chip c-neu">LEVEL</span></li>
<li><span class="time">04:05</span><span>Labor print above consensus, impact scored</span><span class="chip c-up">BULLISH</span></li>
<li><span class="time">05:22</span><span>Session open levels refreshed for the desk</span><span class="chip c-neu">UPDATE</span></li>
</ul>
<div class="chips">
<span>Scored news</span><span>Session levels</span><span>Overnight log</span><span>Alerts</span>
</div>
</aside>
</section>

<section class="section">
<div class="eyebrow">What the watch covers</div>
<h2>Four things that happen while the desk is dark.</h2>
<div class="grid3">
<article class="card"><div class="num">01</div><h2 style="font-size:19px;margin-top:8px">Scored headlines</h2><p>Each market-moving item arrives with a direction, an impact read and a confidence level, so you see what changed before the open.</p></article>
<article class="card"><div class="num">02</div><h2 style="font-size:19px;margin-top:8px">Session context</h2><p>Overnight highs, lows and prior day levels are tracked continuously, so the chart you open already carries the story.</p></article>
<article class="card"><div class="num">03</div><h2 style="font-size:19px;margin-top:8px">A written record</h2><p>Every overnight event is logged with its time, so nothing that moved the market goes unexplained when you wake up.</p></article>
</div>
</section>

<section class="section">
<div class="eyebrow">How it runs</div>
<h2>Set it once. Check it when you choose.</h2>
<div class="steps">
<div><strong>1. Start free</strong>Observer tier, no card required.</div>
<div><strong>2. Go Operator</strong>Full watch, LodeStone TradingView indicator included.</div>
<div><strong>3. Wake up informed</strong>Review the overnight log before your first decision.</div>
<div><strong>4. You decide</strong>Korvus gives you the read. Your trades are your call.</div>
</div>
<figure class="figure" aria-label="Overnight coverage timeline, illustration">
<svg viewBox="0 0 900 180" role="img" aria-label="Illustration of overnight event density across hours">
<line x1="20" y1="150" x2="880" y2="150" stroke="#1c2230" stroke-width="2"/>
<g stroke="#4fd1e0" stroke-width="3" stroke-linecap="round" opacity=".85">
<line x1="60" y1="150" x2="60" y2="110"/>
<line x1="130" y1="150" x2="130" y2="70"/>
<line x1="210" y1="150" x2="210" y2="95"/>
<line x1="300" y1="150" x2="300" y2="120"/>
<line x1="390" y1="150" x2="390" y2="60"/>
<line x1="480" y1="150" x2="480" y2="100"/>
<line x1="570" y1="150" x2="570" y2="45"/>
<line x1="660" y1="150" x2="660" y2="115"/>
<line x1="750" y1="150" x2="750" y2="80"/>
<line x1="840" y1="150" x2="840" y2="130"/>
</g>
<g fill="#8d97ab" font-size="14" font-family="system-ui,sans-serif">
<text x="50" y="172">20:00</text>
<text x="290" y="172">00:00</text>
<text x="540" y="172">04:00</text>
<text x="800" y="172">08:00</text>
</g>
</svg>
<figcaption>Illustration. Event density across an overnight session, not live data.</figcaption>
</figure>
</section>

<section class="final">
<div class="eyebrow">Ready when you are</div>
<h2 style="margin-top:12px">Begin with the free tier. Upgrade when the watch earns it.</h2>
<p>Korvus is market intelligence and education. It is not financial advice, and it does not promise results. Trading involves risk of loss.</p>
<div class="cta" style="justify-content:center">
<a class="btn btn-primary" href="/signup">Create a free account</a>
</div>
</section>
</div>

<footer>
<div class="wrap">
<a href="/">Korvus</a>
<a href="/lodestone">LodeStone</a>
<a href="/legal">Legal</a>
<a href="/login">Log in</a>
<p class="disclaimer">Korvus provides market information and education only. Nothing on this page is financial, investment or trading advice. Past or illustrated outputs do not predict future results. BlackCrownVxJ LLC.</p>
</div>
</footer>
</body>
</html>
