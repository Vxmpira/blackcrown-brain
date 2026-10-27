# Scribe: Rewrite the complete html document for korvus industries p observer

Date: 2026-10-27
Task: Rewrite the COMPLETE html document for korvus.industries/p/observer, Observer vs Operator comparison. HARD CONSTRAINT: never use the <header> or </header> tags 
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Observer vs Operator | Korvus</title>
<meta name="description" content="Compare Korvus Observer and Operator side by side. Free scored news and futures basics, or the full terminal with cross index SMT, session context and LodeStone included.">
<link rel="canonical" href="https://korvus.industries/p/observer">
<style>
:root{--bg:#07080c;--panel:#0d0f16;--line:#1d2130;--text:#e7e9f0;--muted:#8b91a4;--pink:#ff2d8f;--cyan:#2de1ff}
*{box-sizing:border-box}
body{margin:0;background:radial-gradient(900px 500px at 50% -10%,#1a0d1f 0%,var(--bg) 60%);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6;min-height:100vh}
.wrap{max-width:1000px;margin:0 auto;padding:0 20px}
.topbar{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
.brand svg{width:36px;height:33px;vertical-align:middle;margin-right:8px}
.topbar a.navlink{margin-left:auto;color:var(--muted);text-decoration:none;font-size:14px}
.hero{padding:56px 0 28px;text-align:center}
.eyebrow{color:var(--cyan);font-size:12px;letter-spacing:.2em;text-transform:uppercase}
h1{font-size:clamp(32px,5vw,48px);margin:12px 0 14px;letter-spacing:-.01em}
.lede{color:var(--muted);max-width:640px;margin:0 auto;font-size:17px}
.chips{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin:26px 0 8px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:7px 14px;font-size:13px;color:var(--muted)}
.chip b{color:var(--text);font-weight:600}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px;margin:26px 0}
.tablewrap{overflow-x:auto}
table{width:100%;border-collapse:collapse;font-size:15px}
th,td{padding:14px 12px;border-bottom:1px solid var(--line);text-align:left;vertical-align:top}
th{font-size:13px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);font-weight:600}
th.op{color:var(--pink)}
td.feat{color:var(--text);width:34%}
td.no{color:#4d5268}
.yes{color:var(--text)}
.tag{display:inline-block;background:rgba(255,45,143,.12);color:var(--pink);border:1px solid rgba(255,45,143,.35);border-radius:6px;padding:2px 8px;font-size:12px;margin-left:6px;letter-spacing:.04em}
.illus{color:var(--muted);font-size:12px;margin-top:10px;text-align:right}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin:26px 0}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:24px}
.card h2{margin:0 0 6px;font-size:20px}
.card .price{font-size:26px;font-weight:700;margin:8px 0 4px}
.card .sub{color:var(--muted);font-size:14px;margin-bottom:14px}
.card ul{padding-left:18px;margin:12px 0 0;color:var(--muted);font-size:15px}
.card li{margin:6px 0}
.card.op{border-color:rgba(255,45,143,.45);box-shadow:0 0 0 1px rgba(255,45,143,.12) inset}
.save{color:var(--cyan);font-size:13px;margin-top:2px}
.btn{display:block;text-align:center;margin-top:18px;padding:13px 16px;border-radius:10px;text-decoration:none;font-weight:600;font-size:15px}
.btn.primary{background:var(--pink);color:#12040b}
.btn.ghost{border:1px solid var(--line);color:var(--text)}
.note{color:var(--muted);font-size:13px;text-align:center;margin:8px 0 0}
.ctaband{text-align:center;padding:40px 20px;border:1px solid var(--line);border-radius:14px;background:var(--panel);margin:30px 0}
.ctaband h2{margin:0 0 8px;font-size:24px}
.ctaband p{color:var(--muted);margin:0 0 18px}
.ctaband .btn{display:inline-block;padding:13px 26px}
.foot{border-top:1px solid var(--line);padding:26px 0 40px;color:var(--muted);font-size:13px}
.foot p{margin:6px 0}
@media (max-width:720px){.grid{grid-template-columns:1fr}.topbar a.navlink{display:none}}
</style>
</head>
<body>
<div class="wrap">
  <div class="topbar">
    <div class="brand">
      <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" aria-hidden="true">
        <path d="M4 27 L6 10 L13 18 L18 5 L23 18 L30 10 L32 27 Z"/>
        <line x1="4" y1="31" x2="32" y2="31"/>
      </svg>
      Korvus
    </div>
    <a class="navlink" href="/lodestone">LodeStone</a>
  </div>

  <section class="hero">
    <div class="eyebrow">Plans compared</div>
    <h1>Observer vs Operator</h1>
    <p class="lede">Observer is the free look at the market. Operator is the full terminal. Both run on the same scored wire, so you can start free and decide with evidence.</p>
    <div class="chips">
      <span class="chip"><b>Free</b> tier, no card</span>
      <span class="chip">Scored news feed</span>
      <span class="chip">Cross index SMT</span>
      <span class="chip">Session and macro context</span>
      <span class="chip">LodeStone included on Operator</span>
    </div>
  </section>

  <section class="panel">
    <div class="tablewrap">
      <table>
        <thead>
          <tr>
            <th>Feature</th>
            <th>Observer</th>
            <th class="op">Operator</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="feat">Price</td>
            <td>Free, no card</td>
            <td class="yes">Current pricing shown at signup</td>
          </tr>
          <tr>
            <td class="feat">Scored news feed</td>
            <td class="yes">Included</td>
            <td class="yes">Included, full history</td>
          </tr>
          <tr>
            <td class="feat">Futures board</td>
            <td class="yes">Basics</td>
            <td class="yes">Full board</td>
          </tr>
          <tr>
            <td class="feat">Cross index SMT divergence</td>
            <td class="no">Not included</td>
            <td class="yes">Included</td>
          </tr>
          <tr>
            <td class="feat">Session and macro context</td>
            <td class="no">Not included</td>
            <td class="yes">Included</td>
          </tr>
          <tr>
            <td class="feat">Full terminal</td>
            <td class="no">Not included</td>
            <td class="yes">Included</td>
          </tr>
          <tr>
            <td class="feat">LodeStone TradingView indicator</td>
            <td class="no">Not included</td>
            <td class="yes">Included <span class="tag">Operator only</span></td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="illus">Illustration: plan contents as of this page. Current pricing is shown at signup.</div>
  </section>

  <section class="grid">
    <div class="card">
      <h2>Observer</h2>
      <div class="sub">Start here. No card, no clock.</div>
      <div class="price">Free</div>
      <div class="sub">Current pricing shown at signup</div>
      <ul>
        <li>Scored news feed</li>
        <li>Futures board basics</li>
        <li>Enough to learn how the wire reads</li>
      </ul>
      <a class="btn ghost" href="/signup">Start with Observer</a>
    </div>
    <div class="card op">
      <h2>Operator</h2>
      <div class="sub">The full terminal for index futures traders.</div>
      <div class="price">79.99 a year</div>
      <div class="save">Annual listed first. Save about 33 percent against monthly.</div>
      <div class="price" style="font-size:20px;margin-top:10px">9.99 a month</div>
      <div class="sub">Current pricing shown at signup</div>
      <ul>
        <li>Full terminal and cross index SMT divergence</li>
        <li>Session and macro context</li>
        <li>LodeStone TradingView indicator included</li>
      </ul>
      <a class="btn primary" href="/signup">Choose Operator</a>
    </div>
  </section>

  <p class="note">Start free and upgrade whenever the terminal earns its place in your routine.</p>

  <section class="ctaband">
    <h2>See the wire before you pay for it</h2>
    <p>Observer is free and takes a minute to set up. Operator adds the terminal when you want it.</p>
    <a class="btn primary" href="/signup">Create your account</a>
  </section>

  <footer class="foot">
    <p>Market information, not financial advice. Korvus provides scored news, market data views and education tools. Nothing on this page is a recommendation to buy, sell or hold any instrument.</p>
    <p>No profit promises. Trading index futures carries substantial risk of loss. Past readings and illustrations do not predict results.</p>
    <p>Business contact: BlackCrownVxJ.LLC@outlook.com. Your edge while the world sleeps.</p>
  </footer>
</div>
</body>
</html>
