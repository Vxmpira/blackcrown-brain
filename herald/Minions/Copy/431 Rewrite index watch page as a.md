# Copy: Rewrite index watch page as a vault note under 6000

Date: 2026-10-28
Task: Rewrite index-watch page as a vault note, under 6000 characters
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="vault-path" content="vault/pages/index-watch.html">
<title>Index Watch | Korvus Industries</title>
<meta name="description" content="Index Watch: 24/7 market intelligence for index futures traders. Scored news, session context, and Operator with LodeStone included.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080b;color:#e6e8ee;font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
a{color:#c9a84c;text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #1d2028}
header h1{font-size:18px;letter-spacing:.08em;text-transform:uppercase}
main{max-width:860px;margin:0 auto;padding:32px 24px 64px}
h2{font-size:22px;margin:36px 0 12px;color:#fff}
p{margin-bottom:14px;color:#b9bec9}
ul{margin:0 0 14px 20px;color:#b9bec9}
li{margin-bottom:6px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:14px 0}
.chip{border:1px solid #2a2f3a;border-radius:999px;padding:4px 12px;font-size:13px;color:#c9ced8}
.panel{background:#0c0e13;border:1px solid #1d2028;border-radius:10px;padding:20px;margin:24px 0}
.panel-head{display:flex;justify-content:space-between;font-size:13px;color:#8a909c;margin-bottom:12px}
.tag{color:#c9a84c;text-transform:uppercase;letter-spacing:.06em}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px}
.card{background:#0c0e13;border:1px solid #1d2028;border-radius:10px;padding:18px}
.card h3{font-size:16px;color:#fff;margin-bottom:6px}
.price{font-size:26px;color:#fff;margin:6px 0}
.note{font-size:13px;color:#8a909c}
.btn{display:inline-block;margin-top:10px;background:#c9a84c;color:#07080b;padding:10px 18px;border-radius:6px;font-weight:600}
.btn:hover{text-decoration:none;opacity:.9}
.disclaimer{margin-top:40px;font-size:13px;color:#7c828e;border-top:1px solid #1d2028;padding-top:16px}
footer{text-align:center;padding:24px;font-size:13px;color:#6b717d;border-top:1px solid #1d2028}
</style>
</head>
<body>
<header>
<svg width="36" height="36" viewBox="0 0 48 48" aria-hidden="true">
<path d="M8 36 L8 18 L16 26 L24 12 L32 26 L40 18 L40 36 Z" fill="none" stroke="#c9a84c" stroke-width="2.5" stroke-linejoin="round"/>
<circle cx="24" cy="30" r="3" fill="#c9a84c"/>
</svg>
<h1>Korvus Industries</h1>
</header>
<main>
<p class="tag">Index Watch</p>
<h2>Index futures, watched while you sleep</h2>
<p>Index Watch is the Korvus view of the index futures tape. The terminal runs around the clock, scoring incoming news by impact, direction, and confidence, then pairing each item with a written Korvus read. You start the session with the context already assembled.</p>
<div class="chips">
<span class="chip">24/7 terminal</span>
<span class="chip">Scored news wire</span>
<span class="chip">Session context</span>
<span class="chip">Economic agenda</span>
<span class="chip">LodeStone included</span>
</div>

<h2>What the watch covers</h2>
<ul>
<li>Overnight headlines that move index futures, scored and ranked before the open.</li>
<li>Presidential Wire items with impact, direction, and confidence attached.</li>
<li>The daily USD economic agenda, with actuals as they print.</li>
<li>Session levels and context from the LodeStone toolkit, on your chart.</li>
</ul>

<div class="panel" aria-label="Illustration only">
<div class="panel-head"><span class="tag">Illustration</span><span>Sample wire, not live data</span></div>
<svg viewBox="0 0 640 180" width="100%" role="img" aria-label="Illustrative impact score bars">
<line x1="30" y1="150" x2="620" y2="150" stroke="#1d2028" stroke-width="1"/>
<rect x="60" y="92" width="60" height="58" fill="#3a4150"/>
<rect x="150" y="60" width="60" height="90" fill="#c9a84c"/>
<rect x="240" y="104" width="60" height="46" fill="#3a4150"/>
<rect x="330" y="40" width="60" height="110" fill="#c9a84c"/>
<rect x="420" y="78" width="60" height="72" fill="#3a4150"/>
<rect x="510" y="112" width="60" height="38" fill="#3a4150"/>
<text x="60" y="170" fill="#7c828e" font-size="12">09:30</text>
<text x="150" y="170" fill="#7c828e" font-size="12">09:45</text>
<text x="240" y="170" fill="#7c828e" font-size="12">10:00</text>
<text x="330" y="170" fill="#7c828e" font-size="12">10:15</text>
<text x="420" y="170" fill="#7c828e" font-size="12">10:30</text>
<text x="510" y="170" fill="#7c828e" font-size="12">10:45</text>
</svg>
</div>

<h2>Plans</h2>
<div class="grid">
<div class="card">
<h3>Observer</h3>
<div class="price">Free</div>
<p class="note">Core terminal access to get started.</p>
<a class="btn" href="https://korvus.industries/signup">Start free</a>
</div>
<div class="card">
<h3>Operator, annual</h3>
<div class="price">79.99 a year</div>
<p class="note">Saves 39.89 against 12 months at 9.99. LodeStone TradingView indicator included.</p>
<a class="btn" href="https://korvus.industries/signup">Get Operator</a>
</div>
<div class="card">
<h3>Operator, monthly</h3>
<div class="price">9.99 a month</div>
<p class="note">Same access, billed monthly. LodeStone TradingView indicator included.</p>
<a class="btn" href="https://korvus.industries/signup">Get Operator</a>
</div>
</div>

<h2>Built to be read, not trusted blindly</h2>
<p>Korvus gives you a faster read on what is happening. The decision stays with you. Every scored item shows its reasoning so you can check it against your own process.</p>

<p class="disclaimer">Not financial advice. Korvus provides market information and education for traders. Nothing on this page is a recommendation to buy or sell any instrument. Index futures involve substantial risk of loss. Past readings do not predict future results. Figures shown in the illustration are sample data, not live market output.</p>
</main>
<footer>BlackCrownVxJ LLC. Your edge while the world sleeps. <a href="https://korvus.industries/legal">Legal</a></footer>
</body>
</html>
