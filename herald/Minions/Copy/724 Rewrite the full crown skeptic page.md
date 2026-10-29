# Copy: Rewrite the full crown skeptic page as one complete html

Date: 2026-10-29
Task: Rewrite the full Crown skeptic page as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown: Your Context Stays Yours</title>
<meta name="description" content="Crown by BlackCrown Intelligence. Your context stays yours, never sold, never trained on. Four private rooms, a flat 49.99 a month, and a free tier with no card.">
<link rel="canonical" href="https://blackcrown-intelligence.com/">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07080c;--ink:#e9ebf2;--mute:#9aa1b4;--line:#1d2130;--acc:#c9a54a;--acc2:#4a6cff;--card:#0d1019}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(201,165,74,.14),transparent 70%),radial-gradient(50% 40% at 90% 10%,rgba(74,108,255,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(var(--line) 1px,transparent 1px),linear-gradient(90deg,var(--line) 1px,transparent 1px);background-size:48px 48px;opacity:.25;mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{width:min(1060px,92%);margin:0 auto}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;letter-spacing:.04em;color:var(--ink);text-decoration:none}
.brand svg{width:40px;height:40px}
nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:.95rem}
nav a:hover{color:var(--ink)}
h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.1;letter-spacing:-.02em;margin:28px 0 16px;max-width:820px}
h2{font-size:clamp(1.4rem,3vw,1.9rem);margin:0 0 12px}
h3{font-size:1.1rem;margin:0 0 6px;color:var(--acc)}
p{max-width:68ch;margin:0 0 14px;color:var(--ink)}
.lead{font-size:clamp(1.05rem,2vw,1.2rem);color:var(--mute)}
section{padding:44px 0;border-top:1px solid var(--line)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:20px}
.card{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:20px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:18px 0}
.chip{border:1px solid var(--line);background:var(--card);border-radius:999px;padding:7px 14px;font-size:.9rem;color:var(--ink)}
.chip b{color:var(--acc);font-weight:600}
.figure{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:22px;margin-top:20px}
.figure .tag{font-size:.75rem;text-transform:uppercase;letter-spacing:.12em;color:var(--mute)}
.meter{height:14px;border-radius:999px;background:#161b28;overflow:hidden;margin:14px 0 8px}
.meter span{display:block;height:100%;width:62%;background:linear-gradient(90deg,var(--acc2),var(--acc))}
.row{display:flex;justify-content:space-between;gap:12px;font-size:.95rem;color:var(--mute);flex-wrap:wrap}
.row strong{color:var(--ink)}
table{width:100%;border-collapse:collapse;margin-top:18px;font-size:.95rem}
th,td{text-align:left;padding:12px 10px;border-bottom:1px solid var(--line)}
th{color:var(--mute);font-weight:500}
.btns{display:flex;gap:12px;flex-wrap:wrap;margin-top:22px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;text-decoration:none;font-weight:600}
.btn.p{background:var(--acc);color:#0a0a0a}
.btn.s{border:1px solid var(--line);color:var(--ink)}
footer{padding:36px 0 56px;border-top:1px solid var(--line);color:var(--mute);font-size:.9rem}
footer a{color:var(--mute)}
@media (max-width:700px){
.grid{grid-template-columns:1fr}
nav a{margin-left:0;margin-right:14px}
table th:nth-child(3),table td:nth-child(3){display:none}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/">
<svg viewBox="0 0 48 48" aria-hidden="true"><path d="M8 34 L8 18 L16 26 L24 12 L32 26 L40 18 L40 34 Z" fill="none" stroke="#c9a54a" stroke-width="2.5" stroke-linejoin="round"/><rect x="8" y="36" width="32" height="4" rx="1" fill="#c9a54a"/><circle cx="24" cy="8" r="2" fill="#4a6cff"/></svg>
<span>BlackCrown Intelligence</span>
</a>
<nav>
<a href="#ownership">Ownership</a>
<a href="#rooms">Rooms</a>
<a href="#pricing">Pricing</a>
<a href="#judge">Judge it yourself</a>
</nav>
</header>

<main>
<section style="border-top:0;padding-top:20px">
<h3>Crown, by BlackCrown Intelligence</h3>
<h1>Your context stays yours.</h1>
<p class="lead">Crown is a private AI workspace built for people who read the fine print. What you bring into a conversation belongs to you. It is never sold, never trained on, and your chats are nobody's training data. The rest of this page explains how that works and what it costs, in plain terms.</p>
<div class="chips">
<span class="chip"><b>Private</b> by design</span>
<span class="chip"><b>49.99</b> a month flat</span>
<span class="chip"><b>4</b> private rooms</span>
<span class="chip">Free tier, <b>no card</b></span>
</div>
</section>

<section id="ownership">
<h2>What ownership means here</h2>
<p>Ownership is a contract, not a feeling. Three commitments define it, and each one is a statement you can hold us to.</p>
<div class="grid">
<div class="card">
<h3>Never sold</h3>
<p>Your conversations, uploads, and working context are not sold to advertisers, brokers, or data resellers.</p>
</div>
<div class="card">
<h3>Never trained on</h3>
<p>Your chats are not used to train models. What you write stays a working record for you, not raw material for us.</p>
</div>
<div class="card">
<h3>Nobody's training data</h3>
<p>Your inputs do not become someone else's output. Your work product is yours to keep, export, or delete.</p>
</div>
</div>
</section>

<section id="rooms">
<h2>Four private rooms</h2>
<p>Crown is organized into four rooms. Each room is built for a different kind of thinking, and each one runs inside the same private boundary.</p>
<div class="grid">
<div class="card"><h3>Unfiltered</h3><p>Direct answers with fewer guardrails for adult questions, handled inside your private workspace.</p></div>
<div class="card"><h3>Deep-Logic</h3><p>The room for hard problems. It thinks longer, so it draws more credit per answer. More thought costs more compute, and the price reflects that openly.</p></div>
<div class="card"><h3>Visual Analysis</h3><p>Work through images, charts, and documents with a room tuned for reading what is on the page.</p></div>
<div class="card"><h3>Creativity</h3><p>Drafting, ideation, and long-form writing, with your drafts kept private to you.</p></div>
</div>
</section>

<section id="pricing">
<h2>Deep logic on purpose</h2>
<p>Deep-Logic is priced by the work it does. A quick answer uses little room credit. A hard, multi-step reasoning pass uses more, because it really does use more compute. We would rather show you that than hide it behind a vague promise.</p>

<h2 style="margin-top:36px">A flat price with no surprise bills</h2>
<p>Crowned is 49.99 a month and carries $100 of room credit. Think of it as a prepaid balance that is metered live, so you always see what is left. There are no hidden overages and no billing surprises at the end of the month.</p>

<div class="figure" aria-label="Illustrative room credit meter">
<div class="tag">Illustration</div>
<div class="row"><span>Room credit balance</span><strong>$62.00 of $100.00</strong></div>
<div class="meter"><span></span></div>
<div class="row"><span>Deep-Logic draws more per answer</span><span>Top-ups from $4.99, never expire</span></div>
</div>

<table>
<thead><tr><th>Plan</th><th>Price</th><th>What you get</th></tr></thead>
<tbody>
<tr><td>Free</td><td>$0, no card</td><td>A free monthly allowance to judge the output yourself</td></tr>
<tr><td>Crowned</td><td>49.99 a month</td><td>$100 of room credit, all four rooms, live metering</td></tr>
<tr><td>Top-up</td><td>From $4.99</td><td>Added room credit that never expires</td></tr>
</tbody>
</table>
</section>

<section id="judge">
<h2>Judge it yourself</h2>
<p>Skeptics should not have to take our word for anything. The free tier needs no card and no commitment. Run your own questions, check the reasoning, and decide whether the output earns a paid seat.</p>
<div class="btns">
<a class="btn p" href="https://blackcrown-intelligence.com/">Start on the free tier</a>
<a class="btn s" href="mailto:BlackCrownVxJ.LLC@outlook.com">Ask us a question</a>
</div>
</section>
</main>

<footer>
<p>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Crown is a general purpose AI workspace. Nothing on this page is financial advice, and no outcome is promised.</p>
<p>Business contact: <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a> &middot; <a href="https://blackcrownvxj.com">blackcrownvxj.com</a></p>
</footer>
</div>
</body>
</html>
