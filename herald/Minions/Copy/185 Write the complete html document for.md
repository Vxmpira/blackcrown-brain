# Copy: Write the complete html document for the korvus index watch

Date: 2026-10-27
Task: Write the COMPLETE html document for the Korvus index-watch page, doctype through closing html tag, as your full report. No placeholder text. Under 220 lines.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index futures do not stop, Korvus watch 24/7</title>
<meta name="description" content="Korvus watches the index tape, the wire and the session levels around the clock, so you start the day with the read already written. Information and education only.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<meta name="robots" content="index, follow">
<style>
  :root {
    --navy: #0a1024;
    --navy-2: #0f1830;
    --navy-3: #16213f;
    --line: #22305a;
    --magenta: #ff2d8f;
    --text: #e8ecf8;
    --muted: #9aa6c7;
  }
  * { box-sizing: border-box; }
  html, body { margin: 0; padding: 0; }
  body {
    background: var(--navy);
    color: var(--text);
    font-family: "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    font-size: 16px;
  }
  a { color: var(--magenta); text-decoration: none; }
  .wrap { max-width: 1040px; margin: 0 auto; padding: 0 20px; }

  header.site {
    border-bottom: 1px solid var(--line);
    background: var(--navy-2);
  }
  header.site .wrap {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 16px;
    padding-bottom: 16px;
  }
  .brand { display: flex; align-items: center; gap: 10px; color: var(--text); }
  .brand svg { width: 36px; height: 33px; }
  .wordmark { font-size: 20px; font-weight: 700; letter-spacing: 0.08em; }
  nav.site-nav a { color: var(--muted); margin-left: 18px; font-size: 14px; }
  nav.site-nav a:hover { color: var(--text); }

  .hero { padding: 72px 0 56px; background: linear-gradient(180deg, var(--navy) 0%, var(--navy-2) 100%); }
  .eyebrow {
    display: inline-block;
    font-size: 12px;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--magenta);
    border: 1px solid var(--magenta);
    padding: 4px 10px;
    border-radius: 2px;
    margin-bottom: 20px;
  }
  h1 {
    font-size: clamp(30px, 5vw, 52px);
    line-height: 1.12;
    margin: 0 0 18px;
    font-weight: 800;
    max-width: 820px;
  }
  .subhead { font-size: 19px; color: var(--muted); max-width: 680px; margin: 0 0 30px; }

  .chips { display: flex; flex-wrap: wrap; gap: 10px; margin: 0 0 32px; }
  .chip {
    background: var(--navy-3);
    border: 1px solid var(--line);
    color: var(--text);
    padding: 7px 14px;
    border-radius: 999px;
    font-size: 14px;
  }
  .chip.accent { border-color: var(--magenta); color: var(--magenta); }

  .btns { display: flex; flex-wrap: wrap; gap: 12px; }
  .btn {
    display: inline-block;
    padding: 13px 22px;
    border-radius: 3px;
    font-weight: 700;
    font-size: 15px;
    letter-spacing: 0.02em;
  }
  .btn-primary { background: var(--magenta); color: #fff; }
  .btn-primary:hover { background: #ff56a6; }
  .btn-secondary { border: 1px solid var(--magenta); color: var(--magenta); background: transparent; }
  .btn-secondary:hover { background: rgba(255, 45, 143, 0.1); }

  section { padding: 56px 0; }
  .section-title {
    font-size: 26px;
    margin: 0 0 8px;
    font-weight: 700;
  }
  .section-lede { color: var(--muted); margin: 0 0 26px; max-width: 700px; }

  .panel {
    background: var(--navy-2);
    border: 1px solid var(--line);
    border-radius: 6px;
    overflow: hidden;
  }
  .panel-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 14px 18px;
    border-bottom: 1px solid var(--line);
    background: var(--navy-3);
  }
  .panel-head h3 { margin: 0; font-size: 15px; letter-spacing: 0.06em; text-transform: uppercase; }
  .live-dot {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    font-size: 12px;
    color: var(--muted);
  }
  .live-dot::before {
    content: "";
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--magenta);
    box-shadow: 0 0 8px var(--magenta);
  }
  .tag-illus {
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--muted);
    border: 1px dashed var(--line);
    padding: 2px 8px;
    border-radius: 2px;
  }
  .feed-row {
    display: grid;
    grid-template-columns: 90px 110px 1fr auto;
    gap: 14px;
    align-items: center;
    padding: 14px 18px;
    border-bottom: 1px solid var(--line);
    font-size: 14px;
  }
  .feed-row:last-child { border-bottom: none; }
  .feed-time { font-family: Consolas, "Courier New", monospace; color: var(--muted); }
  .feed-src {
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: var(--magenta);
  }
  .feed-msg { color: var(--text); }
  .feed-foot {
    padding: 10px 18px;
    font-size: 12px;
    color: var(--muted);
    background: var(--navy-3);
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 18px;
  }
  .card {
    background: var(--navy-2);
    border: 1px solid var(--line);
    border-radius: 6px;
    padding: 24px;
  }
  .card .num {
    font-family: Consolas, "Courier New", monospace;
    color: var(--magenta);
    font-size: 13px;
    margin-bottom: 8px;
    display: block;
  }
  .card h3 { margin: 0 0 10px; font-size: 20px; }
  .card p { margin: 0; color: var(--muted); font-size: 15px; }

  .strip-wrap { background: var(--navy-2); border: 1px solid var(--line); border-radius: 6px; padding: 22px; }
  .strip-wrap svg { width: 100%; height: auto; display: block; }
  .strip-caption {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 14px;
    font-size: 13px;
    color: var(--muted);
  }

  .cta-band {
    background: linear-gradient(120deg, var(--navy-3) 0%, #2a0f2e 100%);
    border-top: 1px solid var(--magenta);
    border-bottom: 1px solid var(--magenta);
    padding: 56px 0;
    text-align: center;
  }
  .cta-band h2 { font-size: 28px; margin: 0 0 12px; }
  .cta-band p { color: var(--muted); max-width: 620px; margin: 0 auto 26px; }
  .cta-band .btns { justify-content: center; }

  footer.site-foot {
    padding: 36px 0 48px;
    background: var(--navy-2);
    border-top: 1px solid var(--line);
    font-size: 13px;
    color: var(--muted);
  }
  footer.site-foot p { margin: 0 0 10px; }
  footer.site-foot strong { color: var(--text); }

  @media (max-width: 760px) {
    .cards { grid-template-columns: 1fr; }
    .feed-row { grid-template-columns: 1fr; gap: 6px; }
    nav.site-nav { display: none; }
    .hero { padding: 48px 0 40px; }
  }
</style>
</head>
<body>

<header class="site">
  <div class="wrap">
    <a class="brand" href="/" aria-label="Korvus home">
      <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
      <span class="wordmark">Korvus</span>
    </a>
    <nav class="site-nav">
      <a href="/lodestone">LodeStone</a>
      <a href="/login">Log in</a>
    </nav>
  </div>
</header>

<main>

<section class="hero">
  <div class="wrap">
    <span class="eyebrow">Market intelligence terminal</span>
    <h1>Index futures don't stop at 3 a.m. Korvus doesn't either.</h1>
    <p class="subhead">Korvus watches the index tape, the wire and the session levels around the clock, so you start the day with the read already written.</p>

    <div class="chips" role="list">
      <span class="chip" role="listitem">Wire scoring</span>
      <span class="chip" role="listitem">Session levels</span>
      <span class="chip accent" role="listitem">LodeStone included</span>
      <span class="chip" role="listitem">Zero repaint</span>
    </div>

    <div class="btns">
      <a class="btn btn-primary" href="/signup">Start with Observer</a>
      <a class="btn btn-secondary" href="/">See Operator</a>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <h2 class="section-title">The watch feed</h2>
    <p class="section-lede">The overnight tape, scored and timestamped, while you are away from the screen. Every row is an event the terminal logged, not a call.</p>

    <div class="panel" role="region" aria-label="Watch Feed illustration">
      <div class="panel-head">
        <h3>Watch Feed</h3>
        <span class="live-dot">Watching</span>
        <span class="tag-illus">Illustration</span>
      </div>

      <div class="feed-row">
        <span class="feed-time">02:14 ET</span>
        <span class="feed-src">Wire</span>
        <span class="feed-msg">Headline scored for impact, direction and confidence, with a written Korvus read attached.</span>
        <span class="tag-illus">Illustration</span>
      </div>
      <div class="feed-row">
        <span class="feed-time">03:40 ET</span>
        <span class="feed-src">Tape</span>
        <span class="feed-msg">Index futures trade into an overnight session level and hold it on the second test.</span>
        <span class="tag-illus">Illustration</span>
      </div>
      <div class="feed-row">
        <span class="feed-time">05:05 ET</span>
        <span class="feed-src">Levels</span>
        <span class="feed-msg">Prior day high and London open range marked on the chart, with the zone logged as touched.</span>
        <span class="tag-illus">Illustration</span>
      </div>
      <div class="feed-row">
        <span class="feed-time">07:30 ET</span>
        <span class="feed-src">Read</span>
        <span class="feed-msg">Morning summary assembled from the overnight log, ready before the cash open.</span>
        <span class="tag-illus">Illustration</span>
      </div>

      <div class="feed-foot">Illustration only. Sample events are not real market data and not trading signals.</div>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <h2 class="section-title">What the terminal does while you sleep</h2>
    <p class="section-lede">Three jobs, running on the same schedule every session.</p>

    <div class="cards">
      <article class="card">
        <span class="num">01</span>
        <h3>Wire</h3>
        <p>Every headline that touches index futures is pulled, scored for impact, direction and confidence, and filed in order. You see what moved and why it was flagged, not a feed of noise.</p>
      </article>
      <article class="card">
        <span class="num">02</span>
        <h3>Levels</h3>
        <p>Session highs, lows and opens are marked across Asia, London and New York as the day unfolds. Levels are drawn once and kept, so the chart you see at the open matches the chart you left at night.</p>
      </article>
      <article class="card">
        <span class="num">03</span>
        <h3>Read</h3>
        <p>The overnight log becomes a written summary before the cash open. What happened, which levels were tested and what the wire carried, so you start the day informed. The decisions remain yours.</p>
      </article>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <h2 class="section-title">Twenty-four hours, three sessions</h2>
    <p class="section-lede">The index day never closes. Korvus keeps a running log across each handoff.</p>

    <div class="strip-wrap" role="img" aria-label="Illustration of a 24 hour session strip showing Asia, London and New York sessions with a marker">
      <svg viewBox="0 0 720 150" xmlns="http://www.w3.org/2000/svg" font-family="Segoe UI, Roboto, Arial, sans-serif">
        <line x1="0" y1="110" x2="720" y2="110" stroke="#22305a" stroke-width="1"/>
        <g stroke="#22305a" stroke-width="1">
          <line x1="0" y1="104" x2="0" y2="116"/>
          <line x1="180" y1="104" x2="180" y2="116"/>
          <line x1="360" y1="104" x2="360" y2="116"/>
          <line x1="540" y1="104" x2="540" y2="116"/>
          <line x1="720" y1="104" x2="720" y2="116"/>
        </g>
        <g fill="#9aa6c7" font-size="12">
          <text x="0" y="132">00:00</text>
          <text x="180" y="132">06:00</text>
          <text x="360" y="132">12:00</text>
          <text x="540" y="132">18:00</text>
          <text x="690" y="132">24:00</text>
        </g>
        <rect x="0" y="20" width="240" height="30" rx="3" fill="#16213f" stroke="#22305a"/>
        <rect x="210" y="56" width="270" height="30" rx="3" fill="#2a1a3f" stroke="#ff2d8f" stroke-opacity="0.5"/>
        <rect x="360" y="92" width="270" height="12" rx="3" fill="#ff2d8f" fill-opacity="0.35"/>
        <text x="12" y="40" fill="#e8ecf8" font-size="13">Asia</text>
        <text x="222" y="76" fill="#e8ecf8" font-size="13">London</text>
        <text x="372" y="112" fill="#e8ecf8" font-size="11">New York</text>
        <line x1="420" y1="8" x2="420" y2="104" stroke="#ff2d8f" stroke-width="2" stroke-dasharray="4 3"/>
        <circle cx="420" cy="8" r="5" fill="#ff2d8f"/>
        <text x="432" y="12" fill="#ff2d8f" font-size="12">Marker</text>
      </svg>
      <div class="strip-caption">
        <span>Illustration. Session windows are approximate and shown for layout only.</span>
        <span>Log continues across each handoff.</span>
      </div>
    </div>
  </div>
</section>

<section class="cta-band">
  <div class="wrap">
    <h2>Start the day with the read already written.</h2>
    <p>Begin on the free Observer tier. Move up to Operator when the watch feed earns a place in your routine.</p>
    <div class="btns">
      <a class="btn btn-primary" href="/signup">Start with Observer</a>
      <a class="btn btn-secondary" href="/">See Operator</a>
    </div>
  </div>
</section>

</main>

<footer class="site-foot">
  <div class="wrap">
    <p><strong>Information and education only, not financial advice.</strong> Korvus does not recommend trades, promise profits or manage funds. Index futures trading involves risk, including the possible loss of more than you deposit.</p>
    <p>Operator includes the LodeStone TradingView indicator. Watch Feed entries marked Illustration are sample layouts, not live data.</p>
    <p>Korvus is a product of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
  </div>
</footer>

</body>
</html>
