# Copy: Write the entire crown skeptic page as one complete html

Date: 2026-10-29
Task: Write the ENTIRE Crown skeptic page as one complete html document, doctype through closing html tag, as your report. No placeholder text.
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Why Trust Crown With Your Work | BlackCrown Intelligence</title>
<meta name="description" content="Crown is a private AI workspace built on ownership: your context stays yours, never sold, never trained on. Try the free tier with no card.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptic.html">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{background:#07060c}
body{font-family:Georgia,"Times New Roman",serif;color:#e9e6f2;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;
background:
radial-gradient(circle at 15% 10%,rgba(255,45,143,.16),transparent 42%),
radial-gradient(circle at 88% 40%,rgba(123,77,255,.14),transparent 45%),
radial-gradient(circle at 40% 92%,rgba(255,45,143,.08),transparent 40%),
#07060c}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{padding:22px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;color:#e9e6f2;font-family:Georgia,serif;font-size:1.05rem;letter-spacing:.04em}
.brand svg{width:36px;height:33px;flex:none}
.tag{font-family:"Segoe UI",Arial,sans-serif;font-size:.8rem;color:#b9b2cc;letter-spacing:.12em;text-transform:uppercase;margin-top:2px}
h1{font-size:clamp(1.9rem,4.6vw,3.2rem);line-height:1.15;margin:56px 0 18px;font-weight:700}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:56px 0 14px;font-weight:700}
h2 .k{display:block;font-family:"Segoe UI",Arial,sans-serif;font-size:.78rem;letter-spacing:.14em;text-transform:uppercase;color:#ff2d8f;margin-bottom:8px}
p{max-width:70ch;margin:0 0 16px;font-size:1.05rem;color:#d6d1e4}
.lede{font-size:1.2rem;color:#f1edf9}
.cta{display:inline-block;margin-top:10px;padding:14px 26px;background:#ff2d8f;color:#07060c;font-family:"Segoe UI",Arial,sans-serif;font-weight:700;text-decoration:none;border-radius:4px;letter-spacing:.02em}
.cta:hover{background:#ff5aa6}
.note{font-family:"Segoe UI",Arial,sans-serif;font-size:.85rem;color:#a39cb8;margin-top:12px}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:18px 0 6px}
.chip{font-family:"Segoe UI",Arial,sans-serif;font-size:.85rem;padding:7px 14px;border:1px solid rgba(123,77,255,.55);background:rgba(123,77,255,.08);border-radius:999px;color:#ddd6f5}
.panel{width:100%;border:1px solid rgba(255,45,143,.35);background:rgba(15,12,26,.82);border-radius:8px;padding:24px;margin:24px 0}
.panel h3{font-family:"Segoe UI",Arial,sans-serif;font-size:.85rem;letter-spacing:.12em;text-transform:uppercase;color:#b9b2cc;margin-bottom:14px;font-weight:600}
.row{display:flex;justify-content:space-between;gap:16px;font-family:"Segoe UI",Arial,sans-serif;font-size:.95rem;padding:10px 0;border-bottom:1px solid rgba(255,255,255,.07)}
.row:last-child{border-bottom:0}
.row span:last-child{color:#f1edf9;font-weight:600}
.meter{height:14px;width:100%;background:rgba(255,255,255,.07);border-radius:999px;overflow:hidden;margin:14px 0 8px}
.meter i{display:block;height:100%;width:62%;background:linear-gradient(90deg,#7b4dff,#ff2d8f);border-radius:999px}
.scale{display:flex;justify-content:space-between;font-family:"Segoe UI",Arial,sans-serif;font-size:.78rem;color:#a39cb8}
.illus{font-family:"Segoe UI",Arial,sans-serif;font-size:.78rem;color:#ff9fcb;margin-top:14px;letter-spacing:.06em;text-transform:uppercase}
.split{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin:18px 0}
.card{border:1px solid rgba(255,255,255,.1);background:rgba(15,12,26,.7);border-radius:8px;padding:20px}
.card h4{font-family:"Segoe UI",Arial,sans-serif;font-size:1rem;margin-bottom:8px;color:#f1edf9}
.card p{font-size:.98rem;margin:0}
table{width:100%;border-collapse:collapse;font-family:"Segoe UI",Arial,sans-serif;font-size:.95rem;margin:16px 0;background:rgba(15,12,26,.7)}
th,td{text-align:left;padding:12px 14px;border-bottom:1px solid rgba(255,255,255,.08)}
th{color:#b9b2cc;font-weight:600;font-size:.82rem;letter-spacing:.08em;text-transform:uppercase}
td{color:#e4dff2}
.figure{width:100%;border:1px solid rgba(255,255,255,.1);border-radius:8px;padding:20px;background:rgba(15,12,26,.7);margin:20px 0}
.figure svg{width:100%;height:auto;display:block}
.figcap{font-family:"Segoe UI",Arial,sans-serif;font-size:.8rem;color:#a39cb8;margin-top:10px}
footer{margin:72px 0 40px;padding-top:24px;border-top:1px solid rgba(255,255,255,.08);font-family:"Segoe UI",Arial,sans-serif;font-size:.85rem;color:#a39cb8}
footer a{color:#ddd6f5}
@media (max-width:700px){
  .split{grid-template-columns:1fr}
  .row{flex-direction:column;gap:4px}
  .panel{padding:18px}
  th,td{padding:10px 8px;font-size:.88rem}
}
</style>
</head>
<body>
<header>
<div class="wrap">
<a class="brand" href="https://blackcrown-intelligence.com/">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
<span>BlackCrown Intelligence<div class="tag">Intelligence, Crowned</div></span>
</a>
</div>
</header>

<main class="wrap">

<h1>Why should you trust Crown with your work?</h1>
<p class="lede">Fair question. You doubt AI output, and you should. So we will not ask for faith. We will tell you what Crown does with your work, and you can judge the answers yourself before you pay a cent.</p>
<a class="cta" href="https://blackcrown-intelligence.com/">Try the free tier, no card</a>
<p class="note">The free tier needs no card. Run your own questions and grade the output on your terms.</p>

<h2><span class="k">The short answer</span>Your context stays yours.</h2>
<p>Crown is built on ownership. The material you bring into a session, the drafts, the research, the half formed ideas, belongs to you. We do not sell it. We do not use it to train models. Your chats are not training data.</p>

<h2><span class="k">What ownership means here</span>Your chats are nobody's training data.</h2>
<p>That is the whole privacy claim, and it is deliberately narrow. Nothing you write becomes material for training, for ours or anyone else's. If you stop using Crown tomorrow, the work you put into it is still yours to take.</p>

<h2><span class="k">Judge it before you trust it</span>Start on the free tier.</h2>
<p>Skepticism is the right starting point, so we built the free tier to answer it. It carries a free monthly allowance, shown in dollars, and asks for no card. Put the same hard question to Crown that you would put to any tool, then decide from the output alone.</p>
<a class="cta" href="https://blackcrown-intelligence.com/">Open the free tier</a>

<h2><span class="k">Deep logic on purpose</span>Heavy thinking costs more, and it says so.</h2>
<p>Deep-Logic draws more room credit per answer because it works harder. It reasons through a problem instead of skimming it. You see the cost before you spend it, so a hard question never arrives as a surprise line item.</p>

<h2><span class="k">Money, not mystery</span>One flat price, with the balance in view.</h2>
<p>Crowned is 49.99 a month and carries 100 dollars of room credit. Your balance is metered live, like a prepaid balance you can read at a glance. There are no surprise bills at the end of the month.</p>

<div class="panel" aria-label="Room credit balance, illustration">
<h3>Room credit balance</h3>
<div class="row"><span>Monthly plan</span><span>49.99</span></div>
<div class="row"><span>Room credit included</span><span>100.00</span></div>
<div class="row"><span>Remaining this cycle</span><span>62.40</span></div>
<div class="meter"><i></i></div>
<div class="scale"><span>0</span><span>50</span><span>100</span></div>
<div class="illus">Illustration. Sample figures only, not a live account.</div>
</div>

<h2><span class="k">Four private rooms</span>Each room has its own job.</h2>
<p>Work is easier to trust when the tool knows what kind of work it is doing. Crown is organized into four private rooms, each built for a different kind of thinking.</p>
<div class="chips">
<span class="chip">Unfiltered</span>
<span class="chip">Deep-Logic</span>
<span class="chip">Visual Analysis</span>
<span class="chip">Creativity</span>
</div>

<h2><span class="k">Top ups</span>Add credit when you need it.</h2>
<p>Top-ups start at 4.99 and never expire. Credit you add today is still there when your next project lands.</p>

<div class="split">
<div class="card">
<h4>Ownership</h4>
<p>Your context stays yours. It is never sold and never trained on.</p>
</div>
<div class="card">
<h4>Judgment</h4>
<p>The free tier needs no card, so you can test the output before you commit.</p>
</div>
</div>

<h2><span class="k">Side by side</span>What you get at each step.</h2>
<table>
<thead>
<tr><th>Tier</th><th>Cost</th><th>What it gives you</th></tr>
</thead>
<tbody>
<tr><td>Free</td><td>No card</td><td>A free monthly allowance to judge the output yourself</td></tr>
<tr><td>Crowned</td><td>49.99 a month</td><td>100 dollars of room credit, metered live, no surprise bills</td></tr>
<tr><td>Top-up</td><td>From 4.99</td><td>Added room credit that never expires</td></tr>
</tbody>
</table>

<div class="figure" aria-label="Illustration of credit flow">
<svg viewBox="0 0 640 140" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
<rect x="10" y="40" width="150" height="60" rx="6" stroke="#7b4dff"/>
<rect x="245" y="40" width="150" height="60" rx="6" stroke="#7b4dff"/>
<rect x="480" y="40" width="150" height="60" rx="6" stroke="#7b4dff"/>
<path d="M160 70 L245 70"/>
<path d="M395 70 L480 70"/>
<text x="85" y="76" fill="#e9e6f2" stroke="none" font-family="Segoe UI,Arial,sans-serif" font-size="15" text-anchor="middle">Your work</text>
<text x="320" y="76" fill="#e9e6f2" stroke="none" font-family="Segoe UI,Arial,sans-serif" font-size="15" text-anchor="middle">Your room</text>
<text x="555" y="76" fill="#e9e6f2" stroke="none" font-family="Segoe UI,Arial,sans-serif" font-size="15" text-anchor="middle">Your answer</text>
</svg>
<div class="figcap">Illustration. Your inputs and outputs stay with you. Nothing flows out to training.</div>
</div>

<h2><span class="k">Your call</span>Test it, then decide.</h2>
<p>You do not owe us trust. You owe your work a fair test. Use the free tier, ask the questions that matter to you, and judge the answers on the merits. If Crown earns a place in your workflow, Crowned is there at a flat monthly price with the balance in plain view.</p>
<a class="cta" href="https://blackcrown-intelligence.com/">Try the free tier, no card</a>

</main>

<footer>
<div class="wrap">
<p style="font-size:.85rem;color:#a39cb8;margin:0 0 10px">BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Intelligence, Crowned.</p>
<p style="font-size:.85rem;color:#a39cb8;margin:0">Business contact: <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a> &middot; <a href="https://blackcrown-intelligence.com/">blackcrown-intelligence.com</a></p>
</div>
</footer>
</body>
</html>
