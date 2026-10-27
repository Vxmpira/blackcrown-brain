# Copy: Save a complete index watch html document to minions copy

Date: 2026-10-27
Task: Save a complete index-watch html document to Minions/Copy/index-watch-page.md and verify its checklist
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | BlackCrownVxJ</title>
<meta name="description" content="Illustration index watch layout for index futures traders. Korvus runs 24/7 market intelligence. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
body{margin:0;background:#07070a;color:#e8e8ee;font-family:system-ui,Arial,sans-serif;line-height:1.5}
header{display:flex;align-items:center;gap:12px;padding:18px 24px;border-bottom:1px solid #1e1e28}
header span{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
main{max-width:880px;margin:0 auto;padding:28px 24px}
h1{font-size:28px;margin:0 0 8px}
p{color:#b8b8c4;margin:0 0 16px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid #2c2c3a;border-radius:999px;padding:4px 12px;font-size:13px;color:#d4d4de}
.panel{background:#0e0e14;border:1px solid #23232f;border-radius:10px;padding:18px;margin-top:20px}
.label{font-size:12px;color:#8a8a9a;text-transform:uppercase;letter-spacing:.06em;margin-bottom:12px}
.row{display:grid;grid-template-columns:90px 1fr 90px;gap:12px;align-items:center;margin:10px 0;font-size:14px}
.bar{height:10px;background:#1a1a24;border-radius:6px;overflow:hidden}
.bar i{display:block;height:100%;background:linear-gradient(90deg,#5b5b78,#c9c9d9)}
.cta{display:inline-block;margin-top:18px;background:#e8e8ee;color:#07070a;padding:10px 18px;border-radius:6px;text-decoration:none;font-weight:600}
.disc{font-size:12px;color:#7a7a8a;margin-top:24px}
</style>
</head>
<body>
<header>
<svg width="28" height="28" viewBox="0 0 24 24" aria-hidden="true"><path d="M3 18h18l-2-10-5 4-2-6-2 6-5-4z" fill="#e8e8ee"/></svg>
<span>BlackCrownVxJ</span>
</header>
<main>
<h1>Index Watch</h1>
<p>A single view of session activity across the major index futures contracts. Korvus keeps this watch running around the clock so you can review the tape with context when you sit down.</p>
<div class="chips">
<span class="chip">ES</span>
<span class="chip">NQ</span>
<span class="chip">YM</span>
<span class="chip">RTY</span>
<span class="chip">Session levels</span>
<span class="chip">Scored news</span>
</div>
<div class="panel" role="img" aria-label="Illustration: sample index watch layout">
<div class="label">Illustration: sample layout, not live data</div>
<div class="row"><span>ES</span><div class="bar"><i style="width:72%"></i></div><span>Activity</span></div>
<div class="row"><span>NQ</span><div class="bar"><i style="width:58%"></i></div><span>Activity</span></div>
<div class="row"><span>YM</span><div class="bar"><i style="width:44%"></i></div><span>Activity</span></div>
<div class="row"><span>RTY</span><div class="bar"><i style="width:63%"></i></div><span>Activity</span></div>
</div>
<a class="cta" href="https://korvus.industries/signup">Start with the free Observer tier</a>
<p class="disc">Korvus is market intelligence and education, not financial advice. Trading index futures carries substantial risk of loss. Past activity does not predict results. The panel above is an illustration and does not show live market data.</p>
</main>
</body>
<!--
CHECKLIST, Copy, index-watch-page
Note path: Minions/Copy/index-watch-page.md
1. Doctype through closing html tag: PASS
2. Under 6000 characters: PASS
3. Title under 60 characters (Index Watch | BlackCrownVxJ, 27): PASS
4. Non-empty meta description after title: PASS
5. Crown SVG in header: PASS
6. At least one visual element (session bar panel and chips): PASS
7. Illustration label on on-screen panel: PASS
8. No em dashes: PASS
9. No financial advice (education framing and disclaimer present): PASS
10. No emoji: PASS
11. Viewport meta and canonical link: PASS
12. Ends with closing html tag: PASS
13. File saved to Minions/Copy/index-watch-page.md: FAIL. This run has no file write tool, so the document was authored but not saved. Herald or the vault pipeline needs to route this document to the note path.
-->
</html>
