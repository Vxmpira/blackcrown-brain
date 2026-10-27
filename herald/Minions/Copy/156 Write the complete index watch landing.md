# Copy: Write the complete index watch landing page as one html

Date: 2026-10-27
Task: Write the complete index-watch landing page as one html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures Watch, 24/7 | Korvus Operator</title>
<meta name="description" content="Korvus Operator keeps watch on index futures while you sleep. Directional read and LodeStone included. Annual plan 79.99 a year.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07070b;color:#e9e9f0;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.55;min-height:100vh}
a{color:#ff2d8f;text-decoration:none}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #1d1d28}
header svg{width:36px;height:33px}
.brand{font-weight:700;letter-spacing:.18em;font-size:18px}
main{max-width:980px;margin:0 auto;padding:56px 24px 40px}
.eyebrow{color:#ff2d8f;text-transform:uppercase;letter-spacing:.14em;font-size:12px;font-weight:600}
h1{font-size:clamp(30px,5vw,48px);line-height:1.15;margin:14px 0 18px;font-weight:700}
.sub{font-size:18px;color:#c4c4d0;max-width:640px}
.price{margin-top:18px;font-size:16px;color:#e9e9f0}
.price strong{color:#ff2d8f}
.cta{display:inline-block;margin-top:26px;background:#ff2d8f;color:#07070b;font-weight:700;padding:14px 26px;border-radius:6px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:28px 0 8px}
.chip{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:999px;padding:6px 14px;font-size:13px;font-weight:600}
.panel{margin-top:44px;background:#0d0d14;border:1px solid #23232f;border-radius:10px;padding:22px}
.panel-head{display:flex;justify-content:space-between;align-items:center;font-size:13px;color:#8d8da0;margin-bottom:14px}
.tag{font-size:11px;text-transform:uppercase;letter-spacing:.12em;color:#07070b;background:#8d8da0;border-radius:4px;padding:3px 8px;font-weight:700}
.rows{display:grid;gap:10px}
.row{display:grid;grid-template-columns:1.2fr 1fr 1fr;gap:12px;background:#11111a;border-radius:6px;padding:12px 14px;font-size:14px}
.row span:first-child{color:#c4c4d0}
.up{color:#4fe3a1}
.down{color:#ff2d8f}
.bar{height:6px;background:#1d1d28;border-radius:3px;margin-top:16px;overflow:hidden}
.bar i{display:block;height:100%;width:64%;background:linear-gradient(90deg,#ff2d8f,#7a3cff)}
.grid{display:grid;gap:16px;margin-top:44px;grid-template-columns:repeat(auto-fit,minmax(260px,1fr))}
.card{background:#0d0d14;border:1px solid #23232f;border-radius:10px;padding:20px}
.card h2{font-size:17px;margin-bottom:8px}
.card p{color:#c4c4d0;font-size:15px}
footer{max-width:980px;margin:0 auto;padding:28px 24px 48px;border-top:1px solid #1d1d28;color:#8d8da0;font-size:13px}
footer p+p{margin-top:6px}
@media(max-width:600px){.row{grid-template-columns:1fr 1fr}.row span:first-child{grid-column:1/-1}}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">KORVUS</span>
</header>
<main>
<div class="eyebrow">Korvus Operator</div>
<h1>Index futures don't stop at 3 a.m. Korvus doesn't either.</h1>
<p class="sub">Korvus Operator keeps watch on index futures while you sleep. Annual plan: 79.99 a year, LodeStone included.</p>
<div class="chips">
<span class="chip">24/7 watch</span>
<span class="chip">Directional read</span>
<span class="chip">LodeStone included</span>
</div>
<a class="cta" href="https://korvus.industries/signup?utm_source=herald&amp;utm_medium=cta&amp;utm_campaign=operator_annual">Go annual with Korvus Operator</a>
<p class="price">Annual plan: <strong>79.99 a year</strong>, LodeStone TradingView indicator included.</p>

<section class="panel" aria-label="Illustration data panel">
<div class="panel-head"><span>Overnight index watch</span><span class="tag">Illustration</span></div>
<div class="rows">
<div class="row"><span>ES session range</span><span>Watching</span><span class="up">Directional read: up</span></div>
<div class="row"><span>NQ session range</span><span>Watching</span><span class="down">Directional read: down</span></div>
<div class="row"><span>YM session range</span><span>Watching</span><span>Directional read: neutral</span></div>
</div>
<div class="bar"><i></i></div>
</section>

<section class="grid">
<div class="card">
<h2>Watches while you sleep</h2>
<p>Index futures trade through the night. Korvus monitors the market around the clock so you see what moved while you were offline.</p>
</div>
<div class="card">
<h2>A directional read</h2>
<p>Each watch reports a plain directional read on the index you follow, written so you can judge it yourself before the open.</p>
</div>
<div class="card">
<h2>LodeStone included</h2>
<p>Operator includes the LodeStone session level indicator for TradingView, zero repainting, built for index futures.</p>
</div>
</section>
</main>
<footer>
<p>Not financial advice. Trading involves risk.</p>
<p>Korvus provides market information and tools. Past reads and indicator signals do not guarantee future results, and no profit is promised.</p>
</footer>
</body>
</html>
