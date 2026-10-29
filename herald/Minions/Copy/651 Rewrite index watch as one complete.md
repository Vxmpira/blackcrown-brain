# Copy: Rewrite index watch as one complete html document

Date: 2026-10-29
Task: Rewrite index-watch as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch | Korvus 24/7 Index Futures Intelligence</title>
<meta name="description" content="Korvus Index Watch keeps a 24/7 read on index futures while you sleep. Scored news, session levels, and a written read. Not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080b;color:#e6e8ee;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
a{color:#c9a84c;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:1040px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1c1f27;padding:18px 0}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;color:#e6e8ee;font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
nav a{color:#9aa1b2;margin-left:18px;font-size:14px}
nav a.cta{color:#07080b;background:#c9a84c;padding:8px 14px;border-radius:6px;font-weight:600}
.hero{padding:64px 0 36px}
.eyebrow{color:#c9a84c;font-size:13px;text-transform:uppercase;letter-spacing:.12em;margin-bottom:12px}
h1{font-size:40px;line-height:1.15;margin-bottom:16px;max-width:760px}
.lead{font-size:18px;color:#b7bcc9;max-width:700px;margin-bottom:26px}
.btns{display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-block;padding:12px 20px;border-radius:7px;font-weight:600;font-size:15px}
.btn-primary{background:#c9a84c;color:#07080b}
.btn-ghost{border:1px solid #2a2e39;color:#e6e8ee}
.btn:hover{text-decoration:none;opacity:.9}
.panel{margin:34px 0 10px;background:#0d0f14;border:1px solid #1c1f27;border-radius:12px;padding:20px}
.panel-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;font-size:13px;color:#9aa1b2;flex-wrap:wrap;gap:8px}
.tag{font-size:11px;text-transform:uppercase;letter-spacing:.1em;color:#c9a84c;border:1px solid #3a3322;padding:3px 8px;border-radius:4px}
.feed{display:grid;grid-template-columns:1.4fr 1fr;gap:16px}
@media(max-width:760px){.feed{grid-template-columns:1fr}h1{font-size:30px}}
.spark{background:#07080b;border-radius:8px;padding:12px}
.spark svg{width:100%;height:auto;display:block}
.rows{background:#07080b;border-radius:8px;padding:12px;font-size:14px}
.row{display:flex;justify-content:space-between;padding:9px 0;border-bottom:1px solid #151822;gap:10px}
.row:last-child{border-bottom:0}
.up{color:#5fd29a}.down{color:#e06b6b}.mute{color:#8a91a3}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:28px 0 8px}
.chip{background:#11141b;border:1px solid #1f2430;border-radius:999px;padding:7px 14px;font-size:14px;color:#c8cdd9}
section{padding:44px 0;border-top:1px solid #1c1f27}
h2{font-size:26px;margin-bottom:14px}
h3{font-size:17px;margin-bottom:6px;color:#e6e8ee}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:20px}
@media(max-width:760px){.grid{grid-template-columns:1fr}}
.card{background:#0d0f14;border:1px solid #1c1f27;border-radius:10px;padding:20px}
.card p{color:#aab0bf;font-size:15px}
.num{color:#c9a84c;font-weight:700;font-size:14px;margin-bottom:8px;display:block}
.plan{background:#0d0f14;border:1px solid #2a2415;border-radius:12px;padding:26px;max-width:720px}
.plan ul{margin:14px 0 18px 18px;color:#c8cdd9}
.plan li{margin-bottom:6px}
.note{color:#8a91a3;font-size:13px;margin-top:12px}
.faq p{color:#aab0bf;margin-bottom:18px;font-size:15px}
.disclaimer{background:#0d0f14;border:1px solid #1c1f27;border-radius:8px;padding:16px;color:#8a91a3;font-size:13px;margin-top:10px}
footer{border-top:1px solid #1c1f27;padding:26px 0 40px;color:#7a8192;font-size:13px}
footer .links a{color:#9aa1b2;margin-right:16px}
</style>
</head>
<body>

<header>
  <div class="wrap bar">
    <a class="brand" href="/" aria-label="Korvus home">
      <svg viewBox="0 0 48 48" aria-hidden="true">
        <path d="M6 16 L14 28 L24 12 L34 28 L42 16 L38 36 L10 36 Z" fill="none" stroke="#c9a84c" stroke-width="2.4" stroke-linejoin="round"/>
        <rect x="10" y="38" width="28" height="3" fill="#c9a84c"/>
        <circle cx="24" cy="12" r="2.2" fill="#c9a84c"/>
      </svg>
      <span>KORVUS</span>
    </a>
    <nav>
      <a href="/lodestone">LodeStone</a>
      <a href="/legal">Legal</a>
      <a href="/login">Log in</a>
      <a class="cta" href="/signup">Start free</a>
    </nav>
  </div>
</header>

<main>
  <div class="wrap">

    <div class="hero">
      <div class="eyebrow">Index Watch</div>
      <h1>The index market keeps moving after you close the terminal. Korvus keeps watching.</h1>
      <p class="lead">Index Watch is Korvus market intelligence for index futures traders. Scored news, session levels, and a written read on what changed, running around the clock so you start each session informed, not guessing.</p>
      <div class="btns">
        <a class="btn btn-primary" href="/signup">Start with the free Observer tier</a>
        <a class="btn btn-ghost" href="#plans">See Operator</a>
      </div>

      <div class="panel" role="img" aria-label="Illustrative Index Watch panel showing a sample price path and scored headlines">
        <div class="panel-head">
          <span>Index Watch, live panel</span>
          <span class="tag">Illustration</span>
        </div>
        <div class="feed">
          <div class="spark">
            <svg viewBox="0 0 400 160" aria-hidden="true">
              <defs>
                <linearGradient id="g" x1="0" x2="0" y1="0" y2="1">
                  <stop offset="0" stop-color="#c9a84c" stop-opacity=".35"/>
                  <stop offset="1" stop-color="#c9a84c" stop-opacity="0"/>
                </linearGradient>
              </defs>
              <line x1="0" y1="40" x2="400" y2="40" stroke="#1c1f27"/>
              <line x1="0" y1="80" x2="400" y2="80" stroke="#1c1f27"/>
              <line x1="0" y1="120" x2="400" y2="120" stroke="#1c1f27"/>
              <line x1="0" y1="62" x2="400" y2="62" stroke="#4a6fa5" stroke-dasharray="4 4"/>
              <polygon points="0,130 40,118 80,124 120,96 160,104 200,78 240,86 280,60 320,70 360,48 400,54 400,160 0,160" fill="url(#g)"/>
              <polyline points="0,130 40,118 80,124 120,96 160,104 200,78 240,86 280,60 320,70 360,48 400,54" fill="none" stroke="#c9a84c" stroke-width="2.2"/>
              <text x="8" y="58" fill="#8a91a3" font-size="11">Session level</text>
            </svg>
          </div>
          <div class="rows">
            <div class="row"><span>Presidential Wire</span><span class="up">Bullish, high</span></div>
            <div class="row"><span>Impact score</span><span>7.4 / 10</span></div>
            <div class="row"><span>Korvus read</span><span class="mute">Written summary</span></div>
            <div class="row"><span>USD agenda</span><span class="mute">Live actuals</span></div>
            <div class="row"><span>Coverage</span><span class="mute">24/7</span></div>
          </div>
        </div>
      </div>

      <div class="chips">
        <span class="chip">24/7 coverage</span>
        <span class="chip">Scored news with impact and confidence</span>
        <span class="chip">Session and prior day levels</span>
        <span class="chip">Written Korvus read</span>
        <span class="chip">USD economic agenda</span>
      </div>
    </div>

    <section>
      <h2>Your edge while the world sleeps</h2>
      <p class="lead">Overnight sessions move index futures on headlines you will not see until the open. Index Watch reads the wire as it lands, scores each item for impact, direction, and confidence, and writes a short read you can check in under a minute.</p>
      <div class="grid">
        <div class="card">
          <span class="num">01</span>
          <h3>Scan</h3>
          <p>Headlines and economic releases are pulled and ranked continuously, so a late print does not slip past the desk.</p>
        </div>
        <div class="card">
          <span class="num">02</span>
          <h3>Score</h3>
          <p>Each item carries an impact rating, a direction, and a confidence level, so you see how much weight it deserves before you look at the chart.</p>
        </div>
        <div class="card">
          <span class="num">03</span>
          <h3>Read</h3>
          <p>A written Korvus read explains what changed and what it touches on the index you trade, in plain operator language.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Built for the session, not the feed</h2>
      <p class="lead">Index Watch is a watch tool. It shows you what moved, where the session levels sit, and how the USD agenda lines up with the tape. The decisions stay with you.</p>
      <div class="grid">
        <div class="card">
          <h3>Session context</h3>
          <p>Prior day and week levels and session boundaries are laid out so you can see where the market is relative to them at any hour.</p>
        </div>
        <div class="card">
          <h3>Economic agenda</h3>
          <p>The daily USD agenda with live actuals keeps scheduled risk on the screen before the release, not after.</p>
        </div>
        <div class="card">
          <h3>Charts included</h3>
          <p>Operator includes the LodeStone TradingView indicator, a session level toolkit with zero repainting, so your chart and your wire read from the same page.</p>
        </div>
      </div>
    </section>

    <section id="plans">
      <h2>Operator</h2>
      <p class="lead">Start on the free Observer tier and see what Index Watch shows you. Move to Operator when you want the full watch.</p>
      <div class="plan">
        <h3>Operator</h3>
        <ul>
          <li>Full Index Watch panel, 24/7</li>
          <li>Presidential Wire with scored news and written Korvus reads</li>
          <li>Daily USD economic agenda with live actuals</li>
          <li>LodeStone TradingView indicator included</li>
          <li>Annual plan listed first, with the savings shown at checkout</li>
        </ul>
        <div class="btns">
          <a class="btn btn-primary" href="/upgrade">Choose a plan</a>
          <a class="btn btn-ghost" href="/lodestone">About LodeStone</a>
        </div>
        <p class="note">Monthly and annual options are shown with current pricing on the upgrade page.</p>
      </div>
    </section>

    <section class="faq">
      <h2>Questions</h2>
      <h3>Is there a free version?</h3>
      <p>Yes. Observer is free and shows you the core watch so you can judge the output for yourself before you upgrade.</p>
      <h3>Do I need a trading account to start?</h3>
      <p>No. Sign up and look at the panel. Connecting a charting platform is only needed if you want LodeStone on your chart.</p>
      <h3>Does Index Watch tell me what to trade?</h3>
      <p>No. Index Watch is market intelligence and education. It scores and summarizes information. It never gives entry, exit, or position advice.</p>
      <h3>How current is the data?</h3>
      <p>Index Watch runs around the clock. Scored items and the USD agenda update as they land, so the panel reflects the most recent information the system has.</p>

      <div class="disclaimer">
        Not financial advice. Korvus and Index Watch provide market information and education only. Trading index futures involves substantial risk of loss and is not suitable for everyone. Past readings, scores, and illustrations do not predict results. Panels shown with an Illustration mark are sample data, not live market data. You are responsible for your own decisions.
      </div>
    </section>

  </div>
</main>

<footer>
  <div class="wrap">
    <div class="links">
      <a href="/">Korvus</a>
      <a href="/lodestone">LodeStone</a>
      <a href="/signup">Sign up</a>
      <a href="/legal">Legal</a>
    </div>
    <p style="margin-top:14px">Business contact: BlackCrownVxJ.LLC@outlook.com. Korvus is a product of BlackCrownVxJ LLC. Your edge while the world sleeps.</p>
  </div>
</footer>

</body>
</html>
