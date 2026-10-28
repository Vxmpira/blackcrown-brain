# Copy: Write full index watch html into a vault note report

Date: 2026-10-28
Task: Write full index-watch html into a vault note, report its path and final line
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Index Watch: 24/7 Index Futures Intelligence | Korvus</title>
<meta name="description" content="Korvus Index Watch: round-the-clock market intelligence for index futures traders. Scored news, session context, and a written read. Information only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/index-watch">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07080c;color:#d9dde6;font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6;min-height:100vh}
a{color:#e8c870;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1b1f2a;padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;color:#f2f4f8;font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
.brand svg{width:34px;height:34px}
nav{margin-left:auto;display:flex;gap:18px;font-size:14px}
nav a{color:#9aa3b5}
.hero{padding:64px 0 36px}
.kicker{color:#e8c870;font-size:13px;letter-spacing:.14em;text-transform:uppercase}
h1{font-size:40px;line-height:1.15;color:#f5f7fb;margin:14px 0 16px;font-weight:700}
.lede{font-size:18px;color:#b7bfcf;max-width:640px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:26px}
.chip{border:1px solid #2a3040;background:#0d1017;color:#c9d0de;padding:7px 12px;border-radius:999px;font-size:13px}
.cta{display:inline-block;margin-top:30px;background:#e8c870;color:#0a0b10;font-weight:700;padding:13px 22px;border-radius:6px}
.cta:hover{text-decoration:none;filter:brightness(1.07)}
.panel{background:#0d1017;border:1px solid #1f2430;border-radius:10px;padding:22px;margin:24px 0}
.panel-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;font-size:13px;color:#9aa3b5}
.tag{font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:#e8c870;border:1px solid #4a3f1c;padding:3px 8px;border-radius:4px}
.feed{display:grid;gap:10px}
.row{display:grid;grid-template-columns:86px 1fr 96px;gap:12px;align-items:center;background:#090b11;border:1px solid #181c26;border-radius:8px;padding:12px 14px;font-size:14px}
.time{color:#7d8698;font-variant-numeric:tabular-nums}
.bull{color:#7fd39a}
.bear{color:#e8838a}
.neu{color:#c9b36a}
.meter{height:6px;background:#1a1f2b;border-radius:3px;overflow:hidden}
.meter span{display:block;height:100%;background:#e8c870}
h2{font-size:24px;color:#f5f7fb;margin:44px 0 14px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{background:#0d1017;border:1px solid #1f2430;border-radius:10px;padding:18px}
.card h3{color:#f2f4f8;font-size:16px;margin-bottom:8px}
.card p{font-size:14px;color:#aab2c3}
.note{font-size:12px;color:#7d8698;margin-top:10px}
footer{border-top:1px solid #1b1f2a;margin-top:56px;padding:26px 0 40px;font-size:12px;color:#7d8698}
footer p+p{margin-top:8px}
@media(max-width:720px){h1{font-size:30px}.grid{grid-template-columns:1fr}nav{display:none}.row{grid-template-columns:70px 1fr}.row .meter{display:none}}
</style>
</head>
<body>
<header>
<div class="wrap brand">
<svg viewBox="0 0 40 40" aria-hidden="true"><path d="M6 30 L8 14 L15 22 L20 8 L25 22 L32 14 L34 30 Z" fill="none" stroke="#e8c870" stroke-width="2" stroke-linejoin="round"/><rect x="6" y="31" width="28" height="3" fill="#e8c870"/></svg>
Korvus
<nav><a href="/">Home</a><a href="/lodestone">LodeStone</a><a href="/legal">Legal</a></nav>
</div>
</header>

<main class="wrap">
<section class="hero">
<div class="kicker">Index futures intelligence</div>
<h1>The market does not sleep. Neither does your watch.</h1>
<p class="lede">Korvus scores the wire around the clock and writes a plain read on what moved, how hard, and how sure the signal is. You see the session you trade in, not a wall of headlines.</p>
<div class="chips">
<span class="chip">Scored news feed</span>
<span class="chip">Impact and confidence</span>
<span class="chip">Session context</span>
<span class="chip">Written Korvus read</span>
</div>
<a class="cta" href="/signup">Start with the free Observer tier</a>
</section>

<section class="panel" aria-label="Index Watch feed mock">
<div class="panel-head">
<span>Index Watch, live feed layout</span>
<span class="tag">Illustration</span>
</div>
<div class="feed">
<div class="row">
<span class="time">02:14</span>
<span>Rates commentary moves ahead of the overnight auction <span class="neu">(neutral)</span></span>
<div class="meter"><span style="width:45%"></span></div>
</div>
<div class="row">
<span class="time">03:02</span>
<span>Energy headline lifts risk tone in Asia session <span class="bull">(bullish)</span></span>
<div class="meter"><span style="width:72%"></span></div>
</div>
<div class="row">
<span class="time">04:37</span>
<span>Policy speaker repeats guidance, no new signal <span class="neu">(neutral)</span></span>
<div class="meter"><span style="width:30%"></span></div>
</div>
<div class="row">
<span class="time">06:50</span>
<span>Data calendar ahead of the open flags two releases <span class="bear">(bearish risk)</span></span>
<div class="meter"><span style="width:61%"></span></div>
</div>
</div>
<p class="note">Illustration only. Sample layout, not live output and not a record of any market event.</p>
</section>

<h2>What you get</h2>
<div class="grid">
<div class="card">
<h3>Scored, not just posted</h3>
<p>Each item carries an impact level, a direction, and a confidence score so you can sort the noise before the open.</p>
</div>
<div class="card">
<h3>Session awareness</h3>
<p>Asia, London, and New York context stays attached to every read, so an overnight headline is labeled as overnight.</p>
</div>
<div class="card">
<h3>A written read</h3>
<p>Korvus explains in plain language why an item matters and what it does not tell you. Honest about limits by design.</p>
</div>
</div>

<h2>Built for the arena</h2>
<p class="lede" style="font-size:16px">Index Watch is written for traders who run their own process. It informs your read of the tape. It does not place trades, set levels for you, or promise a result.</p>
</main>

<footer class="wrap">
<p>Korvus is an information and education product for index futures traders. Nothing on this page is financial advice, a recommendation to buy or sell any instrument, or a promise of profit. Futures trading involves substantial risk of loss.</p>
<p>BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com. <a href="/legal">Legal</a></p>
</footer>
</body>
</html>
