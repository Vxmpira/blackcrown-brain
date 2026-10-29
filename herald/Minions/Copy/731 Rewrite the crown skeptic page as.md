# Copy: Rewrite the crown skeptic page as one complete html document

Date: 2026-10-29
Task: Rewrite the Crown skeptic page as one complete html document, under 40 lines of CSS
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Judge Crown Yourself | BlackCrown Intelligence</title>
<meta name="description" content="Crown keeps your context yours: never sold, never trained on. Try the free tier with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptics">
<style>
:root{--ink:#e9e7ef;--mute:#9d98ab;--pink:#ff2d8f;--bg:#07060b;--card:#110e18;--line:#2a2435}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
body{min-height:100vh;position:relative;overflow-x:hidden}
.bgglow{position:fixed;inset:0;z-index:-3;background:radial-gradient(60% 40% at 12% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50% 40% at 92% 35%,rgba(120,80,255,.14),transparent 70%)}
.bggrid{position:fixed;inset:0;z-index:-2;opacity:.18;background:linear-gradient(var(--line) 1px,transparent 1px) 0 0/48px 48px,linear-gradient(90deg,var(--line) 1px,transparent 1px) 0 0/48px 48px}
.vig{position:fixed;inset:0;z-index:-1;pointer-events:none;box-shadow:inset 0 0 160px rgba(0,0,0,.85)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;gap:12px;padding:22px 0;border-bottom:1px solid var(--line)}
header svg{width:36px;height:33px}
.brand{font-weight:700;letter-spacing:.04em}
h1{font-size:clamp(1.9rem,5vw,3.2rem);line-height:1.1;margin:56px 0 16px;max-width:20ch}
h2{font-size:clamp(1.3rem,3vw,1.8rem);margin:52px 0 14px}
.lede,.prose{max-width:66ch;color:var(--mute);margin:0 0 12px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:22px}
.card h3{margin:0 0 8px;font-size:1.05rem}
.card p{margin:0;color:var(--mute);font-size:.95rem}
.chip{display:inline-block;border:1px solid var(--pink);color:var(--pink);border-radius:999px;padding:4px 14px;font-size:.88rem;margin:4px 8px 4px 0}
.mock{background:#0c0a12;border:1px solid var(--line);border-radius:14px;padding:18px;max-width:640px}
.tag{font-size:.72rem;color:var(--mute);text-transform:uppercase;letter-spacing:.12em}
.bub{padding:10px 14px;border-radius:10px;margin:10px 0;max-width:85%;font-size:.95rem}
.me{background:#1d1829;margin-left:auto}
.ai{background:#17111f;border-left:2px solid var(--pink)}
.meter{height:8px;background:#221c2e;border-radius:4px;overflow:hidden;margin-top:14px}
.meter i{display:block;height:100%;width:72%;background:linear-gradient(90deg,var(--pink),#8a5cff)}
.cta{display:inline-block;background:var(--pink);color:#07060b;font-weight:700;padding:12px 22px;border-radius:8px;text-decoration:none;margin:8px 12px 0 0}
.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
footer{margin:64px 0 40px;color:var(--mute);font-size:.85rem;border-top:1px solid var(--line);padding-top:20px}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{padding:0 16px}.bub{max-width:100%}}
</style>
</head>
<body>
<div class="bgglow"></div>
<div class="bggrid"></div>
<div class="vig"></div>
<div class="wrap">
<header>
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span class="brand">BlackCrown Intelligence</span>
</header>

<h1>Skeptical? Good. Judge Crown on its output.</h1>
<p class="lede">Crown is a private AI workspace built by BlackCrown. Your context stays yours. It is never sold and never used to train models. Your chats are nobody's training data, including ours.</p>
<p>
<a class="cta" href="https://blackcrown-intelligence.com/chat.html">Try the free tier</a>
<a class="cta ghost" href="#pricing">See the flat price</a>
</p>

<h2>Your context stays yours</h2>
<div class="grid">
<div class="card"><h3>Never sold</h3><p>What you write into Crown is not a product we sell to anyone, to advertisers, or to data brokers.</p></div>
<div class="card"><h3>Never trained on</h3><p>Your prompts, files and answers are not used to train any model, ours or anyone else's.</p></div>
<div class="card"><h3>Nobody's training data</h3><p>Your chats belong to you. Export them, or delete them, on your terms.</p></div>
<div class="card"><h3>Ownership, stated plainly</h3><p>Ownership is the promise. Read the terms, then test the product against the promise.</p></div>
</div>

<h2>Judge the output yourself</h2>
<p class="prose">The free tier includes a free monthly allowance and needs no card. Run your own questions, your own documents, your own edge cases. If the output does not hold up, you have lost nothing but a few minutes.</p>

<h2>What it looks like</h2>
<div class="mock" aria-label="Illustration of a Crown chat">
<div class="tag">Illustration</div>
<div class="bub me">Review this draft contract clause and flag anything unusual.</div>
<div class="bub ai">Clause 4 caps liability at fees paid in the prior month. Two terms conflict with your termination notice. Here is the reasoning, step by step.</div>
<div class="tag" style="margin-top:14px">Room credit, illustrative</div>
<div class="meter"><i></i></div>
</div>

<h2 id="pricing">Flat price, no surprise bills</h2>
<div class="grid">
<div class="card"><h3>Crowned: 49.99 a month</h3><p>A flat monthly plan that carries $100 of room credit. Usage is metered live against that balance, like a prepaid account, so you always see what is left.</p></div>
<div class="card"><h3>Deep-Logic draws more credit</h3><p>Deep-Logic thinks harder, so each answer draws more credit. That is deliberate: real reasoning costs real compute, and the price shows it openly.</p></div>
<div class="card"><h3>Top-ups from $4.99</h3><p>Add room credit when you need it. Top-ups never expire.</p></div>
<div class="card"><h3>Four private rooms</h3><p><span class="chip">Unfiltered</span><span class="chip">Deep-Logic</span><span class="chip">Visual Analysis</span><span class="chip">Creativity</span></p></div>
</div>

<h2>Start with the free tier</h2>
<p class="prose">No card, no trial clock. Test the output, check the privacy terms, and decide for yourself.</p>
<p><a class="cta" href="https://blackcrown-intelligence.com/chat.html">Open Crown free</a></p>

<footer>
BlackCrown Intelligence is a division of BlackCrownVxJ LLC. Business contact: BlackCrownVxJ.LLC@outlook.com. Nothing on this page is financial advice.
</footer>
</div>
</body>
</html>
</body></html>
