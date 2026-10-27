# Copy: Write complete index watch html into a new readable note

Date: 2026-10-27
Task: Write complete index-watch html into a new readable note
For [[Herald]].

<!doctype html>
<!-- Index watch page. Operator annual figure per the filing ask; the live Korvus landing still injects prices server side. Serves at /p/index-watch. -->
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures Watch 24/7 | Korvus</title>
<meta name="description" content="Korvus watches index futures around the clock with scored market intelligence. Operator annual includes the LodeStone TradingView indicator. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<meta name="robots" content="index, follow">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080b;color:#e7e9ee;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;font-size:16px}
a{color:#c9a94a;text-decoration:none}
a:hover{text-decoration:underline}
header{display:flex;align-items:center;gap:12px;padding:18px 24px;border-bottom:1px solid #1d2028}
header .brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px;color:#e7e9ee}
header svg{width:36px;height:33px;fill:#c9a94a}
main{max-width:920px;margin:0 auto;padding:48px 24px 64px}
h1{font-size:clamp(28px,5vw,44px);line-height:1.15;margin-bottom:18px;letter-spacing:-.01em}
h2{font-size:22px;margin:40px 0 12px;color:#e7e9ee}
p{margin-bottom:14px;color:#b9bec9}
.lead{font-size:19px;color:#e7e9ee}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0 8px}
.chip{border:1px solid #2a2e38;background:#0d0f14;padding:6px 12px;border-radius:999px;font-size:13px;color:#c9ced8}
.panel{background:#0d0f14;border:1px solid #1d2028;border-radius:10px;padding:22px;margin:28px 0}
.panel .tag{display:inline-block;font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:#c9a94a;margin-bottom:10px}
.feed{list-style:none;font-family:ui-monospace,Menlo,Consolas,monospace;font-size:13px;color:#aab1bf}
.feed li{padding:8px 0;border-bottom:1px solid #161920}
.feed li:last-child{border-bottom:none}
.feed .t{color:#6f7787;margin-right:10px}
.feed .up{color:#7fd6a0}
.feed .dn{color:#e08a8a}
svg.chart{width:100%;height:auto;display:block;margin-top:10px}
.caption{font-size:12px;color:#6f7787;margin-top:8px}
.plans{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-top:20px}
.card{background:#0d0f14;border:1px solid #1d2028;border-radius:10px;padding:22px}
.card h3{font-size:17px;margin-bottom:6px}
.card .price{font-size:26px;font-weight:700;color:#e7e9ee;margin:8px 0}
.card .price small{font-size:13px;color:#6f7787;font-weight:400}
.card ul{list-style:none;margin:12px 0 18px}
.card li{padding:4px 0;color:#b9bec9;font-size:14px}
.card li::before{content:"-  ";color:#c9a94a}
.btn{display:inline-block;background:#c9a94a;color:#07080b;font-weight:700;padding:12px 20px;border-radius:6px;font-size:15px}
.btn:hover{text-decoration:none;filter:brightness(1.08)}
.badge{display:inline-block;font-size:12px;color:#7fd6a0;margin-left:6px}
.disclaimer{font-size:13px;color:#7d8494;border-top:1px solid #1d2028;margin-top:44px;padding-top:18px}
footer{border-top:1px solid #1d2028;padding:22px 24px;font-size:13px;color:#6f7787;text-align:center}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" aria-hidden="true" focusable="false">
<path d="M4 26 L6 10 L12 17 L18 6 L24 17 L30 10 L32 26 Z"/>
<rect x="5" y="28" width="26" height="3" rx="1"/>
<circle cx="18" cy="3.5" r="2"/>
</svg>
<span class="brand">Korvus</span>
</header>

<main>
<h1>The market moves at 3 a.m. Korvus watches index futures while you sleep.</h1>
<p class="lead">Korvus is a 24/7 market intelligence terminal built for index futures traders. Every headline that can move the tape gets scored for impact, direction, and confidence, with a written Korvus read attached, so you can see what changed before the open.</p>

<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Scored news feed</span>
<span class="chip">USD economic agenda</span>
<span class="chip">LodeStone included with Operator</span>
</div>

<section class="panel" aria-labelledby="feed-title">
<span class="tag">Illustration</span>
<h2 id="feed-title" style="margin-top:6px">Overnight wire, sample layout</h2>
<ul class="feed">
<li><span class="t">02:14</span>Headline scored: impact high, direction <span class="dn">down</span>, confidence medium. Korvus read: risk-off tone builds into Asia.</li>
<li><span class="t">03:40</span>Headline scored: impact medium, direction <span class="up">up</span>, confidence high. Korvus read: breadth improving in futures overnight.</li>
<li><span class="t">05:05</span>USD agenda item released. Actual posted against forecast in the terminal feed.</li>
<li><span class="t">07:30</span>Session levels refreshed for the open. Prior day and week levels carried forward.</li>
</ul>
<p class="caption">Illustration: this layout is a sample of the feed format, not a record of real market events or live data.</p>
</section>

<section aria-labelledby="watch-title">
<h2 id="watch-title">What the watch covers</h2>
<p>The overnight session is where index futures often move while most traders are offline. Korvus keeps the wire running through that window, so the scoring and the written read are waiting when you return to the screen.</p>
<p>Nothing is automated into a trade. Korvus gives you structured information and a clear read. What you do with it is your decision.</p>
</section>

<section aria-labelledby="plans-title">
<h2 id="plans-title">Plans</h2>
<div class="plans">
<div class="card">
<h3>Observer</h3>
<div class="price">Free</div>
<ul>
<li>Market intelligence feed</li>
<li>Core terminal access</li>
</ul>
<a class="btn" href="https://korvus.industries/signup?utm_source=site&amp;utm_medium=page&amp;utm_campaign=index-watch&amp;utm_content=observer">Start free</a>
</div>
<div class="card">
<h3>Operator <span class="badge">Annual</span></h3>
<div class="price">79.99 <small>a year</small></div>
<ul>
<li>Full 24/7 terminal</li>
<li>Scored news feed with Korvus reads</li>
<li>USD economic agenda with live actuals</li>
<li>LodeStone TradingView indicator included</li>
</ul>
<a class="btn" href="https://korvus.industries/upgrade?utm_source=site&amp;utm_medium=page&amp;utm_campaign=index-watch&amp;utm_content=operator-annual">Go Operator annual</a>
</div>
</div>
</section>

<section aria-labelledby="faq-title">
<h2 id="faq-title">Questions</h2>
<p><strong>Is this financial advice?</strong> No. Korvus provides market information, scoring, and educational reads. It does not tell you what to buy, sell, or hold, and it makes no promises about results.</p>
<p><strong>What does LodeStone add?</strong> LodeStone is the session level toolkit on the chart side of the Korvus stack. Operator includes the TradingView version.</p>
<p><strong>Can I cancel?</strong> Plan terms and cancellation are shown at checkout before you pay.</p>
</section>

<p class="disclaimer">Not financial advice. Trading index futures involves substantial risk of loss and is not suitable for every investor. Korvus and LodeStone are analysis tools. Past performance and illustrative material do not guarantee future results. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
</main>

<footer>
<p>BlackCrownVxJ LLC. Korvus is a product of BlackCrown Intelligence. A crown is not handed down, it is built.</p>
</footer>
</body>
</html>
