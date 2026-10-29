# Copy: Write watcher body part 1 open body header hero raw

Date: 2026-10-29
Task: Write Watcher body part 1: open body, header, hero. Raw HTML, no fences.
For [[Herald]].

<body>
<style>
:root{--ink:#e8ecf3;--mute:#8a94a6;--line:#1d2433;--pink:#ff2d8f;--cyan:#27d4ff;--bg:#06080d}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60% 40% at 85% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50% 40% at 0% 30%,rgba(39,212,255,.10),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.top{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--ink)}
.brand svg{width:36px;height:33px}
.brand b{font-size:clamp(16px,2.4vw,20px);letter-spacing:.18em}
.nav{display:flex;gap:18px;flex-wrap:wrap;font-size:14px}
.nav a{color:var(--mute);text-decoration:none}
.nav a:hover{color:var(--ink)}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center;padding:64px 0 48px}
.eyebrow{font-size:12px;letter-spacing:.2em;color:var(--pink);text-transform:uppercase;margin:0 0 14px}
h1{font-size:clamp(34px,5.4vw,58px);line-height:1.08;margin:0 0 18px;letter-spacing:-.01em}
.lede{font-size:clamp(16px,2vw,19px);color:#c5cdda;max-width:58ch;margin:0 0 26px}
.ctas{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:22px}
.btn{display:inline-block;padding:13px 22px;border-radius:8px;font-weight:600;text-decoration:none;font-size:15px}
.btn-p{background:var(--pink);color:#fff}
.btn-g{border:1px solid var(--line);color:var(--ink)}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin:0;padding:0;list-style:none}
.chips li{font-size:13px;border:1px solid var(--line);background:rgba(255,255,255,.02);padding:6px 12px;border-radius:999px;color:#c5cdda}
.fig{border:1px solid var(--line);border-radius:14px;background:rgba(10,14,22,.85);padding:18px;box-shadow:0 0 60px rgba(255,45,143,.08)}
.fig-h{display:flex;justify-content:space-between;font-size:12px;color:var(--mute);letter-spacing:.08em;text-transform:uppercase;margin-bottom:12px}
.row{display:grid;grid-template-columns:72px 1fr auto;gap:10px;align-items:center;padding:10px 0;border-top:1px solid var(--line);font-size:14px}
.tag{font-size:11px;padding:3px 8px;border-radius:6px;font-weight:600}
.t-up{background:rgba(39,212,255,.14);color:var(--cyan)}
.t-dn{background:rgba(255,45,143,.14);color:var(--pink)}
.t-hi{background:rgba(255,255,255,.08);color:#c5cdda}
.meter{height:6px;border-radius:4px;background:#161c28;overflow:hidden}
.meter span{display:block;height:100%;background:linear-gradient(90deg,var(--cyan),var(--pink))}
.note{font-size:12px;color:var(--mute);margin-top:12px}
.disc{font-size:12px;color:var(--mute);max-width:70ch;margin:18px 0 0}
@media (max-width:700px){
  .hero{grid-template-columns:1fr;padding:40px 0 32px;gap:28px}
  .top{flex-direction:column;align-items:flex-start}
  .nav{gap:14px}
}
</style>

<div class="wrap">
  <header class="top">
    <a class="brand" href="/" aria-label="KORVUS home">
      <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="1.6" stroke-linejoin="round" aria-hidden="true">
        <path d="M3 9 L9 2 L18 7 L27 2 L33 9 L30 13 L33 21 L18 31 L3 21 L6 13 Z"/>
        <path d="M9 2 L12 13 L18 7 L24 13 L27 2"/>
        <circle cx="18" cy="17" r="3.2"/>
        <path d="M18 13.8 V11.4 M18 20.2 V22.6 M14.8 17 H12.4 M21.2 17 H23.6"/>
      </svg>
      <b>KORVUS</b>
    </a>
    <nav class="nav" aria-label="Primary">
      <a href="/lodestone">LodeStone</a>
      <a href="/legal">Legal</a>
      <a href="/login">Log in</a>
      <a href="/signup">Start free</a>
    </nav>
  </header>

  <section class="hero" aria-labelledby="watch-title">
    <div>
      <p class="eyebrow">Watcher, 24/7 market surveillance</p>
      <h1 id="watch-title">The market never closes. Watcher doesn't either.</h1>
      <p class="lede">Watcher scans the index futures tape, the wire and the session levels while you sleep, then hands you the picture in one scored view when you wake up. Less noise. Fewer surprises. Your read, sharper.</p>
      <div class="ctas">
        <a class="btn btn-p" href="/signup">Start with the free Observer tier</a>
        <a class="btn btn-g" href="/lodestone">See LodeStone</a>
      </div>
      <ul class="chips" aria-label="What Watcher covers">
        <li>Overnight coverage</li>
        <li>Scored news</li>
        <li>Session levels</li>
        <li>No card to start</li>
      </ul>
      <p class="disc">Korvus provides market information and education only. Nothing on this page is financial advice, a trading recommendation, or a promise of profit. Trading index futures carries substantial risk.</p>
    </div>

    <figure class="fig" aria-label="Illustration of Watcher overnight feed">
      <div class="fig-h"><span>Watcher overnight</span><span>Illustration</span></div>
      <div class="row"><span class="tag t-hi">02:14</span><span>Session open levels mapped</span><span class="tag t-hi">Logged</span></div>
      <div class="row"><span class="tag t-up">Up</span><span>Rate-sensitive headline scored</span><span class="tag t-up">Medium</span></div>
      <div class="row"><span class="tag t-dn">Dn</span><span>Dollar strength pressure flagged</span><span class="tag t-dn">High</span></div>
      <div class="row"><span class="tag t-hi">05:40</span><span>Pre-market range refreshed</span><span class="tag t-hi">Logged</span></div>
      <div class="row"><span class="tag t-up">Up</span><span>Volume shift vs prior session</span><span class="tag t-up">Low</span></div>
      <div style="margin-top:14px">
        <div style="font-size:12px;color:var(--mute);margin-bottom:6px">Coverage across the night (Illustration)</div>
        <div class="meter"><span style="width:86%"></span></div>
      </div>
      <p class="note">Illustrative feed for layout only. Not live data, not a signal.</p>
    </figure>
  </section>
</div>
</body>
