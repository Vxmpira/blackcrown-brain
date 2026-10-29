# Copy: Write the complete crown skeptic html document into a vault

Date: 2026-10-29
Task: Write the complete Crown skeptic html document into a vault note, ending in a closing html tag
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown Privacy for Skeptics | BlackCrown Intelligence</title>
<meta name="description" content="Your context stays yours. Crown is never sold, never trained on, and your chats are nobody's training data. Judge the output yourself on the free tier, no card.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptics">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--panel:#0e1119;--line:#1d2332;--ink:#e7e9ef;--mute:#8a93a6;--gold:#d4a84b;--teal:#3fb8af}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 500px at 15% -10%,rgba(212,168,75,.14),transparent 60%),radial-gradient(800px 500px at 95% 10%,rgba(63,184,175,.10),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.04em}
.brand svg{width:38px;height:38px}
nav a{color:var(--mute);text-decoration:none;margin-left:20px;font-size:.95rem}
nav a:hover{color:var(--ink)}
.hero{padding:72px 0 40px;display:grid;grid-template-columns:1.15fr .85fr;gap:40px;align-items:center}
.eyebrow{color:var(--gold);font-size:.8rem;letter-spacing:.18em;text-transform:uppercase;margin-bottom:14px}
h1{font-size:clamp(2rem,4.6vw,3.3rem);line-height:1.12;letter-spacing:-.01em;margin-bottom:18px}
h2{font-size:clamp(1.4rem,2.6vw,1.9rem);margin:0 0 14px}
h3{font-size:1.05rem;margin-bottom:6px}
.lede{font-size:clamp(1.02rem,1.6vw,1.15rem);color:var(--mute);max-width:36em}
.prose{max-width:44em}
.prose p{color:var(--mute);margin-bottom:14px}
.cta{display:inline-block;margin-top:22px;margin-right:10px;padding:13px 22px;border-radius:10px;font-weight:700;text-decoration:none;background:var(--gold);color:#16120a}
.cta.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
.panel{background:linear-gradient(180deg,var(--panel),#0a0d14);border:1px solid var(--line);border-radius:16px;padding:22px}
.label{color:var(--mute);font-size:.78rem;letter-spacing:.12em;text-transform:uppercase}
.meter{margin:14px 0 8px;height:12px;border-radius:8px;background:#161c2a;overflow:hidden}
.meter span{display:block;height:100%;width:62%;background:linear-gradient(90deg,var(--teal),var(--gold))}
.row{display:flex;justify-content:space-between;font-size:.92rem;color:var(--mute);margin-top:6px}
.row b{color:var(--ink)}
.illus{font-size:.72rem;color:var(--mute);margin-top:12px;font-style:italic}
section{padding:52px 0;border-top:1px solid var(--line)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:22px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.card p{color:var(--mute);font-size:.95rem}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:18px}
.chip{border:1px solid var(--line);border-radius:999px;padding:8px 14px;font-size:.9rem;color:var(--ink);background:#0b0f18}
.chip i{font-style:normal;color:var(--gold);margin-right:6px}
.pricing{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:22px}
.tier{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:24px}
.tier.hot{border-color:rgba(212,168,75,.5)}
.price{font-size:2rem;font-weight:800;margin:8px 0}
.price small{font-size:.9rem;color:var(--mute);font-weight:400}
ul.list{list-style:none;margin-top:12px}
ul.list li{color:var(--mute);padding:6px 0 6px 22px;position:relative;font-size:.95rem}
ul.list li::before{content:"";position:absolute;left:0;top:14px;width:8px;height:8px;border-radius:2px;background:var(--teal)}
.quote{border-left:3px solid var(--gold);padding:6px 0 6px 18px;color:var(--ink);font-size:1.05rem;max-width:44em;margin-top:18px}
footer{padding:30px 0 50px;border-top:1px solid var(--line);color:var(--mute);font-size:.85rem}
footer a{color:var(--mute)}
@media (max-width:700px){
.hero{grid-template-columns:1fr;padding:44px 0 24px;gap:28px}
.grid,.pricing{grid-template-columns:1fr}
nav a{margin-left:14px;font-size:.88rem}
header{flex-wrap:wrap;gap:10px}
section{padding:40px 0}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 48 48" aria-hidden="true"><path d="M8 34 L8 18 L16 26 L24 12 L32 26 L40 18 L40 34 Z" fill="none" stroke="#d4a84b" stroke-width="2.4" stroke-linejoin="round"/><circle cx="24" cy="38" r="3" fill="#3fb8af"/></svg>
<span>BlackCrown Intelligence</span>
</a>
<nav>
<a href="#ownership">Ownership</a>
<a href="#pricing">Pricing</a>
<a href="#try">Try it</a>
</nav>
</header>

<div class="hero">
<div>
<div class="eyebrow">Crown, Intelligence Crowned</div>
<h1>Your context stays yours. Judge the output yourself.</h1>
<p class="lede">Crown is a private AI workspace from BlackCrown. Your conversations are never sold, never trained on, and never handed to anyone as training data. If you are skeptical of AI companies, you are right to be. Start with the terms you can read here, then test the answers on your own work.</p>
<a class="cta" href="#try">Start free, no card</a>
<a class="cta ghost" href="#pricing">See Crowned pricing</a>
</div>
<div class="panel" aria-label="Room credit example">
<div class="label">Room credit, example balance</div>
<div class="row" style="margin-top:10px"><span>Crowned allowance</span><b>$100.00</b></div>
<div class="meter"><span></span></div>
<div class="row"><span>Remaining</span><b>$62.00</b></div>
<div class="row"><span>Deep-Logic answer</span><b>draws more credit</b></div>
<div class="illus">Illustration. Balance shown as money, metered live like a prepaid balance.</div>
</div>
</div>
</div>

<section id="ownership">
<div class="wrap">
<div class="prose">
<h2>Ownership is the whole point</h2>
<p>Most AI products ask you to trust a policy page and move on. Crown is built on a narrower promise you can check against the product itself: the context you bring into Crown belongs to you. We do not sell it. We do not train on it. Your chats are not training data for us or for anyone we partner with.</p>
<p>That is a claim about who holds your work, not a claim about how clever the answers are. We would rather you read the terms, test the output on a real problem, and decide from there.</p>
</div>
<div class="chips">
<div class="chip"><i>/</i>Never sold</div>
<div class="chip"><i>/</i>Never trained on</div>
<div class="chip"><i>/</i>Your chats are nobody's training data</div>
</div>
<p class="quote">Your context is yours. We are the room it lives in, not the buyer of it.</p>
</div>
</section>

<section>
<div class="wrap">
<h2>Four private rooms</h2>
<p class="prose" style="color:var(--mute)">Each room is a different way of working, all inside the same private workspace.</p>
<div class="grid">
<div class="card"><h3>Unfiltered</h3><p>Direct answers to direct questions, without the hedging you have learned to ignore.</p></div>
<div class="card"><h3>Deep-Logic</h3><p>Slower, heavier reasoning on purpose. The heavy rooms draw more credit because they think harder.</p></div>
<div class="card"><h3>Visual Analysis</h3><p>Work through charts, screenshots, and layouts with the image in front of you.</p></div>
<div class="card"><h3>Creativity</h3><p>Drafts, angles, and rough ideas that you shape into something finished.</p></div>
</div>
</div>
</section>

<section id="pricing">
<div class="wrap">
<h2>Pricing you can read in one glance</h2>
<p class="prose" style="color:var(--mute)">Usage is shown as money, the way you would see an allowance on any prepaid account. No surprise bills.</p>
<div class="pricing">
<div class="tier">
<div class="label">Free</div>
<div class="price">$0 <small>a month, no card</small></div>
<ul class="list">
<li>A free monthly allowance to test real work</li>
<li>All four rooms available within the allowance</li>
<li>Same privacy terms as every tier</li>
</ul>
</div>
<div class="tier hot">
<div class="label">Crowned</div>
<div class="price">$49.99 <small>a month</small></div>
<ul class="list">
<li>Carries $100 of room credit each month</li>
<li>Metered live, like a prepaid balance</li>
<li>Deep-Logic draws more credit per answer because real reasoning costs real compute</li>
<li>Top-ups from $4.99, and they never expire</li>
</ul>
</div>
</div>
</div>
</section>

<section id="try">
<div class="wrap">
<div class="prose">
<h2>Skeptical? Good. Test it.</h2>
<p>Take one real problem from your week, a contract clause, a chart you already read, a draft you are stuck on, and run it through the free tier. No card, no sales call. If the answer is useful, keep going. If it is not, you have lost a few minutes and learned something about us.</p>
</div>
<a class="cta" href="/">Open Crown free</a>
<a class="cta ghost" href="#ownership">Read the ownership terms again</a>
</div>
</section>

<footer>
<div class="wrap">
<p>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com</p>
<p style="margin-top:8px">Crown is BlackCrown's own private workspace. Nothing on this page is financial advice.</p>
</div>
</footer>
</body>
</html>
