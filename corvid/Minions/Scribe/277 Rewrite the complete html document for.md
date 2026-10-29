# Scribe: Rewrite the complete html document for the korvus smt divergence

Date: 2026-10-29
Task: Rewrite the COMPLETE html document for the Korvus SMT divergence guide, doctype through closing html, with EXACTLY ONE title tag, EXACTLY ONE meta description, 
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence Explained for Index Futures | Korvus</title>
<meta name="description" content="What SMT divergence is, how ES and NQ disagreement at highs and lows reads as information, and the beginner mistakes to avoid. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence-explained">
<style>
:root{--bg:#060709;--panel:#0d0f14;--line:#1c2029;--text:#e7e9ee;--muted:#9aa3b2;--gold:#d9b25f;--teal:#4fc3b4;--red:#e0686a}
*{box-sizing:border-box;margin:0;padding:0}
html{background:var(--bg)}
body{
  min-height:100vh;color:var(--text);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  line-height:1.65;background-color:var(--bg);
  background-image:
    radial-gradient(900px 500px at 15% -10%,rgba(217,178,95,.10),transparent 60%),
    radial-gradient(800px 480px at 95% 10%,rgba(79,195,180,.08),transparent 60%),
    linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);
  background-size:auto,auto,56px 56px,56px 56px;
  position:relative;
}
body::after{
  content:"";position:fixed;inset:0;pointer-events:none;
  background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%);
}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
header{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid var(--line)}
header .brand{font-weight:700;letter-spacing:.04em;color:var(--text);text-decoration:none}
header .brand span{color:var(--gold)}
header nav{margin-left:auto;display:flex;gap:18px;font-size:.92rem}
header nav a{color:var(--muted);text-decoration:none}
header nav a:hover{color:var(--text)}
.hero{padding:56px 0 28px}
.eyebrow{color:var(--gold);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase}
h1{font-size:clamp(1.9rem,4.6vw,3rem);line-height:1.12;margin:12px 0 16px;letter-spacing:-.01em}
h2{font-size:clamp(1.4rem,3vw,1.9rem);margin:44px 0 12px;line-height:1.2}
h3{font-size:clamp(1.05rem,2.2vw,1.2rem);margin:24px 0 8px;color:var(--gold)}
.lede{font-size:clamp(1.02rem,1.8vw,1.15rem);color:var(--muted);max-width:68ch}
.prose{max-width:68ch}
.prose p{margin:0 0 16px}
.prose ul,.prose ol{margin:0 0 16px 22px}
.prose li{margin-bottom:8px}
strong{color:var(--text)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0 0}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:6px 14px;font-size:.85rem;color:var(--muted)}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin:20px 0}
.grid .card h3{margin-top:0}
figure{margin:28px 0;background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:18px}
figure svg{width:100%;height:auto;display:block}
figcaption{color:var(--muted);font-size:.88rem;margin-top:12px;display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.tag{background:rgba(217,178,95,.12);color:var(--gold);border:1px solid rgba(217,178,95,.35);border-radius:6px;padding:2px 8px;font-size:.78rem;letter-spacing:.06em;text-transform:uppercase}
.mistakes{counter-reset:m;list-style:none;margin:0;padding:0}
.mistakes li{counter-increment:m;position:relative;padding:14px 16px 14px 56px;border:1px solid var(--line);border-radius:12px;background:var(--panel);margin-bottom:12px}
.mistakes li::before{content:counter(m);position:absolute;left:16px;top:14px;color:var(--gold);font-weight:700}
.cta{margin:40px 0 0;border:1px solid rgba(217,178,95,.35);border-radius:16px;padding:26px;background:linear-gradient(135deg,rgba(217,178,95,.10),rgba(79,195,180,.05)),var(--panel)}
.btn{display:inline-block;margin-top:10px;background:var(--gold);color:#101010;font-weight:700;text-decoration:none;padding:12px 20px;border-radius:10px}
.btn:hover{filter:brightness(1.08)}
.disclaimer{margin-top:44px;padding:18px 0;border-top:1px solid var(--line);color:var(--muted);font-size:.86rem;max-width:72ch}
footer{padding:26px 0 40px;color:var(--muted);font-size:.86rem;border-top:1px solid var(--line);display:flex;flex-wrap:wrap;gap:14px;justify-content:space-between}
footer a{color:var(--muted)}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  header nav{display:none}
  .hero{padding-top:36px}
}
</style>
</head>
<body>
<div class="wrap">

<header>
  <svg width="34" height="30" viewBox="0 0 34 30" aria-hidden="true" focusable="false">
    <polygon points="4,24 4,10 10,16 17,4 24,16 30,10 30,24" fill="none" stroke="#d9b25f" stroke-width="2" stroke-linejoin="round"/>
    <rect x="4" y="24" width="26" height="3" fill="#d9b25f"/>
    <circle cx="17" cy="4" r="2" fill="#4fc3b4"/>
  </svg>
  <a class="brand" href="https://korvus.industries/">KORVUS<span>.</span></a>
  <nav>
    <a href="https://korvus.industries/lodestone">LodeStone</a>
    <a href="https://korvus.industries/?utm_source=guide&amp;utm_medium=seo&amp;utm_campaign=smt">Korvus</a>
  </nav>
</header>

<section class="hero">
  <div class="eyebrow">Index futures guide</div>
  <h1>SMT Divergence Explained: When ES and NQ Stop Agreeing</h1>
  <p class="lede">Smart Money Technique divergence is a simple idea with a lot of misuse attached. Two related index futures make a high or a low, and one of them fails to confirm. This guide explains what that disagreement is, how to read it as information rather than a signal, and where beginners tend to go wrong.</p>
  <div class="chips">
    <span class="chip">ES and NQ</span>
    <span class="chip">Highs and lows</span>
    <span class="chip">Beginner friendly</span>
    <span class="chip">Information, not signals</span>
  </div>
</section>

<section class="prose">
  <h2>What SMT divergence means</h2>
  <p>SMT stands for Smart Money Technique. In index futures, the most common version compares the E-mini S&amp;P 500 (ES) with the E-mini Nasdaq 100 (NQ). The two contracts usually move together, because the broad market drives both. When they stop agreeing at a turning point, traders call that disagreement a divergence.</p>
  <p>The classic pattern looks like this. Price in one contract pushes to a new high. The other contract pushes to a new high too, but it stalls just short of its prior high. Or it does not try at all. That gap between the two charts is the SMT divergence. The same logic applies at lows, with the roles reversed.</p>
  <p>Some traders also compare ES with YM (Dow futures) or RTY (Russell 2000 futures). The principle is the same. The pair you choose matters less than understanding what the disagreement is telling you about the market's internal strength.</p>
</section>

<section class="prose">
  <h2>How to read it as information, not a signal</h2>
  <p>This is the part most beginners skip. A divergence is a fact about two charts. It is not a trade instruction. It tells you that the market is not unanimous at that moment. It does not tell you what happens next.</p>
  <div class="grid">
    <div class="card">
      <h3>What it can tell you</h3>
      <ul>
        <li>Leadership may be narrowing to one index.</li>
        <li>A move may lack broad participation.</li>
        <li>A level that looked important may be contested.</li>
      </ul>
    </div>
    <div class="card">
      <h3>What it cannot tell you</h3>
      <ul>
        <li>Direction, timing, or size of the next move.</li>
        <li>Whether a divergence will resolve in either direction.</li>
        <li>Whether a trade is worth taking or how to manage it.</li>
      </ul>
    </div>
  </div>
  <p>Treat each divergence as one piece of context. Ask what the price structure, session, and higher timeframe look like around it. A divergence that agrees with nothing else on your chart deserves less attention than one that lines up with several observations.</p>
</section>

<figure>
  <svg viewBox="0 0 640 300" role="img" aria-labelledby="smt-title smt-desc">
    <title id="smt-title">Illustrative SMT divergence mock</title>
    <desc id="smt-desc">Two lines rise to a new high together. The ES line makes a higher high while the NQ line stalls below its prior high.</desc>
    <rect x="0" y="0" width="640" height="300" fill="#0a0c10"/>
    <g stroke="#1c2029" stroke-width="1">
      <line x1="40" y1="60" x2="620" y2="60"/>
      <line x1="40" y1="130" x2="620" y2="130"/>
      <line x1="40" y1="200" x2="620" y2="200"/>
      <line x1="40" y1="260" x2="620" y2="260"/>
    </g>
    <line x1="40" y1="20" x2="40" y2="270" stroke="#2a303c" stroke-width="1"/>
    <line x1="260" y1="30" x2="260" y2="270" stroke="#d9b25f" stroke-width="1" stroke-dasharray="4 4" opacity="0.6"/>
    <polyline fill="none" stroke="#4fc3b4" stroke-width="3" stroke-linejoin="round"
      points="50,230 110,200 160,212 205,150 240,120 260,70 290,110 330,95 380,60"/>
    <polyline fill="none" stroke="#9aa3b2" stroke-width="3" stroke-linejoin="round" stroke-dasharray="7 5"
      points="50,240 110,214 160,222 205,168 240,140 260,102 290,128 330,118 380,104"/>
    <circle cx="260" cy="70" r="5" fill="#4fc3b4"/>
    <circle cx="260" cy="102" r="5" fill="#9aa3b2"/>
    <circle cx="380" cy="60" r="5" fill="#4fc3b4"/>
    <circle cx="380" cy="104" r="5" fill="#e0686a"/>
    <text x="392" y="66" fill="#4fc3b4" font-size="13" font-family="system-ui,sans-serif">ES new high</text>
    <text x="392" y="112" fill="#e0686a" font-size="13" font-family="system-ui,sans-serif">NQ fails to confirm</text>
    <text x="50" y="30" fill="#9aa3b2" font-size="13" font-family="system-ui,sans-serif">Solid: ES</text>
    <text x="50" y="50" fill="#9aa3b2" font-size="13" font-family="system-ui,sans-serif">Dashed: NQ</text>
  </svg>
  <figcaption><span class="tag">Illustration</span> A made up example of two contracts disagreeing at a high. Not a real chart and not a prediction.</figcaption>
</figure>

<section class="prose">
  <h2>Common beginner mistakes</h2>
  <ol class="mistakes">
    <li><strong>Treating every divergence as an entry.</strong> A divergence is context. Entries come from a complete plan, and most divergences never become one.</li>
    <li><strong>Ignoring the broader structure.</strong> A divergence against a strong trend can persist far longer than a beginner's account can survive.</li>
    <li><strong>Forgetting the timeframe.</strong> A divergence on a one minute chart and one on a daily chart describe different things. Mixing them confuses the read.</li>
    <li><strong>Comparing the wrong contracts or months.</strong> Front month and back month charts can differ for reasons unrelated to market disagreement. Check which contract each chart shows.</li>
    <li><strong>Hunting for divergences.</strong> If you need one to exist before you act, you are reading your own hopes into the chart.</li>
    <li><strong>Skipping risk.</strong> No pattern removes the need to define what you lose if you are wrong, before you take any position.</li>
    <li><strong>Counting it as proof.</strong> Divergences fail often. Writing down what happened after each one is the fastest way to learn what they actually tell you.</li>
  </ol>
</section>

<section class="prose">
  <h2>Tracking cross index SMT live</h2>
  <p>Spotting a divergence on a chart takes practice, and checking several index pairs across sessions by hand takes time you may not have. Korvus is a 24/7 market intelligence terminal for index futures traders. Its tooling tracks cross index SMT so you can see where ES, NQ, and related pairs are disagreeing while you work through your own plan.</p>
  <p>Korvus gives you information to study. It does not decide your trades for you, and it does not promise any outcome.</p>
  <div class="cta">
    <h3>See cross index SMT live</h3>
    <p>Start with the free Observer tier, then decide whether the deeper tools fit how you trade.</p>
    <a class="btn" href="https://korvus.industries/?utm_source=guide&amp;utm_medium=seo&amp;utm_campaign=smt">Open Korvus</a>
  </div>
</section>

<div class="disclaimer">
  Not financial advice. This guide is education about one market concept. Nothing here is a recommendation to buy, sell, or hold any instrument, and no result is guaranteed. Futures trading involves substantial risk of loss and is not suitable for everyone. Past chart patterns do not predict future prices.
</div>

<footer>
  <span>BlackCrownVxJ LLC. Your edge while the world sleeps.</span>
  <span><a href="https://korvus.industries/legal">Legal</a> &middot; <a href="https://korvus.industries/">Korvus</a></span>
</footer>

</div>
</body>
</html>
