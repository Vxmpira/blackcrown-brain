# Scribe: Rewrite the complete liquidity sweeps html page with a clean

Date: 2026-10-28
Task: Rewrite the COMPLETE liquidity sweeps html page with a clean head: the head must contain EXACTLY ONE title tag, EXACTLY ONE meta description, EXACTLY ONE canoni
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Liquidity Sweeps in Index Futures | Korvus</title>
<meta name="description" content="How liquidity sweeps form in index futures, where resting orders sit, and how Korvus watches the market around the clock. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/liquidity-sweeps">
<style>
:root{--bg:#07070a;--panel:#0f0f16;--line:#24242f;--text:#e8e8ef;--muted:#9a9aab;--pink:#ff2d8f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.65 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid var(--line)}
header svg{width:36px;height:33px}
.brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase}
main{max-width:760px;margin:0 auto;padding:40px 24px 64px}
h1{font-size:2rem;line-height:1.2;margin:0 0 12px}
h2{font-size:1.25rem;margin:36px 0 10px;color:var(--pink)}
p{margin:0 0 16px;color:var(--text)}
.lede{color:var(--muted)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chip{border:1px solid var(--line);background:var(--panel);padding:6px 12px;border-radius:999px;font-size:13px;color:var(--muted)}
figure{margin:28px 0;background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:20px}
figure svg{width:100%;height:auto;display:block}
figcaption{margin-top:10px;font-size:13px;color:var(--muted)}
ul{padding-left:20px;margin:0 0 16px}
li{margin-bottom:8px}
.cta{display:inline-block;margin-top:12px;background:var(--pink);color:#07070a;text-decoration:none;font-weight:700;padding:12px 20px;border-radius:8px}
.note{font-size:13px;color:var(--muted);border-top:1px solid var(--line);margin-top:40px;padding-top:16px}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">Korvus</span>
</header>
<main>
<h1>Liquidity Sweeps in Index Futures</h1>
<p class="lede">A sweep is price trading through a level where orders are waiting, then moving away. This page explains the idea. It does not tell you what to trade.</p>
<div class="chips">
<span class="chip">Education only</span>
<span class="chip">Index futures</span>
<span class="chip">Session context</span>
</div>

<h2>What a liquidity sweep is</h2>
<p>Price rarely moves in a straight line through open space. It moves toward places where orders are stacked. A stop order is an order that triggers once price reaches a set level. Many traders place those stops in the same few spots.</p>
<p>When price runs through one of those clusters, it takes out the resting orders. That move is the sweep. Price trades beyond the level, collects the orders sitting there, and often returns inside the range.</p>

<h2>Where resting orders cluster</h2>
<p>Traders tend to look at the same reference points. Those points attract orders from many people at once.</p>
<ul>
<li>Prior session highs and lows</li>
<li>Prior day and prior week highs and lows</li>
<li>Round numbers and obvious equal highs or equal lows</li>
<li>Session opens and session range boundaries</li>
</ul>
<p>Not every level holds real size. A level is only a candidate. Confirmation still matters.</p>

<h2>Why sweeps get linked to reversals</h2>
<p>ICT style frameworks describe a sweep as a possible turning point. The idea goes like this. Price takes liquidity above or below a level. The move then fails and price shifts direction. Some traders treat that failure as the signal of interest.</p>
<p>That is a framework, not a rule. Sweeps happen often. Not every sweep reverses. Many simply continue. Treat the pattern as a question to investigate, not an answer.</p>

<figure>
<svg viewBox="0 0 400 200" role="img" aria-label="Illustration: price pokes above a prior high, then falls back below it">
<rect x="0" y="0" width="400" height="200" fill="#0f0f16"/>
<line x1="20" y1="70" x2="380" y2="70" stroke="#9a9aab" stroke-width="1.5" stroke-dasharray="6 5"/>
<text x="24" y="62" fill="#9a9aab" font-size="12" font-family="system-ui,sans-serif">Prior high</text>
<path d="M30 150 L90 120 L140 135 L200 95 L250 62 L280 40 L310 100 L350 130" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"/>
<circle cx="280" cy="40" r="4" fill="#ff2d8f"/>
</svg>
<figcaption>Illustration. Price trades above a prior high, takes the resting orders there, and returns below the level. Not real market data.</figcaption>
</figure>

<h2>How Korvus frames sweeps</h2>
<p>Korvus watches index futures around the clock. Sweeps are easier to judge when you know the session they happen in. A move through the Asia range during London is a different event from the same move at the New York open.</p>
<p>Korvus session context labels where price sits against the session levels that matter. It shows what was swept, what is still resting, and how the current session compares to prior ones. The read is descriptive. It is meant to help you see the structure faster, and it is still your call.</p>

<h2>Take the next step</h2>
<p>If you want the session context running while you sleep, start with a free Observer account. Upgrade only if the tools earn it.</p>
<a class="cta" href="https://korvus.industries/signup">Create a free Korvus account</a>

<p class="note">Education only. Nothing on this page is financial advice, a trade signal, or a promise of results. Index futures carry substantial risk of loss. Trade only with capital you can afford to lose.</p>
</main>
</body>
</html>
