# Copy: Rewrite index watch page as compact spec under 4000 characters

Date: 2026-10-28
Task: Rewrite index-watch page as compact spec under 4000 characters, full text to vault note
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch: Korvus Market Spec</title>
<meta name="description" content="Index Watch is a compact spec for how Korvus tracks ES, NQ, YM and RTY around the clock. Information only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
body{margin:0;background:#07080c;color:#e8e9ee;font-family:system-ui,Segoe UI,Arial,sans-serif;line-height:1.5}
header{display:flex;align-items:center;gap:12px;padding:18px 24px;border-bottom:1px solid #1d2030}
header span{font-weight:700;letter-spacing:.08em}
main{max-width:860px;margin:0 auto;padding:28px 24px}
h1{font-size:28px;margin:0 0 8px}
h2{font-size:18px;margin:28px 0 8px;color:#c9ccd8}
p,li{color:#b7bac8}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:14px 0}
.chip{border:1px solid #2a2e44;border-radius:999px;padding:4px 12px;font-size:13px;color:#d6d9e6}
table{width:100%;border-collapse:collapse;font-size:14px}
td,th{border-bottom:1px solid #1d2030;padding:8px;text-align:left}
th{color:#8f94a8;font-weight:600}
.mock{background:#0d0f17;border:1px solid #232740;border-radius:10px;padding:16px;margin:20px 0}
.tag{font-size:12px;color:#8f94a8;text-transform:uppercase;letter-spacing:.08em}
.up{color:#7fd6a4}.dn{color:#e18a8a}
.cta{display:inline-block;margin-top:16px;background:#e8e9ee;color:#07080c;padding:10px 18px;border-radius:6px;text-decoration:none;font-weight:700}
footer{max-width:860px;margin:0 auto;padding:20px 24px 40px;font-size:12px;color:#7d8196;border-top:1px solid #1d2030}
</style>
</head>
<body>
<header>
<svg width="28" height="28" viewBox="0 0 32 32" aria-hidden="true"><polygon points="4,24 6,10 12,17 16,7 20,17 26,10 28,24" fill="#e8e9ee"/><rect x="4" y="25" width="24" height="3" fill="#e8e9ee"/></svg>
<span>KORVUS</span>
</header>
<main>
<div class="tag">Index Watch, spec</div>
<h1>Index Watch</h1>
<p>Index Watch is the compact view Korvus uses to keep four index futures in one place: ES, NQ, YM and RTY. It is a monitoring spec, not a signal service. It shows what changed, when, and what the wire recorded.</p>
<div class="chips"><span class="chip">ES</span><span class="chip">NQ</span><span class="chip">YM</span><span class="chip">RTY</span><span class="chip">24/7 coverage</span></div>

<h2>What the watch tracks</h2>
<ul>
<li>Session state for Asia, London and New York</li>
<li>Prior day and prior week reference levels</li>
<li>Scored wire events with impact, direction and confidence</li>
<li>Economic agenda items and live actuals</li>
</ul>

<h2>Illustration: watch board layout</h2>
<div class="mock">
<div class="tag">Illustration, sample data, not live</div>
<table>
<tr><th>Contract</th><th>Session</th><th>Wire events</th><th>State</th></tr>
<tr><td>ES</td><td>New York</td><td>3</td><td class="up">Tracking</td></tr>
<tr><td>NQ</td><td>New York</td><td>2</td><td class="up">Tracking</td></tr>
<tr><td>YM</td><td>London</td><td>1</td><td class="dn">Review</td></tr>
<tr><td>RTY</td><td>Asia</td><td>0</td><td class="up">Tracking</td></tr>
</table>
</div>

<h2>How it runs</h2>
<p>The watch refreshes continuously. Each event carries a timestamp, so you can line it up against your own charts. Nothing on this page is a recommendation to buy or sell any instrument.</p>

<a class="cta" href="https://korvus.industries/signup">Start on the free Observer tier</a>
</main>
<footer>Information only, not financial advice. Futures trading involves substantial risk of loss. Past readings do not predict future results. BlackCrownVxJ LLC.</footer>
</body>
</html>
