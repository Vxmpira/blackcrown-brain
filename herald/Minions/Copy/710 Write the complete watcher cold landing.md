# Copy: Write the complete watcher cold landing page html document doctype

Date: 2026-10-29
Task: Write the complete Watcher cold landing page html document, doctype through closing html tag.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watch: Market Surveillance While You Sleep</title>
<meta name="description" content="Korvus watches index futures around the clock, scoring news and levels while you sleep. Start with a free Observer account. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--ink:#e9e7ef;--mute:#9b97a8;--line:rgba(255,255,255,.08);--accent:#ff2d8f;--cyan:#38d6ff;--bg:#0a0a10;--panel:#11111a}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{min-height:100vh;position:relative;overflow-x:hidden}
.fx{position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 85% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(800px 560px at -10% 40%,rgba(56,214,255,.10),transparent 60%),radial-gradient(700px 500px at 60% 110%,rgba(255,45,143,.08),transparent 60%)}
.grid{position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.vig{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 22px}
header{padding:22px 0;border-bottom:1px solid var(--line)}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:14px;color:var(--ink);text-decoration:none}
.brand svg{width:36px;height:33px}
.nav a{color:var(--mute);text-decoration:none;font-size:14px;margin-left:22px}
.nav a:hover{color:var(--ink)}
.btn{display:inline-block;background:var(--accent);color:#0a0a10;font-weight:700;padding:14px 24px;border-radius:10px;text-decoration:none;font-size:15px}
.btn.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
.hero{padding:76px 0 56px}
.eyebrow{color:var(--accent);text-transform:uppercase;letter-spacing:.18em;font-size:12px;font-weight:700;margin-bottom:18px}
h1{font-size:clamp(34px,6vw,62px);line-height:1.06;letter-spacing:-.02em;max-width:18ch;margin-bottom:22px}
h1 em{font-style:normal;color:var(--accent)}
.lede{font-size:clamp(17px,2vw,19px);color:var(--mute);max-width:62ch;margin-bottom:30px}
.ctas{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
.note{color:var(--mute);font-size:13px;margin-top:14px}
h2{font-size:clamp(24px,3.6vw,36px);line-height:1.15;letter-spacing:-.01em;margin-bottom:14px}
.sec{padding:64px 0;border-top:1px solid var(--line)}
.prose{max-width:66ch;color:var(--mute);margin-bottom:12px}
.prose strong{color:var(--ink);font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:24px 0 8px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:8px 14px;font-size:14px;color:var(--ink)}
.chip b{color:var(--cyan);font-weight:600;margin-right:6px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:22px;margin-top:28px}
.panel-head{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;margin-bottom:16px}
.tag{font-size:11px;letter-spacing:.14em;text-transform:uppercase;color:var(--cyan);border:1px solid rgba(56,214,255,.35);padding:4px 10px;border-radius:999px}
.panel-title{font-weight:600;font-size:15px}
.row{display:grid;grid-template-columns:1.3fr 1fr 0.7fr 0.9fr;gap:12px;padding:12px 0;border-top:1px solid var(--line);font-size:14px;align-items:center}
.row.head{border-top:0;color:var(--mute);font-size:12px;text-transform:uppercase;letter-spacing:.1em}
.up{color:#5cf2a0}
.dn{color:#ff6b8a}
.read{color:var(--mute)}
.cols{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:28px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:24px}
.card h3{font-size:18px;margin-bottom:8px}
.card p{color:var(--mute);font-size:15px;max-width:52ch}
.steps{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:28px}
.step{border-left:2px solid var(--accent);padding:4px 0 4px 16px}
.step span{display:block;color:var(--accent);font-size:12px;font-weight:700;letter-spacing:.14em;margin-bottom:6px}
.step p{color:var(--mute);font-size:15px}
.final{padding:72px 0;border-top:1px solid var(--line);text-align:left}
.final .prose{margin-bottom:24px}
.disc{font-size:12px;color:#6f6b7d;max-width:80ch;margin-top:36px;padding-top:22px;border-top:1px solid var(--line)}
footer{padding:28px 0 40px;color:#6f6b7d;font-size:13px}
footer a{color:var(--mute)}
@media (max-width:700px){
.nav{display:none}
.row{grid-template-columns:1.4fr 1fr 0.8fr}
.row>:nth-child(4){display:none}
.row.head>:nth-child(4){display:none}
.cols,.steps{grid-template-columns:1fr}
.hero{padding:52px 0 40px}
.sec{padding:48px 0}
.final{padding:52px 0}
}
</style>
</head>
<body>
<div class="fx" aria-hidden="true"></div>
<div class="grid" aria-hidden="true"></div>
<div class="vig" aria-hidden="true"></div>

<header>
<div class="wrap bar">
<a class="brand" href="/">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>Korvus</span>
</a>
<nav class="nav">
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
</nav>
</div>
</header>

<main>
<section class="hero">
<div class="wrap">
<div class="eyebrow">Index futures surveillance</div>
<h1>The watcher that never <em>sleeps</em>.</h1>
<p class="lede">The market moves while you are off the screen. Korvus keeps watch over index futures around the clock, scores the news as it lands, and reports what matters before the open. You set the rules. It does the watching.</p>
<div class="ctas">
<a class="btn" href="/signup">Create your free Observer account</a>
<a class="btn ghost" href="/lodestone">See LodeStone</a>
</div>
<p class="note">Free account, no card required. Information and education only.</p>

<div class="chips" role="list">
<span class="chip" role="listitem"><b>24/7</b>market watch</span>
<span class="chip" role="listitem"><b>Scored</b>news with impact</span>
<span class="chip" role="listitem"><b>Live</b>session levels</span>
<span class="chip" role="listitem"><b>Zero</b>repainting charts</span>
</div>

<div class="panel" aria-label="Illustration of the Korvus event feed">
<div class="panel-head">
<div class="panel-title">Overnight event feed</div>
<span class="tag">Illustration</span>
</div>
<div class="row head"><div>Event</div><div>Impact</div><div>Direction</div><div>Confidence</div></div>
<div class="row"><div>Macro release, overnight session</div><div>High</div><div class="up">Up</div><div class="read">Moderate</div></div>
<div class="row"><div>Central bank speaker, headline</div><div>Medium</div><div class="dn">Down</div><div class="read">Moderate</div></div>
<div class="row"><div>Session high tested, sweep logged</div><div>Medium</div><div class="up">Up</div><div class="read">Strong</div></div>
<div class="row"><div>Calendar event, pre-open window</div><div>Low</div><div class="read">Flat</div><div class="read">Light</div></div>
</div>
</div>
</section>

<section class="sec">
<div class="wrap">
<h2>The market does not clock out.</h2>
<p class="prose"><strong>Your best setups often form while you are asleep.</strong> Overnight sessions carry releases, headlines, and liquidity shifts that change the open before you can check a chart.</p>
<p class="prose">Korvus runs the watch in your place. It tracks index futures through the overnight session, flags the events that carry weight, and writes each one up so you can read it in under a minute.</p>
<div class="cols">
<div class="card">
<h3>Scored, not dumped</h3>
<p>Each headline arrives with an impact rating, a direction, and a confidence level, plus a written read. Less noise, faster decisions.</p>
</div>
<div class="card">
<h3>Built for the open</h3>
<p>Session levels and the economic agenda sit in one place, so the pre-market routine starts from a finished picture instead of a blank screen.</p>
</div>
</div>
</div>
</section>

<section class="sec">
<div class="wrap">
<h2>Three steps, no setup theater.</h2>
<div class="steps">
<div class="step"><span>01</span><p>Create a free Observer account in under a minute. No card needed.</p></div>
<div class="step"><span>02</span><p>Open the terminal and review the overnight feed and the scored event log.</p></div>
<div class="step"><span>03</span><p>Decide what to act on. Korvus informs the read, the call stays yours.</p></div>
</div>
</div>
</section>

<section class="sec">
<div class="wrap">
<h2>Start free. Upgrade when the watch earns it.</h2>
<p class="prose"><strong>Observer</strong> gives you the free terminal view so you can judge the output for yourself.</p>
<p class="prose"><strong>Operator</strong> adds the full surveillance layer and includes the LodeStone TradingView indicator, so the chart and the wire work from the same playbook. Annual billing is listed first with the savings shown on the upgrade page.</p>
</div>
</section>

<section class="final">
<div class="wrap">
<h2>Let the watch run tonight.</h2>
<p class="prose">Create your free Observer account, open the terminal, and see what came in while you were away.</p>
<div class="ctas">
<a class="btn" href="/signup">Create your free Observer account</a>
<a class="btn ghost" href="/legal">Legal and terms</a>
</div>
<p class="disc">Not financial advice. Korvus provides market information and education for index futures traders. Nothing on this page is a recommendation to buy, sell, or hold any instrument, and nothing here promises profit. Futures trading carries substantial risk of loss. Figures shown in the illustration are examples for layout only.</p>
</div>
</section>
</main>

<footer>
<div class="wrap">
<p>Korvus, a BlackCrownVxJ LLC product. <a href="/legal">Legal</a> · <a href="/">Home</a></p>
</div>
</footer>
</body>
</html>
