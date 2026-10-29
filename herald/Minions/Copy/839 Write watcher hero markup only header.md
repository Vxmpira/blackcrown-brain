# Copy: Write watcher hero markup only header h1 subhead data panel

Date: 2026-10-29
Task: Write Watcher hero markup only: header, h1, subhead, data panel, closed section.
For [[Herald]].

<section class="ix-hero" aria-labelledby="ix-title">
<style>
.ix-hero{position:relative;overflow:hidden;background:#07060b;color:#e9e6f2;padding:0 0 clamp(48px,8vw,96px);font-family:system-ui,-apple-system,"Segoe UI",sans-serif}
.ix-hero::before{content:"";position:absolute;inset:0;background:radial-gradient(60% 50% at 80% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50% 40% at 0% 100%,rgba(90,70,255,.14),transparent 70%);pointer-events:none}
.ix-hero::after{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;pointer-events:none;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 80%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 80%)}
.ix-wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 20px}
.ix-head{display:flex;align-items:center;gap:12px;padding:24px 0}
.ix-head svg{width:36px;height:33px;flex:0 0 auto}
.ix-brand{font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:14px}
.ix-grid{display:grid;grid-template-columns:1.1fr 1fr;gap:clamp(24px,4vw,48px);align-items:center;padding-top:clamp(24px,6vw,64px)}
.ix-kicker{color:#ff2d8f;font-size:12px;letter-spacing:.16em;text-transform:uppercase;margin:0 0 14px}
.ix-hero h1{font-size:clamp(32px,5vw,56px);line-height:1.08;margin:0 0 18px;font-weight:800}
.ix-sub{font-size:clamp(16px,1.6vw,18px);line-height:1.6;color:#b9b4c9;max-width:34em;margin:0 0 26px}
.ix-chips{display:flex;flex-wrap:wrap;gap:10px;list-style:none;margin:0;padding:0}
.ix-chips li{border:1px solid rgba(255,45,143,.45);border-radius:999px;padding:7px 14px;font-size:13px;background:rgba(255,45,143,.07)}
.ix-panel{border:1px solid rgba(255,255,255,.12);border-radius:14px;background:rgba(18,15,28,.85);padding:18px;box-shadow:0 0 60px rgba(255,45,143,.12)}
.ix-panel-top{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:#9a95ab;margin-bottom:14px}
.ix-tag{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:6px;padding:2px 8px;font-size:11px;letter-spacing:.08em;text-transform:uppercase}
.ix-row{display:grid;grid-template-columns:auto 1fr auto;gap:12px;align-items:center;padding:10px 0;border-top:1px solid rgba(255,255,255,.08);font-size:14px}
.ix-row:first-of-type{border-top:0}
.ix-dot{width:8px;height:8px;border-radius:50%;background:#ff2d8f;box-shadow:0 0 10px #ff2d8f}
.ix-dot.g{background:#7ee0c3;box-shadow:0 0 10px #7ee0c3}
.ix-dot.v{background:#8c7bff;box-shadow:0 0 10px #8c7bff}
.ix-meta{color:#9a95ab;font-size:12px;text-align:right}
@media (max-width:700px){.ix-grid{grid-template-columns:1fr}}
</style>
<div class="ix-wrap">
<header class="ix-head">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="ix-brand">Korvus</span>
</header>
<div class="ix-grid">
<div>
<p class="ix-kicker">Index futures market intelligence</p>
<h1 id="ix-title">The all seeing watcher, 24/7 while you sleep.</h1>
<p class="ix-sub">Korvus keeps the index futures tape under watch around the clock, scores the headlines that move it, and hands you a written read by the time you sit down. Information and education only, not financial advice.</p>
<ul class="ix-chips">
<li>Round the clock wire watch</li>
<li>Scored headlines with a written read</li>
<li>LodeStone on Operator</li>
</ul>
</div>
<aside class="ix-panel" aria-label="Illustration of the Korvus watch feed">
<div class="ix-panel-top"><span>Watch feed</span><span class="ix-tag">Illustration</span></div>
<div class="ix-row"><span class="ix-dot"></span><span>Policy headline scored</span><span class="ix-meta">Impact high</span></div>
<div class="ix-row"><span class="ix-dot g"></span><span>Overnight session levels mapped</span><span class="ix-meta">Watching</span></div>
<div class="ix-row"><span class="ix-dot v"></span><span>Economic agenda updated</span><span class="ix-meta">Confidence moderate</span></div>
</aside>
</div>
</div>
</section>
