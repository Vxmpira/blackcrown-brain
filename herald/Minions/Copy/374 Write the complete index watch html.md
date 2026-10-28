# Copy: Write the complete index watch html document as your report

Date: 2026-10-28
Task: Write the complete index-watch html document as your report, last line </html>
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | Korvus Market Intelligence</title>
<meta name="description" content="Korvus watches index futures around the clock. Operator includes LodeStone. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07070b;color:#e8e8ef;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.55;min-height:100vh}
a{color:#ff2d8f;text-decoration:none}
.wrap{max-width:880px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid #1d1d2a}
header svg{width:36px;height:33px}
.brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#fff}
.nav{margin-left:auto;font-size:14px}
h1{font-size:clamp(28px,5vw,44px);margin:44px 0 12px;color:#fff;letter-spacing:-.01em}
.lead{font-size:19px;color:#b9b9c8;max-width:640px}
.panel{margin:36px 0;background:#0e0e16;border:1px solid #2a2a3c;border-radius:10px;padding:20px}
.panel-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;font-size:13px;color:#8d8da3;text-transform:uppercase;letter-spacing:.06em}
.tag{border:1px solid #ff2d8f;color:#ff2d8f;padding:2px 8px;border-radius:999px;font-size:11px}
.row{display:grid;grid-template-columns:1.2fr 1fr 1fr 1fr;gap:8px;padding:10px 0;border-top:1px solid #1d1d2a;font-size:15px}
.row.h{border-top:none;color:#8d8da3;font-size:12px;text-transform:uppercase}
.up{color:#4ef2b0}.dn{color:#ff6b6b}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.chip{background:#16162a;border:1px solid #2a2a3c;border-radius:999px;padding:5px 12px;font-size:13px;color:#cfcfe0}
.plans{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-bottom:36px}
.card{background:#0e0e16;border:1px solid #2a2a3c;border-radius:10px;padding:22px}
.card.main{border-color:#ff2d8f}
.card h2{font-size:14px;text-transform:uppercase;letter-spacing:.06em;color:#8d8da3;margin-bottom:10px}
.price{font-size:32px;font-weight:700;color:#fff}
.price small{font-size:14px;font-weight:400;color:#8d8da3}
.save{display:inline-block;margin:8px 0 12px;font-size:13px;color:#4ef2b0}
ul{list-style:none;margin:12px 0 18px;font-size:15px;color:#c8c8d8}
ul li{padding:4px 0}
ul li::before{content:"-";color:#ff2d8f;margin-right:8px}
.btn{display:inline-block;background:#ff2d8f;color:#07070b;font-weight:700;padding:12px 20px;border-radius:8px}
.btn.ghost{background:transparent;color:#e8e8ef;border:1px solid #2a2a3c}
.disc{font-size:13px;color:#8d8da3;border-top:1px solid #1d1d2a;padding:20px 0 6px;margin-top:20px}
footer{padding:20px 0 40px;font-size:13px;color:#6b6b80}
@media(max-width:640px){.plans{grid-template-columns:1fr}.row{grid-template-columns:1fr 1fr 1fr}.row>*:first-child{grid-column:1/-1}}
</style>
</head>
<body>
<div class="wrap">
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">Korvus</span>
<nav class="nav"><a href="/signup">Sign up</a></nav>
</header>

<h1>Index Watch</h1>
<p class="lead">The market moves at 3 a.m. Korvus watches index futures while you sleep.</p>

<section class="panel" aria-label="Illustration">
<div class="panel-head"><span>ES / NQ / YM session levels</span><span class="tag">Illustration</span></div>
<div class="row h"><span>Contract</span><span>Last</span><span>Session high</span><span>Session low</span></div>
<div class="row"><span>ES</span><span class="up">5,412.25</span><span>5,418.50</span><span>5,396.00</span></div>
<div class="row"><span>NQ</span><span class="dn">18,904.75</span><span>18,951.25</span><span>18,870.50</span></div>
<div class="row"><span>YM</span><span class="up">40,118</span><span>40,162</span><span>40,071</span></div>
<div class="chips">
<span class="chip">Overnight range</span>
<span class="chip">Prior day levels</span>
<span class="chip">Economic agenda</span>
<span class="chip">Scored news wire</span>
</div>
</section>

<div class="plans">
<div class="card main">
<h2>Operator, annual</h2>
<div class="price">$79.99 <small>a year</small></div>
<span class="save">Annual plan, save versus monthly</span>
<ul>
<li>24/7 market intelligence terminal</li>
<li>LodeStone TradingView indicator included</li>
<li>Full Korvus wire and scored news</li>
</ul>
<a class="btn" href="/signup">Start Operator</a>
</div>
<div class="card">
<h2>Operator, monthly</h2>
<div class="price">$9.99 <small>a month</small></div>
<ul>
<li>Same terminal access</li>
<li>LodeStone TradingView indicator included</li>
<li>Cancel any time</li>
</ul>
<a class="btn ghost" href="/signup">Choose monthly</a>
</div>
</div>

<p class="disc">Not financial advice. Korvus provides market intelligence and education only. It does not give trading recommendations. Futures trading carries substantial risk of loss and is not suitable for everyone.</p>
</div>

<footer>
<div class="wrap">Korvus by BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com</div>
</footer>
</body>
</html>
