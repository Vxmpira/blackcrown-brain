# Copy: Write the complete crown skeptic page as one full html

Date: 2026-10-30
Task: Write the complete Crown skeptic page as one full html document, rebuilt style block included.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown: Judge the Output Yourself</title>
<meta name="description" content="Crown is BlackCrown's private AI workspace. Your context stays yours, never sold, never trained on. Try it free with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptics">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07070b;--ink:#e9e9f0;--mute:#9a9aae;--acc:#ff2d8f;--cy:#3fd3ff;--line:rgba(255,255,255,.09);--panel:rgba(16,16,24,.78)}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.22),transparent 38%),radial-gradient(circle at 88% 30%,rgba(63,211,255,.14),transparent 42%),radial-gradient(circle at 50% 100%,rgba(255,45,143,.12),transparent 45%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.75) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wrap{max-width:1060px;margin:0 auto;padding:0 22px}
header{padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:var(--ink);font-weight:700;letter-spacing:.04em}
.brand svg{width:36px;height:33px}
.brand span{font-size:1.02rem}
nav{float:right;display:flex;gap:18px;margin-top:6px}
nav a{color:var(--mute);text-decoration:none;font-size:.92rem}
nav a:hover{color:var(--ink)}
.hdr{display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:14px}
section{padding:58px 0;border-bottom:1px solid var(--line)}
h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.1;letter-spacing:-.01em;max-width:18ch}
h2{font-size:clamp(1.45rem,3.2vw,2.1rem);line-height:1.2;margin-bottom:14px}
h3{font-size:1.08rem;margin-bottom:8px}
.kicker{color:var(--acc);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase;font-weight:700;margin-bottom:12px}
p{max-width:75ch;color:var(--ink);margin-bottom:14px}
.lead{font-size:clamp(1.05rem,2vw,1.2rem);color:var(--mute)}
.muted{color:var(--mute)}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:700;text-decoration:none;margin-right:10px;margin-top:8px}
.btn-p{background:var(--acc);color:#120008}
.btn-g{border:1px solid var(--line);color:var(--ink)}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-top:20px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:22px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}
.chip{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:7px 14px;border-radius:999px;font-size:.9rem;background:rgba(255,45,143,.08)}
.chip.c{border-color:rgba(63,211,255,.45);background:rgba(63,211,255,.08)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:24px;margin-top:20px;width:100%}
.panel-top{display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;gap:10px}
.price{font-size:clamp(1.8rem,4vw,2.4rem);font-weight:800}
.tag{font-size:.75rem;letter-spacing:.12em;text-transform:uppercase;color:var(--cy);border:1px solid rgba(63,211,255,.4);padding:4px 10px;border-radius:999px}
.bar{height:14px;border-radius:999px;background:rgba(255,255,255,.06);overflow:hidden;margin:16px 0 8px}
.bar i{display:block;height:100%;width:100%;background:linear-gradient(90deg,var(--acc),var(--cy))}
.row{display:flex;justify-content:space-between;gap:12px;font-size:.92rem;color:var(--mute);flex-wrap:wrap}
.rows{width:100%;border-collapse:collapse;margin-top:16px;font-size:.95rem}
.rows td{padding:10px 4px;border-bottom:1px solid var(--line);vertical-align:top}
.rows td:last-child{text-align:right;white-space:nowrap}
.note{font-size:.82rem;color:var(--mute);margin-top:12px}
footer{padding:36px 0 56px;color:var(--mute);font-size:.9rem}
footer a{color:var(--ink)}
@media (max-width:700px){
.grid{grid-template-columns:1fr}
nav{float:none;width:100%;margin-top:8px}
.btn{display:block;text-align:center;margin-right:0}
section{padding:44px 0}
}
</style>
</head>
<body>
<header>
<div class="wrap hdr">
<a class="brand" href="/" aria-label="BlackCrown Intelligence home">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>BlackCrown Intelligence</span>
</a>
<nav>
<a href="#ownership">Ownership</a>
<a href="#pricing">Pricing</a>
<a href="#rooms">Rooms</a>
<a href="#try">Try it free</a>
</nav>
</div>
</header>

<main>
<section>
<div class="wrap">
<div class="kicker">Crown, BlackCrown Intelligence</div>
<h1>Judge the output yourself.</h1>
<p class="lead">Crown is a private AI workspace from BlackCrown Intelligence. You are skeptical, and that is the right starting point. This page makes the case in plain terms, then gets out of your way so you can test it.</p>
<div class="chips">
<span class="chip">Private workspace</span>
<span class="chip c">Flat monthly price</span>
<span class="chip">Four private rooms</span>
<span class="chip c">Free tier, no card</span>
</div>
<a class="btn btn-p" href="https://blackcrown-intelligence.com/chat.html">Try Crown free</a>
<a class="btn btn-g" href="#ownership">Read the ownership terms</a>
</div>
</section>

<section id="ownership">
<div class="wrap">
<div class="kicker">The argument</div>
<h2>Your context stays yours.</h2>
<p>Crown is built around ownership. What you bring into a conversation, the documents, the questions, the working notes, belongs to you. It is never sold. It is never used to train models. Your chats are not training data, for us or anyone we work with.</p>
<p>That is the whole promise, and it is a promise about what happens to your material after you type it. Judge it against the terms, not against our adjectives.</p>
<div class="grid">
<div class="card">
<h3>Never sold</h3>
<p class="muted">Your conversations are not a product we package or license.</p>
</div>
<div class="card">
<h3>Never trained on</h3>
<p class="muted">Your chats do not become training data. Your context stays in your workspace.</p>
</div>
</div>
</div>
</section>

<section id="deep">
<div class="wrap">
<div class="kicker">Deep-Logic, on purpose</div>
<h2>Heavy thinking costs more, and we say so.</h2>
<p>Deep-Logic rooms think harder. Harder thinking uses real compute, so those answers draw more room credit than a quick reply. We would rather show you that cost openly than hide it behind a flat illusion of effort.</p>
<p>Lighter rooms draw less per answer. You always see the balance move, and you choose which room fits the question.</p>
</div>
</section>

<section id="pricing">
<div class="wrap">
<div class="kicker">Pricing, in dollars</div>
<h2>49.99 a month. 100 dollars of room credit. No surprise bills.</h2>
<p>Crowned is one flat monthly price of 49.99 that carries 100 dollars of room credit. Credit is metered live, like a prepaid balance. When it runs low you see it before it runs out, not on an invoice you did not expect.</p>

<div class="panel" role="img" aria-label="Illustration of a room credit balance panel">
<div class="panel-top">
<div>
<div class="muted" style="font-size:.85rem">Crowned plan</div>
<div class="price">49.99 / month</div>
</div>
<span class="tag">Illustration</span>
</div>
<div class="bar"><i></i></div>
<div class="row">
<span>Room credit included: 100 dollars</span>
<span>Example balance shown: full</span>
</div>
<table class="rows">
<tr><td>Standard room answer</td><td>Draws a small share of credit</td></tr>
<tr><td>Deep-Logic answer</td><td>Draws more, because it thinks harder</td></tr>
<tr><td>Top-up</td><td>From 4.99, never expires</td></tr>
</table>
<p class="note">Illustration. Figures on this panel are an example layout, not a live account or a quoted usage rate.</p>
</div>
</div>
</section>

<section id="rooms">
<div class="wrap">
<div class="kicker">Four private rooms</div>
<h2>Each room does one job well.</h2>
<p>Crown gives you four rooms. Pick the one that matches the work. Each room runs inside the same private workspace and the same ownership terms.</p>
<div class="grid">
<div class="card"><h3>Unfiltered</h3><p class="muted">Direct answers with fewer guardrails on tone, for candid working sessions.</p></div>
<div class="card"><h3>Deep-Logic</h3><p class="muted">Slower, heavier reasoning for hard problems. Draws more credit because it thinks harder.</p></div>
<div class="card"><h3>Visual Analysis</h3><p class="muted">Work through charts, layouts, and images you bring into the workspace.</p></div>
<div class="card"><h3>Creativity</h3><p class="muted">Drafting, ideation, and rewrites when the first version needs to be better.</p></div>
</div>
</div>
</section>

<section id="try">
<div class="wrap">
<div class="kicker">Judge it yourself</div>
<h2>Start free. No card.</h2>
<p>The free tier includes a monthly allowance and needs no card. You do not have to trust our copy. Ask Crown the questions you would ask any tool, then decide from the output.</p>
<div class="chips">
<span class="chip c">No card required</span>
<span class="chip">Monthly allowance</span>
<span class="chip c">Upgrade only if it earns it</span>
</div>
<a class="btn btn-p" href="https://blackcrown-intelligence.com/chat.html">Open Crown, free</a>
</div>
</section>
</main>

<footer>
<div class="wrap">
<p>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Crown is a private AI workspace. Nothing on this page is financial advice, and no outcome is promised.</p>
<p>Business contact: <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a> &middot; <a href="https://blackcrownvxj.com">blackcrownvxj.com</a></p>
</div>
</footer>
</body>
</html>
