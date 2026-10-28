# Scribe: Rewrite the complete html for korvus pages killzones html as

Date: 2026-10-28
Task: Rewrite the complete html for korvus:pages/killzones.html as a vault note where the html document appears EXACTLY ONCE: the very first characters are <!doctype 
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Killzones: Session Windows for Index Futures</title>
<meta name="description">
<meta name="description" content="What killzones are, why traders watch session windows in index futures, and how Korvus tracks them. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/killzones">
<style>
:root{--bg:#07070b;--panel:#0e0e16;--line:#22222e;--text:#e8e8f0;--muted:#9a9ab0;--pink:#ff2d8f;--cyan:#2de2ff}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid var(--line)}
header svg{width:36px;height:33px}
header span{font-weight:700;letter-spacing:.04em}
main{max-width:860px;margin:0 auto;padding:32px 24px 56px}
h1{font-size:2rem;line-height:1.2;margin:0 0 12px}
h2{font-size:1.3rem;margin:36px 0 10px;color:var(--pink)}
p{margin:0 0 14px;color:var(--text)}
.lede{color:var(--muted);font-size:1.05rem}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid var(--line);background:var(--panel);padding:6px 12px;border-radius:999px;font-size:.85rem;color:var(--muted)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:20px;margin:20px 0}
.tag{display:inline-block;font-size:.75rem;color:var(--cyan);letter-spacing:.08em;text-transform:uppercase;margin-bottom:8px}
table{width:100%;border-collapse:collapse;font-size:.95rem}
th,td{text-align:left;padding:10px 8px;border-bottom:1px solid var(--line)}
th{color:var(--muted);font-weight:600}
.note{font-size:.85rem;color:var(--muted)}
.cta{display:inline-block;margin-top:8px;background:var(--pink);color:#07070b;text-decoration:none;font-weight:700;padding:10px 18px;border-radius:8px}
.cta.ghost{background:transparent;color:var(--text);border:1px solid var(--line);margin-left:8px}
footer{border-top:1px solid var(--line);padding:20px 24px;color:var(--muted);font-size:.85rem;text-align:center}
footer a{color:var(--muted)}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>KORVUS</span>
</header>
<main>
<p class="tag">Education</p>
<h1>Killzones: session windows for index futures</h1>
<p class="lede">A killzone is a block of time that traders who use ICT style concepts often watch for higher activity. This page explains what the term means, where the windows usually sit, and how Korvus tracks them. It is education, not a signal and not financial advice.</p>

<div class="chips">
<span class="chip">Session timing</span>
<span class="chip">Index futures</span>
<span class="chip">New York time</span>
<span class="chip">Education only</span>
</div>

<h2>What a killzone is</h2>
<p>The term comes from ICT style trading. It names windows when price often moves with more volume and more range than the quiet hours around them. The idea is simple: liquidity tends to concentrate when major financial centers open and when a session hands off to the next one.</p>
<p>A killzone is a label for a time window. It does not tell you what price will do inside that window. Plenty of sessions move hard outside these hours, and plenty of killzones pass quietly.</p>

<h2>The commonly cited windows</h2>
<p>Traders use slightly different definitions. The table below shows the windows most often cited in ICT material, in New York time. Treat it as a reference you check against your own data.</p>

<div class="panel">
<span class="tag">Illustration</span>
<svg viewBox="0 0 640 150" width="100%" role="img" aria-label="Illustrative session timeline, not live data">
<line x1="20" y1="110" x2="620" y2="110" stroke="#22222e" stroke-width="2"/>
<rect x="60" y="70" width="120" height="30" fill="#2de2ff" opacity=".35"/>
<rect x="250" y="50" width="130" height="50" fill="#ff2d8f" opacity=".45"/>
<rect x="430" y="80" width="100" height="20" fill="#2de2ff" opacity=".35"/>
<text x="60" y="130" fill="#9a9ab0" font-size="13">London</text>
<text x="250" y="130" fill="#9a9ab0" font-size="13">New York open</text>
<text x="430" y="130" fill="#9a9ab0" font-size="13">London close</text>
</svg>
<p class="note">Illustration. Bar heights and positions are schematic, not market data.</p>
</div>

<table>
<thead><tr><th>Window</th><th>Typical time (New York)</th><th>Why people watch it</th></tr></thead>
<tbody>
<tr><td>London killzone</td><td>2:00 to 5:00 am</td><td>London open and early European flow</td></tr>
<tr><td>New York open killzone</td><td>7:00 to 10:00 am</td><td>US cash open and the first hours of US volume</td></tr>
<tr><td>London close</td><td>10:00 to 12:00 pm</td><td>European close and the handoff into the afternoon</td></tr>
</tbody>
</table>

<h2>How Korvus handles this</h2>
<p>Korvus runs a 24/7 market intelligence terminal for index futures traders. Session timing is one of the things it keeps in view so you do not have to track the clock yourself. Session windows are context. They sit next to news scoring, economic events, and the levels your own process already uses.</p>
<p>LodeStone, the session level toolkit in the Korvus stack, draws session and timezone references on your chart. Its inputs let you set the session times yourself, so the windows match the definition you actually use.</p>

<h2>What this page does not do</h2>
<p>It does not say a killzone will produce a move, a trade, or a profit. It does not tell you when to enter or exit. Win rates and results depend on your process, your risk, and market conditions that change from day to day. If someone sells you a killzone as a guaranteed edge, walk away.</p>

<div class="panel">
<p>Want the session context in one place while you work? Start on the free Observer tier, or look at what Operator adds.</p>
<a class="cta" href="/signup">Start free</a>
<a class="cta ghost" href="/lodestone">See LodeStone</a>
</div>

<p class="note">Not financial advice. Trading index futures involves substantial risk of loss. Past sessions do not predict future sessions. Times shown are typical reference windows and may vary with daylight saving changes and your own definitions.</p>
</main>
<footer>
<p>BlackCrownVxJ LLC. <a href="/legal">Legal</a> · <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></p>
<p>A crown is not handed down, it is built.</p>
</footer>
</body>
</html>
