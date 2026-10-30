# Copy: Write the crown skeptic body markup only header through closing

Date: 2026-10-30
Task: Write the Crown skeptic body markup only, header through closing main tag, no head, no style.
For [[Herald]].

<header class="site-header">
  <a class="brand" href="/" aria-label="Crown home">
    <svg class="crown-mark" viewBox="0 0 48 48" width="36" height="36" aria-hidden="true" focusable="false">
      <path d="M6 36 L10 16 L18 26 L24 10 L30 26 L38 16 L42 36 Z" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linejoin="round"/>
      <rect x="6" y="36" width="36" height="5" rx="1.5" fill="currentColor"/>
      <circle cx="24" cy="8" r="2.5" fill="currentColor"/>
    </svg>
    <span class="brand-name">Crown</span>
  </a>
  <nav class="site-nav" aria-label="Primary">
    <a href="#ownership">Ownership</a>
    <a href="#rooms">Rooms</a>
    <a href="#try-free" class="nav-cta">Try it free</a>
  </nav>
</header>

<main class="crown-skeptic">

  <section class="hero">
    <p class="eyebrow">BlackCrown Intelligence</p>
    <h1>Judge the output yourself. Then decide.</h1>
    <p class="hero-sub">Crown is BlackCrown's private AI workspace. Ask it the hard questions, read what comes back, and make up your own mind. No card, no sales call, no pitch.</p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="#try-free">Start free, no card</a>
      <a class="btn btn-ghost" href="#ownership">Read the ownership terms</a>
    </div>
  </section>

  <section class="ownership" id="ownership">
    <h2>Your context stays yours.</h2>
    <p>Your conversations are not sold. They are not used to train models. Your chats are nobody's training data but yours. That is the whole promise, and it is written into how Crown is built, not left to a policy page you will never open.</p>
    <ul class="chips" aria-label="Ownership commitments">
      <li class="chip">Never sold</li>
      <li class="chip">Never trained on</li>
      <li class="chip">Your chats, your data</li>
    </ul>
  </section>

  <section class="rooms" id="rooms">
    <h2>Four private rooms.</h2>
    <p>Pick the room that fits the question. Each one is built for a different kind of work.</p>
    <ul class="chips" aria-label="Crown rooms">
      <li class="chip">Unfiltered</li>
      <li class="chip">Deep-Logic</li>
      <li class="chip">Visual Analysis</li>
      <li class="chip">Creativity</li>
    </ul>
    <p class="note">Deep-Logic draws more room credit per answer on purpose. Harder thinking takes more compute, and the credit reflects that honestly.</p>
  </section>

  <section class="meter-figure" aria-labelledby="meter-title">
    <h2 id="meter-title">How the balance works</h2>
    <p>Crowned is a flat 49.99 a month and carries $100 of room credit. It meters like a prepaid balance, so there are no surprise bills at the end of the month.</p>
    <figure class="mock">
      <figcaption class="mock-label">Illustration</figcaption>
      <div class="mock-row">
        <span>Room credit remaining</span>
        <span class="mock-value">$72.40</span>
      </div>
      <div class="mock-bar" role="img" aria-label="Illustrative balance at seventy two percent">
        <div class="mock-fill" style="width:72%"></div>
      </div>
      <div class="mock-foot">
        <span>Top-ups from $4.99, never expire</span>
      </div>
    </figure>
  </section>

  <section class="try-free" id="try-free">
    <h2>Skeptical? Good. Test it.</h2>
    <p>The free tier gives you a monthly allowance with no card required. Run your own questions, compare the answers against what you already know, and judge the output for yourself. If it does not hold up, you lose nothing.</p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="/signup">Start free, no card</a>
    </div>
    <p class="fine">Crown is an AI workspace for research and analysis. It is not financial advice.</p>
  </section>

</main>
