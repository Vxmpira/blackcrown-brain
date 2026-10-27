# Copy: Write the complete korvus cold landing page html document

Date: 2026-10-27
Task: Write the complete Korvus cold landing page html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus | Index futures keep watch</title>
<meta name="description" content="Korvus is a 24/7 market intelligence terminal for index futures traders. Start on the free Observer tier, or upgrade to Operator with LodeStone included.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07070b;--panel:#0e0e16;--line:#22222e;--text:#e9e9f1;--mute:#9a9ab0;--pink:#ff2d8f}
body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
a{color:var(--pink);text-decoration:none}
.wrap{max-width:1040px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;color:var(--text)}
.brand svg{width:34px;height:31px}
.nav{float:right;display:flex;gap:18px;align-items:center;font-size:14px}
.nav a{color:var(--mute)}
.hdr::after{content:"";display:block;clear:both}
.hero{padding:72px 0 48px;display:grid;grid-template-columns:1.1fr 1fr;gap:40px;align-items:center}
h1{font-size:46px;line-height:1.1;letter-spacing:-.01em;margin-bottom:18px}
.lede{color:var(--mute);font-size:18px;max-width:520px}
.cta{display:inline-block;margin-top:28px;background:var(--pink);color:#07070b;font-weight:700;padding:14px 26px;border-radius:6px}
.note{margin-top:12px;font-size:13px;color:var(--mute)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px}
.panel-top{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--mute);margin-bottom:12px}
.tag{border:1px solid var(--pink);color:var(--pink);padding:2px 8px;border-radius:4px;font-size:11px;letter-spacing:.08em;text-transform:uppercase}
.row{display:flex;justify-content:space-between;padding:9px 0;border-bottom:1px solid var(--line);font-size:14px}
.row:last-child{border-bottom:0}
.up{color:#4ade80}.dn{color:#f87171}.mute{color:var(--mute)}
.spark{margin-top:14px;width:100%;height:70px}
.chips{display:flex;flex-wrap:wrap;gap:10px;padding:8px 0 40px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:7px 14px;font-size:13px;color:var(--text)}
section{padding:48px 0;border-top:1px solid var(--line)}
h2{font-size:28px;margin-bottom:12px}
.sub{color:var(--mute);max-width:640px;margin-bottom:28px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:22px}
.card h3{font-size:17px;margin-bottom:8px}
.card p{color:var(--mute);font-size:15px}
.tiers{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.tier{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:26px}
.tier.op{border-color:var(--pink)}
.tier h3{font-size:20px;margin-bottom:6px}
.tier ul{list-style:none;margin:14px 0 22px;color:var(--mute);font-size:15px}
.tier li{padding:4px 0}
.tier li::before{content:"- ";color:var(--pink)}
.btn{display:inline-block;border:1px solid var(--pink);color:var(--pink);padding:11px 20px;border-radius:6px;font-weight:600}
.btn.solid{background:var(--pink);color:#07070b}
.disc{font-size:13px;color:var(--mute);border:1px solid var(--line);border-radius:8px;padding:16px;margin-top:8px}
footer{border-top:1px solid var(--line);padding:26px 0 40px;font-size:13px;color:var(--mute)}
footer a{color:var(--mute);margin-right:16px}
@media(max-width:820px){.hero{grid-template-columns:1fr}.grid{grid-template-columns:1fr}.tiers{grid-template-columns:1fr}h1{font-size:36px}.nav{display:none}}
</style>
</head>
<body>
<header class="hdr">
<div class="wrap">
<div class="nav"><a href="/lodestone">LodeStone</a><a href="/legal">Legal</a><a href="/login">Log in</a></div>
<div class="brand">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>KORVUS</span>
</div>
</div>
</header>

<main>
<div class="wrap hero">
<div>
<h1>Index futures keep watch.</h1>
<p class="lede">Korvus is a 24/7 market intelligence terminal built for index futures traders. It watches the wire, scores what moves, and keeps the context in one place while you sleep, work, or trade.</p>
<a class="cta" href="/signup">Start with Observer, free</a>
<p class="note">No card required to start. Upgrade to Operator when you want the full stack.</p>
</div>
<div class="panel" aria-label="Illustration data panel">
<div class="panel-top"><span class="tag">Illustration</span><span>Overnight watch</span></div>
<div class="row"><span>Wire events scored</span><span>128</span></div>
<div class="row"><span>High impact flags</span><span class="up">7</span></div>
<div class="row"><span>Bias shift, ES session</span><span class="dn">Bearish lean</span></div>
<div class="row"><span>Bias shift, NQ session</span><span class="up">Bullish lean</span></div>
<div class="row"><span>Confidence on latest read</span><span class="mute">Medium</span></div>
<svg class="spark" viewBox="0 0 300 70" preserveAspectRatio="none" fill="none">
<path d="M0 50 L30 42 L60 46 L90 30 L120 36 L150 22 L180 28 L210 14 L240 24 L270 12 L300 18" stroke="#ff2d8f" stroke-width="2"/>
<path d="M0 60 L300 60" stroke="#22222e" stroke-width="1"/>
</svg>
</div>
</div>

<div class="wrap">
<div class="chips">
<span class="chip">24/7 wire monitoring</span>
<span class="chip">Scored news with direction</span>
<span class="chip">Session context</span>
<span class="chip">Daily USD agenda</span>
<span class="chip">LodeStone on TradingView</span>
<span class="chip">Built by a futures trader</span>
</div>
</div>

<section>
<div class="wrap">
<h2>Built for the hours you are not watching.</h2>
<p class="sub">Index futures do not wait for your session. Korvus is the watch that stays on, with the reads you need to start the day from the same page every time.</p>
<div class="grid">
<div class="card">
<h3>Scored wire, not noise</h3>
<p>Market headlines are ranked by impact, direction, and confidence, with a written Korvus read on each one so you know what the wire is saying before you open the chart.</p>
</div>
<div class="card">
<h3>Session context in one view</h3>
<p>Overnight moves, the economic agenda, and the levels that matter for the open sit together. Less tab switching, fewer missed prints.</p>
</div>
<div class="card">
<h3>Your tools, connected</h3>
<p>Operator includes the LodeStone TradingView indicator, a session level toolkit built on ICT concepts for index futures with zero repainting.</p>
</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<h2>Start free. Upgrade when the watch earns it.</h2>
<p class="sub">Observer lets you see how Korvus reads the market. Operator adds the full terminal and LodeStone. Pricing is shown at checkout, with monthly and annual options.</p>
<div class="tiers">
<div class="tier">
<h3>Observer</h3>
<p class="mute">Free, always</p>
<ul>
<li>Core market intelligence feed</li>
<li>Scored headlines, delayed read access</li>
<li>Community access</li>
</ul>
<a class="btn" href="/signup">Create free account</a>
</div>
<div class="tier op">
<h3>Operator</h3>
<p class="mute">Monthly or annual</p>
<ul>
<li>Full 24/7 terminal</li>
<li>Live scored wire with written reads</li>
<li>Daily USD economic agenda with actuals</li>
<li>LodeStone TradingView indicator included</li>
</ul>
<a class="btn solid" href="/signup">Start Operator</a>
</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="disc">
<strong>Not financial advice.</strong> Korvus is an information and education product. Scored headlines, reads, levels, and indicators are tools for your own analysis. They are not recommendations to buy or sell any instrument, and they do not guarantee results. Index futures carry substantial risk of loss and are not suitable for every trader. Past readings do not predict future outcomes. Trade only with capital you can afford to lose.
</div>
</div>
</section>
</main>

<footer>
<div class="wrap">
<p>
<a href="/">Korvus</a>
<a href="/lodestone">LodeStone</a>
<a href="/legal">Legal</a>
<a href="/login">Log in</a>
</p>
<p style="margin-top:10px">Korvus is a product of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</footer>
</body>
</html>
