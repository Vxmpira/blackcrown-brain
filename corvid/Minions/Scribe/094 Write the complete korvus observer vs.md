# Scribe: Write the complete korvus observer vs operator comparison html page

Date: 2026-10-27
Task: Write the COMPLETE Korvus Observer vs Operator comparison html page, but your report's LITERAL FIRST LINE must be exactly: COUNTS: head=N body=N title=N, with N
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<!-- COUNTS: head=1 body=1 title=1 -->
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Observer vs Operator: Compare Tiers</title>
<meta name="description" content="Compare Korvus Observer (free) and Operator at 79.99 a year or 9.99 a month. Scored news, session context, SMT depth and LodeStone. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/observer-vs-operator">
<style>
  :root { --bg:#07070b; --panel:#0e0e16; --line:#24243a; --text:#e8e8f0; --muted:#9a9ab0; --pink:#ff2d8f; }
  * { box-sizing:border-box; }
  body { margin:0; background:var(--bg); color:var(--text); font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif; line-height:1.6; }
  header { display:flex; align-items:center; gap:14px; padding:22px 24px; border-bottom:1px solid var(--line); }
  header svg { width:36px; height:33px; flex:none; }
  header .brand { font-weight:700; letter-spacing:.08em; }
  main { max-width:880px; margin:0 auto; padding:40px 24px 64px; }
  h1 { font-size:2rem; margin:0 0 12px; line-height:1.2; }
  h2 { font-size:1.25rem; margin:36px 0 10px; color:var(--pink); }
  p { margin:0 0 14px; color:var(--text); }
  .lede { color:var(--muted); font-size:1.05rem; }
  .chips { display:flex; flex-wrap:wrap; gap:10px; margin:24px 0; }
  .chip { border:1px solid var(--line); background:var(--panel); padding:8px 14px; border-radius:999px; font-size:.9rem; color:var(--muted); }
  .chip b { color:var(--text); }
  table { width:100%; border-collapse:collapse; background:var(--panel); border:1px solid var(--line); border-radius:10px; overflow:hidden; margin:18px 0; }
  th, td { padding:14px 16px; text-align:left; border-bottom:1px solid var(--line); vertical-align:top; font-size:.95rem; }
  th { color:var(--muted); font-weight:600; background:#11111b; }
  td.tick { color:var(--pink); font-weight:700; }
  .price { font-size:1.4rem; font-weight:700; }
  .save { display:inline-block; margin-top:6px; color:var(--pink); font-size:.85rem; }
  .cta { display:inline-block; margin-top:22px; background:var(--pink); color:#07070b; font-weight:700; text-decoration:none; padding:14px 26px; border-radius:8px; }
  .note { color:var(--muted); font-size:.85rem; border-top:1px solid var(--line); margin-top:40px; padding-top:18px; }
  @media (max-width:600px) { h1 { font-size:1.6rem; } th, td { padding:10px; font-size:.85rem; } }
</style>
</head>
<body>
<header>
  <svg viewBox="0 0 36 33" aria-hidden="true">
    <path d="M4 26 L8 10 L14 18 L18 6 L22 18 L28 10 L32 26 Z" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round"/>
    <line x1="4" y1="29" x2="32" y2="29" stroke="#ff2d8f" stroke-width="2" stroke-linecap="round"/>
  </svg>
  <span class="brand">KORVUS</span>
</header>
<main>
  <h1>Observer or Operator: which Korvus tier fits you</h1>
  <p class="lede">Korvus is a 24/7 market intelligence terminal for index futures traders. It watches the wire, scores the news and keeps session context on screen while you sleep. Two tiers. Here is what each one includes, without the hype.</p>

  <div class="chips" aria-label="Feature summary">
    <span class="chip"><b>Scored news feed</b></span>
    <span class="chip"><b>Futures board</b></span>
    <span class="chip"><b>Session context</b></span>
    <span class="chip"><b>Cross index SMT depth</b></span>
    <span class="chip"><b>LodeStone TradingView indicator</b></span>
  </div>

  <h2>Tier comparison</h2>
  <table>
    <thead>
      <tr><th>Feature</th><th>Observer (free)</th><th>Operator</th></tr>
    </thead>
    <tbody>
      <tr><td>Price</td><td>Free</td><td>
        <div class="price">79.99 a year</div>
        <span class="save">Save 39.89 a year against monthly billing</span>
        <div style="margin-top:10px">or 9.99 a month</div>
      </td></tr>
      <tr><td>Scored news feed</td><td class="tick">Included</td><td class="tick">Included</td></tr>
      <tr><td>Futures board</td><td class="tick">Included</td><td class="tick">Included</td></tr>
      <tr><td>Session context</td><td class="tick">Included</td><td class="tick">Included</td></tr>
      <tr><td>Cross index SMT depth</td><td>Not included</td><td class="tick">Included</td></tr>
      <tr><td>LodeStone TradingView indicator</td><td>Not included</td><td class="tick">Included</td></tr>
    </tbody>
  </table>

  <h2>Who Observer is for</h2>
  <p>Observer is the free way in. You get the scored news feed, the futures board and session context. Use it to see whether the wire and the layout suit how you read the market. It costs nothing and asks for no card.</p>

  <h2>Who Operator is for</h2>
  <p>Operator adds cross index SMT depth and the LodeStone TradingView indicator. LodeStone is a session level toolkit built on ICT concepts, with zero repainting. If you already work across index futures and want that depth on your chart, Operator puts it in one place. Annual billing is listed first because it costs less over the year. Monthly is there if you want to test it for a shorter stretch.</p>

  <h2>What Korvus does not do</h2>
  <p>Korvus does not promise profits and it does not tell you what to trade. It gives you information, scoring and tools. Every decision and every outcome stays with you. Results depend on your own process, risk and discipline.</p>

  <a class="cta" href="/signup">Start with Observer, upgrade when it earns it</a>

  <p class="note">Korvus is market intelligence and educational tooling. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of returns. Futures trading carries substantial risk of loss. Prices shown are current tier prices and may change.</p>
</main>
</body>
</html>
