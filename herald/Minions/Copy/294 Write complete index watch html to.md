# Copy: Write complete index watch html to vault file then report

Date: 2026-10-27
Task: Write complete index-watch html to vault file, then report file name and last 40 characters
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- FILING NOTE: this session has no vault write tool. This document is NOT confirmed filed at korvus:pages/index-watch.html. Herald or the executor must file it and verify the tail. -->
<title>Index Watch | Korvus</title>
<meta name="description" content="24/7 index futures market watch from Korvus: scored news, session levels and a written read while you sleep. Information only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07070b;color:#e8e8f0;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.55}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid #1d1d2a}
header span{font-weight:700;letter-spacing:.08em;font-size:14px;text-transform:uppercase}
main{max-width:960px;margin:0 auto;padding:40px 24px 64px}
h1{font-size:40px;line-height:1.15;margin-bottom:14px}
h2{font-size:22px;margin:40px 0 12px}
p.lede{font-size:18px;color:#c4c4d4;max-width:680px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:24px 0}
.chip{border:1px solid #2a2a3c;border-radius:999px;padding:6px 14px;font-size:13px;color:#d6d6e6;background:#0e0e16}
.panel{background:#0e0e16;border:1px solid #1d1d2a;border-radius:12px;padding:20px;margin-top:24px}
.panel figcaption{font-size:12px;color:#8a8aa0;margin-top:10px;text-transform:uppercase;letter-spacing:.06em}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px;margin-top:12px}
.card{background:#0e0e16;border:1px solid #1d1d2a;border-radius:10px;padding:16px}
.card h3{font-size:15px;margin-bottom:6px}
.card p{font-size:14px;color:#b4b4c6}
.tag{display:inline-block;font-size:11px;color:#ff2d8f;border:1px solid #ff2d8f;border-radius:4px;padding:1px 6px;margin-bottom:8px;letter-spacing:.05em}
.actions{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;text-decoration:none;font-weight:600;font-size:15px}
.btn-primary{background:#ff2d8f;color:#07070b}
.btn-ghost{border:1px solid #2a2a3c;color:#e8e8f0}
footer{max-width:960px;margin:0 auto;padding:24px;border-top:1px solid #1d1d2a;font-size:12px;color:#8a8aa0}
footer a{color:#c4c4d4}
</style>
</head>
<body>
<header>
<svg width="36" height="33" viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" aria-hidden="true">
<path d="M4 26 L2 8 L11 16 L18 4 L25 16 L34 8 L32 26 Z"/>
<line x1="4" y1="30" x2="32" y2="30"/>
</svg>
<span>Korvus</span>
</header>
<main>
<h1>Index Watch</h1>
<p class="lede">The market does not close for you. Korvus keeps watch on index futures around the clock, scores what moves, and writes a plain read you can check before the open.</p>

<div class="chips">
<span class="chip">24/7 coverage</span>
<span class="chip">Scored news</span>
<span class="chip">Session levels</span>
<span class="chip">Written read</span>
<span class="chip">No repainting</span>
</div>

<figure class="panel" aria-label="Illustrative index watch board">
<svg width="100%" height="180" viewBox="0 0 640 180" preserveAspectRatio="none" role="img" aria-label="Illustration of an index price line with session markers">
<line x1="0" y1="45" x2="640" y2="45" stroke="#1d1d2a"/>
<line x1="0" y1="90" x2="640" y2="90" stroke="#1d1d2a"/>
<line x1="0" y1="135" x2="640" y2="135" stroke="#1d1d2a"/>
<polyline fill="none" stroke="#ff2d8f" stroke-width="2.5" points="0,110 40,104 80,118 120,96 160,100 200,78 240,86 280,64 320,72 360,58 400,80 440,70 480,92 520,84 560,62 600,68 640,50"/>
<line x1="200" y1="0" x2="200" y2="180" stroke="#3a3a52" stroke-dasharray="4 4"/>
<line x1="440" y1="0" x2="440" y2="180" stroke="#3a3a52" stroke-dasharray="4 4"/>
<text x="206" y="16" fill="#8a8aa0" font-size="11">Session open</text>
<text x="446" y="16" fill="#8a8aa0" font-size="11">Scored event</text>
</svg>
<figcaption>Illustration: sample board layout, not live market data.</figcaption>
</figure>

<h2>What the watch covers</h2>
<div class="grid">
<div class="card"><span class="tag">FEED</span><h3>Scored news</h3><p>Headlines ranked by likely impact on index futures, with direction and confidence stated.</p></div>
<div class="card"><span class="tag">LEVELS</span><h3>Session levels</h3><p>Prior day and session reference levels plotted on the chart through LodeStone.</p></div>
<div class="card"><span class="tag">READ</span><h3>Written context</h3><p>A plain English summary of what changed and what it touches, so you decide faster.</p></div>
<div class="card"><span class="tag">ALERTS</span><h3>Event calendar</h3><p>Economic releases on the agenda, so nothing scheduled catches you off guard.</p></div>
</div>

<h2>Start watching</h2>
<p class="lede">Begin on the free Observer tier. Upgrade only when the watch earns a place in your routine.</p>
<div class="actions">
<a class="btn btn-primary" href="/signup">Start free</a>
<a class="btn btn-ghost" href="/lodestone">See LodeStone</a>
</div>
</main>
<footer>
<p>Korvus provides market information and education only. Nothing on this page is financial advice, a trading recommendation, or a promise of profit. Trading index futures carries substantial risk of loss. <a href="/legal">Legal</a></p>
</footer>
</body>
</html>
