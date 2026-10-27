# Copy: Write the index watch landing page as one complete html

Date: 2026-10-27
Task: Write the index-watch landing page as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures Watch | Korvus</title>
<meta name="description" content="Korvus Operator watches index futures around the clock. Annual plan 79.99 a year with LodeStone included. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07070b;color:#e8e8f0;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.55;min-height:100vh}
.wrap{max-width:880px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1d1d2a;padding:18px 0}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#fff;text-decoration:none}
.brand svg{width:36px;height:33px}
main{padding:56px 0 40px}
h1{font-size:clamp(30px,5vw,46px);line-height:1.1;color:#fff;margin-bottom:18px;letter-spacing:-.01em}
.lede{font-size:18px;color:#b8b8c8;max-width:620px;margin-bottom:28px}
.panel{background:#0f0f17;border:1px solid #26263a;border-radius:10px;padding:22px;margin:32px 0}
.panel-head{display:flex;justify-content:space-between;align-items:center;font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:#8a8aa0;margin-bottom:16px}
.tag{border:1px solid #ff2d8f;color:#ff2d8f;padding:3px 8px;border-radius:4px}
.row{display:grid;grid-template-columns:1fr auto;gap:12px;padding:12px 0;border-top:1px solid #1d1d2a;font-size:15px}
.row:first-of-type{border-top:0}
.chip{font-size:12px;color:#e8e8f0;background:#1a1a28;border-radius:999px;padding:4px 10px}
.bar{height:6px;background:#1d1d2a;border-radius:3px;overflow:hidden;margin-top:6px}
.bar span{display:block;height:100%;background:linear-gradient(90deg,#ff2d8f,#7a5cff)}
.price{display:flex;flex-wrap:wrap;align-items:baseline;gap:12px;margin:8px 0 20px}
.amount{font-size:34px;font-weight:700;color:#fff}
.note{color:#8a8aa0;font-size:14px}
.cta{display:inline-block;background:#ff2d8f;color:#07070b;font-weight:700;text-decoration:none;padding:14px 26px;border-radius:6px}
.cta:hover{background:#ff5aa6}
footer{border-top:1px solid #1d1d2a;padding:24px 0 36px;color:#8a8aa0;font-size:13px}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="https://korvus.industries/">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>Korvus</span>
</a>
</div>
</header>
<main>
<div class="wrap">
<h1>Index futures do not stop at 3 a.m.</h1>
<p class="lede">Korvus Operator keeps watch while you sleep. Overnight wire events, session levels, and market context are tracked around the clock so you start the session informed, not behind.</p>

<section class="panel" aria-label="Overnight watch panel">
<div class="panel-head"><span>Overnight watch</span><span class="tag">Illustration</span></div>
<div class="row"><span>Scored news wire</span><span class="chip">Live</span></div>
<div class="row"><span>Session level tracking</span><span class="chip">Live</span></div>
<div class="row"><span>Index futures coverage</span><span class="chip">24/7</span></div>
<div class="row"><div>Watch coverage across the night<div class="bar"><span style="width:82%"></span></div></div><span class="chip">Illustration</span></div>
</section>

<div class="price">
<span class="amount">79.99</span>
<span class="note">a year, Korvus Operator annual plan. LodeStone included.</span>
</div>

<a class="cta" href="https://korvus.industries/signup">Start with Korvus</a>
</div>
</main>
<footer>
<div class="wrap">
<p>Not financial advice. Korvus is a market intelligence tool for index futures traders. Trading involves risk, and you are responsible for your own decisions.</p>
</div>
</footer>
</body>
</html>
