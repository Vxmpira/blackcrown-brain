# Copy: Rewrite crown skeptic page as one complete html document under

Date: 2026-10-29
Task: Rewrite Crown skeptic page as one complete html document, under 240 lines
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown for Skeptics: Your Context, Your Call</title>
<meta name="description" content="Crown is BlackCrown's private AI workspace. Your context stays yours, never sold, never trained on. Flat 49.99 a month, $100 of room credit, and a free tier with no card.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptics.html">
<style>
:root{--bg:#07080c;--panel:#0e1119;--line:#1d2332;--ink:#e7eaf2;--mute:#9aa3b8;--gold:#d7b15a;--cyan:#4fd1e0}
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(79,209,224,.10),transparent 70%),radial-gradient(50% 35% at 90% 10%,rgba(215,177,90,.09),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.03) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.03) 1px,transparent 1px);background-size:44px 44px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;justify-content:space-between;padding:22px 0;border-bottom:1px solid var(--line);gap:12px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;color:var(--ink);text-decoration:none}
.brand small{display:block;font-weight:400;color:var(--mute);font-size:12px;letter-spacing:.02em}
nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:14px}
nav a:hover{color:var(--ink)}
.hero{padding:72px 0 48px;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
.eyebrow{color:var(--gold);font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin-bottom:14px}
h1{font-size:clamp(30px,4.6vw,50px);line-height:1.12;letter-spacing:-.02em;margin-bottom:18px}
h2{font-size:clamp(22px,3vw,30px);line-height:1.2;margin-bottom:12px}
h3{font-size:17px;margin-bottom:6px}
p{color:var(--mute);max-width:66ch;margin-bottom:14px}
.lead{font-size:clamp(16px,1.8vw,19px);color:var(--ink)}
.cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:24px}
.btn{display:inline-block;padding:13px 22px;border-radius:10px;font-weight:600;text-decoration:none;font-size:15px}
.btn-primary{background:var(--gold);color:#16120a}
.btn-ghost{border:1px solid var(--line);color:var(--ink);background:rgba(255,255,255,.02)}
.note{font-size:13px;color:var(--mute);margin-top:12px}
.panel{background:linear-gradient(180deg,rgba(255,255,255,.03),rgba(255,255,255,0)),var(--panel);border:1px solid var(--line);border-radius:16px;padding:22px}
.tag{display:inline-block;font-size:11px;letter-spacing:.1em;text-transform:uppercase;color:var(--cyan);border:1px solid rgba(79,209,224,.35);padding:3px 8px;border-radius:999px;margin-bottom:12px}
.meter{height:10px;background:#161c2a;border-radius:999px;overflow:hidden;margin:10px 0 6px}
.meter span{display:block;height:100%;width:64%;background:linear-gradient(90deg,var(--cyan),var(--gold))}
.row{display:flex;justify-content:space-between;font-size:14px;color:var(--mute);gap:10px}
.row b{color:var(--ink);font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.chip{font-size:13px;padding:6px 11px;border-radius:999px;background:#131a27;border:1px solid var(--line);color:var(--ink)}
section{padding:56px 0;border-top:1px solid var(--line)}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:22px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:20px}
.card p{margin:0;font-size:15px}
.price{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:22px}
.big{font-size:clamp(30px,4vw,40px);font-weight:700;letter-spacing:-.02em}
.big small{font-size:15px;color:var(--mute);font-weight:400}
ul.plain{list-style:none;margin-top:10px}
ul.plain li{padding:8px 0;border-bottom:1px solid var(--line);color:var(--mute);font-size:15px}
ul.plain li:last-child{border-bottom:0}
ul.plain li b{color:var(--ink)}
footer{padding:36px 0 56px;border-top:1px solid var(--line);color:var(--mute);font-size:13px}
footer a{color:var(--mute)}
@media (max-width:700px){
  .hero{grid-template-columns:1fr;padding:44px 0 32px;gap:28px}
  .grid3,.price{grid-template-columns:1fr}
  nav a{margin-left:12px}
  section{padding:40px 0}
}
</style>
</head>
<body>
<div class="wrap">
<header>
  <a class="brand" href="/">
    <svg width="34" height="34" viewBox="0 0 48 48" aria-hidden="true">
      <path d="M6 16 L16 28 L24 12 L32 28 L42 16 L38 36 H10 Z" fill="none" stroke="#d7b15a" stroke-width="2.4" stroke-linejoin="round"/>
      <circle cx="24" cy="8" r="2.4" fill="#4fd1e0"/>
      <rect x="10" y="38" width="28" height="3" rx="1.5" fill="#d7b15a"/>
    </svg>
    <span>BlackCrown Intelligence<small>Crown, private AI workspace</small></span>
  </a>
  <nav>
    <a href="#ownership">Ownership</a>
    <a href="#money">Pricing</a>
    <a href="#rooms">Rooms</a>
    <a href="#questions">Questions</a>
  </nav>
</header>

<div class="hero">
  <div>
    <div class="eyebrow">For skeptics</div>
    <h1>Your context stays yours. Judge the output yourself.</h1>
    <p class="lead">Crown is an AI workspace built on one rule: what you bring into it is never sold, never used to train models, and never handed to anyone else.</p>
    <p>You do not have to take our word for the answers. Start on the free tier, no card, and grade the work with your own standards.</p>
    <div class="cta">
      <a class="btn btn-primary" href="https://blackcrown-intelligence.com/chat.html">Try Crown free</a>
      <a class="btn btn-ghost" href="#money">See the flat price</a>
    </div>
    <div class="note">Free tier includes a monthly allowance. No card required.</div>
  </div>
  <div class="panel" aria-label="Illustration of room credit meter">
    <span class="tag">Illustration</span>
    <h3>Room credit, metered like a prepaid balance</h3>
    <div class="meter"><span></span></div>
    <div class="row"><span>Crowned balance</span><b>$64.00 of $100.00</b></div>
    <div class="row"><span>Deep-Logic answer</span><b>draws more credit</b></div>
    <div class="row"><span>Top-up credit</span><b>never expires</b></div>
    <div class="chips">
      <span class="chip">Private rooms</span>
      <span class="chip">Never trained on</span>
      <span class="chip">No surprise bills</span>
    </div>
  </div>
</div>

<section id="ownership">
  <div class="eyebrow">The core promise</div>
  <h2>Ownership is the product, not a feature bullet.</h2>
  <p>Most AI tools ask you to trust their data policy and move on. Crown is built so the question mostly stops mattering. Your conversations belong to you. They are not sold, they are not used as training data, and they are not shared with partners for ad targeting.</p>
  <div class="grid3">
    <div class="card"><h3>Not sold</h3><p>Your chats and the context you build inside Crown are never a product we sell to anyone.</p></div>
    <div class="card"><h3>Not trained on</h3><p>Your conversations are nobody's training data. Not ours, not a partner's, not a vendor's.</p></div>
    <div class="card"><h3>Yours to leave with</h3><p>Your context is yours. Take it when you go, or keep it where it is.</p></div>
  </div>
</section>

<section id="money">
  <div class="eyebrow">The price, in dollars</div>
  <h2>One flat monthly price. Usage shown as money.</h2>
  <p>Crowned is a flat monthly plan that carries $100 of room credit. Your balance is metered live, the way a prepaid balance works, so you always know what is left.</p>
  <div class="price">
    <div class="card">
      <h3>Free</h3>
      <div class="big">$0 <small>a month</small></div>
      <ul class="plain">
        <li><b>Monthly allowance</b> included</li>
        <li><b>No card</b> required to start</li>
        <li>All four rooms available to test</li>
      </ul>
    </div>
    <div class="card">
      <h3>Crowned</h3>
      <div class="big">$49.99 <small>a month</small></div>
      <ul class="plain">
        <li><b>$100 of room credit</b> each month</li>
        <li><b>Deep-Logic</b> draws more credit per answer, on purpose, because heavy reasoning uses real compute</li>
        <li><b>Top-ups from $4.99</b> that never expire</li>
      </ul>
    </div>
  </div>
  <p class="note">No surprise bills. You see the balance draw down as you work, and you choose whether to top up.</p>
</section>

<section id="rooms">
  <div class="eyebrow">Four private rooms</div>
  <h2>Pick the room for the job.</h2>
  <div class="grid3">
    <div class="card"><h3>Unfiltered</h3><p>Direct answers with fewer guardrails on tone. Your room, your call.</p></div>
    <div class="card"><h3>Deep-Logic</h3><p>Slower, heavier reasoning for hard problems. It draws more room credit because it thinks harder.</p></div>
    <div class="card"><h3>Visual Analysis</h3><p>Work through images and diagrams with the same ownership rules as text.</p></div>
  </div>
  <div class="grid3" style="margin-top:16px">
    <div class="card"><h3>Creativity</h3><p>Drafts, concepts, and rewrites. Keep the ideas, leave the rest.</p></div>
    <div class="card"><h3>Same rules everywhere</h3><p>Every room runs under the same ownership promise. No room is treated as a loophole.</p></div>
    <div class="card"><h3>Judge it yourself</h3><p>Run the same prompt in the free tier and compare the output to whatever you use today.</p></div>
  </div>
</section>

<section id="questions">
  <div class="eyebrow">Fair questions</div>
  <h2>What a skeptic would ask first.</h2>
  <div class="grid3">
    <div class="card"><h3>Do you train on my chats?</h3><p>No. Your conversations are nobody's training data.</p></div>
    <div class="card"><h3>Is there a hidden meter?</h3><p>No. The balance is shown in dollars and drawn down live.</p></div>
    <div class="card"><h3>Do I need a card to test?</h3><p>No. The free tier has a monthly allowance and needs no card.</p></div>
  </div>
</section>

<section>
  <div class="eyebrow">Start with the free tier</div>
  <h2>Grade the output before you pay a dollar.</h2>
  <p>Open Crown, run your hardest real question, and decide for yourself. If the work holds up and the privacy promise matters to you, Crowned is one flat monthly price.</p>
  <div class="cta">
    <a class="btn btn-primary" href="https://blackcrown-intelligence.com/chat.html">Open Crown free</a>
    <a class="btn btn-ghost" href="mailto:BlackCrownVxJ.LLC@outlook.com">Contact the business</a>
  </div>
</section>
</div>

<footer>
  <div class="wrap">
    <p>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Crown is a general purpose workspace and nothing on this page is financial advice.</p>
    <p><a href="https://blackcrownvxj.com">blackcrownvxj.com</a> &middot; <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></p>
  </div>
</footer>
</body>
</html>
