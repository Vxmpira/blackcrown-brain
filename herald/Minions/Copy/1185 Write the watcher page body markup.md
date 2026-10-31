# Copy: Write the watcher page body markup only from the body

Date: 2026-10-31
Task: Write the Watcher page body markup only, from the body open tag through the closing body tag.
For [[Herald]].

<body>
<style>
body{margin:0;background:#07070b;color:#e9e9f1;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 45% at 15% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(90,70,255,.12),transparent 70%)}
body:after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.w{max-width:1060px;margin:0 auto;padding:0 20px}
header.top{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid rgba(255,255,255,.08)}
header.top .name{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:15px}
.hero{padding:clamp(40px,8vw,88px) 0 28px}
.eyebrow{color:#ff2d8f;font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin:0 0 14px}
h1{font-size:clamp(30px,5.2vw,58px);line-height:1.08;margin:0 0 18px;max-width:18ch;font-weight:750}
.lede{font-size:clamp(16px,2vw,19px);line-height:1.6;color:#b9b9c8;max-width:60ch;margin:0 0 26px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:0 0 30px;padding:0;list-style:none}
.chips li{border:1px solid rgba(255,45,143,.35);background:rgba(255,45,143,.07);color:#ffd1e6;border-radius:999px;padding:7px 14px;font-size:14px}
.btn{display:inline-block;background:#ff2d8f;color:#120611;font-weight:700;text-decoration:none;padding:14px 26px;border-radius:10px;font-size:16px}
.panel{margin:44px 0 0;border:1px solid rgba(255,255,255,.1);border-radius:14px;background:rgba(14,14,22,.85);padding:20px;box-shadow:0 0 0 1px rgba(255,45,143,.06),0 20px 60px rgba(0,0,0,.45)}
.panel-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;font-size:13px;color:#8d8da3}
.tag{border:1px solid rgba(255,255,255,.18);border-radius:6px;padding:3px 8px;font-size:12px;letter-spacing:.06em;text-transform:uppercase}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.cell{border:1px solid rgba(255,255,255,.08);border-radius:10px;padding:14px;background:rgba(255,255,255,.02)}
.cell h3{margin:0 0 6px;font-size:14px;color:#f3f3fa}
.cell p{margin:0;font-size:13px;color:#9a9ab0;line-height:1.5}
.dot{display:inline-block;width:8px;height:8px;border-radius:50%;background:#ff2d8f;margin-right:8px;box-shadow:0 0 10px #ff2d8f}
.dot.off{background:#4b4b60;box-shadow:none}
.foot{padding:28px 0 40px;color:#7d7d92;font-size:13px;line-height:1.6;border-top:1px solid rgba(255,255,255,.08);margin-top:44px}
@media (max-width:700px){.grid{grid-template-columns:1fr}.btn{width:100%;text-align:center;box-sizing:border-box}}
</style>
<div class="w">
<header class="top">
<svg width="36" height="33" viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" stroke-linecap="round" aria-hidden="true">
<path d="M4 26 L4 11 L12 18 L18 7 L24 18 L32 11 L32 26 Z"/>
<path d="M4 30 L32 30"/>
</svg>
<span class="name">Korvus</span>
</header>
<section class="hero">
<p class="eyebrow">The market, watched while you sleep</p>
<h1>Something is always watching the index futures.</h1>
<p class="lede">Korvus keeps a 24/7 watch over the tape across sessions, scores the news as it breaks, and writes you a clear read so you wake up already caught up. Information only, built for operators who trade their own plan.</p>
<ul class="chips">
<li>24/7 coverage</li>
<li>Session watch</li>
<li>Scored news wire</li>
<li>Free tier, no card</li>
</ul>
<a class="btn" href="https://korvus.industries/signup">Create your free account</a>
<figure class="panel" aria-label="Illustration">
<div class="panel-head"><span>Overnight watch board</span><span class="tag">Illustration</span></div>
<div class="grid">
<div class="cell"><h3><span class="dot"></span>Asia session</h3><p>Range tracked, levels logged, quiet flow flagged for the open.</p></div>
<div class="cell"><h3><span class="dot"></span>London open</h3><p>Liquidity sweeps and prior day levels marked as they print.</p></div>
<div class="cell"><h3><span class="dot off"></span>Wire alert</h3><p>No high impact release in queue. Watch continues.</p></div>
</div>
</figure>
<p class="foot">Information only, not financial advice. Korvus provides market information and education. Trading involves risk, and you are responsible for your own decisions.</p>
</section>
</div>
</body>
