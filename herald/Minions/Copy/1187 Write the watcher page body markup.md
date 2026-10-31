# Copy: Write the watcher page body markup only from the body

Date: 2026-10-31
Task: Write the Watcher page body markup only, from the body open tag through the closing body tag. No style block, no script, no meta tags.
For [[Herald]].

<body>
<header class="site-head">
  <a class="brand" href="/" aria-label="Korvus home">
    <svg class="crown-mark" viewBox="0 0 48 32" width="48" height="32" aria-hidden="true" focusable="false">
      <path d="M4 26 L8 8 L17 18 L24 4 L31 18 L40 8 L44 26 Z" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linejoin="round"/>
      <circle cx="8" cy="7" r="2" fill="currentColor"/>
      <circle cx="24" cy="3" r="2" fill="currentColor"/>
      <circle cx="40" cy="7" r="2" fill="currentColor"/>
      <rect x="4" y="26" width="40" height="3" fill="currentColor"/>
    </svg>
    <span class="brand-name">Korvus</span>
  </a>
  <nav class="site-nav" aria-label="Primary">
    <a href="/lodestone">LodeStone</a>
    <a href="/legal">Legal</a>
    <a class="nav-cta" href="/signup">Start free</a>
  </nav>
</header>

<main class="wrap">

  <section class="hero">
    <p class="eyebrow">Korvus Watcher</p>
    <h1>The market does not sleep. Your watch should not either.</h1>
    <p class="lead">Korvus Watcher keeps a continuous read on index futures while you are offline. It scores the news as it lands, flags what moves the open, and leaves the write-up waiting when you wake up.</p>
    <div class="cta-row">
      <a class="btn btn-primary" href="/signup">Start with the free Observer tier</a>
      <a class="btn btn-ghost" href="#how">See how it reads</a>
    </div>
    <p class="fine">No card required to start. Observer is free. Operator adds the full terminal and the LodeStone indicator.</p>
  </section>

  <section class="panel" aria-labelledby="panel-title">
    <div class="panel-head">
      <h2 id="panel-title">Overnight watch board</h2>
      <span class="tag">Illustration</span>
    </div>
    <div class="chips" role="list">
      <span class="chip" role="listitem">Session: Asia</span>
      <span class="chip" role="listitem">Feeds monitored: 24/7</span>
      <span class="chip" role="listitem">Last scan: 03:12 ET</span>
    </div>
    <div class="feed">
      <div class="feed-row">
        <span class="feed-time">02:41</span>
        <span class="feed-text">Macro headline scored, impact high, direction mixed</span>
        <span class="feed-read">Read: wait for the open</span>
      </div>
      <div class="feed-row">
        <span class="feed-time">02:58</span>
        <span class="feed-text">Rate expectations repriced on a speaker remark</span>
        <span class="feed-read">Read: watch the level</span>
      </div>
      <div class="feed-row">
        <span class="feed-time">03:12</span>
        <span class="feed-text">Volatility pocket flagged ahead of the session</span>
        <span class="feed-read">Read: note for the desk</span>
      </div>
    </div>
    <p class="caption">Illustrative board. Not live data and not a signal.</p>
  </section>

  <section class="block" id="how">
    <h2>What it does while you sleep</h2>
    <div class="grid three">
      <article class="card">
        <h3>Scans around the clock</h3>
        <p>Watcher reads the wire through every session, so the overnight picture is already assembled when you open the terminal.</p>
      </article>
      <article class="card">
        <h3>Scores each headline</h3>
        <p>Every item gets an impact rating, a direction, a confidence level, and a written Korvus read in plain language.</p>
      </article>
      <article class="card">
        <h3>Keeps the record</h3>
        <p>Flagged items stay in one timeline, so you can see what was called, when it was called, and what followed.</p>
      </article>
    </div>
  </section>

  <section class="block">
    <h2>Built for the operator, not the pedestal</h2>
    <p class="prose">Watcher is a tool for traders who already run their own process. It does not tell you what to buy or sell. It keeps the watch, shows its reasoning, and hands the decision back to you. You stay in the seat. The software stays on the post.</p>
    <ul class="chips chips-wide">
      <li class="chip">Always on</li>
      <li class="chip">Reasoning shown</li>
      <li class="chip">Index futures focus</li>
      <li class="chip">No card to start</li>
    </ul>
  </section>

  <section class="block">
    <h2>Start where the risk is lowest</h2>
    <div class="grid two">
      <article class="card">
        <h3>Observer, free</h3>
        <p>Read the scored feed and get a feel for the output before you commit to anything.</p>
        <a class="link" href="/signup">Create a free account</a>
      </article>
      <article class="card card-accent">
        <h3>Operator</h3>
        <p>The full terminal, the LodeStone TradingView indicator included, and the complete watch.</p>
        <a class="link" href="/signup">See Operator options</a>
      </article>
    </div>
  </section>

  <section class="disclaimer" aria-label="Disclaimer">
    <p>Korvus is market intelligence and education. Nothing on this page is financial advice, a trade recommendation, or a promise of profit. Index futures carry substantial risk of loss. Past readings do not predict results. Illustrative boards on this page are examples only. Read the full terms on the <a href="/legal">legal page</a> before you act on any output.</p>
  </section>

  <section class="final">
    <h2>Keep the watch running.</h2>
    <p>Start free, read the output yourself, and decide whether the watch earns a place in your process.</p>
    <a class="btn btn-primary" href="/signup">Start with Observer</a>
  </section>

</main>

<footer class="site-foot">
  <p>Korvus is a product of BlackCrownVxJ LLC. <a href="/legal">Legal</a> · <a href="/lodestone">LodeStone</a></p>
  <p>Business contact: BlackCrownVxJ.LLC@outlook.com</p>
</footer>
</body>
