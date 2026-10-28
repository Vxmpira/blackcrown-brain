# Scribe: Author a complete standalone html page on fair value gaps

Date: 2026-10-28
Task: Author a COMPLETE standalone html page on fair value gaps for index futures, saved to the vault as korvus-fvg-page.md, ready to serve at /p/fair-value-gaps
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Fair Value Gaps on Index Futures | Korvus</title>
<meta name="description" content="How fair value gaps form on index futures, what the ICT framing claims, and how Korvus shows session context around price. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/fair-value-gaps">
<style>
:root{--bg:#07080c;--panel:#0e1119;--line:#1d2433;--text:#d9dee8;--muted:#8a94a8;--gold:#d4a93c;--green:#3fbf7f;--red:#d25b5b}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;font-size:17px}
header{display:flex;align-items:center;gap:14px;padding:18px 24px;border-bottom:1px solid var(--line);background:#050609}
header .brand{font-weight:700;letter-spacing:.04em;color:var(--gold)}
header nav{margin-left:auto;display:flex;gap:16px;flex-wrap:wrap}
header nav a{color:var(--muted);text-decoration:none;font-size:15px}
header nav a:hover{color:var(--text)}
main{max-width:860px;margin:0 auto;padding:32px 24px 56px}
h1{font-size:2.1rem;line-height:1.2;margin:8px 0 14px;color:#fff}
h2{font-size:1.35rem;margin:40px 0 12px;color:var(--gold)}
p{margin:0 0 14px}
ul{margin:0 0 14px;padding-left:20px}
li{margin-bottom:6px}
.lede{font-size:1.1rem;color:var(--text)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px}
figure{margin:28px 0;background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:16px}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:14px;margin-top:10px}
.tag{display:inline-block;font-size:12px;letter-spacing:.06em;text-transform:uppercase;color:var(--gold);border:1px solid var(--gold);border-radius:4px;padding:1px 6px;margin-right:6px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{background:#141a27;border:1px solid var(--line);border-radius:999px;padding:6px 12px;font-size:14px;color:var(--text)}
.note{border-left:3px solid var(--red);padding:12px 16px;background:#120d0f;color:var(--muted);font-size:15px;border-radius:0 8px 8px 0}
.cta{text-align:center;margin:40px 0 0;padding:28px;background:var(--panel);border:1px solid var(--line);border-radius:12px}
.btn{display:inline-block;background:var(--gold);color:#120e02;font-weight:700;text-decoration:none;padding:12px 22px;border-radius:8px;margin-top:10px}
.btn:hover{filter:brightness(1.08)}
footer{border-top:1px solid var(--line);padding:22px 24px;color:var(--muted);font-size:14px;text-align:center}
footer a{color:var(--muted)}
</style>
</head>
<body>
<header>
<svg width="34" height="30" viewBox="0 0 34 30" aria-hidden="true">
<polygon points="4,24 4,10 10,16 17,4 24,16 30,10 30,24" fill="#d4a93c"/>
<rect x="4" y="24" width="26" height="3" fill="#b88a2a"/>
<circle cx="17" cy="19" r="2" fill="#07080c"/>
</svg>
<span class="brand">KORVUS</span>
<nav>
<a href="https://korvus.industries/">Home</a>
<a href="https://korvus.industries/lodestone">LodeStone</a>
<a href="https://korvus.industries/signup">Sign up</a>
<a href="https://korvus.industries/legal">Legal</a>
</nav>
</header>

<main>
<p><span class="tag">Education</span><span class="tag">ICT concepts</span></p>
<h1>Fair value gaps on index futures</h1>
<p class="lede">A fair value gap is a three candle pattern where price moves so quickly that it leaves an empty space between the candles. ICT traders watch these spaces closely. This page explains what the pattern is, how it shows up on index futures, and what Korvus shows around it. It is education, not a signal.</p>

<h2>What the pattern is</h2>
<p>A fair value gap, often shortened to FVG, needs three consecutive candles on a chosen timeframe.</p>
<ul>
<li><strong>Bullish FVG:</strong> the low of the third candle sits above the high of the first candle. The empty space between those two prices is the gap.</li>
<li><strong>Bearish FVG:</strong> the high of the third candle sits below the low of the first candle. The empty space between those two prices is the gap.</li>
<li><strong>The middle candle</strong> is the displacement candle. It moved hard enough, in one direction, to leave the gap behind.</li>
</ul>
<p>The gap is a visual fact on the chart. Whether it matters is a separate question, and that is where most of the debate lives.</p>

<h2>The ICT framing, stated plainly</h2>
<p>The ICT framing says that price delivered inefficiently often returns to rebalance that inefficiency. Under that view, a fair value gap is a zone price may revisit. Traders who use the framing mark the gap, then watch how price behaves when it arrives there.</p>
<p>That is a claim to test, not a law. Some gaps get filled quickly. Many do not. Some get filled and keep going. A gap on its own tells you that price moved fast. It does not tell you what happens next.</p>

<h2>Why index futures are different</h2>
<p>Index futures such as ES and NQ trade around the clock. The same chart can hold gaps formed in very different conditions. A few factors shape how gaps read:</p>
<ul>
<li><strong>Session handoffs.</strong> A gap formed during the London session often reads differently from one formed at the New York open.</li>
<li><strong>Scheduled news.</strong> Releases produce displacement. The gap left behind may reflect an event, not a repeatable pattern.</li>
<li><strong>Thin liquidity windows.</strong> Quiet hours can produce sharp moves that leave large gaps on small volume.</li>
<li><strong>Higher timeframe context.</strong> A small gap on a five minute chart can sit inside a much larger move on the hourly or daily chart.</li>
</ul>

<h2>Common misreadings</h2>
<ul>
<li>Treating every gap as a level worth acting on.</li>
<li>Reading a gap without knowing which session produced it.</li>
<li>Assuming a fill guarantees a reversal, or that a miss guarantees continuation.</li>
<li>Marking gaps on one timeframe and ignoring the structure on the next one up.</li>
</ul>

<h2>Visual reference</h2>
<figure>
<svg viewBox="0 0 420 270" role="img" aria-label="Illustration of a bullish fair value gap across three candles">
<text x="10" y="20" font-size="13" fill="#d4a93c">Illustration</text>
<line x1="20" y1="250" x2="400" y2="250" stroke="#1d2433" stroke-width="1"/>
<rect x="100" y="130" width="200" height="40" fill="#3fbf7f" fill-opacity="0.18" stroke="#3fbf7f" stroke-dasharray="4 3"/>
<text x="112" y="154" font-size="12" fill="#d9dee8">Fair value gap</text>
<line x1="100" y1="170" x2="100" y2="240" stroke="#8a94a8" stroke-width="2"/>
<rect x="88" y="185" width="24" height="40" fill="#d25b5b"/>
<line x1="200" y1="40" x2="200" y2="200" stroke="#8a94a8" stroke-width="2"/>
<rect x="186" y="70" width="28" height="110" fill="#3fbf7f"/>
<line x1="300" y1="70" x2="300" y2="130" stroke="#8a94a8" stroke-width="2"/>
<rect x="288" y="80" width="24" height="30" fill="#3fbf7f"/>
<text x="70" y="262" font-size="12" fill="#8a94a8">candle 1</text>
<text x="170" y="262" font-size="12" fill="#8a94a8">candle 2 (displacement)</text>
<text x="272" y="262" font-size="12" fill="#8a94a8">candle 3</text>
</svg>
<figcaption>Illustration. A bullish fair value gap: the low of candle 3 sits above the high of candle 1. Schematic only, not market data.</figcaption>
</figure>

<h2>How Korvus shows session context</h2>
<p>Korvus is a 24/7 market intelligence terminal for index futures traders. It does not hand you a signal. It keeps the context around price in one place, so a gap is read against the session and the news that surround it.</p>
<div class="chips">
<span class="chip">Asia, London and New York sessions</span>
<span class="chip">Prior day and week reference levels</span>
<span class="chip">Scored news wire</span>
<span class="chip">Coverage across the full day</span>
</div>
<p>The LodeStone indicator carries a session level toolkit built on ICT concepts, covering sessions, prior day and week levels, and premium and discount. This page does not claim LodeStone draws fair value gaps. Check the feature list before you assume any tool does a specific job.</p>

<div class="note">
Not financial advice. This page is for education. Nothing here is a recommendation to buy, sell, or hold any instrument, and nothing here promises any result. Index futures carry substantial risk of loss. Test any idea on your own, with your own rules, before you risk capital.
</div>

<div class="cta">
<p><strong>See the session context yourself.</strong></p>
<p>Start on the free Observer tier and look at the market with the context around it.</p>
<a class="btn" href="https://korvus.industries/signup">Create your Korvus account</a>
</div>
</main>

<footer>
<p>BlackCrownVxJ LLC. Korvus is a market intelligence product. Education only, not financial advice.</p>
<p><a href="https://korvus.industries/legal">Legal</a> · <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></p>
</footer>
</body>
</html>
