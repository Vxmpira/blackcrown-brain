# Copy: Rewrite index watch as one complete html document compact css

Date: 2026-10-29
Task: Rewrite index-watch as one complete html document, compact CSS
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<!-- Caption check: the locked Watcher caption from Projects.md was not included in this brief. Confirm the headline and subhead match it before shipping. -->
<title>Index Watch: Market Surveillance, 24/7 | Korvus</title>
<meta name="description" content="Korvus keeps watch over index futures around the clock. Scored news, live context, and a written read on every move. Free tier, no card required.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080c;color:#e6e8ee;font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,sans-serif}
a{color:#d4af37;text-decoration:none}
.wrap{max-width:880px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid #1c1f2a}
header span{font-weight:700;letter-spacing:.08em;font-size:14px;color:#c9ccd6}
h1{font-size:40px;line-height:1.15;margin:56px 0 14px;letter-spacing:-.01em}
.sub{font-size:18px;color:#a9aebd;max-width:640px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:22px 0 0}
.chip{border:1px solid #2a2e3d;background:#0d0f16;border-radius:999px;padding:6px 12px;font-size:13px;color:#c9ccd6}
.panel{margin:48px 0 0;background:#0d0f16;border:1px solid #23273385;border-radius:12px;padding:22px}
.panel-head{display:flex;justify-content:space-between;align-items:center;font-size:13px;color:#8a90a2;margin-bottom:14px}
.tag{background:#1b1608;color:#d4af37;border:1px solid #4a3d12;border-radius:6px;padding:3px 8px;font-size:12px}
.row{display:grid;grid-template-columns:1.2fr 1fr 1fr;gap:10px;padding:12px 0;border-top:1px solid #1c1f2a;font-size:14px}
.row.hd{border-top:none;color:#8a90a2;font-size:12px;text-transform:uppercase;letter-spacing:.06em}
.up{color:#4fd1a5}.dn{color:#f07178}.nt{color:#c9ccd6}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:56px 0 0}
.card{border:1px solid #1c1f2a;border-radius:12px;padding:20px;background:#0a0c12}
.card h3{font-size:16px;margin-bottom:6px}
.card p{font-size:14px;color:#a9aebd}
.cta{margin:60px 0 0;padding:28px;border:1px solid #2a2e3d;border-radius:12px;background:#0d0f16;text-align:center}
.btn{display:inline-block;margin-top:14px;background:#d4af37;color:#07080c;font-weight:700;padding:12px 22px;border-radius:8px}
footer{margin:64px 0 40px;padding-top:22px;border-top:1px solid #1c1f2a;font-size:13px;color:#8a90a2}
@media(max-width:640px){h1{font-size:30px}.grid{grid-template-columns:1fr}.row{font-size:13px}}
</style>
</head>
<body>
<div class="wrap">
<header>
<svg width="34" height="28" viewBox="0 0 34 28" aria-hidden="true">
<polygon points="3,22 3,8 11,15 17,4 23,15 31,8 31,22" fill="none" stroke="#d4af37" stroke-width="2" stroke-linejoin="round"/>
<rect x="3" y="24" width="28" height="2.5" fill="#d4af37"/>
</svg>
<span>KORVUS</span>
</header>

<h1>The watcher that never sleeps.</h1>
<p class="sub">Korvus keeps eyes on index futures around the clock, so you can step away from the screen without stepping away from the market.</p>

<div class="chips">
<span class="chip">24/7 watch</span>
<span class="chip">Scored news</span>
<span class="chip">Written read</span>
<span class="chip">Session levels</span>
<span class="chip">Free to start</span>
</div>

<section class="panel" aria-label="Illustrative watch feed">
<div class="panel-head"><span>Live watch feed</span><span class="tag">Illustration</span></div>
<div class="row hd"><span>Item</span><span>Impact</span><span>Direction</span></div>
<div class="row"><span>Rate expectations shift</span><span class="nt">High</span><span class="up">Bullish</span></div>
<div class="row"><span>Overnight session range</span><span class="nt">Medium</span><span class="dn">Bearish</span></div>
<div class="row"><span>Prior week level tested</span><span class="nt">Medium</span><span class="nt">Neutral</span></div>
<div class="row"><span>Economic release queued</span><span class="nt">Low</span><span class="nt">Neutral</span></div>
</section>

<div class="grid">
<div class="card"><h3>Watches while you sleep</h3><p>Index news and session activity are scanned around the clock, so the overnight move is never a surprise at the open.</p></div>
<div class="card"><h3>Scored, not dumped</h3><p>Each item carries an impact level, a direction, and a confidence read, so you see what matters first.</p></div>
<div class="card"><h3>A written read</h3><p>Every scored item comes with a plain English read you can check against your own chart.</p></div>
</div>

<section class="cta">
<h2>See the watch for yourself.</h2>
<p class="sub">Start on the free Observer tier. No card needed.</p>
<a class="btn" href="/signup">Start free</a>
</section>

<footer>
<p>Korvus is market information and education, not financial advice. Nothing on this page is a recommendation to buy or sell any instrument. Futures trading carries substantial risk of loss. Past or illustrated data does not predict results.</p>
<p style="margin-top:10px">BlackCrownVxJ LLC · <a href="/legal">Legal</a></p>
</footer>
</div>
</body>
</html>
