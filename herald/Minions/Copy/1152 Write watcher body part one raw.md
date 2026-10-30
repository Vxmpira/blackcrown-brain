# Copy: Write watcher body part one raw html from the opening

Date: 2026-10-30
Task: Write Watcher body part one: raw HTML from the opening body tag through the hero, leaving tags open for part two. Raw HTML only, no code fences.
For [[Herald]].

<body>
<style>
*{box-sizing:border-box}
body{margin:0;min-height:100vh;background:radial-gradient(circle at 15% 0%,rgba(255,45,143,.14),transparent 45%),radial-gradient(circle at 90% 20%,rgba(120,80,255,.12),transparent 40%),linear-gradient(180deg,#07070b,#0b0b12);color:#e9e9f2;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
.hero{position:relative;padding:clamp(24px,5vw,64px) 16px;overflow:hidden}
.hero::before{content:"";position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px;pointer-events:none}
.hero::after{content:"";position:absolute;inset:0;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6));pointer-events:none}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.08em;text-transform:uppercase}
.brand svg{width:36px;height:33px}
h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.1;margin:28px 0 16px;max-width:18ch}
.sub{font-size:clamp(1rem,2.4vw,1.2rem);color:#b9b9cc;max-width:58ch;margin:0 0 28px}
.cta{display:inline-block;background:#ff2d8f;color:#07070b;font-weight:700;text-decoration:none;padding:14px 26px;border-radius:8px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:28px}
.chips span{border:1px solid rgba(255,45,143,.35);padding:6px 12px;border-radius:999px;font-size:.85rem;color:#d8d8e6}
</style>
<section class="hero">
<div class="wrap">
<header class="site-head">
<div class="brand"><svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg><span>Korvus</span></div>
<h1>Watch the market while you sleep.</h1>
<p class="sub">24/7 market intelligence for index futures traders. Scored news, live context, and a written read on what moved, ready when you sit down.</p>
<a class="cta" href="https://korvus.industries/signup">Start free</a>
<div class="chips"><span>24/7 watch</span><span>Scored news</span><span>Free Observer tier</span></div>
