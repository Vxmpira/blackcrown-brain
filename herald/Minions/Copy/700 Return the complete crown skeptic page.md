# Copy: Return the complete crown skeptic page doctype through closing html

Date: 2026-10-29
Task: Return the complete Crown skeptic page, doctype through closing html tag
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown: Judge the Output Yourself</title>
<meta name="description" content="BlackCrown Intelligence Crown is a private AI workspace. Your context stays yours, never sold, never trained on. Try the free tier with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/">
<style>
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:#07080b;color:#e7e9ee;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(900px 500px at 15% -10%,rgba(124,92,255,.22),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(0,190,220,.14),transparent 60%),radial-gradient(700px 500px at 50% 110%,rgba(255,176,64,.08),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{width:min(1060px,calc(100% - 40px));margin:0 auto}
header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:22px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.brand{display:flex;align-items:center;gap:12px;color:#e7e9ee;text-decoration:none;font-weight:700;letter-spacing:.02em}
.brand span{font-size:15px}
nav a{color:#aab0bd;text-decoration:none;margin-left:20px;font-size:14px}
nav a:hover{color:#fff}
.hero{padding:72px 0 48px}
.kicker{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:#b9a6ff;font-weight:600}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:14px 0 18px;letter-spacing:-.02em;max-width:18ch}
.lead{font-size:clamp(1.02rem,2vw,1.2rem);color:#c3c8d3;max-width:62ch}
.ctas{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:600;text-decoration:none;font-size:15px}
.btn.primary{background:#e7e9ee;color:#07080b}
.btn.ghost{border:1px solid rgba(255,255,255,.2);color:#e7e9ee}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:28px}
.chip{font-size:13px;padding:7px 12px;border-radius:999px;border:1px solid rgba(255,255,255,.14);background:rgba(255,255,255,.03);color:#d4d8e0}
section{padding:56px 0;border-top:1px solid rgba(255,255,255,.07)}
h2{font-size:clamp(1.5rem,3.4vw,2.1rem);line-height:1.2;margin-bottom:14px;letter-spacing:-.01em}
h3{font-size:1.05rem;margin-bottom:8px}
p{color:#c3c8d3;max-width:66ch;margin-bottom:14px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:28px}
.card{border:1px solid rgba(255,255,255,.1);border-radius:14px;padding:22px;background:rgba(12,14,20,.7)}
.card p{margin-bottom:0;font-size:15px}
.split{display:grid;grid-template-columns:1fr 1fr;gap:32px;align-items:start}
.figure{border:1px solid rgba(255,255,255,.1);border-radius:14px;padding:22px;background:rgba(12,14,20,.8)}
.figure-title{display:flex;justify-content:space-between;font-size:13px;color:#8e96a6;margin-bottom:16px}
.tag{font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:#ffc27a;border:1px solid rgba(255,194,122,.35);padding:3px 8px;border-radius:6px}
.bar{margin-bottom:14px}
.bar-label{display:flex;justify-content:space-between;font-size:13px;color:#aab0bd;margin-bottom:6px}
.track{height:10px;border-radius:999px;background:rgba(255,255,255,.07);overflow:hidden}
.fill{height:100%;border-radius:999px;background:linear-gradient(90deg,#7c5cff,#00c2dc)}
.fill.warm{background:linear-gradient(90deg,#ffb040,#ff7a59)}
.note{font-size:12px;color:#8e96a6;margin-top:12px}
.rooms{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:24px}
.room{border-left:2px solid #7c5cff;padding:14px 16px;background:rgba(255,255,255,.02);border-radius:8px}
.room p{font-size:14px;margin:6px 0 0}
.price{border:1px solid rgba(185,166,255,.35);border-radius:16px;padding:28px;background:linear-gradient(180deg,rgba(124,92,255,.12),rgba(12,14,20,.8))}
.price-amt{font-size:2.6rem;font-weight:700;letter-spacing:-.02em}
.price-amt small{font-size:15px;color:#aab0bd;font-weight:500}
ul.clean{list-style:none;margin:16px 0 0}
ul.clean li{padding:8px 0;border-bottom:1px solid rgba(255,255,255,.06);color:#c3c8d3;font-size:15px}
ul.clean li:last-child{border-bottom:0}
.faq{margin-top:24px;display:grid;gap:14px}
.faq div{border:1px solid rgba(255,255,255,.1);border-radius:12px;padding:18px 20px;background:rgba(12,14,20,.6)}
.faq p{margin:6px 0 0;font-size:15px}
.closing{text-align:left;padding:64px 0}
footer{border-top:1px solid rgba(255,255,255,.08);padding:28px 0 40px;font-size:13px;color:#8e96a6}
footer .row{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}
footer a{color:#aab0bd}
@media (max-width:900px){
.rooms{grid-template-columns:repeat(2,1fr)}
.grid{grid-template-columns:1fr 1fr}
}
@media (max-width:700px){
.wrap{width:calc(100% - 28px)}
header{flex-wrap:wrap}
nav a{margin-left:0;margin-right:16px}
.hero{padding:44px 0 32px}
.grid,.split,.rooms{grid-template-columns:1fr}
section{padding:40px 0}
.price{padding:22px}
}
</style>
</head>
<body>
<div class="wrap">
<header>
<a class="brand" href="/" aria-label="BlackCrown Intelligence home">
<svg width="34" height="34" viewBox="0 0 48 48" aria-hidden="true" focusable="false">
<path d="M8 36 L8 18 L17 27 L24 12 L31 27 L40 18 L40 36 Z" fill="none" stroke="#e7e9ee" stroke-width="2.4" stroke-linejoin="round"/>
<rect x="8" y="36" width="32" height="3" fill="#b9a6ff"/>
<circle cx="24" cy="8" r="2.2" fill="#00c2dc"/>
</svg>
<span>BlackCrown Intelligence</span>
</a>
<nav>
<a href="#ownership">Ownership</a>
<a href="#rooms">Rooms</a>
<a href="#pricing">Pricing</a>
<a href="#questions">Questions</a>
</nav>
</header>

<div class="hero">
<div class="kicker">Crown, BlackCrown Intelligence</div>
<h1>Judge the output yourself.</h1>
<p class="lead">Crown is a private AI workspace built by BlackCrown Intelligence, the AI division of BlackCrownVxJ LLC. Your context stays yours. It is never sold, never trained on, and your chats are nobody's training data. You do not have to take our word for the answers. Start free, with no card, and check them against your own work.</p>
<div class="ctas">
<a class="btn primary" href="https://blackcrown-intelligence.com/">Try the free tier</a>
<a class="btn ghost" href="#ownership">Read the privacy line</a>
</div>
<div class="chips">
<span class="chip">No card on the free tier</span>
<span class="chip">Four private rooms</span>
<span class="chip">Flat 49.99 a month</span>
<span class="chip">Context never sold</span>
</div>
</div>

<section id="ownership">
<div class="kicker">Ownership</div>
<h2>Your context belongs to you.</h2>
<p>Most AI tools are built around the question of what happens to your data after you hit enter. Crown answers that question first. What you type, upload, and build stays under your control. We do not sell it, we do not train models on it, and we do not treat your conversations as a resource for anything else.</p>
<div class="grid">
<div class="card">
<h3>Never sold</h3>
<p>Your context is not a product, not an ad signal, and not a data licensing deal.</p>
</div>
<div class="card">
<h3>Never trained on</h3>
<p>Your chats are not training data. They are your working material, and they stay that way.</p>
</div>
<div class="card">
<h3>Yours to take with you</h3>
<p>Your work belongs to your account. You decide what stays in the workspace and what leaves it.</p>
</div>
</div>
</section>

<section>
<div class="split">
<div>
<div class="kicker">Deep-Logic on purpose</div>
<h2>Heavy rooms cost more, because they think harder.</h2>
<p>Deep-Logic is built for the questions that need real reasoning. That reasoning uses real compute, so each answer draws more room credit than a quick reply. We state that plainly instead of hiding it behind a vague limit. You see the cost before you spend it.</p>
<p>Your balance works like a prepaid meter. You can watch it move as you work.</p>
</div>
<div class="figure" role="img" aria-label="Illustration: room credit draw per answer by room">
<div class="figure-title"><span>Room credit draw per answer</span><span class="tag">Illustration</span></div>
<div class="bar">
<div class="bar-label"><span>Quick reply</span><span>Light draw</span></div>
<div class="track"><div class="fill" style="width:22%"></div></div>
</div>
<div class="bar">
<div class="bar-label"><span>Creativity</span><span>Moderate draw</span></div>
<div class="track"><div class="fill" style="width:46%"></div></div>
</div>
<div class="bar">
<div class="bar-label"><span>Visual Analysis</span><span>Heavy draw</span></div>
<div class="track"><div class="fill warm" style="width:70%"></div></div>
</div>
<div class="bar">
<div class="bar-label"><span>Deep-Logic</span><span>Heaviest draw</span></div>
<div class="track"><div class="fill warm" style="width:92%"></div></div>
</div>
<p class="note">Illustrative only. Relative draw shown for comparison, not a quoted rate.</p>
</div>
</div>
</section>

<section id="rooms">
<div class="kicker">Four private rooms</div>
<h2>One workspace, four ways to work.</h2>
<p>Each room is built for a different kind of thinking. Use the one that fits the job in front of you.</p>
<div class="rooms">
<div class="room"><h3>Unfiltered</h3><p>Direct, plain answers for hard questions you want stated straight.</p></div>
<div class="room"><h3>Deep-Logic</h3><p>Slower, heavier reasoning for problems that need careful steps.</p></div>
<div class="room"><h3>Visual Analysis</h3><p>Work through charts, images, and layouts with a close read.</p></div>
<div class="room"><h3>Creativity</h3><p>Drafts, angles, and ideas when you need options fast.</p></div>
</div>
</section>

<section id="pricing">
<div class="split">
<div>
<div class="kicker">Pricing</div>
<h2>A flat monthly price with no surprise bills.</h2>
<p>Crowned is 49.99 a month and carries $100 of room credit. Your balance is metered live, so you always know where you stand. If you need more, top-ups start at 4.99, and top-up credit never expires.</p>
<p>Not sure yet? The free tier includes a free monthly allowance and needs no card. Run the same questions you would ask anyone else and judge the output yourself.</p>
</div>
<div class="price">
<div class="kicker">Crowned</div>
<div class="price-amt">49.99 <small>per month</small></div>
<ul class="clean">
<li>$100 of room credit included each month</li>
<li>Live metering, no surprise bills</li>
<li>All four private rooms</li>
<li>Top-ups from 4.99, never expire</li>
</ul>
<div class="ctas"><a class="btn primary" href="https://blackcrown-intelligence.com/">Start with the free tier</a></div>
</div>
</div>
</section>

<section id="questions">
<div class="kicker">Questions</div>
<h2>Fair questions, plain answers.</h2>
<div class="faq">
<div>
<h3>Do you train on my chats?</h3>
<p>No. Your chats are nobody's training data. We do not sell your context or use it to train models.</p>
</div>
<div>
<h3>Do I need a card to try it?</h3>
<p>No. The free tier needs no card. You can test the output before you decide anything.</p>
</div>
<div>
<h3>Why does Deep-Logic cost more?</h3>
<p>It reasons harder, and harder reasoning uses more compute. The credit draw is shown up front so you are never guessing.</p>
</div>
<div>
<h3>Is this unlimited?</h3>
<p>No. Crown runs on a stated room credit balance. We would rather tell you the number than promise something we cannot price honestly.</p>
</div>
</div>
</section>

<section class="closing">
<div class="kicker">Judge it yourself</div>
<h2>Start free. Check the work. Keep your context.</h2>
<p>Crown is built for people who want to verify before they trust. Open the free tier, run your own questions, and decide on the output.</p>
<div class="ctas">
<a class="btn primary" href="https://blackcrown-intelligence.com/">Open Crown free</a>
</div>
</section>
</div>

<footer>
<div class="wrap">
<div class="row">
<span>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC.</span>
<span>Contact: <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></span>
</div>
<p style="margin-top:12px;font-size:12px;color:#8e96a6">Nothing on this page is financial advice. Crown is a general AI workspace and does not give trading recommendations.</p>
</div>
</footer>
</body>
</html>
