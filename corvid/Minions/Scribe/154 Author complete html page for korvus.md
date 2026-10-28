# Scribe: Author complete html page for korvus p liquidity sweeps into

Date: 2026-10-28
Task: Author COMPLETE html page for korvus /p/liquidity-sweeps into the vault as pages/liquidity-sweeps.html
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Liquidity Sweeps Trading: Index Futures Guide</title>
<meta name="description" content="Liquidity sweeps trading explained for index futures: resting liquidity, session clusters, and how LodeStone and Korvus mark the levels.">
<link rel="canonical" href="https://korvus.industries/p/liquidity-sweeps">
<meta name="robots" content="index, follow">
<style>
:root{--bg:#07080c;--panel:#0f1119;--line:#1f2331;--text:#d8dce8;--muted:#8a90a6;--gold:#d4a84b;--teal:#3fb8a8;--red:#e05d5d}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font:16px/1.65 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:var(--gold);text-decoration:none}
a:hover{text-decoration:underline}
header{border-bottom:1px solid var(--line);padding:18px 24px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:12px}
.brand{display:flex;align-items:center;gap:10px;color:var(--text);font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);margin-left:18px;font-size:14px}
nav a:hover{color:var(--text)}
main{max-width:860px;margin:0 auto;padding:40px 24px 64px}
.eyebrow{color:var(--teal);font-size:13px;letter-spacing:.12em;text-transform:uppercase;margin:0 0 10px}
h1{font-size:clamp(28px,4.4vw,40px);line-height:1.2;margin:0 0 16px;color:#fff}
h2{font-size:22px;color:#fff;margin:44px 0 12px;padding-top:6px;border-top:1px solid var(--line)}
h3{font-size:17px;color:var(--gold);margin:22px 0 6px}
p{margin:0 0 14px}
ul{padding-left:20px;margin:0 0 14px}
li{margin-bottom:6px}
.lede{font-size:18px;color:#c4c9d9}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0 6px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:5px 12px;font-size:13px;color:var(--muted)}
.figure{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:20px;margin:26px 0}
.figure svg{width:100%;height:auto;display:block}
.figure figcaption{color:var(--muted);font-size:13px;margin-top:10px}
.tag{display:inline-block;background:#1b1f2c;color:var(--gold);border:1px solid #3a3320;border-radius:6px;padding:1px 8px;font-size:12px;letter-spacing:.06em;text-transform:uppercase;margin-right:6px}
.mock{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:18px;margin:22px 0;font-family:ui-monospace,Menlo,Consolas,monospace;font-size:14px}
.mock .row{display:flex;justify-content:space-between;padding:7px 0;border-bottom:1px dashed var(--line)}
.mock .row:last-child{border-bottom:0}
.mock .k{color:var(--muted)}
.up{color:var(--teal)}
.dn{color:var(--red)}
.cta{background:linear-gradient(180deg,#14161f,#0f1119);border:1px solid #3a3320;border-radius:14px;padding:26px;margin:38px 0 10px;text-align:center}
.cta h2{border:0;margin:0 0 8px;padding:0}
.btn{display:inline-block;margin-top:10px;background:var(--gold);color:#140f02;font-weight:700;padding:12px 22px;border-radius:8px}
.btn:hover{text-decoration:none;filter:brightness(1.08)}
.disclaimer{border-left:3px solid var(--red);background:var(--panel);padding:14px 16px;color:var(--muted);font-size:14px;border-radius:0 8px 8px 0;margin:30px 0}
footer{border-top:1px solid var(--line);padding:22px 24px;color:var(--muted);font-size:13px;text-align:center}
footer a{color:var(--muted)}
</style>
</head>
<body>
<header>
  <a class="brand" href="https://korvus.industries/" aria-label="Korvus home">
    <svg viewBox="0 0 40 40" aria-hidden="true">
      <polygon points="6,30 8,14 15,22 20,10 25,22 32,14 34,30" fill="none" stroke="#d4a84b" stroke-width="2.2" stroke-linejoin="round"/>
      <rect x="6" y="31" width="28" height="3" fill="#d4a84b"/>
      <circle cx="20" cy="6" r="2" fill="#3fb8a8"/>
    </svg>
    <span>Korvus</span>
  </a>
  <nav>
    <a href="https://korvus.industries/lodestone">LodeStone</a>
    <a href="https://korvus.industries/legal">Legal</a>
    <a href="https://korvus.industries/login">Log in</a>
  </nav>
</header>

<main>
  <p class="eyebrow">Market structure guide</p>
  <h1>Liquidity sweeps trading: how resting orders move index futures</h1>
  <p class="lede">A liquidity sweep is price trading through an obvious level, taking the orders stacked there, and then either reversing or continuing. This guide explains the mechanics, the sessions where they tend to cluster, and how the Korvus stack marks them so you can study them yourself.</p>
  <div class="chips">
    <span class="chip">ES and NQ</span>
    <span class="chip">Resting liquidity</span>
    <span class="chip">Session levels</span>
    <span class="chip">News context</span>
  </div>

  <h2>What resting liquidity is</h2>
  <p>Resting liquidity is working orders that sit in the book waiting to be filled. Most of the orders that matter in index futures are not hidden. They are placed in predictable places that many traders also watch.</p>
  <ul>
    <li>Stop orders for short positions usually rest just above prior highs.</li>
    <li>Stop orders for long positions usually rest just below prior lows.</li>
    <li>Equal highs and equal lows give many participants the same obvious level.</li>
    <li>Prior day and prior week highs and lows are watched by desks across the session.</li>
  </ul>
  <p>When a level like this is clear to many participants, the orders stacked behind it are a pool of liquidity. Price has to trade through the level to reach that pool.</p>

  <h2>Why price sweeps prior highs and lows</h2>
  <p>A sweep is the move through the level. The wick or push takes out the stops and pending orders, often within a few ticks, and price comes back inside the range. Some traders call this a stop run. The label matters less than the sequence: an obvious level is breached, activity spikes, and the level stops working as support or resistance.</p>
  <p>What happens after a sweep is not guaranteed. Price can reverse hard, drift, or continue through the level and keep going. A sweep describes what the tape did. It does not say what comes next. Anyone who tells you a sweep always means a specific direction is selling you certainty.</p>

  <figure class="figure">
    <svg viewBox="0 0 640 260" role="img" aria-label="Illustration of price sweeping above a prior high and closing back inside the range">
      <rect x="0" y="0" width="640" height="260" fill="#0f1119"/>
      <line x1="30" y1="90" x2="610" y2="90" stroke="#d4a84b" stroke-width="1.5" stroke-dasharray="6 6"/>
      <line x1="30" y1="170" x2="610" y2="170" stroke="#3a4158" stroke-width="1" stroke-dasharray="3 5"/>
      <polyline points="40,170 100,150 150,160 200,130 250,140 300,118 340,128 380,95 410,70 440,96 470,120 510,140 560,150 610,146" fill="none" stroke="#3fb8a8" stroke-width="2.4" stroke-linejoin="round"/>
      <circle cx="410" cy="70" r="4" fill="#e05d5d"/>
      <rect x="380" y="110" width="200" height="0" fill="none"/>
      <text x="36" y="82" fill="#d4a84b" font-size="13" font-family="system-ui,sans-serif">Prior high</text>
      <text x="36" y="164" fill="#8a90a6" font-size="13" font-family="system-ui,sans-serif">Range floor</text>
      <text x="420" y="66" fill="#e05d5d" font-size="13" font-family="system-ui,sans-serif">Sweep wick</text>
      <text x="470" y="230" fill="#8a90a6" font-size="12" font-family="system-ui,sans-serif">Close back inside the range</text>
    </svg>
    <figcaption><span class="tag">Illustration</span> Schematic only. Not a chart of any real session and not a signal.</figcaption>
  </figure>

  <h2>Sessions where sweeps cluster</h2>
  <p>Sweeps show up across the day, but they tend to bunch around moments when new liquidity arrives and older levels get tested.</p>
  <h3>Asia range</h3>
  <p>The overnight range often forms the levels the London session tests. Many traders mark the Asia high and low before the European open.</p>
  <h3>London open</h3>
  <p>The first push out of the London open frequently probes Asia highs and lows and the prior day levels. This is one of the most watched windows for sweep behavior.</p>
  <h3>New York cash open</h3>
  <p>The U.S. cash open brings the largest volume shift in index futures. Sweeps of London levels and overnight extremes are common in the first hour, and so are fast reversals.</p>
  <h3>Lunch and late session</h3>
  <p>Volume often thins midday. Sweeps can still occur, but they are more likely to run into a thin book and fade quickly.</p>

  <h2>How LodeStone marks resting liquidity and sweep cleanup</h2>
  <p>LodeStone is the chart side of the Korvus stack, a session level toolkit built on ICT concepts for index futures. It draws the levels a sweep trader would otherwise mark by hand, so the study is faster and more consistent.</p>
  <ul>
    <li>Session levels with timezone control, including Asia, London, and New York ranges.</li>
    <li>Prior day and prior week highs and lows, marked as resting liquidity pools.</li>
    <li>Premium and discount framing around the current range.</li>
    <li>Sweep cleanup, which removes levels once they have been taken so the chart stays readable.</li>
    <li>Restrained volume profile and SMT divergence context for cross checking a sweep.</li>
  </ul>
  <p>LodeStone does not repaint, so the levels you study are the levels that were on the chart at the time. It is a study tool. It does not place trades or tell you which way to trade.</p>

  <div class="mock" aria-label="Illustration of a level panel">
    <span class="tag">Illustration</span>
    <div class="row"><span class="k">Asia high</span><span>marked, untaken</span></div>
    <div class="row"><span class="k">London low</span><span class="dn">swept, cleaned up</span></div>
    <div class="row"><span class="k">Prior day high</span><span>marked, resting liquidity</span></div>
    <div class="row"><span class="k">Prior week low</span><span class="up">in range</span></div>
  </div>

  <h2>How Korvus adds the news context</h2>
  <p>A sweep on a quiet tape reads differently from a sweep into a scheduled release or a headline spike. Korvus runs a 24/7 market intelligence terminal that scores incoming news so you can see the backdrop next to the levels.</p>
  <ul>
    <li>Each scored item shows impact, direction, and confidence.</li>
    <li>A written Korvus read explains the context in plain language.</li>
    <li>Economic agenda and actuals help you see when the session is about to get busy.</li>
  </ul>
  <p>The news layer is context, not a forecast. A sweep with a strong news backdrop is still a sweep, and the outcome is still unknown until the tape confirms it.</p>

  <section class="cta">
    <h2>Study the levels alongside the news</h2>
    <p>Korvus Observer is free. Operator adds the LodeStone TradingView indicator and the full terminal. Plans and savings are shown at signup.</p>
    <a class="btn" href="https://korvus.industries/signup?utm_source=korvus_page&amp;utm_medium=seo&amp;utm_campaign=liquidity-sweeps&amp;utm_content=cta">Start with the free Observer tier</a>
  </section>

  <div class="disclaimer">
    <strong>Not financial advice.</strong> This page is education about market structure. Korvus and LodeStone are analysis tools, not investment advisers. Nothing here is a recommendation to buy, sell, or hold any instrument, and no result is promised. Index futures carry substantial risk of loss and are not suitable for everyone. Past sweeps do not predict future price.
  </div>
</main>

<footer>
  <p>Korvus, a product of BlackCrownVxJ LLC. <a href="https://korvus.industries/legal">Legal</a> | <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></p>
  <p>Your edge while the world sleeps.</p>
</footer>
</body>
</html>
