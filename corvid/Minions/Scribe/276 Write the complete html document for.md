# Scribe: Write the complete html document for a new korvus guide

Date: 2026-10-29
Task: Write the COMPLETE html document for a new Korvus guide page: SMT divergence explained for index futures beginners, serving at korvus.industries/p/smt-divergenc
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Explained for Index Futures Beginners</title>
<meta name="description" content="SMT divergence explained for index futures beginners. What ES and NQ disagreement means, how to read it as information, and the mistakes new traders make.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence-explained">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080b;--panel:#0d0f14;--line:#1c2029;--text:#e6e8ee;--muted:#9aa3b2;--gold:#d4af5a;--teal:#4fd1c5;--red:#e0666a}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(212,175,90,.10),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(79,209,197,.08),transparent 70%),radial-gradient(60% 50% at 50% 100%,rgba(224,102,106,.06),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:56px 56px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.vignette{position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--text)}
.brand svg{width:34px;height:34px;flex:0 0 34px}
.brand span{font-weight:700;letter-spacing:.06em;font-size:1.05rem}
.brand small{display:block;color:var(--muted);font-weight:400;letter-spacing:.02em;font-size:.78rem}
main{padding:44px 0 60px}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.16em;font-size:.75rem;font-weight:700}
h1{font-size:clamp(1.9rem,5vw,3.1rem);line-height:1.12;margin:12px 0 16px;letter-spacing:-.01em}
h2{font-size:clamp(1.35rem,3.2vw,1.85rem);margin:44px 0 12px;color:var(--text)}
h3{font-size:1.08rem;margin:18px 0 6px;color:var(--gold)}
.lede{font-size:clamp(1.05rem,2.2vw,1.2rem);color:var(--muted);max-width:68ch}
.prose{max-width:68ch}
.prose p{margin:0 0 14px;color:var(--text)}
.prose ul,.prose ol{margin:0 0 14px 22px}
.prose li{margin-bottom:6px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0 4px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:6px 14px;font-size:.84rem;color:var(--muted)}
.chip b{color:var(--teal);font-weight:600}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:14px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.card p{color:var(--muted);font-size:.95rem}
figure{margin:26px 0;background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:18px}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:.86rem;margin-top:10px}
.tag{display:inline-block;background:rgba(212,175,90,.14);color:var(--gold);border:1px solid rgba(212,175,90,.35);border-radius:6px;padding:2px 8px;font-size:.74rem;letter-spacing:.08em;text-transform:uppercase;margin-bottom:8px}
.legend{display:flex;gap:18px;flex-wrap:wrap;font-size:.84rem;color:var(--muted);margin-top:8px}
.legend i{display:inline-block;width:18px;height:3px;vertical-align:middle;margin-right:6px;border-radius:2px}
.cta{margin-top:48px;background:linear-gradient(135deg,rgba(212,175,90,.12),rgba(79,209,197,.07));border:1px solid rgba(212,175,90,.3);border-radius:16px;padding:28px}
.cta h2{margin-top:0}
.btn{display:inline-block;margin-top:10px;background:var(--gold);color:#120e04;font-weight:700;text-decoration:none;padding:12px 20px;border-radius:10px}
.note{margin-top:34px;color:var(--muted);font-size:.85rem;border-top:1px solid var(--line);padding-top:18px}
footer{border-top:1px solid var(--line);padding:22px 0;color:var(--muted);font-size:.84rem}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  main{padding:30px 0 44px}
  .panel,.card,.cta,figure{padding:16px}
}
</style>
</head>
<body>
<div class="vignette" aria-hidden="true"></div>
<header>
  <div class="wrap">
    <a class="brand" href="/" aria-label="Korvus home">
      <svg viewBox="0 0 40 40" aria-hidden="true">
        <defs><linearGradient id="g" x1="0" x2="1" y1="0" y2="1"><stop offset="0" stop-color="#f1d089"/><stop offset="1" stop-color="#b8892f"/></linearGradient></defs>
        <polygon points="6,30 6,14 14,22 20,8 26,22 34,14 34,30" fill="url(#g)"/>
        <rect x="6" y="31" width="28" height="4" rx="1" fill="#d4af5a"/>
        <circle cx="20" cy="6" r="2" fill="#4fd1c5"/>
      </svg>
      <span>KORVUS<small>24/7 market intelligence</small></span>
    </a>
  </div>
</header>

<main>
  <article class="wrap">
    <div class="eyebrow">Korvus Guide</div>
    <h1>SMT Divergence Explained for Index Futures Beginners</h1>
    <p class="lede">Two indexes usually move together. When they stop agreeing, that disagreement is information. This guide explains what SMT divergence is, what it can and cannot tell you, and the mistakes new traders make with it.</p>

    <div class="chips" aria-label="Topics covered">
      <span class="chip"><b>ES</b> S&amp;P 500 futures</span>
      <span class="chip"><b>NQ</b> Nasdaq 100 futures</span>
      <span class="chip">Cross index</span>
      <span class="chip">Education only</span>
    </div>

    <h2>What SMT divergence is</h2>
    <div class="prose">
      <p>SMT stands for Smart Money Technique. In index futures, it usually means comparing two related markets. The two most common are ES, the E-mini S&amp;P 500, and NQ, the E-mini Nasdaq 100.</p>
      <p>These two products are highly correlated. Large tech names sit heavily in both. So in normal conditions, they tend to reach new highs and new lows at around the same time.</p>
      <p>SMT divergence happens when they stop agreeing. One market prints a new high or new low. The other one fails to confirm it. That failure is the divergence.</p>
      <p>That is the whole definition. It is an observation about two charts, not an instruction.</p>
    </div>

    <h2>Why it can signal weakness in a move</h2>
    <div class="prose">
      <p>Think of a move as a group effort. If every index is pushing, the move looks healthy. If one index keeps pushing and the other stalls, the group is no longer in sync.</p>
      <p>Traders use that gap to ask a question: is this move broad, or is it coming from one corner of the market? A divergence does not answer the question. It only tells you the question is worth asking.</p>
      <p>Some traders read a divergence as a sign of fading momentum. Others read it as a sign that a move needs more confirmation before they trust it. Both readings are interpretations. Neither is guaranteed.</p>
    </div>

    <h2>A simple example</h2>
    <div class="prose">
      <p>The figure below shows a stylized case. Both lines climb. Then NQ prints a higher high, while ES prints a lower high. The gap between the two peaks is the divergence.</p>
    </div>

    <figure>
      <span class="tag">Illustration</span>
      <svg viewBox="0 0 640 300" role="img" aria-labelledby="smtfig smtdesc">
        <title id="smtfig">Illustration: NQ makes a higher high while ES makes a lower high</title>
        <desc id="smtdesc">Two stylized price lines. NQ reaches a new high at the right while ES stays below its earlier high, marking an SMT divergence.</desc>
        <rect x="0" y="0" width="640" height="300" fill="#0a0c11"/>
        <g stroke="#1c2029" stroke-width="1">
          <line x1="40" y1="60" x2="620" y2="60"/>
          <line x1="40" y1="130" x2="620" y2="130"/>
          <line x1="40" y1="200" x2="620" y2="200"/>
          <line x1="40" y1="260" x2="620" y2="260"/>
        </g>
        <polyline fill="none" stroke="#4fd1c5" stroke-width="3" stroke-linejoin="round" points="50,230 110,200 160,215 220,160 270,180 320,120 370,150 420,95 470,130 520,70 560,96 600,88"/>
        <polyline fill="none" stroke="#d4af5a" stroke-width="3" stroke-linejoin="round" points="50,235 110,205 160,220 220,165 270,185 320,125 370,152 420,100 470,134 520,82 560,110 600,118"/>
        <circle cx="420" cy="95" r="5" fill="#4fd1c5"/>
        <circle cx="520" cy="82" r="5" fill="#d4af5a"/>
        <line x1="420" y1="95" x2="420" y2="250" stroke="#9aa3b2" stroke-dasharray="4 4"/>
        <line x1="520" y1="70" x2="520" y2="250" stroke="#9aa3b2" stroke-dasharray="4 4"/>
        <line x1="420" y1="45" x2="520" y2="45" stroke="#e0666a" stroke-width="2"/>
        <text x="470" y="36" fill="#e0666a" font-size="14" text-anchor="middle" font-family="system-ui,sans-serif">SMT gap</text>
        <text x="420" y="278" fill="#9aa3b2" font-size="12" text-anchor="middle" font-family="system-ui,sans-serif">Earlier high</text>
        <text x="520" y="278" fill="#9aa3b2" font-size="12" text-anchor="middle" font-family="system-ui,sans-serif">New high</text>
      </svg>
      <div class="legend">
        <span><i style="background:#4fd1c5"></i>NQ (illustrative)</span>
        <span><i style="background:#d4af5a"></i>ES (illustrative)</span>
      </div>
      <figcaption>Illustration only. Stylized lines, not real market data. The point is the shape: one high confirmed, one high not confirmed.</figcaption>
    </figure>

    <h2>Common beginner mistakes</h2>
    <div class="grid">
      <div class="card">
        <h3>Treating every gap as a signal</h3>
        <p>Small differences between two charts happen all day. Not every gap is meaningful. Context decides which ones matter.</p>
      </div>
      <div class="card">
        <h3>Ignoring the timeframe</h3>
        <p>A divergence on a one minute chart and one on a daily chart describe different things. Mixing them creates confusion.</p>
      </div>
      <div class="card">
        <h3>Mismatched timestamps</h3>
        <p>If the two charts do not line up in time, the comparison is wrong before you start. Check that both markets share the same clock and session.</p>
      </div>
      <div class="card">
        <h3>Using it alone</h3>
        <p>One observation rarely tells the full story. Volume, structure, and the wider tape all shape how a divergence reads.</p>
      </div>
      <div class="card">
        <h3>Assuming it must resolve</h3>
        <p>A divergence can persist. Markets can keep moving in one direction while the other index lags for a long time.</p>
      </div>
      <div class="card">
        <h3>Confusing it with oscillator divergence</h3>
        <p>SMT compares two markets. Oscillator divergence compares price with an indicator on one market. They are different tools.</p>
      </div>
    </div>

    <h2>How to think about it</h2>
    <div class="prose">
      <ul>
        <li>Start by asking whether both markets are making the same kind of move.</li>
        <li>Note the timeframe you are looking at, and keep it fixed.</li>
        <li>Write down what the divergence shows, and what it does not show.</li>
        <li>Treat it as one input among several, never as a complete plan.</li>
      </ul>
    </div>

    <section class="cta">
      <h2>Korvus tracks cross index SMT live</h2>
      <p>Korvus watches ES and NQ around the clock and surfaces cross index SMT as it forms. The Observer tier is free. Create an account at korvus.industries and see how the readings look on your own schedule.</p>
      <a class="btn" href="https://korvus.industries/signup?utm_source=guide&amp;utm_medium=seo&amp;utm_campaign=smt">Create a free Observer account</a>
    </section>

    <p class="note">Educational content only. Nothing on this page is trading advice, a recommendation to buy or sell, or a promise of profit. Index futures carry substantial risk and are not suitable for everyone. Past readings do not predict future results. Illustrations are stylized and not real market data.</p>
  </article>
</main>

<footer>
  <div class="wrap">
    Korvus is a product of BlackCrownVxJ LLC. Contact: BlackCrownVxJ.LLC@outlook.com
  </div>
</footer>
</body>
</html>
