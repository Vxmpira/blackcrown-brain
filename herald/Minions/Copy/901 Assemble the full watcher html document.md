# Copy: Assemble the full watcher html document with doctype head title

Date: 2026-10-30
Task: Assemble the full Watcher html document with doctype, head, title, viewport, style block and body. Output raw html, no code fences, ending with </html>.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Korvus Watcher, the market that never blinks</title>
<meta name="description" content="Korvus Watcher scans index futures around the clock and turns the wire into scored reads. Start free with Observer. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/watcher">
<style>
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  background:
    radial-gradient(60% 40% at 15% 0%, rgba(255,45,143,.18), transparent 70%),
    radial-gradient(50% 35% at 90% 10%, rgba(80,120,255,.14), transparent 70%),
    linear-gradient(rgba(255,255,255,.035) 1px, transparent 1px) 0 0/48px 48px,
    linear-gradient(90deg, rgba(255,255,255,.035) 1px, transparent 1px) 0 0/48px 48px,
    #07080c;
  color:#e8e8ee;
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  line-height:1.6;
  min-height:100vh;
  position:relative;
}
body::after{
  content:"";position:fixed;inset:0;pointer-events:none;
  background:radial-gradient(120% 90% at 50% 50%, transparent 55%, rgba(0,0,0,.65) 100%);
}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
header{display:flex;align-items:center;gap:12px;padding:24px 0;border-bottom:1px solid #1a1d28}
header svg{width:28px;height:28px;fill:#ff2d8f}
header .brand{font-weight:700;letter-spacing:.04em;font-size:16px}
main{padding:56px 0 72px}
h1{font-size:clamp(30px,6vw,56px);line-height:1.1;margin:0 0 20px;font-weight:800;letter-spacing:-.01em;max-width:18ch}
main p{font-size:clamp(16px,2vw,18px);max-width:64ch;color:#c9ccd8;margin:0 0 20px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span{padding:6px 12px;border:1px solid #ff2d8f;border-radius:99px;color:#e8e8ee;font-size:13px}
.mock{margin:24px 0;padding:16px;border:1px solid #1a1d28;border-radius:10px;background:#0c0e15}
.mock figcaption,.fine{font-size:12px;color:#8a8fa3}
.fine{line-height:1.5}
.watch{display:grid;grid-template-columns:1fr;gap:12px;margin:0 0 12px}
.line{display:flex;justify-content:space-between;align-items:center;padding:14px 16px;border:1px solid #1a1d28;border-radius:8px;background:#11141d;font-family:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace;font-size:14px}
.line b{color:#ff2d8f;font-weight:700}
.line i{font-style:normal;color:#7fd4a6}
.cta{display:inline-block;margin:8px 0 28px;padding:14px 24px;border-radius:8px;background:#ff2d8f;color:#07080c;font-weight:700;text-decoration:none}
.cta:hover{background:#ff5aa6}
@media (max-width:699px){
  header{padding:18px 0}
  main{padding:36px 0 52px}
  .line{font-size:13px;padding:12px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<svg viewBox="0 0 36 33" aria-hidden="true" focusable="false"><rect x="3" y="27" width="30" height="5" rx="1"/><path d="M3 25 L6 9 L13 18 L18 4 L23 18 L30 9 L33 25 Z"/></svg>
<span class="brand">Korvus</span>
</header>
<main>
<h1>The watcher that never blinks.</h1>
<p>Korvus Watcher runs 24/7 scanning of index futures, so the overnight move, the economic print, and the headline that lands at 3 a.m. are already scored and waiting when you sit down. You get the context in one glance and you make your own call.</p>
<div class="chips">
<span>24/7 scan</span>
<span>Scored wire</span>
<span>Free tier</span>
</div>
<figure class="mock">
<div class="watch">
<div class="line"><span><b>ES</b> watching</span><i>scanning</i></div>
<div class="line"><span><b>NQ</b> watching</span><i>scanning</i></div>
</div>
<figcaption>Illustration</figcaption>
</figure>
<a class="cta" href="/signup">Start free with Observer</a>
<p class="fine">Education only, not financial advice.</p>
</main>
</div>
</body>
</html>
