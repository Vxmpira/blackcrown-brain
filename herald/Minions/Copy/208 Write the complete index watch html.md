# Copy: Write the complete index watch html document as your report

Date: 2026-10-27
Task: Write the complete index-watch html document as your report
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Index Watch</title>
<meta name="description" content="Index futures do not stop at 3 a.m. Korvus Operator keeps watch while you sleep. Annual plan: 79.99 a year, LodeStone included. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0d0f16;--line:#1d2030;--text:#e8e9f0;--muted:#8a8fa3;--pink:#ff2d8f}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.55}
body{min-height:100vh}
a{color:var(--pink);text-decoration:none}
.wrap{max-width:1040px;margin:0 auto;padding:0 22px}
header{border-bottom:1px solid var(--line);padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.18em;font-size:15px}
.brand svg{width:36px;height:33px;flex:none}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center;padding:64px 0 48px}
.eyebrow{color:var(--pink);font-size:12px;letter-spacing:.2em;text-transform:uppercase;font-weight:600;margin-bottom:16px}
h1{font-size:clamp(32px,5vw,52px);line-height:1.1;letter-spacing:-.02em;margin-bottom:18px}
.sub{font-size:18px;color:var(--muted);max-width:520px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px;box-shadow:0 0 0 1px rgba(255,45,143,.08),0 24px 60px rgba(0,0,0,.5)}
.panel-top{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--muted);margin-bottom:14px}
.live{color:var(--pink);font-weight:600;letter-spacing:.12em;text-transform:uppercase;font-size:11px}
.tag{display:inline-block;font-size:11px;letter-spacing:.14em;text-transform:uppercase;color:var(--muted);border:1px solid var(--line);border-radius:999px;padding:3px 10px}
.rows{display:grid;gap:10px}
.row{display:flex;justify-content:space-between;align-items:center;background:#090b11;border:1px solid var(--line);border-radius:10px;padding:12px 14px;font-size:14px}
.row span:first-child{color:var(--muted)}
.bar{height:6px;border-radius:6px;background:linear-gradient(90deg,#2a2d3d,var(--pink));width:var(--w,50%)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.chip{font-size:12px;padding:6px 11px;border-radius:999px;background:#12141e;border:1px solid var(--line);color:var(--text)}
.chip.hot{border-color:rgba(255,45,143,.5);color:var(--pink)}
.illus{font-size:11px;color:var(--muted);margin-top:12px;text-align:right;letter-spacing:.08em;text-transform:uppercase}
.price{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:32px;display:grid;grid-template-columns:1fr auto;gap:24px;align-items:center;margin-bottom:40px}
.plan{font-size:13px;letter-spacing:.16em;text-transform:uppercase;color:var(--muted);margin-bottom:8px}
.amount{font-size:44px;font-weight:700;letter-spacing:-.02em}
.amount small{font-size:16px;color:var(--muted);font-weight:500;margin-left:6px}
.badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.badge{font-size:12px;font-weight:600;padding:6px 12px;border-radius:999px}
.badge.save{background:var(--pink);color:#07080c}
.badge.inc{border:1px solid var(--pink);color:var(--pink)}
.note{color:var(--muted);font-size:14px;margin-top:14px}
.cta{display:inline-block;background:var(--pink);color:#07080c;font-weight:700;padding:16px 28px;border-radius:10px;font-size:16px;text-align:center;white-space:nowrap}
.cta:hover{filter:brightness(1.08)}
footer{border-top:1px solid var(--line);padding:24px 0 36px;color:var(--muted);font-size:13px}
footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}
@media (max-width:820px){
.hero{grid-template-columns:1fr;padding:44px 0 36px;gap:28px}
.price{grid-template-columns:1fr;padding:24px}
.cta{width:100%}
}
</style>
</head>
<body>
<header>
<div class="wrap">
<div class="brand">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>KORVUS</span>
</div>
</div>
</header>

<main class="wrap">
<section class="hero">
<div>
<div class="eyebrow">Korvus Operator</div>
<h1>Index futures do not stop at 3 a.m.</h1>
<p class="sub">Korvus Operator keeps watch while you sleep.</p>
</div>

<div>
<div class="panel" role="img" aria-label="Illustration of a 24/7 watch panel">
<div class="panel-top">
<span class="live">Watch active</span>
<span class="tag">24/7</span>
</div>
<div class="rows">
<div class="row"><span>Asia session</span><span class="bar" style="--w:72%"></span></div>
<div class="row"><span>London session</span><span class="bar" style="--w:48%"></span></div>
<div class="row"><span>New York session</span><span class="bar" style="--w:86%"></span></div>
<div class="row"><span>Scored news wire</span><span class="bar" style="--w:61%"></span></div>
</div>
<div class="chips">
<span class="chip hot">Session levels</span>
<span class="chip">Wire scoring</span>
<span class="chip">Overnight watch</span>
<span class="chip">LodeStone included</span>
</div>
<div class="illus">Illustration. Not live data.</div>
</div>
</div>
</section>

<section class="price" aria-label="Annual plan">
<div>
<div class="plan">Annual plan</div>
<div class="amount">79.99<small>a year</small></div>
<div class="badges">
<span class="badge save">Save 39.89</span>
<span class="badge inc">LodeStone included</span>
</div>
<p class="note">One payment a year. Full Operator access.</p>
</div>
<a class="cta" href="https://korvus.industries/signup">Start Operator</a>
</section>
</main>

<footer>
<div class="wrap">
<span>Not financial advice.</span>
<span>KORVUS by BlackCrownVxJ LLC</span>
</div>
</footer>
</body>
</html>
