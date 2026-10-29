# Copy: Write the complete korvus watcher landing html document ending with

Date: 2026-10-29
Task: Write the complete Korvus watcher landing html document ending with </html>
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Index Watch: Overnight Futures Coverage</title>
<meta name="description">
<meta name="description" content="Korvus keeps watch over index futures while you sleep. Scored market news, session context, and a written read, delivered to your terminal. Information only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{background:#05060a}
body{font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;color:#e7e9ef;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden;background:#05060a}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 600px at 15% -10%,rgba(92,70,255,.22),transparent 60%),radial-gradient(800px 560px at 95% 10%,rgba(0,200,180,.14),transparent 60%),radial-gradient(700px 500px at 50% 110%,rgba(140,60,255,.12),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:#fff;text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand span{font-size:1.05rem}
nav a{color:#b9bfd0;text-decoration:none;margin-left:22px;font-size:.95rem}
nav a:hover{color:#fff}
.hero{padding:56px 0 40px;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.eyebrow{display:inline-block;font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;color:#9ad8ff;border:1px solid rgba(154,216,255,.3);padding:6px 12px;border-radius:999px;margin-bottom:18px}
h1{font-size:clamp(2rem,4.6vw,3.3rem);line-height:1.12;letter-spacing:-.02em;color:#fff;margin-bottom:18px}
h2{font-size:clamp(1.5rem,3vw,2.1rem);line-height:1.2;color:#fff;margin-bottom:14px}
h3{font-size:1.08rem;color:#fff;margin-bottom:8px}
.lede{font-size:clamp(1rem,1.6vw,1.12rem);color:#c5cad8;max-width:620px}
.cta-row{display:flex;gap:12px;flex-wrap:wrap;margin-top:26px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:600;text-decoration:none;font-size:.98rem}
.btn-primary{background:linear-gradient(135deg,#7b61ff,#3ad1c4);color:#05060a}
.btn-ghost{border:1px solid rgba(255,255,255,.2);color:#e7e9ef}
.note{font-size:.85rem;color:#8d94a8;margin-top:14px}
.panel{background:rgba(14,16,26,.8);border:1px solid rgba(255,255,255,.08);border-radius:16px;padding:20px;box-shadow:0 20px 60px rgba(0,0,0,.45)}
.panel-head{display:flex;justify-content:space-between;font-size:.8rem;color:#8d94a8;margin-bottom:12px;gap:8px;flex-wrap:wrap}
.tag-illus{color:#ffd27a;border:1px solid rgba(255,210,122,.35);padding:2px 8px;border-radius:6px;font-size:.72rem;letter-spacing:.08em;text-transform:uppercase}
.feed{display:grid;gap:10px}
.item{display:grid;grid-template-columns:auto 1fr auto;gap:12px;align-items:center;background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.06);border-radius:10px;padding:12px}
.pill{font-size:.72rem;font-weight:700;padding:4px 8px;border-radius:6px;letter-spacing:.06em}
.up{background:rgba(60,220,160,.15);color:#6ef0be}
.dn{background:rgba(255,95,120,.15);color:#ff8aa0}
.neu{background:rgba(160,170,200,.15);color:#c5cad8}
.item p{font-size:.9rem;color:#dfe3ee}
.score{font-size:.8rem;color:#8d94a8;white-space:nowrap}
section{padding:48px 0}
.divider{border-top:1px solid rgba(255,255,255,.07)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:24px}
.card{background:rgba(14,16,26,.7);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:22px}
.card p{color:#b9bfd0;font-size:.95rem}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:22px}
.chip{font-size:.85rem;padding:8px 14px;border-radius:999px;background:rgba(123,97,255,.12);border:1px solid rgba(123,97,255,.3);color:#d9d2ff}
.prose{max-width:720px;color:#c5cad8}
.prose p+p{margin-top:14px}
.tiers{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:24px}
.tier{background:rgba(14,16,26,.7);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:24px}
.tier.feat{border-color:rgba(58,209,196,.45);background:linear-gradient(180deg,rgba(58,209,196,.08),rgba(14,16,26,.7))}
.tier ul{list-style:none;margin:14px 0 0;color:#c5cad8;font-size:.95rem}
.tier li{padding:6px 0 6px 22px;position:relative}
.tier li::before{content:"";position:absolute;left:4px;top:14px;width:8px;height:8px;border-radius:2px;background:#3ad1c4}
.faq details{border-bottom:1px solid rgba(255,255,255,.08);padding:16px 0}
.faq summary{cursor:pointer;color:#fff;font-weight:600;list-style:none}
.faq p{margin-top:10px;color:#b9bfd0;font-size:.95rem;max-width:720px}
.closer{text-align:center;padding:56px 0}
.closer p{color:#c5cad8;margin:12px auto 0;max-width:640px}
footer{border-top:1px solid rgba(255,255,255,.07);padding:28px 0 40px;color:#8d94a8;font-size:.85rem}
footer p+p{margin-top:10px}
.disclaimer{color:#9aa1b5}
@media (max-width:900px){.hero{grid-template-columns:1fr;gap:28px;padding-top:36px}.grid3{grid-template-columns:1fr 1fr}}
@media (max-width:700px){.grid3,.tiers{grid-template-columns:1fr}nav a{margin-left:14px;font-size:.88rem}header{justify-content:center;text-align:center}.item{grid-template-columns:1fr}.score{white-space:normal}section{padding:36px 0}}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/" aria-label="Korvus home">
<svg width="34" height="34" viewBox="0 0 48 48" aria-hidden="true" focusable="false">
<defs><linearGradient id="g" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#7b61ff"/><stop offset="1" stop-color="#3ad1c4"/></linearGradient></defs>
<path d="M6 16l8 8 10-14 10 14 8-8-3 22H9z" fill="url(#g)"/>
<rect x="9" y="34" width="30" height="4" rx="2" fill="#e7e9ef" opacity=".85"/>
</svg>
<span>KORVUS</span>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
<a href="/signup">Start free</a>
</nav>
</header>

<div class="hero">
<div>
<span class="eyebrow">Index futures market intelligence</span>
<h1>The market does not sleep. Korvus keeps watch while you do.</h1>
<p class="lede">Overnight moves in index futures set up the open before you wake. Korvus scores the news as it breaks, places it against session context, and writes a plain read you can check against your own charts. Your edge while the world sleeps.</p>
<div class="cta-row">
<a class="btn btn-primary" href="/signup">Start with the free Observer tier</a>
<a class="btn btn-ghost" href="/lodestone">See LodeStone</a>
</div>
<p class="note">No card required to start. Information and education only, not financial advice.</p>
</div>

<div class="panel" role="img" aria-label="Illustrative Korvus news feed mock">
<div class="panel-head"><span>Overnight watch feed</span><span class="tag-illus">Illustration</span></div>
<div class="feed">
<div class="item"><span class="pill dn">BEARISH</span><p>Rate path repricing after a hotter than expected services print. Index futures bid fades into the Asia session.</p><span class="score">Impact 8 / Conf 72</span></div>
<div class="item"><span class="pill up">BULLISH</span><p>Earnings revisions lift semis overnight. Breadth improves on the cash open watchlist.</p><span class="score">Impact 6 / Conf 64</span></div>
<div class="item"><span class="pill neu">NEUTRAL</span><p>Central bank speaker sticks to script. Headline risk low through the London handoff.</p><span class="score">Impact 3 / Conf 58</span></div>
<div class="item"><span class="pill up">BULLISH</span><p>Dollar softens into the US data window. Session levels logged for the 9:30 read.</p><span class="score">Impact 5 / Conf 61</span></div>
</div>
</div>
</div>
</div>

<section class="divider">
<div class="wrap" style="padding:0">
<h2>Built for the hours nobody is watching</h2>
<p class="prose">Most traders can cover one session at a time. The overnight tape moves on its own schedule: headlines land in Tokyo, reprice in London, and set the mood before the bell. Korvus covers all of it so the first thing you read in the morning is a structured picture, not a scroll of unsorted noise.</p>
<div class="grid3">
<div class="card"><h3>Scored news, always on</h3><p>Every headline is rated for likely market impact, direction, and confidence, with a written Korvus read beside it.</p></div>
<div class="card"><h3>Session context</h3><p>Overnight highs, lows, and the session map are kept in one view so you can see where price is relative to the levels that matter.</p></div>
<div class="card"><h3>Your charts, sharper</h3><p>Operator includes the LodeStone TradingView indicator: session level tools built on ICT concepts for index futures, with zero repainting.</p></div>
</div>
<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Impact and confidence scores</span>
<span class="chip">Session level map</span>
<span class="chip">Written reads</span>
<span class="chip">Free Observer tier</span>
</div>
</div>
</section>

<section class="divider">
<div class="wrap" style="padding:0">
<h2>Two ways to start</h2>
<p class="prose">Start on Observer to see how the feed reads before you commit anything. Move to Operator when you want the full terminal and the LodeStone indicator on your charts.</p>
<div class="tiers">
<div class="tier">
<h3>Observer</h3>
<p class="prose">The free tier. See the watch feed and get a feel for how Korvus scores and frames the news.</p>
<ul>
<li>Overnight watch feed</li>
<li>Scored headlines with written reads</li>
<li>No card required</li>
</ul>
<p style="margin-top:20px"><a class="btn btn-ghost" href="/signup">Create a free account</a></p>
</div>
<div class="tier feat">
<h3>Operator</h3>
<p class="prose">The full terminal for traders who run the session. Plans and pricing are shown inside your account.</p>
<ul>
<li>Full terminal access</li>
<li>LodeStone TradingView indicator included</li>
<li>Session level toolkit and deeper context</li>
</ul>
<p style="margin-top:20px"><a class="btn btn-primary" href="/signup">Start with Observer, upgrade anytime</a></p>
</div>
</div>
</div>
</section>

<section class="divider faq">
<div class="wrap" style="padding:0">
<h2>Questions traders ask</h2>
<details><summary>Is Korvus a trading signal service?</summary><p>No. Korvus is market information and education. It scores and describes news and session context. It does not tell you what to buy or sell, and it does not promise results. Every decision stays with you.</p></details>
<details><summary>Does Korvus watch the market overnight?</summary><p>Yes. The watch feed runs around the clock so overnight headlines and session shifts are captured as they happen, ready for the open.</p></details>
<details><summary>What is the LodeStone indicator?</summary><p>LodeStone is the chart side of the Korvus stack: a session level toolkit for index futures, build V7.5, with seven feature layers and zero repainting. It is included with Operator and also available on its own.</p></details>
<details><summary>Can I start without paying?</summary><p>Yes. The Observer tier is free and needs no card. Upgrade only when the feed has earned it for you.</p></details>
</div>
</section>

<section class="divider closer">
<div class="wrap" style="padding:0">
<h2>Let the watch run tonight</h2>
<p>Open a free account, read the overnight feed, and judge the output yourself before the open.</p>
<div class="cta-row" style="justify-content:center">
<a class="btn btn-primary" href="/signup">Start free on Korvus</a>
</div>
</div>
</section>

<footer>
<div class="wrap">
<p>Korvus is part of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
<p class="disclaimer">Korvus provides market information and education only. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Futures trading carries substantial risk of loss and is not suitable for everyone. Past scores and reads do not guarantee future outcomes. The feed illustration above is labeled as Illustration and does not show live data.</p>
<p><a href="/legal" style="color:#b9bfd0">Legal</a> &nbsp;|&nbsp; <a href="/lodestone" style="color:#b9bfd0">LodeStone</a> &nbsp;|&nbsp; <a href="/login" style="color:#b9bfd0">Log in</a></p>
</div>
</footer>
</div>
</body>
</html>
