# Copy: Rewrite korvus index watch page as a lean complete html

Date: 2026-10-28
Task: Rewrite Korvus index-watch page as a lean complete html document, ending with the closing html tag
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Index Watch: Overnight Market Intelligence</title>
<meta name="description" content="Korvus watches index futures while you sleep. Scored news, session context, and a written read, 24/7. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080c;color:#e7e9ee;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #1d2130}
header svg{width:36px;height:36px}
.brand{font-weight:700;letter-spacing:.08em;color:#f2c14e}
main{max-width:880px;margin:0 auto;padding:40px 24px}
h1{font-size:2.1rem;line-height:1.2;margin-bottom:16px;color:#ffffff}
.hook{font-size:1.25rem;color:#f2c14e;margin-bottom:24px}
p{margin-bottom:16px;color:#b9bfcc}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:24px 0}
.chip{border:1px solid #2a3044;border-radius:999px;padding:6px 14px;font-size:.9rem;color:#dfe3ec;background:#0d1019}
.panel{border:1px solid #1d2130;border-radius:12px;background:#0b0e16;padding:20px;margin:28px 0}
.panel-label{font-size:.75rem;text-transform:uppercase;letter-spacing:.12em;color:#7d8599;margin-bottom:12px}
.panel svg{width:100%;height:auto;display:block}
.cta{display:inline-block;background:#f2c14e;color:#07080c;font-weight:700;text-decoration:none;padding:12px 22px;border-radius:8px;margin-top:8px}
.disclaimer{font-size:.85rem;color:#7d8599;margin-top:36px;border-top:1px solid #1d2130;padding-top:16px}
footer{text-align:center;color:#5d6478;font-size:.8rem;padding:24px}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 48 48" aria-hidden="true">
<path d="M6 36 L10 16 L18 26 L24 12 L30 26 L38 16 L42 36 Z" fill="#f2c14e"/>
<rect x="6" y="38" width="36" height="4" rx="1" fill="#f2c14e"/>
</svg>
<span class="brand">KORVUS</span>
</header>
<main>
<h1>The market moves at 3 a.m. Korvus watches index futures while you sleep.</h1>
<p class="hook">Your edge while the world sleeps.</p>
<p>Korvus is a 24/7 market intelligence terminal for index futures traders. It scans the wire around the clock, scores each headline for impact, direction, and confidence, and writes a plain Korvus read you can check in seconds. You set the agenda. Korvus keeps the watch.</p>

<div class="chips">
<span class="chip">24/7 wire coverage</span>
<span class="chip">Scored news</span>
<span class="chip">Session context</span>
<span class="chip">Written Korvus read</span>
<span class="chip">Free Observer tier</span>
</div>

<section class="panel" aria-label="Illustration of an overnight watch feed">
<div class="panel-label">Illustration</div>
<svg viewBox="0 0 640 220" role="img" aria-label="Illustrative overnight index chart with scored event markers">
<rect width="640" height="220" fill="#0b0e16"/>
<line x1="40" y1="180" x2="620" y2="180" stroke="#1d2130"/>
<line x1="40" y1="40" x2="40" y2="180" stroke="#1d2130"/>
<polyline fill="none" stroke="#f2c14e" stroke-width="3" points="40,140 90,128 140,134 190,112 240,120 290,96 340,104 390,80 440,88 490,64 540,72 590,50 620,58"/>
<circle cx="290" cy="96" r="6" fill="#ffffff"/>
<circle cx="490" cy="64" r="6" fill="#ffffff"/>
<text x="300" y="86" fill="#b9bfcc" font-size="13">Scored event</text>
<text x="500" y="56" fill="#b9bfcc" font-size="13">Scored event</text>
<text x="40" y="206" fill="#7d8599" font-size="12">Overnight session, illustrative only</text>
</svg>
</section>

<p>Operator adds the LodeStone TradingView indicator at no extra step, so the chart and the wire read from the same desk.</p>
<a class="cta" href="/signup">Start with the free Observer tier</a>

<p class="disclaimer">Not financial advice. Korvus provides market information and education only. Nothing on this page is a recommendation to buy or sell any instrument. Trading futures involves substantial risk of loss. Chart and feed visuals are illustrative.</p>
</main>
<footer>BlackCrownVxJ LLC. Korvus is a product of BlackCrown Intelligence.</footer>
</body>
</html>
