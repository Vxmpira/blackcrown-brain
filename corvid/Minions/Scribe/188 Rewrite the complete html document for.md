# Scribe: Rewrite the complete html document for korvus pages fair value

Date: 2026-10-28
Task: Rewrite the COMPLETE html document for korvus:pages/fair-value-gaps.html as a fresh clean note, doctype through closing html
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Fair Value Gaps: A Plain Reading for Index Traders</title>
<meta name="description" content="What a fair value gap is, how to spot one on a chart, and where traders often misread it. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/fair-value-gaps">
<meta property="og:type" content="article">
<meta property="og:title" content="Fair Value Gaps: A Plain Reading for Index Traders">
<meta property="og:description" content="What a fair value gap is, how to spot one, and where traders misread it. Education only.">
<meta property="og:url" content="https://korvus.industries/p/fair-value-gaps">
<meta property="og:site_name" content="Korvus">
<meta name="twitter:card" content="summary">
<style>
:root{--bg:#0b0d10;--panel:#14181e;--line:#252b34;--text:#d6dbe3;--muted:#8a94a3;--gold:#c9a949;--green:#3fae7a;--red:#c8554f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.65 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
header{display:flex;align-items:center;gap:12px;padding:18px 24px;border-bottom:1px solid var(--line)}
header a{color:var(--text);text-decoration:none;font-weight:600;letter-spacing:.02em}
header svg{width:34px;height:34px}
main{max-width:760px;margin:0 auto;padding:32px 24px 64px}
h1{font-size:30px;line-height:1.25;margin:0 0 12px}
h2{font-size:21px;margin:36px 0 10px;color:var(--gold)}
p{margin:0 0 16px}
.lede{color:var(--muted);font-size:18px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px;margin:28px 0}
.panel h3{margin:0 0 6px;font-size:15px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:12px 0 0;padding:0;list-style:none}
.chips li{border:1px solid var(--line);border-radius:999px;padding:4px 12px;font-size:14px;color:var(--muted)}
.caption{font-size:13px;color:var(--muted);margin-top:10px}
ol,ul{padding-left:20px}
li{margin-bottom:8px}
.note{border-left:3px solid var(--gold);padding:12px 16px;background:var(--panel);color:var(--muted);font-size:14px;margin-top:36px}
a{color:var(--gold)}
footer{max-width:760px;margin:0 auto;padding:0 24px 40px;color:var(--muted);font-size:13px}
</style>
</head>
<body>
<header>
  <svg viewBox="0 0 40 40" aria-hidden="true">
    <path d="M6 30 L8 14 L14 22 L20 8 L26 22 L32 14 L34 30 Z" fill="none" stroke="#c9a949" stroke-width="2" stroke-linejoin="round"/>
    <rect x="6" y="31" width="28" height="3" fill="#c9a949"/>
    <circle cx="20" cy="8" r="2" fill="#c9a949"/>
  </svg>
  <a href="/">Korvus</a>
</header>

<main>
  <p class="lede">A fair value gap is a three candle pattern that shows price moved fast enough to leave an open space. Traders watch these spaces. That is all this note claims.</p>
  <h1>Fair Value Gaps: A Plain Reading for Index Traders</h1>

  <h2>What the pattern is</h2>
  <p>A fair value gap, often shortened to FVG, forms across three consecutive candles. The middle candle moves hard in one direction. The high of the first candle and the low of the third candle do not overlap in a bullish gap, so a space stays open between them. In a bearish gap the logic flips: the low of the first candle and the high of the third candle leave the space open.</p>
  <p>The idea is simple. Fast moves can skip prices. Some traders believe price later returns to those skipped areas. Whether it does is a question the chart answers after the fact, not before.</p>

  <div class="panel" aria-label="Three candle figure">
    <h3>Figure: bullish three candle gap</h3>
    <svg viewBox="0 0 360 200" width="100%" role="img" aria-label="Illustration of three candles with a shaded gap between the first candle high and the third candle low">
      <line x1="80" y1="30" x2="80" y2="150" stroke="#8a94a3" stroke-width="2"/>
      <rect x="66" y="70" width="28" height="60" fill="#3fae7a"/>
      <line x1="180" y1="20" x2="180" y2="170" stroke="#8a94a3" stroke-width="2"/>
      <rect x="164" y="45" width="32" height="100" fill="#3fae7a"/>
      <line x1="280" y1="10" x2="280" y2="110" stroke="#8a94a3" stroke-width="2"/>
      <rect x="266" y="20" width="28" height="60" fill="#3fae7a"/>
      <rect x="94" y="70" width="170" height="30" fill="#c9a949" opacity="0.25"/>
      <line x1="94" y1="70" x2="264" y2="70" stroke="#c9a949" stroke-dasharray="4 4"/>
      <line x1="94" y1="100" x2="264" y2="100" stroke="#c9a949" stroke-dasharray="4 4"/>
    </svg>
    <p class="caption">Illustration. Not market data. Shows the shape of a bullish gap between candle one and candle three.</p>
    <ul class="chips">
      <li>Three candles</li>
      <li>Open space</li>
      <li>Bullish or bearish</li>
      <li>Illustration</li>
    </ul>
  </div>

  <h2>How to read one without fooling yourself</h2>
  <ol>
    <li>Define the gap before you look at outcomes. Write down the high, the low, and the candles that formed it.</li>
    <li>Note the context. A gap during a quiet session means something different from a gap released by a news print.</li>
    <li>Check the higher timeframe. A small gap inside a large range carries less weight than one that sits at the edge of the range.</li>
    <li>Keep a log of gaps you saw, not only the ones that filled. Traders who only remember the hits overrate the pattern.</li>
  </ol>

  <h2>Where traders go wrong</h2>
  <ul>
    <li>Treating every three candle shape as a gap. Most are noise.</li>
    <li>Assuming a gap must fill. Some never do, and some fill after a deeper move through them.</li>
    <li>Sizing positions as if the pattern were a promise. It is a description of past price, nothing more.</li>
    <li>Adding more indicators until the chart agrees with the story you already believe.</li>
  </ul>

  <h2>Going further</h2>
  <p>Fair value gaps pair naturally with other structure work. For a related concept, read the notes on <a href="/p/smt-divergence">SMT divergence</a>, which looks at whether correlated index futures confirm or reject the same move. For the live market terminal that tracks these levels across sessions, see <a href="/">Korvus</a>.</p>

  <div class="note">
    Education only. Nothing on this page is financial advice, a trading signal, or a recommendation to buy or sell any instrument. Index futures carry substantial risk of loss. Past chart patterns do not predict future results. Make your own decisions and test any idea on paper first.
  </div>
</main>

<footer>
  Korvus is a product of BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com
</footer>
</body>
</html>
