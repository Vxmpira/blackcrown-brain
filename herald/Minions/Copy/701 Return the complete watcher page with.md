# Copy: Return the complete watcher page with one meta description ending

Date: 2026-10-29
Task: Return the complete watcher page with one meta description, ending in </html>
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>The Watcher | Korvus Market Intelligence</title>
<meta name="description" content="Korvus watches index futures markets around the clock, scores the news as it lands, and tells you what it means. Operator tier includes LodeStone.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:#06070b;color:#e7e9f0;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;-webkit-font-smoothing:antialiased}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 40vw at 15% 0%,rgba(90,70,255,.22),transparent 70%),radial-gradient(50vw 35vw at 90% 10%,rgba(0,200,180,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.brand{display:flex;align-items:center;gap:12px;color:#e7e9f0;text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px;flex:none}
nav a{color:#b9bfd0;text-decoration:none;margin-left:18px;font-size:.95rem}
nav a:hover{color:#fff}
.hero{padding:72px 0 40px}
.eyebrow{font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;color:#7fd8cf;margin-bottom:14px}
h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.1;letter-spacing:-.02em;max-width:18ch}
h2{font-size:clamp(1.4rem,3vw,1.9rem);line-height:1.2;margin-bottom:14px}
.lede{font-size:clamp(1.02rem,2vw,1.18rem);color:#b9bfd0;max-width:62ch;margin-top:18px}
.cta{display:inline-block;margin-top:28px;padding:13px 22px;border-radius:10px;background:#e7e9f0;color:#06070b;font-weight:700;text-decoration:none}
.cta:hover{background:#fff}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:26px}
.chip{font-size:.85rem;padding:6px 12px;border-radius:999px;border:1px solid rgba(255,255,255,.14);color:#cfd4e2;background:rgba(255,255,255,.03)}
section{padding:48px 0;border-top:1px solid rgba(255,255,255,.07)}
.prose{max-width:66ch}
.prose p{color:#c4c9d8;margin-bottom:14px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:24px}
.card{padding:22px;border-radius:14px;border:1px solid rgba(255,255,255,.09);background:rgba(255,255,255,.025)}
.card h3{font-size:1.02rem;margin-bottom:8px}
.card p{color:#aab1c3;font-size:.95rem}
.figure{margin-top:24px;border-radius:14px;border:1px solid rgba(255,255,255,.1);background:#0b0d14;overflow:hidden}
.figure-head{display:flex;justify-content:space-between;align-items:center;padding:12px 18px;border-bottom:1px solid rgba(255,255,255,.07);font-size:.85rem;color:#9aa2b8}
.tag{font-size:.72rem;letter-spacing:.1em;text-transform:uppercase;color:#f0c674;border:1px solid rgba(240,198,116,.4);padding:3px 8px;border-radius:6px}
.row{display:grid;grid-template-columns:110px 1fr 120px;gap:14px;align-items:center;padding:14px 18px;border-bottom:1px solid rgba(255,255,255,.05);font-size:.93rem}
.row:last-child{border-bottom:0}
.time{color:#7d8498;font-variant-numeric:tabular-nums}
.headline{color:#e7e9f0}
.score{justify-self:end;font-variant-numeric:tabular-nums;font-weight:700;padding:4px 10px;border-radius:8px}
.hi{background:rgba(127,216,207,.15);color:#7fd8cf}
.md{background:rgba(240,198,116,.14);color:#f0c674}
.lo{background:rgba(255,255,255,.07);color:#aab1c3}
.disclaimer{font-size:.85rem;color:#7d8498;max-width:70ch;margin-top:20px}
footer{padding:36px 0 56px;border-top:1px solid rgba(255,255,255,.08);color:#7d8498;font-size:.88rem}
footer a{color:#b9bfd0}
@media (max-width:700px){
header{flex-wrap:wrap}
nav a{margin-left:0;margin-right:16px}
.grid{grid-template-columns:1fr}
.row{grid-template-columns:1fr;gap:6px}
.score{justify-self:start}
.hero{padding:48px 0 28px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 48 48" aria-hidden="true"><path d="M6 36 L10 16 L18 26 L24 12 L30 26 L38 16 L42 36 Z" fill="none" stroke="#e7e9f0" stroke-width="2.5" stroke-linejoin="round"/><rect x="6" y="36" width="36" height="4" rx="1" fill="#7fd8cf"/><circle cx="24" cy="27" r="2.4" fill="#7fd8cf"/></svg>
<span>KORVUS</span>
</a>
<nav>
<a href="/lodestone">LodeStone</a>
<a href="/login">Log in</a>
<a href="/signup">Sign up</a>
</nav>
</header>

<div class="hero">
<div class="eyebrow">The Watcher</div>
<h1>The market never sleeps. Your watch doesn't have to.</h1>
<p class="lede">Korvus watches index futures around the clock, scores each headline as it lands, and writes a plain read on what it could mean for the session. You stay in the arena. It keeps the overnight watch.</p>
<a class="cta" href="/signup">Start with the free Observer tier</a>
<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Scored news</span>
<span class="chip">Written Korvus read</span>
<span class="chip">LodeStone included with Operator</span>
</div>
</div>

<section>
<div class="prose">
<h2>Watching while you sleep</h2>
<p>Overnight moves in index futures often start in headlines you never saw. Korvus reads the wire continuously, grades each item for impact, direction, and confidence, and keeps the record so you can review it at the open.</p>
<p>Nothing here tells you what to trade. Korvus gives you structure and context so your own process has better inputs.</p>
</div>
</section>

<section>
<h2>What the watcher reports</h2>
<div class="grid">
<div class="card">
<h3>Scored headlines</h3>
<p>Each item carries an impact grade, a directional lean, and a confidence level, so the loud stories and the quiet ones are ranked the same way.</p>
</div>
<div class="card">
<h3>Written read</h3>
<p>A short plain-language note on what the item could mean for index futures, written for an operator, not a headline reader.</p>
</div>
<div class="card">
<h3>Session continuity</h3>
<p>The watch never closes. What broke overnight is waiting in the feed before the bell, with nothing to piece together by hand.</p>
</div>
</div>
</section>

<section>
<h2>A look at the feed</h2>
<p class="prose" style="color:#aab1c3;margin-bottom:6px">Example layout of a scored wire feed.</p>
<div class="figure" role="img" aria-label="Illustration of a scored news feed with impact grades">
<div class="figure-head"><span>Wire feed, index futures</span><span class="tag">Illustration</span></div>
<div class="row"><span class="time">02:14</span><span class="headline">Central bank official signals data dependence in overnight remarks</span><span class="score md">Impact 6 / Mixed</span></div>
<div class="row"><span class="time">03:02</span><span class="headline">Energy inventory print comes in below the prior week's draw</span><span class="score hi">Impact 7 / Up lean</span></div>
<div class="row"><span class="time">04:38</span><span class="headline">Regional survey shows modest slowdown in new orders</span><span class="score lo">Impact 3 / Soft</span></div>
<div class="row"><span class="time">06:10</span><span class="headline">Pre-open economic agenda posted with consensus and prior values</span><span class="score md">Impact 5 / Watch</span></div>
</div>
<p class="disclaimer">Illustration only. Figures and headlines are sample layout, not market data or a signal. Korvus is information and education, not financial advice. Trading involves risk, and you can lose money.</p>
</section>

<section>
<h2>Start watching</h2>
<p class="prose" style="color:#c4c9d8">The Observer tier is free and gives you the terminal's core feed. Operator adds the full scored wire and the LodeStone TradingView indicator, included with the plan.</p>
<a class="cta" href="/signup">Open your account</a>
<p class="disclaimer">Korvus is market information and education only. Nothing on this page is a recommendation to buy or sell any instrument. Past scoring is not a promise of future results.</p>
</section>
</div>

<footer>
<div class="wrap" style="padding:0 20px">
<p>&copy; BlackCrownVxJ LLC. Korvus is a product of BlackCrownVxJ LLC. <a href="/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></p>
</div>
</footer>
</body>
</html>
