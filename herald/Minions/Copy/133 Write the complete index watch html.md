# Copy: Write the complete index watch html to minions copy index

Date: 2026-10-27
Task: Write the complete index-watch html to Minions/Copy/index-watch-page.md, then audit it
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Futures Watched Overnight | Korvus</title>
<meta name="description" content="Korvus watches index futures overnight with a 24/7 market intelligence terminal. Operator is 79.99 a year with LodeStone included. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
body{margin:0;background:#0a0a0f;color:#e8e8ee;font-family:system-ui,Arial,sans-serif;line-height:1.5}
header{display:flex;align-items:center;gap:10px;padding:18px 24px;border-bottom:1px solid #22222c}
header svg{width:36px;height:33px;flex:none}
.brand{font-weight:700;letter-spacing:.08em}
.tag{color:#8a8a99;font-size:.85rem;margin-left:auto}
main{max-width:860px;margin:0 auto;padding:32px 24px}
h1{font-size:2rem;margin:0 0 12px}
h2{font-size:1.15rem;margin:28px 0 8px;color:#ff2d8f}
p{margin:0 0 14px;color:#c4c4d0}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid #33333f;padding:6px 12px;border-radius:999px;font-size:.85rem}
.panel{background:#11111a;border:1px solid #2a2a36;border-radius:10px;padding:18px;margin:20px 0}
.panel small{color:#8a8a99;display:block;margin-top:8px}
.plan{background:#11111a;border:1px solid #2a2a36;border-radius:10px;padding:18px;margin:12px 0}
.price{font-size:1.4rem;font-weight:700}
.save{color:#ff2d8f;font-size:.9rem}
.cta{display:inline-block;background:#ff2d8f;color:#0a0a0f;font-weight:700;padding:12px 20px;border-radius:8px;text-decoration:none;margin-top:10px}
.disc{font-size:.8rem;color:#8a8a99;border-top:1px solid #22222c;margin-top:32px;padding-top:14px}
</style>
</head>
<body>
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">KORVUS</span>
<span class="tag">Your edge while the world sleeps</span>
</header>
<main>
<h1>Index futures, watched overnight.</h1>
<p>Korvus runs a 24/7 market intelligence terminal for index futures traders. While you sleep, the terminal keeps watch on the overnight session and surfaces scored news, levels, and context so you start the day with the picture already built.</p>

<div class="chips">
<span class="chip">Overnight session coverage</span>
<span class="chip">Scored news feed</span>
<span class="chip">LodeStone chart toolkit</span>
<span class="chip">Zero repainting</span>
</div>

<div class="panel" aria-label="Illustration">
<svg viewBox="0 0 600 180" width="100%" height="180" role="img" aria-label="Illustrative overnight watch panel">
<rect x="0" y="0" width="600" height="180" fill="#0a0a0f"/>
<line x1="20" y1="150" x2="580" y2="150" stroke="#2a2a36"/>
<line x1="20" y1="100" x2="580" y2="100" stroke="#1c1c26"/>
<line x1="20" y1="50" x2="580" y2="50" stroke="#1c1c26"/>
<polyline points="20,120 60,110 100,126 140,95 180,104 220,80 260,92 300,70 340,84 380,62 420,74 460,50 500,66 540,44 580,56" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round"/>
<rect x="470" y="14" width="110" height="26" rx="6" fill="#11111a" stroke="#33333f"/>
<text x="525" y="31" fill="#e8e8ee" font-size="12" text-anchor="middle" font-family="system-ui,Arial,sans-serif">Overnight</text>
</svg>
<small>Illustration: sample overnight panel layout. Not live data.</small>
</div>

<h2>Plans</h2>
<div class="plan">
<div class="price">Operator, annual: 79.99 a year</div>
<div class="save">Annual plan. Save 39.89 versus paying monthly.</div>
<p>Operator includes the LodeStone TradingView indicator at no extra cost.</p>
</div>
<div class="plan">
<div class="price">Operator, monthly: 9.99 a month</div>
<p>Same terminal, billed monthly. LodeStone included.</p>
</div>
<a class="cta" href="https://korvus.industries/signup">Start with the free Observer tier</a>

<div class="disc">
Korvus is market intelligence and education, not financial advice. Nothing on this page recommends a trade, a position, or a level to act on, and nothing promises a profit. Index futures carry substantial risk of loss. Trade only with capital you can afford to lose.
</div>

<!--
AUDIT (Copy, index-watch-page)
1. Full document doctype to closing html tag: PASS
2. Under 6000 characters: PASS
3. No em dashes: PASS
4. No emoji: PASS
5. Single meta description with real text in head: PASS
6. Title under 60 characters (41): PASS
7. Viewport meta and canonical link present: PASS
8. Inline crown SVG beside site name in header: PASS
9. Visual element present, marked Illustration: PASS
10. Copy states index futures watched overnight: PASS
11. Operator 79.99 a year with LodeStone included: PASS
12. Not financial advice disclaimer present: PASS
13. Savings label computed (9.99 x 12 = 119.88, minus 79.99 = 39.89): PASS
14. Dollar amounts hardcoded: NOTE. The no hardcoded prices rule covers korvus_landing only, and this page is a new pages/ file. The owner specified 79.99 in copy, so it is included. Flag for owner if prices change and this page drifts.
15. Write to Minions/Copy/index-watch-page.md: FAIL. Copy has no file write tool in this session, so the document is delivered inline for filing by the writing desk or executor.
16. UTM tagging: standing infrastructure, not added manually.
FROM NOTE: Minions/Copy/index-watch-page.md
-->
</main>
</body>
</html>
