# Scribe: Write the complete html document for a new korvus guide

Date: 2026-10-29
Task: Write the COMPLETE html document for a new Korvus guide page: futures contract expiration and rollover explained for beginners (ES, NQ, MES, MNQ quarterly cycle
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Futures Rollover Explained: ES, NQ, MES, MNQ</title>
<meta name="description">
<meta name="description" content="Learn how index futures expire and roll. A beginner guide to the ES, NQ, MES and MNQ quarterly cycle, contract codes, and why front month matters.">
<link rel="canonical" href="https://korvus.industries/p/futures-rollover-explained">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07070b;--ink:#e9e7ef;--mute:#9a97a8;--pink:#ff2d8f;--cyan:#27d3f0;--line:#23222c;--card:#0f0f16}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.65}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60vw 40vh at 15% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50vw 40vh at 90% 10%,rgba(39,211,240,.14),transparent 70%),radial-gradient(60vw 50vh at 50% 100%,rgba(255,45,143,.08),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.08em;text-transform:uppercase}
.brand svg{width:36px;height:33px;stroke:var(--pink);fill:none;stroke-width:2;stroke-linejoin:round;stroke-linecap:round}
nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:.95rem}
nav a:hover{color:var(--ink)}
.hero{padding:48px 0 28px}
.eyebrow{color:var(--cyan);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;font-weight:600}
h1{font-size:clamp(2rem,5vw,3.2rem);line-height:1.12;margin:12px 0 16px;letter-spacing:-.01em}
h2{font-size:clamp(1.4rem,3vw,1.9rem);margin:44px 0 12px}
h3{font-size:1.1rem;margin:0 0 6px;color:var(--ink)}
p,li{color:#d4d1de}
.prose{max-width:75ch}
.prose p{margin:0 0 14px}
.prose ul{margin:0 0 14px 20px}
.lede{font-size:1.1rem;color:var(--ink)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0 0}
.chip{border:1px solid var(--line);background:var(--card);border-radius:999px;padding:6px 14px;font-size:.85rem;color:var(--mute)}
.chip b{color:var(--pink);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:18px 0}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:20px}
.card code{color:var(--cyan);font-family:ui-monospace,Menlo,Consolas,monospace}
.fig{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:22px;margin:22px 0}
.fig-tag{display:inline-block;font-size:.72rem;letter-spacing:.12em;text-transform:uppercase;color:var(--pink);border:1px solid rgba(255,45,143,.5);border-radius:6px;padding:2px 8px;margin-bottom:12px}
.fig-cap{color:var(--mute);font-size:.88rem;margin-top:12px}
table{width:100%;border-collapse:collapse;font-size:.95rem}
th,td{text-align:left;padding:12px 10px;border-bottom:1px solid var(--line)}
th{color:var(--cyan);font-weight:600;font-size:.82rem;letter-spacing:.06em;text-transform:uppercase}
td.hot{color:var(--pink);font-weight:600}
.timeline{display:flex;gap:0;margin:18px 0 6px;position:relative}
.timeline::before{content:"";position:absolute;left:8px;right:8px;top:11px;height:2px;background:linear-gradient(90deg,var(--cyan),var(--pink))}
.tick{flex:1;text-align:center;position:relative;font-size:.8rem;color:var(--mute);padding-top:28px}
.tick::before{content:"";position:absolute;left:50%;top:4px;width:14px;height:14px;margin-left:-7px;border-radius:50%;background:var(--bg);border:2px solid var(--cyan)}
.tick.roll::before{border-color:var(--pink);background:var(--pink)}
.tick b{display:block;color:var(--ink)}
.cta{margin:44px 0 10px;background:linear-gradient(135deg,rgba(255,45,143,.14),rgba(39,211,240,.10));border:1px solid var(--line);border-radius:16px;padding:26px;display:flex;align-items:center;justify-content:space-between;gap:18px;flex-wrap:wrap}
.cta p{margin:0;max-width:52ch}
.btn{display:inline-block;background:var(--ink);color:var(--bg);text-decoration:none;font-weight:700;padding:12px 20px;border-radius:10px}
.related{margin:40px 0 10px}
.related ul{list-style:none;display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.related a{display:block;height:100%;text-decoration:none;color:var(--ink);background:var(--card);border:1px solid var(--line);border-radius:12px;padding:16px}
.related a span{display:block;color:var(--mute);font-size:.88rem;margin-top:4px}
.related a:hover{border-color:var(--pink)}
.disclaimer{margin:36px 0 0;padding:18px 0 0;border-top:1px solid var(--line);color:var(--mute);font-size:.85rem;max-width:75ch}
footer{padding:28px 0 44px;color:var(--mute);font-size:.85rem;display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
footer a{color:var(--mute)}
@media (max-width:700px){
.grid,.related ul{grid-template-columns:1fr}
nav a{margin-left:12px}
.cta{flex-direction:column;align-items:flex-start}
.timeline{flex-direction:column;gap:14px}
.timeline::before{top:0;bottom:0;left:10px;right:auto;width:2px;height:auto;background:linear-gradient(180deg,var(--cyan),var(--pink))}
.tick{text-align:left;padding:0 0 0 30px}
.tick::before{left:4px;top:4px;margin:0}
.table-wrap{overflow-x:auto}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="https://korvus.industries/" aria-label="Korvus home">
<svg viewBox="0 0 36 33" role="img" aria-label="Korvus crown mark"><path d="M4 26 L6 10 L13 18 L18 6 L23 18 L30 10 L32 26 Z"/><path d="M4 30 H32"/></svg>
<span>Korvus</span>
</a>
<nav aria-label="Primary">
<a href="https://korvus.industries/lodestone">LodeStone</a>
<a href="https://korvus.industries/signup">Sign up</a>
<a href="https://korvus.industries/login">Log in</a>
</nav>
</header>

<section class="hero">
<div class="eyebrow">Beginner guide</div>
<h1>Futures Rollover Explained: How Index Contracts Expire and Roll</h1>
<p class="lede prose">Index futures do not last forever. Every contract has an expiration date, and the contract you see on your chart changes as that date approaches. This guide walks through the quarterly cycle behind ES, NQ, MES and MNQ, so the roll stops being a surprise.</p>
<div class="chips" aria-label="Topics covered">
<span class="chip"><b>Quarterly</b> cycle</span>
<span class="chip"><b>Contract</b> codes</span>
<span class="chip"><b>Front month</b> basics</span>
<span class="chip"><b>Beginner</b> safe</span>
</div>
</section>

<section class="prose">
<h2>What expiration actually means</h2>
<p>A futures contract is an agreement with a set end date. When that date arrives, the contract stops trading and is settled. For the equity index products covered here, settlement is cash based. Nobody receives shares. Open positions are closed out at the final settlement price, and the account is credited or debited.</p>
<p>Expiration is not the same as the day traders switch. Most activity moves to the next contract well before the expiring one stops trading. That move is the roll.</p>

<h2>The quarterly cycle</h2>
<p>E-mini S&amp;P 500 (ES), E-mini Nasdaq-100 (NQ), Micro E-mini S&amp;P 500 (MES) and Micro E-mini Nasdaq-100 (MNQ) share the same four-times-a-year calendar. Contracts expire in March, June, September and December. The expiration is tied to the third Friday of each of those months.</p>
<p>Each contract has a month code. The codes are the same across all four products:</p>
<ul>
<li><strong>H</strong> is March</li>
<li><strong>M</strong> is June</li>
<li><strong>U</strong> is September</li>
<li><strong>Z</strong> is December</li>
</ul>
<p>Put the root symbol and the code together and you get the contract name. ESM is the June E-mini S&amp;P contract. NQZ is the December E-mini Nasdaq contract. MESU and MNQH follow the same pattern for the micros.</p>
</section>

<section class="prose">
<h2>Reading the roll with an illustration</h2>
<p>The timeline below shows the general shape of a quarterly roll. It is a teaching sketch, not a live schedule.</p>
</section>

<figure class="fig" aria-label="Illustrative quarterly roll calendar">
<span class="fig-tag">Illustration</span>
<div class="timeline" role="list">
<div class="tick" role="listitem"><b>Weeks before</b>Front month trades normally, volume is concentrated here</div>
<div class="tick roll" role="listitem"><b>Roll window</b>Volume and open interest shift to the next contract</div>
<div class="tick" role="listitem"><b>Expiry Friday</b>Third Friday, the expiring contract settles</div>
<div class="tick" role="listitem"><b>After expiry</b>Next quarter becomes the active front month</div>
</div>
<div class="table-wrap">
<table>
<thead>
<tr><th>Stage</th><th>Typical timing (illustration)</th><th>What a beginner sees</th></tr>
</thead>
<tbody>
<tr><td>Normal trading</td><td>Most of the quarter</td><td>One front month with the deepest liquidity</td></tr>
<tr><td>Roll window</td><td>Roughly the final week or two before expiry</td><td>Two contracts trade side by side, prices can differ</td></tr>
<tr><td class="hot">Expiry</td><td>Third Friday of Mar, Jun, Sep, Dec</td><td>Expiring contract stops trading and settles</td></tr>
<tr><td>Next front month</td><td>Immediately after expiry</td><td>The next quarterly code becomes the default</td></tr>
</tbody>
</table>
</div>
<p class="fig-cap">Illustration only. Exact roll timing varies by product and by holiday calendar. Check the exchange contract specifications before you rely on any date.</p>
</figure>

<section class="prose">
<h2>Why the front month matters on charts</h2>
<p>Many charting platforms show a continuous contract. It stitches the front months together so you see one unbroken line. The stitch is where people get tripped up. When the roll happens, the old and new contracts can trade at slightly different prices. A gap appears that is not a real market move.</p>
<p>Know which contract your chart is showing. Check whether the chart is the expiring month, the next month, or a continuous series. The same five minute candle can look different depending on which one you are reading.</p>

<h2>Common beginner mistakes</h2>
<ul>
<li>Reading a roll gap as a new trend or a broken level.</li>
<li>Holding a position into expiry without knowing it is cash settled or how your broker closes it.</li>
<li>Comparing price levels across two contract months as if they were the same instrument.</li>
<li>Assuming the micro and the standard contract roll on different days. They share the same expiry calendar.</li>
<li>Forgetting that expiry Friday can carry thin liquidity and sharp moves in the final hours.</li>
</ul>
</section>

<section class="related" aria-label="Related guides">
<h2>Keep reading</h2>
<ul>
<li><a href="https://korvus.industries/p/futures-tick-value-explained">Tick value explained<span>What a single tick is worth in ES, NQ, MES and MNQ.</span></a></li>
<li><a href="https://korvus.industries/p/futures-margin-explained">Margin explained<span>Initial and maintenance margin, and why it moves.</span></a></li>
<li><a href="https://korvus.industries/p/futures-trading-sessions">Trading sessions<span>Globex hours, the cash open, and when volume shows up.</span></a></li>
</ul>
</section>

<section class="cta" aria-label="Korvus free account">
<p>Korvus watches index futures around the clock and keeps the context in one place. A free account costs nothing to open, and you can judge the output yourself.</p>
<a class="btn" href="https://korvus.industries/signup">Create a free account</a>
</section>

<p class="disclaimer">Education only. This page explains how futures contracts expire and roll. It is not financial advice, a recommendation to buy or sell any instrument, or a promise of any result. Futures carry substantial risk of loss and are not suitable for everyone. Verify contract dates and specifications with the exchange before trading. Korvus and BlackCrownVxJ LLC are not responsible for decisions made from this material.</p>
</div>

<footer class="wrap">
<span>BlackCrownVxJ LLC. Your edge while the world sleeps.</span>
<span><a href="https://korvus.industries/legal">Legal</a> · <a href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact</a></span>
</footer>
</body>
</html>
