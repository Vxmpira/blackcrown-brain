# Scribe: Write the complete html document for korvus pages fair value

Date: 2026-10-28
Task: Write the COMPLETE html document for korvus:pages/fair-value-gaps.html, doctype through closing html tag, exactly one head, as a vault note I can file verbatim
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Fair Value Gap Explained for Index Futures Traders</title>
<meta name="description">
<meta name="description" content="What a fair value gap is, how the three candle pattern forms it, how traders use it, common beginner mistakes, and how Korvus shows session context around it.">
<link rel="canonical" href="https://korvus.industries/p/fair-value-gaps">
<meta property="og:type" content="article">
<meta property="og:title" content="Fair Value Gap Explained for Index Futures Traders">
<meta property="og:description" content="What a fair value gap is, how traders read it, common mistakes, and how Korvus adds session and macro context.">
<meta property="og:url" content="https://korvus.industries/p/fair-value-gaps">
<meta property="og:site_name" content="Korvus">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Fair Value Gap Explained for Index Futures Traders">
<meta name="twitter:description" content="What a fair value gap is, how traders read it, common mistakes, and session context.">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0b0b0d;color:#e6e6ea;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.65;font-size:17px}
a{color:#ff2d8f}
header{display:flex;align-items:center;gap:12px;padding:18px 24px;border-bottom:1px solid #22222a}
header svg{width:36px;height:33px}
.brand{font-weight:700;letter-spacing:.04em;color:#fff;text-decoration:none}
nav{margin-left:auto}
nav a{color:#9a9aa6;text-decoration:none;margin-left:18px;font-size:15px}
main{max-width:760px;margin:0 auto;padding:40px 24px 64px}
h1{font-size:2.1rem;line-height:1.2;color:#fff;margin-bottom:14px}
h2{font-size:1.4rem;color:#fff;margin:40px 0 12px}
p{margin-bottom:16px}
ul{margin:0 0 16px 22px}
li{margin-bottom:8px}
.lede{font-size:1.1rem;color:#c8c8d0}
figure{margin:28px 0;background:#121216;border:1px solid #22222a;border-radius:10px;padding:20px}
figure svg{width:100%;height:auto;display:block}
figcaption{font-size:14px;color:#8a8a96;margin-top:12px}
.tag{display:inline-block;font-size:12px;letter-spacing:.08em;text-transform:uppercase;color:#ff2d8f;border:1px solid #ff2d8f;border-radius:4px;padding:2px 7px;margin-right:6px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{background:#16161c;border:1px solid #2a2a34;border-radius:999px;padding:6px 14px;font-size:14px;color:#d0d0d8}
.panel{background:#121216;border:1px solid #22222a;border-radius:10px;padding:20px;margin:20px 0}
.cta{display:inline-block;margin:12px 0 8px;background:#ff2d8f;color:#0b0b0d;font-weight:700;text-decoration:none;padding:12px 22px;border-radius:6px}
.disclaimer{font-size:14px;color:#8a8a96;border-top:1px solid #22222a;margin-top:44px;padding-top:18px}
footer{text-align:center;font-size:13px;color:#66666f;padding:24px}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<a class="brand" href="https://korvus.industries/?utm_source=blackcrownvxj&utm_medium=seo&utm_campaign=fair-value-gaps">KORVUS</a>
<nav>
<a href="https://korvus.industries/lodestone?utm_source=blackcrownvxj&utm_medium=seo&utm_campaign=fair-value-gaps">LodeStone</a>
<a href="https://korvus.industries/signup?utm_source=blackcrownvxj&utm_medium=seo&utm_campaign=fair-value-gaps">Sign up</a>
</nav>
</header>

<main>
<span class="tag">ICT concepts</span>
<span class="tag">Index futures</span>
<h1>Fair Value Gap: What It Is and How Traders Read It</h1>
<p class="lede">A fair value gap, often shortened to FVG, is a gap in price left behind by a fast move. Traders mark these areas to watch how price returns to them. This page explains the idea plainly, the mistakes beginners make, and the context you need around it.</p>

<h2>What is a fair value gap?</h2>
<p>A fair value gap is a three candle pattern. The middle candle moves so fast that the wicks of the candles before and after it do not overlap. That empty space between them is the gap.</p>
<p>In a bullish fair value gap, the high of the first candle sits below the low of the third candle. The space between those two prices is the gap. In a bearish fair value gap, the low of the first candle sits above the high of the third candle.</p>
<p>Some traders call these imbalances. The idea is that price moved through the area with little trading, so the market may later revisit it. Revisiting is not guaranteed. A gap can stay open for a long time, or price can move away from it and never return.</p>

<figure>
<svg viewBox="0 0 400 240" role="img" aria-label="Illustration of a bullish fair value gap across three candles">
<rect x="0" y="0" width="400" height="240" fill="#0b0b0d"/>
<line x1="60" y1="40" x2="60" y2="180" stroke="#55555f" stroke-width="2"/>
<rect x="44" y="90" width="32" height="60" fill="#3a3a44" stroke="#8a8a96" stroke-width="1.5"/>
<line x1="200" y1="30" x2="200" y2="200" stroke="#ff2d8f" stroke-width="2"/>
<rect x="184" y="70" width="32" height="90" fill="#ff2d8f"/>
<line x1="340" y1="40" x2="340" y2="170" stroke="#55555f" stroke-width="2"/>
<rect x="324" y="60" width="32" height="50" fill="#3a3a44" stroke="#8a8a96" stroke-width="1.5"/>
<rect x="60" y="90" width="264" height="30" fill="#ff2d8f" fill-opacity="0.18" stroke="#ff2d8f" stroke-width="1" stroke-dasharray="4 4"/>
<text x="70" y="112" fill="#e6e6ea" font-size="13" font-family="system-ui,sans-serif">Fair value gap</text>
<text x="20" y="228" fill="#8a8a96" font-size="12" font-family="system-ui,sans-serif">Illustration. Not real market data.</text>
</svg>
<figcaption><span class="tag">Illustration</span> Three candles. The first candle's high sits below the third candle's low, leaving an open band in the middle. The shaded band marks the gap.</figcaption>
</figure>

<h2>How to spot one</h2>
<ul>
<li>Find a strong impulsive candle. Its body is large and its range is wide.</li>
<li>Check the candle before it and the candle after it.</li>
<li>Look for an empty price band between the first and third candle wicks.</li>
<li>Mark the top and bottom of that band. That is the gap zone.</li>
</ul>
<p>Most charts show many gaps. Not all of them matter. Size, location, and the broader trend change how useful a gap is for reading the market.</p>

<h2>How traders use fair value gaps</h2>
<p>Traders use fair value gaps as reference zones. They are areas to watch, not buttons to press. Common uses include:</p>
<ul>
<li>Marking where price may react when it returns to the zone.</li>
<li>Checking whether a move has left unfilled space above or below.</li>
<li>Comparing gaps across timeframes, such as a five minute gap inside a larger hourly one.</li>
<li>Building a written plan before the session, so the zone is not chosen in the heat of a move.</li>
</ul>
<p>A gap is one piece of a read. It does not tell you direction, timing, or size on its own.</p>

<h2>Common beginner mistakes</h2>
<div class="panel">
<ul>
<li><strong>Treating every gap as a signal.</strong> Many gaps are noise. Mark them, then wait for context.</li>
<li><strong>Ignoring the trend.</strong> A bullish gap inside a strong downtrend behaves differently from one inside an uptrend.</li>
<li><strong>Trading without a stop plan.</strong> Price can move through a gap and keep going. Know your exit before entry.</li>
<li><strong>Marking too many zones.</strong> A chart full of boxes shows nothing. Keep only the gaps that matter to your plan.</li>
<li><strong>Forgetting the timeframe.</strong> A gap on a one minute chart is not the same as a gap on a daily chart.</li>
<li><strong>Chasing a fill.</strong> Waiting for price to come back is a plan. Rushing into the zone because you expect it to fill is a bet.</li>
</ul>
</div>

<h2>How Korvus shows session and macro context</h2>
<p>A fair value gap read without context is easy to misjudge. Korvus is built to show the surrounding conditions so you can judge a zone in its setting. These are the layers traders commonly look at:</p>
<div class="chips">
<span class="chip">Session highs and lows</span>
<span class="chip">Prior day levels</span>
<span class="chip">Prior week levels</span>
<span class="chip">Session timing</span>
<span class="chip">Economic calendar</span>
<span class="chip">Scored news flow</span>
<span class="chip">Premium and discount context</span>
</div>
<p>Session context shows where a gap sits relative to the open, the overnight range, and the prior day's levels. Macro context shows whether scheduled data or news may be moving the market near the zone. Korvus presents these as information to read, not as instructions to act.</p>
<p>The LodeStone TradingView indicator, included with Korvus Operator, draws session levels and related layers directly on your chart. Its features and inputs are described on the LodeStone page.</p>

<div class="panel">
<p><strong>Want the context around your charts?</strong> Korvus runs around the clock and keeps the session and macro layers in one place. The Observer tier is free.</p>
<a class="cta" href="https://korvus.industries/signup?utm_source=blackcrownvxj&utm_medium=seo&utm_campaign=fair-value-gaps">Create a free Korvus account</a>
</div>

<div class="disclaimer">
<p>Not financial advice. Nothing on this page is a recommendation to buy, sell, or hold any instrument, and no outcome is promised or predicted. Index futures carry substantial risk of loss and are not suitable for everyone. Examples and figures are illustrations, not real market data. Practice on a simulator and make your own decisions.</p>
<p>BlackCrownVxJ LLC. Korvus is a market intelligence terminal. Questions: BlackCrownVxJ.LLC@outlook.com</p>
</div>
</main>

<footer>
<p>&copy; BlackCrownVxJ LLC. A crown is not handed down, it is built.</p>
</footer>
</body>
</html>
