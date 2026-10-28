# Scribe: Author the complete standalone html document for a korvus marketing

Date: 2026-10-28
Task: Author the COMPLETE standalone html document for a Korvus marketing page selling the Operator annual plan, saved to the vault as pages/operator-annual.html
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Operator annual plan | BlackCrown</title>
<meta name="description" content="Korvus Operator annual plan: 79.99 a year with the LodeStone TradingView indicator, a 24/7 scored wire, futures board and session context. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/operator-annual">
<meta property="og:type" content="website">
<meta property="og:title" content="Korvus Operator annual plan">
<meta property="og:description" content="Operator annual at 79.99 a year. LodeStone TradingView, scored wire, futures board and session context for index futures traders.">
<meta property="og:url" content="https://korvus.industries/p/operator-annual">
<meta property="og:site_name" content="Korvus">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Korvus Operator annual plan">
<meta name="twitter:description" content="Operator annual at 79.99 a year. LodeStone TradingView, scored wire, futures board and session context.">
<style>
:root{--bg:#07070a;--panel:#0e0e14;--line:#22212d;--text:#e9e7ef;--muted:#9a97a8;--royal:#b8962e;--royal-hi:#e2c15a;--violet:#5b3fa0}
*{box-sizing:border-box}
html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
a{color:var(--royal-hi)}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px;color:var(--text);text-decoration:none}
.brand svg{width:34px;height:28px}
nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-size:14px}
nav a:hover{color:var(--royal-hi)}
.hero{padding:64px 0 40px;text-align:left}
.eyebrow{color:var(--royal);text-transform:uppercase;letter-spacing:.16em;font-size:12px;margin:0 0 14px}
h1{font-size:40px;line-height:1.15;margin:0 0 16px;font-weight:700}
.lede{color:var(--muted);font-size:18px;max-width:640px;margin:0 0 26px}
.btn{display:inline-block;background:linear-gradient(180deg,var(--royal-hi),var(--royal));color:#111;font-weight:700;text-decoration:none;padding:14px 26px;border-radius:6px;margin-right:12px;margin-bottom:10px}
.btn.ghost{background:transparent;color:var(--royal-hi);border:1px solid var(--royal)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:28px 0 8px;padding:0;list-style:none}
.chips li{border:1px solid var(--line);background:var(--panel);color:var(--text);padding:7px 14px;border-radius:999px;font-size:14px}
.chips li span{color:var(--royal-hi);margin-right:6px}
section{padding:40px 0;border-top:1px solid var(--line)}
h2{font-size:26px;margin:0 0 14px}
h3{font-size:17px;margin:0 0 8px;color:var(--royal-hi)}
p{margin:0 0 14px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:22px}
.price{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.plan{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:24px}
.plan.best{border-color:var(--royal);box-shadow:0 0 0 1px var(--royal) inset}
.plan .amt{font-size:34px;font-weight:700;margin:6px 0}
.plan .amt small{font-size:14px;color:var(--muted);font-weight:400}
.label{display:inline-block;background:var(--royal);color:#111;font-size:12px;font-weight:700;padding:3px 9px;border-radius:4px;letter-spacing:.05em;text-transform:uppercase}
.muted{color:var(--muted);font-size:14px}
ul.check{list-style:none;padding:0;margin:14px 0 0}
ul.check li{padding:6px 0 6px 24px;position:relative;border-bottom:1px dashed var(--line)}
ul.check li:before{content:"";position:absolute;left:2px;top:13px;width:10px;height:10px;background:var(--royal-hi);transform:rotate(45deg)}
.figure{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px}
.figure svg{width:100%;height:auto;display:block}
.figure .cap{color:var(--muted);font-size:13px;margin-top:10px}
.disclaimer{font-size:13px;color:var(--muted);border:1px solid var(--line);border-radius:8px;padding:16px 18px;background:#09090e}
.closing{text-align:center;padding:56px 0}
.closing blockquote{margin:0;font-size:24px;color:var(--royal-hi);font-style:italic}
footer{border-top:1px solid var(--line);padding:26px 0;color:var(--muted);font-size:13px}
footer .wrap{display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px}
footer a{color:var(--muted)}
@media (max-width:640px){h1{font-size:30px}.price{grid-template-columns:1fr}nav a{margin-left:12px}}
</style>
</head>
<body>
<header>
  <div class="wrap">
    <a class="brand" href="https://korvus.industries/">
      <svg viewBox="0 0 48 40" aria-hidden="true" focusable="false">
        <polygon points="6,30 10,12 18,22 24,8 30,22 38,12 42,30" fill="#b8962e"/>
        <rect x="6" y="32" width="36" height="4" fill="#e2c15a"/>
        <circle cx="24" cy="6" r="2.5" fill="#e2c15a"/>
      </svg>
      Korvus
    </a>
    <nav>
      <a href="https://korvus.industries/lodestone">LodeStone</a>
      <a href="https://korvus.industries/legal">Legal</a>
      <a href="https://korvus.industries/login">Log in</a>
    </nav>
  </div>
</header>

<main>
  <div class="hero wrap">
    <p class="eyebrow">Korvus Operator, annual</p>
    <h1>Korvus Operator annual plan</h1>
    <p class="lede">Market intelligence for index futures traders who trade their own book. Operator annual is 79.99 a year. Monthly is 9.99. That is about 33 percent saved over twelve months, and the LodeStone TradingView indicator is included.</p>
    <a class="btn" href="https://korvus.industries/signup">Start Operator annual</a>
    <a class="btn ghost" href="https://korvus.industries/lodestone">See LodeStone</a>
    <ul class="chips">
      <li><span>+</span>LodeStone TradingView included</li>
      <li><span>+</span>24/7 scored wire</li>
      <li><span>+</span>Futures board</li>
      <li><span>+</span>SMT divergence</li>
      <li><span>+</span>Session context</li>
    </ul>
  </div>

  <section class="wrap">
    <h2>The annual math</h2>
    <p class="muted">Figures as listed. Monthly billing at 9.99 across twelve months comes to 119.88. Annual is 79.99 for the year.</p>
    <div class="price">
      <div class="plan">
        <h3>Operator monthly</h3>
        <div class="amt">9.99 <small>per month</small></div>
        <p class="muted">Cancel any time. Twelve months adds up to 119.88.</p>
      </div>
      <div class="plan best">
        <span class="label">About 33 percent saved</span>
        <h3 style="margin-top:12px">Operator annual</h3>
        <div class="amt">79.99 <small>per year</small></div>
        <p class="muted">Everything in Operator, billed once a year.</p>
        <a class="btn" href="https://korvus.industries/signup">Choose annual</a>
      </div>
    </div>
  </section>

  <section class="wrap">
    <h2>What runs on the desk</h2>
    <div class="grid">
      <div class="card">
        <h3>LodeStone TradingView</h3>
        <p>The session level toolkit, built on ICT concepts for index futures. Included with Operator annual, so there is no separate TradingView subscription to add on top.</p>
      </div>
      <div class="card">
        <h3>24/7 scored wire</h3>
        <p>News scored for impact, direction and confidence, with a written Korvus read on each item. It runs while you sleep, so the overnight tape is not a blind spot.</p>
      </div>
      <div class="card">
        <h3>Futures board</h3>
        <p>One board for the index futures you watch, kept current by the same engine that scores the wire.</p>
      </div>
      <div class="card">
        <h3>SMT divergence</h3>
        <p>Cross-market divergence readings so you can see when related index futures stop agreeing with each other.</p>
      </div>
      <div class="card">
        <h3>Session context</h3>
        <p>Where you are in the session, which levels are in play and what has already traded. Context, not a signal.</p>
      </div>
    </div>
  </section>

  <section class="wrap">
    <h2>Session figure</h2>
    <div class="figure">
      <svg viewBox="0 0 600 220" role="img" aria-label="Illustrative session chart with level lines and a divergence marker">
        <rect x="0" y="0" width="600" height="220" fill="#07070a"/>
        <line x1="0" y1="60" x2="600" y2="60" stroke="#22212d" stroke-width="1"/>
        <line x1="0" y1="110" x2="600" y2="110" stroke="#22212d" stroke-width="1"/>
        <line x1="0" y1="160" x2="600" y2="160" stroke="#22212d" stroke-width="1"/>
        <line x1="0" y1="78" x2="600" y2="78" stroke="#b8962e" stroke-width="1.5" stroke-dasharray="6 5"/>
        <line x1="0" y1="140" x2="600" y2="140" stroke="#5b3fa0" stroke-width="1.5" stroke-dasharray="6 5"/>
        <polyline points="20,150 80,130 130,140 190,100 250,118 310,84 370,104 430,70 490,92 560,60" fill="none" stroke="#e2c15a" stroke-width="2.5"/>
        <polyline points="20,160 80,146 130,152 190,128 250,140 310,116 370,132 430,108 490,124 560,104" fill="none" stroke="#5b3fa0" stroke-width="2" opacity="0.8"/>
        <circle cx="430" cy="70" r="5" fill="#e2c15a"/>
        <rect x="446" y="42" width="120" height="22" rx="4" fill="#0e0e14" stroke="#b8962e"/>
        <text x="456" y="58" fill="#e9e7ef" font-size="12" font-family="system-ui,sans-serif">Divergence</text>
      </svg>
      <p class="cap">Illustration. Sample shapes only, not market data and not a live reading.</p>
    </div>
  </section>

  <section class="wrap">
    <h2>What Operator annual is</h2>
    <ul class="check">
      <li>Market intelligence terminal for index futures, built for the trader inside the arena.</li>
      <li>LodeStone TradingView indicator included at no extra charge with the plan.</li>
      <li>Scored wire and futures board running around the clock.</li>
      <li>SMT divergence and session context on the same screen.</li>
      <li>Annual billing at 79.99 a year. Monthly is 9.99 if you prefer to pay as you go.</li>
    </ul>
    <p style="margin-top:22px"><a class="btn" href="https://korvus.industries/signup">Start Operator annual</a></p>
  </section>

  <section class="wrap">
    <div class="disclaimer">
      <p><strong>Not financial advice.</strong> Korvus provides market information and education. Nothing on this page, in the wire, on the board or in LodeStone is a recommendation to buy, sell or hold any instrument, and nothing here is a promise of profit. Trading index futures involves substantial risk of loss and is not suitable for everyone. Past readings do not predict future results. Use your own judgment and your own risk rules.</p>
    </div>
  </section>

  <div class="closing wrap">
    <blockquote>A crown is not handed down, it is built.</blockquote>
    <p style="margin-top:22px"><a class="btn" href="https://korvus.industries/signup">Start Operator annual</a></p>
  </div>
</main>

<footer>
  <div class="wrap">
    <span>BlackCrownVxJ LLC. Korvus is a product of BlackCrown Intelligence.</span>
    <span><a href="https://korvus.industries/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></span>
  </div>
</footer>
</body>
</html>
