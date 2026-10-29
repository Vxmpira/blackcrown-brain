# Copy: Rewrite crown skeptic page as one complete html document saved

Date: 2026-10-29
Task: Rewrite Crown skeptic page as one complete html document saved to vault
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown for Skeptics: Judge the Output Yourself</title>
<meta name="description">
<meta name="description" content="Crown is BlackCrown's private AI workspace. Your context stays yours, never sold, never trained on. Try the free tier with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptic">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0f1117;--line:#1f2431;--text:#e7e9ee;--muted:#9aa3b5;--gold:#d4a85a;--teal:#4fb6c4}
html,body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(212,168,90,.13),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(79,182,196,.10),transparent 70%),var(--bg)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--text);text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:34px;height:34px}
nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-size:.95rem}
nav a:hover{color:var(--text)}
.hero{padding:64px 0 36px}
.eyebrow{color:var(--gold);text-transform:uppercase;letter-spacing:.14em;font-size:.8rem;font-weight:600}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:14px 0 18px;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,3vw,2rem);margin:0 0 14px;letter-spacing:-.01em}
h3{font-size:1.05rem;margin:0 0 8px}
.lede{font-size:clamp(1.05rem,2vw,1.2rem);color:var(--muted);max-width:62ch}
.prose{max-width:66ch}
.prose p{margin-bottom:14px;color:#cfd4df}
section{padding:44px 0;border-bottom:1px solid var(--line)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:22px}
.chip{border:1px solid var(--line);background:var(--panel);border-radius:999px;padding:7px 14px;font-size:.88rem;color:var(--text)}
.chip b{color:var(--gold);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.card p{color:var(--muted);font-size:.95rem}
.figure{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:24px;margin-top:24px}
.figure-head{display:flex;justify-content:space-between;align-items:baseline;gap:12px;flex-wrap:wrap;margin-bottom:14px}
.tag{font-size:.75rem;text-transform:uppercase;letter-spacing:.12em;color:var(--teal);border:1px solid rgba(79,182,196,.4);border-radius:6px;padding:3px 8px}
.meter{height:14px;background:#171b26;border-radius:999px;overflow:hidden;border:1px solid var(--line)}
.meter span{display:block;height:100%;background:linear-gradient(90deg,var(--gold),#f0cf8a)}
.rows{margin-top:16px;display:grid;gap:10px}
.row{display:flex;justify-content:space-between;gap:12px;font-size:.93rem;color:var(--muted);border-bottom:1px dashed var(--line);padding-bottom:8px}
.row strong{color:var(--text);font-weight:600}
.note{font-size:.8rem;color:var(--muted);margin-top:12px}
.rooms{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:22px}
.room{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:18px}
.room h3{color:var(--gold)}
.room p{font-size:.9rem;color:var(--muted)}
.cta{display:flex;flex-wrap:wrap;gap:12px;margin-top:24px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;text-decoration:none;font-weight:600;font-size:.98rem}
.btn-primary{background:var(--gold);color:#140f05}
.btn-ghost{border:1px solid var(--line);color:var(--text)}
.fine{font-size:.82rem;color:var(--muted);margin-top:20px;max-width:70ch}
footer{padding:30px 0 50px;color:var(--muted);font-size:.85rem;display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
footer a{color:var(--muted)}
@media (max-width:700px){
  nav a{margin-left:12px;font-size:.85rem}
  .grid{grid-template-columns:1fr}
  .rooms{grid-template-columns:1fr 1fr}
  .hero{padding:44px 0 24px}
}
@media (max-width:420px){
  .rooms{grid-template-columns:1fr}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 48 48" aria-hidden="true"><path d="M8 34 L6 14 L17 22 L24 8 L31 22 L42 14 L40 34 Z" fill="none" stroke="#d4a85a" stroke-width="2.4" stroke-linejoin="round"/><rect x="8" y="36" width="32" height="4" rx="1" fill="#d4a85a"/></svg>
<span>BlackCrown Intelligence</span>
</a>
<nav>
<a href="#ownership">Ownership</a>
<a href="#pricing">Pricing</a>
<a href="#rooms">Rooms</a>
</nav>
</header>

<div class="hero">
<div class="eyebrow">Crown, for skeptics</div>
<h1>Your context stays yours. Judge the output yourself.</h1>
<p class="lede">Crown is BlackCrown's private AI workspace. Skeptical of AI tools? Good. Start on the free tier with no card, run your own questions, and decide from the answers, not the marketing.</p>
<div class="chips">
<span class="chip"><b>Free tier</b>, no card</span>
<span class="chip"><b>49.99</b> a month</span>
<span class="chip"><b>$100</b> of room credit</span>
<span class="chip"><b>4</b> private rooms</span>
</div>
</div>

<section id="ownership">
<div class="eyebrow">The point</div>
<h2>Ownership is the product</h2>
<div class="prose">
<p>Most AI tools ask you to trust where your questions go. Crown is built on a simpler answer. Your context belongs to you. It is never sold. It is never used to train models. Your chats are not anyone's training data, ours included.</p>
<p>That is a commitment we can state plainly and hold to. It is the reason we run Crown as a private workspace instead of a feed of your thinking.</p>
</div>
<div class="grid" style="margin-top:24px">
<div class="card"><h3>Never sold</h3><p>Your context is not a product line. We do not package it, license it, or trade it.</p></div>
<div class="card"><h3>Never trained on</h3><p>Your conversations are not training data. Not for Crown, not for anyone else.</p></div>
</div>
</section>

<section id="pricing">
<div class="eyebrow">Pricing in dollars</div>
<h2>A flat monthly price with a visible balance</h2>
<div class="prose">
<p>Crowned is 49.99 a month and carries $100 of room credit. It runs like a prepaid balance you can watch. There are no surprise bills. Top-ups start at 4.99 and never expire.</p>
<p>Deep-Logic draws more credit per answer on purpose. Those rooms think harder, and real reasoning costs real compute, so the credit reflects that cost openly.</p>
</div>

<div class="figure" role="img" aria-label="Illustration of a room credit balance draining across a month">
<div class="figure-head">
<strong>Your room credit this month</strong>
<span class="tag">Illustration</span>
</div>
<div class="meter"><span style="width:62%"></span></div>
<div class="rows">
<div class="row"><span>Starting room credit</span><strong>$100.00</strong></div>
<div class="row"><span>Standard room questions</span><strong>-$14.20</strong></div>
<div class="row"><span>Deep-Logic analysis</span><strong>-$18.60</strong></div>
<div class="row"><span>Remaining balance</span><strong>$67.20</strong></div>
</div>
<p class="note">Illustration only. Figures show how a balance moves, not a typical bill or an expected usage pattern.</p>
</div>
</section>

<section id="rooms">
<div class="eyebrow">Four private rooms</div>
<h2>Pick the room for the job</h2>
<div class="rooms">
<div class="room"><h3>Unfiltered</h3><p>Direct answers with fewer guardrails on tone, for blunt working conversations.</p></div>
<div class="room"><h3>Deep-Logic</h3><p>Slower, heavier reasoning. Draws more credit per answer because it thinks harder.</p></div>
<div class="room"><h3>Visual Analysis</h3><p>Work through charts, screenshots, and images you already have.</p></div>
<div class="room"><h3>Creativity</h3><p>Drafts, outlines, and alternate framings when you need options.</p></div>
</div>
</section>

<section>
<div class="eyebrow">Test it before you pay</div>
<h2>The free tier is the argument</h2>
<div class="prose">
<p>The free tier includes a monthly allowance and needs no card. Run the questions you would actually ask. Check the reasoning. Compare it to what you already use. If the output does not hold up, that is a fair result and you owe us nothing.</p>
</div>
<div class="cta">
<a class="btn btn-primary" href="/">Start free, no card</a>
<a class="btn btn-ghost" href="/">See the Crowned plan</a>
</div>
<p class="fine">Crown is an information and productivity tool. Nothing on this page is financial, trading, or investment advice, and no output should be treated as a promise of results. Pricing and credit terms are as stated at the time of viewing.</p>
</section>

<footer>
<span>BlackCrown Intelligence, a BlackCrownVxJ LLC division</span>
<span><a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></span>
</footer>
</div>
</body>
</html>
