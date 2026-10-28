# Scribe: Rewrite the complete smt divergence seo page html for korvus

Date: 2026-10-28
Task: Rewrite the complete SMT divergence SEO page html for korvus:pages/smt-divergence.html, one single clean document
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Futures: Cross Index Read | Korvus</title>
<meta name="description" content="How SMT divergence works across ES, NQ and YM index futures. A plain, honest look at cross index confirmation and failure. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<meta property="og:title" content="SMT Divergence Futures: Cross Index Read">
<meta property="og:description" content="Plain talk on SMT divergence across index futures. What it shows, what it does not, and how Korvus watches it for you.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://korvus.industries/p/smt-divergence">
<style>
:root{--bg:#07080c;--panel:#0e1019;--line:#22263a;--text:#e6e8f0;--muted:#9aa0b8;--accent:#ff2d8f;--gold:#d7b56d}
*{box-sizing:border-box}
body{margin:0;background:radial-gradient(1200px 600px at 50% -10%,#1a0d1f 0%,var(--bg) 60%);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
.wrap{max-width:860px;margin:0 auto;padding:24px 20px 56px}
header{display:flex;align-items:center;gap:14px;padding-bottom:20px;border-bottom:1px solid var(--line)}
header svg{width:44px;height:40px}
.brand{font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:14px}
.brand span{color:var(--accent)}
h1{font-size:clamp(28px,4.4vw,40px);line-height:1.15;margin:32px 0 12px}
h2{font-size:20px;margin:36px 0 10px;color:var(--gold)}
p{margin:0 0 14px;color:var(--text)}
.lede{color:var(--muted);font-size:17px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px;margin:24px 0}
figure{margin:0}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:13px;margin-top:10px}
.tag{display:inline-block;font-size:12px;color:var(--gold);border:1px solid #5a4a24;border-radius:999px;padding:2px 10px;margin-right:6px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:18px 0}
.chip{background:#14121c;border:1px solid #3a1d33;color:var(--text);border-radius:10px;padding:10px 14px;font-size:14px;flex:1 1 200px}
.chip b{display:block;color:var(--accent);font-size:13px;margin-bottom:2px}
.cta{display:inline-block;margin-top:10px;background:var(--accent);color:#07080c;font-weight:700;text-decoration:none;padding:14px 22px;border-radius:10px}
.disclaimer{font-size:13px;color:var(--muted);border-top:1px solid var(--line);margin-top:40px;padding-top:16px}
footer{margin-top:28px;color:var(--muted);font-size:13px}
</style>
</head>
<body>
<div class="wrap">
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="1.6" stroke-linejoin="round" aria-hidden="true">
<path d="M4 26 L8 12 L14 19 L18 6 L22 19 L28 12 L32 26 Z"/>
<path d="M4 29 H32"/>
<circle cx="18" cy="3" r="1.6" fill="#ff2d8f"/>
</svg>
<div class="brand">Kor<span>vus</span></div>
</header>

<h1>SMT divergence for index futures traders</h1>
<p class="lede">SMT stands for Smart Money Technique. The idea is simple: correlated index futures usually move together. When one makes a new high or low and the other does not confirm it, that gap is the signal worth looking at. Here is how it works, where it misleads, and how to read it without a guru telling you what to do.</p>

<div class="panel">
<figure>
<svg viewBox="0 0 560 220" role="img" aria-label="Illustration: two index lines, one making a higher high while the other fails to confirm">
<rect x="0" y="0" width="560" height="220" fill="#0a0c14"/>
<path d="M20 180 L80 150 L130 165 L190 110 L250 130 L310 70 L370 95 L430 40 L500 60" fill="none" stroke="#ff2d8f" stroke-width="3"/>
<path d="M20 170 L80 140 L130 155 L190 100 L250 118 L310 82 L370 104 L430 96 L500 112" fill="none" stroke="#d7b56d" stroke-width="3" stroke-dasharray="6 5"/>
<circle cx="430" cy="40" r="5" fill="#ff2d8f"/>
<circle cx="430" cy="96" r="5" fill="#d7b56d"/>
<line x1="430" y1="40" x2="430" y2="96" stroke="#9aa0b8" stroke-width="1" stroke-dasharray="3 4"/>
<text x="446" y="72" fill="#9aa0b8" font-size="12" font-family="system-ui,sans-serif">gap</text>
<text x="20" y="206" fill="#9aa0b8" font-size="12" font-family="system-ui,sans-serif">Illustration: not live data</text>
</svg>
<figcaption><span class="tag">Illustration</span>Solid line makes a new high. Dashed line fails to confirm. The gap between them is the divergence.</figcaption>
</figure>
</div>

<h2>What the signal is</h2>
<p>Traders often compare ES, NQ and YM because they track the same broad market through different baskets. When the pair moves in lockstep, nothing is interesting. When one index sets a fresh extreme and a correlated index stops short, one of them is telling a different story than the other. That disagreement is the divergence.</p>
<p>It is a reading of structure, not a prediction. A divergence says the tape is not unanimous. It does not say which side wins, or when.</p>

<h2>Where it misleads</h2>
<p>A divergence can appear on a quiet session with thin liquidity, on a roll day when contracts are not lined up, or right before a news release that changes everything. Many divergences resolve without any move worth trading. Treat the signal as one input among several, and be willing to ignore it.</p>
<p>Check the session, the timeframe and whether both contracts are reading the same kind of level. A divergence on a 1 minute chart in the overnight session is not the same object as one on a daily chart at the cash open.</p>

<h2>What Korvus does with it</h2>
<p>Korvus watches the correlated index pairs around the clock and flags structural divergences as they form, so you are not staring at three charts while the market moves. The LodeStone SMT divergence feature is part of the chart toolkit that comes with Operator. It marks the divergence on your chart. You still decide what it means for your plan.</p>

<div class="chips">
<div class="chip"><b>Cross index</b>ES, NQ and YM compared in one read</div>
<div class="chip"><b>24/7 watch</b>Structure flagged while you sleep</div>
<div class="chip"><b>No repaint</b>Marks stay where they formed</div>
<div class="chip"><b>Your call</b>Context first, signal second</div>
</div>

<a class="cta" href="https://korvus.industries/signup?utm_source=seo&amp;utm_medium=page&amp;utm_campaign=smt-divergence">Start with the free Observer tier</a>

<div class="disclaimer">
<p>Not financial advice. Korvus is market intelligence and education for index futures traders. Nothing on this page is a recommendation to buy, sell or hold any instrument, and no profit or result is promised. Futures carry substantial risk of loss. Past structure does not guarantee future behavior. Trade only capital you can afford to lose.</p>
</div>

<footer>BlackCrownVxJ LLC. Korvus is a product of BlackCrown Intelligence. Business contact: BlackCrownVxJ.LLC@outlook.com</footer>
</div>
</body>
</html>
