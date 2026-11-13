# Copy: Rewrite the crown skeptic body header with house crown svg

Date: 2026-11-13
Task: Rewrite the Crown skeptic body: header with house crown SVG, h1, proof chips, CTA, then closing main, body and html tags.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>BlackCrown Intelligence: Your Context Stays Yours</title>
<meta name="description" content="Crown keeps your context yours. It is never sold and never trained on. Try the free tier with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptic">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--ink:#e9e6ef;--mute:#9a95a8;--pink:#ff2d8f;--line:rgba(255,255,255,.08);--card:rgba(255,255,255,.035)}
html,body{background:#0b0912;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden;background:
radial-gradient(900px 500px at 15% -10%,rgba(255,45,143,.14),transparent 60%),
radial-gradient(800px 480px at 95% 10%,rgba(120,80,255,.12),transparent 60%),
linear-gradient(180deg,#0d0a16 0%,#0b0912 60%,#08070d 100%)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;
background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);
background-size:48px 48px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;
background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 24px}
header.top{display:flex;align-items:center;gap:14px;padding:28px 0 0}
header.top svg{width:36px;height:33px;flex:0 0 36px}
.brand{font-weight:700;letter-spacing:.06em;text-transform:uppercase;font-size:14px}
.brand span{color:var(--mute);font-weight:500}
main{padding:64px 0 40px}
.kicker{color:var(--pink);font-size:13px;letter-spacing:.14em;text-transform:uppercase;font-weight:600}
h1{font-size:clamp(30px,5vw,52px);line-height:1.12;font-weight:750;margin:14px 0 20px;max-width:18ch}
.lede{font-size:clamp(17px,2vw,20px);color:var(--mute);max-width:60ch}
.chips{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:40px 0 0}
.chip{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px 20px}
.chip b{display:block;font-size:15px;margin-bottom:4px}
.chip small{color:var(--mute);font-size:14px}
.panel{margin-top:44px;background:var(--card);border:1px solid var(--line);border-radius:18px;padding:26px 28px}
.panel h2{font-size:clamp(20px,2.6vw,26px);margin-bottom:10px}
.panel p{color:var(--mute);max-width:64ch}
.meter{margin-top:18px;display:flex;align-items:center;gap:14px;flex-wrap:wrap;font-size:14px;color:var(--mute)}
.bar{flex:1 1 220px;height:10px;border-radius:99px;background:rgba(255,255,255,.07);overflow:hidden}
.bar i{display:block;height:100%;width:72%;background:linear-gradient(90deg,var(--pink),#b06bff)}
.note{margin-top:10px;font-size:12px;color:var(--mute);opacity:.8}
.cta{margin-top:40px;display:flex;gap:14px;flex-wrap:wrap;align-items:center}
.btn{display:inline-block;padding:14px 26px;border-radius:12px;background:var(--pink);color:#140713;font-weight:700;text-decoration:none}
.btn.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
.fine{color:var(--mute);font-size:13px;margin-top:14px}
footer{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:24px;color:var(--mute);font-size:13px;border-top:1px solid var(--line)}
@media (max-width:700px){
.chips{grid-template-columns:1fr}
main{padding:44px 0 28px}
.panel{padding:22px 20px}
}
</style>
</head>
<body>
<div class="wrap">
<header class="top">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<div class="brand">BlackCrown <span>Intelligence</span></div>
</header>

<main>
<div class="kicker">Crown, for skeptics</div>
<h1>Your context stays yours.</h1>
<p class="lede">Crown is a private AI workspace. What you bring into it is never sold, never trained on, and never handed to anyone else. Judge the output yourself before you pay a cent.</p>

<div class="chips">
<div class="chip"><b>No card to start</b><small>The free tier runs on a monthly allowance. Test the answers first.</small></div>
<div class="chip"><b>Never trained on</b><small>Your chats are nobody's training data, including ours.</small></div>
<div class="chip"><b>49.99 flat</b><small>Crowned carries $100 of room credit each month. No surprise bills.</small></div>
</div>

<section class="panel" aria-labelledby="meter-h">
<h2 id="meter-h">Room credit, shown as money</h2>
<p>Crowned draws down a prepaid balance, metered live. Deep-Logic draws more credit per answer on purpose, because the heavier reasoning takes more compute. You always see the balance in dollars.</p>
<div class="meter" role="img" aria-label="Illustration: a room credit balance at roughly 72 percent">
<span>Room credit</span>
<div class="bar"><i></i></div>
<span>$72.00 of $100.00</span>
</div>
<p class="note">Illustration. Not a live account balance.</p>
</section>

<div class="cta">
<a class="btn" href="https://blackcrown-intelligence.com/chat">Try the free tier</a>
<a class="btn ghost" href="https://blackcrown-intelligence.com/pricing">See Crowned at 49.99</a>
</div>
<p class="fine">No card required for the free tier. Crown is an AI tool, not financial advice.</p>
</main>
</div>

<footer>
BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com
</footer>
</body>
</html>
