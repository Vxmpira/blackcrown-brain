# Scribe: Rewrite the complete html document for korvus industries p observer

Date: 2026-10-27
Task: Rewrite the COMPLETE html document for korvus.industries/p/observer, Observer vs Operator comparison page, with these HARD constraints: the literal string <head
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Observer vs Operator: Plans Compared</title>
<meta name="description" content="Korvus Observer is free with no card. Operator adds the LodeStone TradingView indicator. Compare both plans side by side and decide for yourself.">
<link rel="canonical" href="https://korvus.industries/p/observer">
<meta name="robots" content="index, follow">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e8e8ec;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
.top{border-bottom:1px solid #1d1d24;padding:16px 0}
.top .wrap{display:flex;align-items:center;gap:12px}
.brand{font-weight:700;letter-spacing:.08em;color:#fff;text-transform:uppercase;font-size:15px}
.brand svg{width:36px;height:33px;display:block}
.top nav{margin-left:auto;display:flex;gap:18px;font-size:14px}
.top nav a{color:#9a9aa6}
.hero{padding:56px 0 28px}
.eyebrow{color:#ff2d8f;font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin-bottom:12px}
h1{font-size:clamp(28px,5vw,42px);line-height:1.15;color:#fff;margin-bottom:16px}
.lead{color:#b4b4c0;font-size:17px;max-width:680px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:22px}
.chip{border:1px solid #2a2a34;border-radius:999px;padding:5px 12px;font-size:13px;color:#c8c8d2;background:#111116}
.chip.pink{border-color:#ff2d8f;color:#ff2d8f}
.plans{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin:28px 0}
.card{background:#111116;border:1px solid #23232c;border-radius:14px;padding:26px}
.card.hot{border-color:#ff2d8f;box-shadow:0 0 0 1px #ff2d8f inset}
.card h2{color:#fff;font-size:20px;margin-bottom:6px}
.price{font-size:30px;color:#fff;font-weight:700;margin:12px 0 4px}
.price small{font-size:14px;color:#8d8d99;font-weight:400}
.save{display:inline-block;background:#ff2d8f;color:#0a0a0c;font-size:12px;font-weight:700;padding:3px 9px;border-radius:6px;margin-top:4px}
.card ul{list-style:none;margin:16px 0 20px}
.card li{padding:7px 0;border-bottom:1px solid #1c1c24;color:#c8c8d2;font-size:15px}
.btn{display:inline-block;background:#ff2d8f;color:#0a0a0c;font-weight:700;padding:12px 22px;border-radius:10px;font-size:15px}
.btn:hover{text-decoration:none;opacity:.9}
.btn.ghost{background:transparent;color:#ff2d8f;border:1px solid #ff2d8f}
h3.section{color:#fff;font-size:22px;margin:44px 0 14px}
.table-wrap{overflow-x:auto;border:1px solid #23232c;border-radius:14px;background:#111116}
table{width:100%;border-collapse:collapse;font-size:15px;min-width:520px}
th,td{padding:14px 18px;text-align:left;border-bottom:1px solid #1c1c24}
thead th{background:#15151c;color:#ff2d8f;font-size:13px;letter-spacing:.08em;text-transform:uppercase}
tbody th{color:#fff;font-weight:600;width:34%}
td{color:#c8c8d2}
td.yes{color:#ff2d8f;font-weight:600}
td.no{color:#6e6e7a}
.note{font-size:13px;color:#7c7c88;margin-top:12px}
.cta{text-align:center;padding:48px 0 16px}
.cta p{color:#b4b4c0;margin-bottom:18px}
.disclaimer{border-left:3px solid #ff2d8f;background:#111116;padding:16px 20px;border-radius:8px;color:#a8a8b4;font-size:14px;margin:36px 0}
footer{border-top:1px solid #1d1d24;padding:24px 0;color:#6e6e7a;font-size:13px;margin-top:40px}
footer .wrap{display:flex;flex-wrap:wrap;gap:16px;justify-content:space-between}
</style>
</head>
<body>
<div class="top">
  <div class="wrap">
    <a class="brand" href="/" style="display:flex;align-items:center;gap:10px;color:#fff">
      <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
      Korvus
    </a>
    <nav>
      <a href="/lodestone">LodeStone</a>
      <a href="/legal">Legal</a>
      <a href="/login">Log in</a>
    </nav>
  </div>
</div>

<main class="wrap">
  <section class="hero">
    <div class="eyebrow">Plans</div>
    <h1>Observer or Operator. Here is what changes.</h1>
    <p class="lead">Observer is free and needs no card. Operator adds the LodeStone TradingView indicator and costs 79.99 a year or 9.99 a month. Both are the same product. The difference is what you get on top.</p>
    <div class="chips">
      <span class="chip pink">Observer: free, no card</span>
      <span class="chip">Operator: LodeStone included</span>
      <span class="chip">Annual saves 39.89 a year</span>
    </div>
  </section>

  <section class="plans">
    <div class="card hot">
      <h2>Operator</h2>
      <div class="price">79.99 <small>a year</small></div>
      <span class="save">Save 39.89 vs monthly</span>
      <ul>
        <li>Everything in Observer</li>
        <li>LodeStone TradingView indicator included</li>
        <li>Or 9.99 a month, cancel when you like</li>
      </ul>
      <a class="btn" href="https://korvus.industries/signup">Start with Operator</a>
    </div>
    <div class="card">
      <h2>Observer</h2>
      <div class="price">0 <small>forever</small></div>
      <ul>
        <li>No card required</li>
        <li>Market intelligence on the free tier</li>
        <li>Upgrade to Operator at any time</li>
      </ul>
      <a class="btn ghost" href="https://korvus.industries/signup">Create a free account</a>
    </div>
  </section>

  <h3 class="section">Side by side</h3>
  <div class="table-wrap">
    <table>
      <thead>
        <tr><th>Feature</th><th>Observer</th><th>Operator</th></tr>
      </thead>
      <tbody>
        <tr><th>Price</th><td>Free</td><td>79.99 a year or 9.99 a month</td></tr>
        <tr><th>Card needed to start</th><td class="no">No</td><td>Yes, at checkout</td></tr>
        <tr><th>LodeStone TradingView indicator</th><td class="no">Not included</td><td class="yes">Included</td></tr>
        <tr><th>Best for</th><td>Looking around before you pay</td><td>Traders who want the full toolkit</td></tr>
        <tr><th>Cancel</th><td>Nothing to cancel</td><td>Any time from your account</td></tr>
      </tbody>
    </table>
  </div>
  <p class="note">Prices shown are list prices in USD. Plan contents can change. The current terms live on the signup page.</p>

  <section class="cta">
    <p>Test the free tier first. Upgrade only if the tools earn it.</p>
    <a class="btn" href="https://korvus.industries/signup">Sign up at Korvus</a>
  </section>

  <div class="disclaimer">
    Korvus is an information and education product. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Index futures trading carries substantial risk of loss. Past analysis does not predict results.
  </div>
</main>

<footer>
  <div class="wrap">
    <span>BlackCrownVxJ LLC. Korvus.industries</span>
    <span><a href="/legal">Legal</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></span>
  </div>
</footer>
</body>
</html>
