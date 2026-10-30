# Scribe: Write the complete html document for a new korvus guide

Date: 2026-10-29
Task: Write the COMPLETE html document for a new Korvus guide page: SMT divergence explained for beginners. Canonical https://korvus.industries/p/smt-divergence-expla
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<!-- Filing note: the canonical slug given in the task is "smt-divergence-expla". Confirm the intended slug before the proposal is filed. -->
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Explained for Beginners | Korvus</title>
<meta name="description" content="A plain guide to SMT divergence for index futures traders. What it is, how to read correlated charts, a worked illustration, and the mistakes beginners make. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence-expla">
<meta property="og:title" content="SMT Divergence Explained for Beginners">
<meta property="og:description" content="What SMT divergence means on index futures, how to compare correlated charts, and what it cannot tell you. Education only, not financial advice.">
<meta property="og:type" content="article">
<meta property="og:url" content="https://korvus.industries/p/smt-divergence-expla">
<meta name="robots" content="index, follow">
<style>
:root{
  --bg:#07070b;
  --panel:#0e0e16;
  --line:#23232f;
  --text:#e7e7ef;
  --muted:#9a9aae;
  --pink:#ff2d8f;
  --cyan:#3fd0ff;
  --amber:#ffb547;
}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  color:var(--text);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  line-height:1.65;
  min-height:100vh;
  background-color:var(--bg);
  background-image:
    radial-gradient(60% 40% at 15% 0%, rgba(255,45,143,.16), transparent 70%),
    radial-gradient(50% 35% at 90% 10%, rgba(63,208,255,.12), transparent 70%),
    radial-gradient(70% 50% at 50% 100%, rgba(255,181,71,.07), transparent 75%),
    linear-gradient(rgba(255,255,255,.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.03) 1px, transparent 1px),
    radial-gradient(120% 90% at 50% 50%, transparent 55%, rgba(0,0,0,.65) 100%);
  background-size:auto,auto,auto,56px 56px,56px 56px,auto;
  background-attachment:fixed;
}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header.top{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text);font-weight:700;letter-spacing:.04em}
.brand svg{width:36px;height:33px}
.brand span{font-size:18px}
nav.links{display:flex;gap:18px;flex-wrap:wrap}
nav.links a{color:var(--muted);text-decoration:none;font-size:15px}
nav.links a:hover{color:var(--text)}
main{padding-bottom:40px}
.hero{padding:36px 0 18px}
.eyebrow{color:var(--pink);font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin:0 0 10px}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:0 0 16px;font-weight:800}
h2{font-size:clamp(21px,3.2vw,28px);margin:44px 0 14px;line-height:1.25}
h3{font-size:clamp(17px,2.4vw,19px);margin:0 0 8px}
.lede{font-size:clamp(17px,2.2vw,19px);color:var(--text);max-width:75ch;margin:0}
.prose{max-width:75ch}
.prose p{margin:0 0 16px;color:#d6d6e2}
.prose ol,.prose ul{margin:0 0 16px;padding-left:22px;color:#d6d6e2}
.prose li{margin-bottom:8px}
.panel{
  background:linear-gradient(180deg,rgba(14,14,22,.92),rgba(10,10,16,.92));
  border:1px solid var(--line);
  border-radius:14px;
  padding:22px;
}
.figure{margin:24px 0 8px}
.figure svg{width:100%;height:auto;display:block;background:var(--panel);border:1px solid var(--line);border-radius:14px}
.caption{font-size:14px;color:var(--muted);margin:10px 0 0}
.tag{display:inline-block;font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--amber);border:1px solid rgba(255,181,71,.4);padding:2px 8px;border-radius:999px;margin-right:6px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:18px 0 6px}
.chip{background:var(--panel);border:1px solid var(--line);border-radius:999px;padding:8px 14px;font-size:14px;color:var(--text)}
.chip b{color:var(--cyan);font-weight:700;margin-right:6px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:18px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.card p{margin:0;color:#c9c9d8;font-size:15px}
.mock{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:18px 0}
.mock div{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:14px}
.mock small{display:block;color:var(--muted);font-size:12px;text-transform:uppercase;letter-spacing:.08em}
.mock strong{font-size:18px}
.up{color:#4ade80}
.down{color:#f87171}
.disclaimer{font-size:14px;color:var(--muted);border-left:3px solid var(--amber);padding:6px 0 6px 14px;margin:28px 0 0;max-width:75ch}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin:26px 0 0}
.btn{display:inline-block;background:var(--pink);color:#fff;text-decoration:none;font-weight:700;padding:12px 20px;border-radius:10px}
.btn.ghost{background:transparent;border:1px solid var(--line);color:var(--text)}
footer{border-top:1px solid var(--line);padding:24px 0 36px;color:var(--muted);font-size:14px}
footer a{color:var(--muted)}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  .mock{grid-template-columns:1fr}
  nav.links{gap:12px}
}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <a class="brand" href="https://korvus.industries/" aria-label="Korvus home">
      <svg viewBox="0 0 36 33" aria-label="Crown mark" role="img" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M4 26 L6 10 L13 18 L18 6 L23 18 L30 10 L32 26 Z"/>
        <path d="M4 30 L32 30"/>
      </svg>
      <span>KORVUS</span>
    </a>
    <nav class="links" aria-label="Primary">
      <a href="https://korvus.industries/lodestone">LodeStone</a>
      <a href="https://korvus.industries/legal">Legal</a>
      <a href="https://korvus.industries/login">Log in</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <p class="eyebrow">Korvus guide</p>
      <h1>SMT Divergence Explained for Beginners</h1>
      <p class="lede">SMT divergence is a way to compare two or three correlated index futures charts and notice when one fails to confirm what the others just did. This guide explains the idea in plain language, shows what it looks like, and lists the mistakes new traders make with it.</p>
      <p style="margin-top:14px"><span class="tag">Education only</span><span class="tag">Not financial advice</span></p>
    </section>

    <section class="prose">
      <h2>What SMT stands for</h2>
      <p>SMT is short for Smart Money Technique. The name comes from a family of chart concepts that look at how price moves relative to other markets. The version most index traders meet first compares closely related futures contracts, such as the E-mini S&amp;P 500 (ES) and the E-mini Nasdaq 100 (NQ), and checks whether they agree at the same moments.</p>
      <p>The core observation is simple. These markets usually move together. When they stop agreeing, that disagreement is the thing people call divergence.</p>

      <h2>The basic idea in three steps</h2>
      <ol>
        <li>Pick two or three related contracts that normally track each other, for example ES, NQ and YM.</li>
        <li>Watch for one market to make a new high or new low while another does not make a matching one at the same time.</li>
        <li>Note the disagreement. Treat it as information to study, not as a signal to act on.</li>
      </ol>
      <p>That is the whole concept. Everything else is about reading it carefully and understanding its limits.</p>
    </section>

    <section>
      <h2>What it looks like</h2>
      <p class="caption" style="margin:0 0 10px"><span class="tag">Illustration</span>Two index lines, drawn for teaching only. Not market data.</p>
      <figure class="figure" style="margin-left:0;margin-right:0">
        <svg viewBox="0 0 640 300" role="img" aria-label="Illustration showing two index lines. Line A makes a higher high while line B fails to make a matching higher high, a divergence.">
          <line x1="40" y1="260" x2="600" y2="260" stroke="#23232f" stroke-width="1"/>
          <line x1="40" y1="40" x2="40" y2="260" stroke="#23232f" stroke-width="1"/>
          <line x1="40" y1="150" x2="600" y2="150" stroke="#1b1b26" stroke-width="1" stroke-dasharray="4 6"/>
          <polyline points="40,200 110,170 160,210 230,120 290,180 350,90 420,150 480,70 540,120 600,60" fill="none" stroke="#3fd0ff" stroke-width="3" stroke-linejoin="round"/>
          <polyline points="40,205 110,175 160,215 230,130 290,185 350,110 420,160 480,115 540,140 600,125" fill="none" stroke="#ffb547" stroke-width="3" stroke-linejoin="round"/>
          <circle cx="480" cy="70" r="6" fill="#ff2d8f"/>
          <circle cx="480" cy="115" r="6" fill="#ff2d8f"/>
          <text x="500" y="62" fill="#e7e7ef" font-size="14" font-family="system-ui,sans-serif">Line A new high</text>
          <text x="500" y="128" fill="#e7e7ef" font-size="14" font-family="system-ui,sans-serif">Line B no match</text>
          <text x="48" y="28" fill="#9a9aae" font-size="13" font-family="system-ui,sans-serif">Illustration</text>
        </svg>
      </figure>
      <p class="caption">In the drawing, line A reaches a higher high. Line B, the related market, does not reach a matching high at that same point. The gap between them is the divergence the lesson is about.</p>
    </section>

    <section class="prose">
      <h2>Why traders look at it</h2>
      <p>Index futures are linked. Large moves in one often show up in the others. A divergence can show that a move is being tested, that participants are not agreeing on the direction, or that one market is carrying a move the others are not confirming. None of those readings is a promise about what happens next.</p>
      <p>Many traders use divergence as a context tool. It tells them where to look more closely, which levels to watch, and which questions to ask before they make any decision on their own.</p>
    </section>

    <section>
      <h2>Ways to read it</h2>
      <div class="grid">
        <div class="card">
          <h3>Confirmation</h3>
          <p>Both markets make a similar high or low together. The picture agrees. Beginners often treat this as the baseline and learn to notice when it breaks.</p>
        </div>
        <div class="card">
          <h3>Divergence</h3>
          <p>One market makes a new extreme and the other does not. The disagreement is the observation. What it means depends on the surrounding structure, the session and the levels involved.</p>
        </div>
        <div class="card">
          <h3>Timing matters</h3>
          <p>Divergence is judged at the same moments on the same timeframe. Comparing a 1 minute chart on one market to a 15 minute chart on another creates false readings.</p>
        </div>
        <div class="card">
          <h3>Context first</h3>
          <p>A divergence in the middle of a quiet range is different from one at a major prior day or week level. Beginners learn the setting before they learn the label.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Illustration: what a reading card might look like</h2>
      <p class="caption" style="margin:0 0 10px"><span class="tag">Illustration</span>Sample layout only. Numbers are placeholders, not data.</p>
      <div class="mock" role="group" aria-label="Illustrative comparison card">
        <div><small>Market A, illustration</small><strong class="up">Higher high</strong></div>
        <div><small>Market B, illustration</small><strong class="down">No matching high</strong></div>
        <div><small>Reading, illustration</small><strong>Divergence noted</strong></div>
      </div>
      <p class="caption">A learning checklist, not a trade plan. The card only asks the question. It does not answer it.</p>
    </section>

    <section class="prose">
      <h2>Common beginner mistakes</h2>
      <ul>
        <li>Treating every small disagreement as meaningful. Most are noise.</li>
        <li>Comparing charts on different timeframes and calling the result a divergence.</li>
        <li>Ignoring session context, such as the open, a news release, or a thin overnight market.</li>
        <li>Assuming a divergence must resolve in a specific direction. It does not have to.</li>
        <li>Using one divergence as a complete reason to act. It is one observation among many.</li>
      </ul>
    </section>

    <section class="prose">
      <h2>What it cannot tell you</h2>
      <p>SMT divergence does not predict price. It does not show size, timing or outcome. Markets can diverge and keep trending. They can diverge and reverse. They can diverge and go nowhere. A reading is useful for study and journaling, and it is only that until you have tested your own process against your own rules.</p>
      <p>Korvus does not give trading advice, and nothing on this page is a recommendation to buy, sell or hold any instrument.</p>
    </section>

    <section>
      <h2>Where this fits in Korvus</h2>
      <div class="chips" aria-label="Related tools">
        <span class="chip"><b>LodeStone</b>session level toolkit</span>
        <span class="chip"><b>TradingView</b>input panel</span>
        <span class="chip"><b>Korvus</b>24/7 market intelligence</span>
      </div>
      <div class="panel" style="margin-top:18px">
        <p class="prose" style="margin:0;color:#d6d6e2">The LodeStone TradingView version includes an SMT divergence input among its seven feature layers, so you can see the comparison drawn on your own charts while you learn. Operator members get TradingView access to LodeStone included. Every indicator is a tool for reading the market, not a forecast of it.</p>
      </div>
      <p class="disclaimer">Education only. Past chart behavior does not predict future results. Trading index futures involves substantial risk of loss and is not suitable for everyone. Nothing here is financial, investment or trading advice.</p>
      <div class="cta">
        <a class="btn" href="https://korvus.industries/signup">Start with the free Observer tier</a>
        <a class="btn ghost" href="https://korvus.industries/lodestone">See LodeStone</a>
      </div>
    </section>
  </main>

  <footer>
    <p style="margin:0 0 8px">Korvus is a product of BlackCrownVxJ LLC. Your edge while the world sleeps.</p>
    <p style="margin:0">
      <a href="https://korvus.industries/legal">Legal</a> &middot;
      <a href="https://korvus.industries/">Home</a> &middot;
      BlackCrownVxJ.LLC@outlook.com
    </p>
  </footer>
</div>
</body>
</html>
