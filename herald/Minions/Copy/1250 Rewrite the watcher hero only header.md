# Copy: Rewrite the watcher hero only header with inline crown svg

Date: 2026-10-31
Task: Rewrite the Watcher hero only: header with inline crown svg beside KORVUS, then the hero section with label, h1, subline and a start free link to /signup. Raw h
For [[Herald]].

<style>
.wt-wrap{position:relative;max-width:1060px;margin:0 auto;padding:24px clamp(16px,4vw,32px);color:#e9e6f0;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:radial-gradient(900px 420px at 15% -10%,rgba(255,45,143,.14),transparent 60%),radial-gradient(700px 380px at 95% 0%,rgba(90,70,255,.12),transparent 60%),#0b0a12;border-radius:14px;overflow:hidden}
.wt-wrap::before{content:"";position:absolute;inset:0;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;opacity:.6}
.wt-wrap::after{content:"";position:absolute;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wt-wrap>*{position:relative;z-index:1}
.wt-top{display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap;padding-bottom:18px;border-bottom:1px solid rgba(255,255,255,.08)}
.wt-brand{display:flex;align-items:center;gap:10px}
.wt-brand svg{display:block;width:36px;height:33px}
.wt-word{font-weight:800;letter-spacing:.22em;font-size:15px;color:#fff}
.wt-hero{padding:clamp(40px,8vw,88px) 0 clamp(32px,6vw,64px);max-width:760px}
.wt-label{display:inline-block;font-size:12px;letter-spacing:.18em;text-transform:uppercase;color:#ff2d8f;border:1px solid rgba(255,45,143,.4);padding:6px 10px;border-radius:999px;margin:0 0 18px}
.wt-hero h1{font-size:clamp(30px,5.2vw,56px);line-height:1.08;margin:0 0 18px;font-weight:800;color:#fff}
.wt-sub{font-size:clamp(16px,2vw,19px);line-height:1.6;color:#c9c4d6;margin:0 0 28px;max-width:600px}
.wt-cta{display:inline-block;background:#ff2d8f;color:#0b0a12;font-weight:700;text-decoration:none;padding:14px 22px;border-radius:10px;font-size:16px}
.wt-cta:hover{background:#ff5aa6}
.wt-note{font-size:13px;color:#8c869c;margin:14px 0 0}
@media (max-width:700px){.wt-top{justify-content:flex-start}}
</style>

<div class="wt-wrap">
  <header class="wt-top">
    <div class="wt-brand">
      <svg viewBox="0 0 36 33" aria-hidden="true" focusable="false">
        <path d="M3 27 L5 10 L13 18 L18 6 L23 18 L31 10 L33 27 Z" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round"/>
        <path d="M3 31 L33 31" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linecap="round"/>
      </svg>
      <span class="wt-word">KORVUS</span>
    </div>
  </header>

  <section class="wt-hero">
    <span class="wt-label">Korvus Watcher</span>
    <h1>The watcher that never sleeps, for index futures.</h1>
    <p class="wt-sub">24/7 market intelligence while you sleep.</p>
    <a class="wt-cta" href="/signup">Start free</a>
    <p class="wt-note">Market intelligence, not financial advice. Free tier, no card required.</p>
  </section>
</div>
