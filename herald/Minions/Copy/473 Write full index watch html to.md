# Copy: Write full index watch html to vault note report path

Date: 2026-10-28
Task: Write full index-watch html to vault note, report path and last line
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | Korvus, 24/7 Index Futures Intelligence</title>
<meta name="description" content="Korvus Index Watch: a 24/7 market intelligence feed for index futures traders. Free Observer tier. Operator adds the LodeStone TradingView indicator.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080c;color:#e7e9ee;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
a{color:#c9a84c;text-decoration:none}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1d2030;padding:18px 0}
header .wrap{display:flex;align-items:center;gap:12px}
header .name{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
header svg{width:34px;height:34px}
h1{font-size:40px;line-height:1.15;margin:48px 0 14px;letter-spacing:-.01em}
h2{font-size:24px;margin:44px 0 12px}
p{margin-bottom:14px;color:#c6cad4}
.lede{font-size:19px;color:#e7e9ee}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chip{border:1px solid #2a2f44;background:#0d0f17;border-radius:999px;padding:6px 12px;font-size:13px;color:#b9bfd0}
.panel{background:#0d0f17;border:1px solid #1d2030;border-radius:12px;padding:22px;margin:28px 0}
.tag{display:inline-block;font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:#c9a84c;margin-bottom:10px}
.feed{font-family:ui-monospace,Menlo,Consolas,monospace;font-size:13px;color:#b9bfd0}
.feed div{padding:8px 0;border-bottom:1px solid #161a27}
.feed div:last-child{border-bottom:0}
.up{color:#6fd39a}.dn{color:#e07a7a}.nt{color:#c9a84c}
.cols{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:20px}
.card{background:#0d0f17;border:1px solid #1d2030;border-radius:12px;padding:22px}
.card h3{font-size:18px;margin-bottom:8px}
.card ul{list-style:none;margin:10px 0 0}
.card li{padding:5px 0;color:#c6cad4;font-size:15px}
.card li:before{content:"- ";color:#c9a84c}
.btn{display:inline-block;background:#c9a84c;color:#07080c;font-weight:700;padding:12px 20px;border-radius:8px;margin-top:14px}
.btn.ghost{background:transparent;color:#c9a84c;border:1px solid #c9a84c}
.note{font-size:12px;color:#8a90a3;margin-top:10px}
.caption{font-style:italic;color:#e7e9ee;border-left:2px solid #c9a84c;padding-left:14px;margin:18px 0}
footer{border-top:1px solid #1d2030;margin-top:60px;padding:26px 0;color:#8a90a3;font-size:13px}
footer p{color:#8a90a3;font-size:13px;margin-bottom:8px}
@media(max-width:700px){h1{font-size:30px}.cols{grid-template-columns:1fr}}
</style>
</head>
<body>
<header>
<div class="wrap">
<svg viewBox="0 0 48 48" aria-hidden="true"><polygon points="6,34 10,16 18,26 24,12 30,26 38,16 42,34" fill="none" stroke="#c9a84c" stroke-width="2.5" stroke-linejoin="round"/><rect x="8" y="36" width="32" height="4" fill="#c9a84c"/><circle cx="24" cy="10" r="2.5" fill="#c9a84c"/></svg>
<span class="name">Korvus</span>
</div>
</header>

<main class="wrap">
<h1>Index Watch. The market, watched while you sleep.</h1>
<p class="lede">Korvus Index Watch is a 24/7 market intelligence feed for index futures traders. It scores the wire, flags what moves the open, and writes a plain read you can check against your own chart.</p>

<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Scored news wire</span>
<span class="chip">Written Korvus read</span>
<span class="chip">USD economic agenda</span>
<span class="chip">Free Observer tier</span>
</div>

<section class="panel" aria-label="Illustration of the Index Watch feed">
<span class="tag">Illustration</span>
<div class="feed">
<div><span class="nt">21:04</span> Wire item scored: impact HIGH, direction <span class="up">UP</span>, confidence MED. Korvus read: headline sensitivity sits in the overnight range.</div>
<div><span class="nt">21:32</span> Agenda event queued: USD data, 08:30 ET. Consensus logged. Actual pending.</div>
<div><span class="nt">22:10</span> Wire item scored: impact LOW, direction <span class="dn">DOWN</span>, confidence LOW. Noted, no action flag.</div>
<div><span class="nt">02:47</span> Session watch: overnight high tested. Level flagged for the London open read.</div>
</div>
<svg viewBox="0 0 640 140" width="100%" role="img" aria-label="Illustrative price path with flagged levels" style="margin-top:18px">
<rect width="640" height="140" fill="#07080c"/>
<line x1="0" y1="40" x2="640" y2="40" stroke="#1d2030"/>
<line x1="0" y1="90" x2="640" y2="90" stroke="#1d2030"/>
<polyline points="10,100 70,88 120,96 180,70 230,78 290,52 340,62 400,44 450,58 510,36 570,48 630,30" fill="none" stroke="#c9a84c" stroke-width="2.5"/>
<text x="10" y="34" fill="#8a90a3" font-size="11" font-family="monospace">overnight high</text>
<text x="10" y="128" fill="#8a90a3" font-size="11" font-family="monospace">Illustration, not live data</text>
</svg>
</section>

<div class="caption">The all seeing watcher. Your market never closes, and neither does the read.</div>

<h2>What the watcher covers</h2>
<p>Index Watch runs the wire around the clock, so overnight headlines reach you with a score and a written read instead of a raw stream. The USD economic agenda posts with consensus and live actuals as they land. Session levels are marked so you can see where the overnight range stood when the cash session opened.</p>
<p>It is a reading tool. It does not tell you what to buy, sell, or when. Every read is information for your own analysis.</p>

<h2>Choose your tier</h2>
<div class="cols">
<div class="card">
<h3>Observer, free</h3>
<p>See the feed, the scored wire, and the public agenda. Start without a card.</p>
<ul>
<li>Live scored wire</li>
<li>Daily USD agenda</li>
<li>Session level marks</li>
</ul>
<a class="btn ghost" href="/signup">Start free</a>
</div>
<div class="card">
<h3>Operator</h3>
<p>Everything in Observer, plus the full terminal and the LodeStone TradingView indicator included.</p>
<ul>
<li>Full terminal access</li>
<li>LodeStone TradingView indicator included</li>
<li>Annual plan listed first, with the savings shown at checkout</li>
</ul>
<a class="btn" href="/upgrade">Go Operator</a>
<p class="note">Annual is the better value against monthly. The savings label is calculated at checkout.</p>
</div>
</div>

<h2>Built to be checked</h2>
<p>Korvus is pre profit and built in the open. Read the scores, test the reads against your own charts, and keep what holds up. No feature here promises a result, and no tier offers unlimited anything.</p>

<p class="note">Not financial advice. Korvus provides market information and education for index futures traders. Trading involves substantial risk of loss. Past readings do not predict future results.</p>
</main>

<footer>
<div class="wrap">
<p>BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
<p><a href="/legal">Legal</a> | <a href="/lodestone">LodeStone</a> | <a href="/">Korvus home</a></p>
<p>A crown is not handed down, it is built.</p>
</div>
</footer>
</body>
</html>
