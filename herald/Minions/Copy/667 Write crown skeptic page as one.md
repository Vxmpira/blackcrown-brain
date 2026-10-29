# Copy: Write crown skeptic page as one complete html document

Date: 2026-10-29
Task: Write Crown skeptic page as one complete html document
For [[Herald]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crown for Skeptics: Your Context Stays Yours</title>
<meta name="description" content="Crown is BlackCrown's private AI workspace. Your context is never sold and never trained on. Try the free tier with no card and judge the output yourself.">
<link rel="canonical" href="https://blackcrown-intelligence.com/skeptics">
<style>
:root{--bg:#07080c;--panel:#0e1118;--line:#1d2330;--ink:#e7eaf2;--mute:#8d95a8;--gold:#d4a72c;--gold2:#f0cd6a}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:var(--gold2)}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid var(--line);padding:18px 0}
header .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:10px;color:var(--ink);text-decoration:none;font-weight:700;letter-spacing:.04em}
.nav a{color:var(--mute);text-decoration:none;margin-left:18px;font-size:14px}
.nav a:hover{color:var(--ink)}
.hero{padding:64px 0 40px}
.eyebrow{color:var(--gold);font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin:0 0 12px}
h1{font-size:40px;line-height:1.15;margin:0 0 16px;max-width:760px}
h2{font-size:24px;margin:0 0 12px}
p{margin:0 0 14px;color:#c9cfdc}
.lead{font-size:19px;color:var(--ink);max-width:700px}
.btn{display:inline-block;background:var(--gold);color:#120e02;font-weight:700;text-decoration:none;padding:12px 20px;border-radius:6px;margin-right:10px;margin-top:6px}
.btn.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
section{padding:40px 0;border-top:1px solid var(--line)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px;margin-top:18px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:18px}
.card h3{margin:0 0 8px;font-size:17px}
.card p{font-size:15px;margin:0}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px}
.chip{background:var(--panel);border:1px solid var(--line);border-radius:999px;padding:6px 14px;font-size:14px;color:var(--gold2)}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:22px}
.tag{display:inline-block;font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:var(--mute);border:1px solid var(--line);border-radius:4px;padding:2px 8px;margin-bottom:12px}
.meter{height:12px;background:#171c27;border-radius:999px;overflow:hidden;margin:10px 0 6px}
.meter span{display:block;height:100%;width:62%;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.row{display:flex;justify-content:space-between;font-size:14px;color:var(--mute)}
.pricing{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px}
.plan{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:22px}
.plan.featured{border-color:var(--gold)}
.price{font-size:32px;font-weight:700;margin:6px 0 10px}
.price small{font-size:14px;color:var(--mute);font-weight:400}
ul{padding-left:18px;margin:0;color:#c9cfdc}
li{margin-bottom:6px}
.rooms{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px}
.room{border:1px solid var(--line);border-radius:10px;padding:14px;background:var(--panel)}
.room b{color:var(--gold2)}
footer{border-top:1px solid var(--line);padding:28px 0;color:var(--mute);font-size:13px}
footer a{color:var(--mute)}
</style>
</head>
<body>
<header>
  <div class="wrap">
    <a class="brand" href="/" aria-label="BlackCrown Intelligence home">
      <svg width="34" height="28" viewBox="0 0 34 28" aria-hidden="true">
        <polygon points="2,8 9,18 17,4 25,18 32,8 29,24 5,24" fill="none" stroke="#d4a72c" stroke-width="2" stroke-linejoin="round"/>
        <circle cx="17" cy="4" r="2" fill="#f0cd6a"/>
        <circle cx="2" cy="8" r="2" fill="#f0cd6a"/>
        <circle cx="32" cy="8" r="2" fill="#f0cd6a"/>
      </svg>
      <span>BlackCrown Intelligence</span>
    </a>
    <nav class="nav">
      <a href="#ownership">Ownership</a>
      <a href="#pricing">Pricing</a>
      <a href="#rooms">Rooms</a>
      <a href="chat.html">Open Crown</a>
    </nav>
  </div>
</header>

<main>
  <div class="wrap">
    <div class="hero">
      <p class="eyebrow">Crown, for skeptics</p>
      <h1>Your context stays yours.</h1>
      <p class="lead">Crown is BlackCrown's private AI workspace. What you bring into it is never sold, never trained on, and never shared as training data. You do not have to take our word for the output. The free tier needs no card, so judge it yourself.</p>
      <a class="btn" href="chat.html">Try Crown free</a>
      <a class="btn ghost" href="#pricing">See the pricing</a>
    </div>
  </div>

  <section id="ownership">
    <div class="wrap">
      <h2>Ownership is the whole point</h2>
      <p>Most people who doubt AI tools have a fair question: where does my material go after I hit enter? Crown answers that question first and plainly.</p>
      <div class="grid">
        <div class="card"><h3>Never sold</h3><p>Your context is not a product. It is not sold, licensed, or packaged for anyone.</p></div>
        <div class="card"><h3>Never trained on</h3><p>Your chats are not used to train models. What you write stays in your workspace.</p></div>
        <div class="card"><h3>Nobody's training data</h3><p>Your conversations belong to you. They are not feedstock for anyone else's system.</p></div>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <h2>Judge the output, not the pitch</h2>
      <p>Skeptics should test before they trust. Here is what you can check in a few minutes with no card on file.</p>
      <div class="panel">
        <span class="tag">Illustration</span>
        <div class="row"><span>Room credit this cycle</span><span>Illustrative balance</span></div>
        <div class="meter" role="img" aria-label="Illustrative credit meter at 62 percent"><span></span></div>
        <div class="row"><span>Standard answers draw less credit</span><span>Deep-Logic draws more, by design</span></div>
        <p style="margin:14px 0 0;font-size:14px">The meter is a prepaid balance that moves live as you work. Nothing here is a real account.</p>
      </div>
      <div class="chips">
        <span class="chip">No card on free tier</span>
        <span class="chip">Live metering</span>
        <span class="chip">No surprise bills</span>
        <span class="chip">Four private rooms</span>
      </div>
    </div>
  </section>

  <section id="pricing">
    <div class="wrap">
      <h2>Flat pricing, no surprises</h2>
      <p>One monthly price, one clear balance. Deep-Logic uses more credit per answer on purpose, because heavy reasoning takes more compute, and you can see that draw as it happens.</p>
      <div class="pricing">
        <div class="plan">
          <h3>Free</h3>
          <div class="price">$0 <small>no card</small></div>
          <ul>
            <li>A free monthly allowance</li>
            <li>No card required to start</li>
            <li>All four rooms at a smaller allowance</li>
          </ul>
        </div>
        <div class="plan featured">
          <h3>Crowned</h3>
          <div class="price">$49.99 <small>per month</small></div>
          <ul>
            <li>$100 of room credit each month</li>
            <li>Metered live like a prepaid balance</li>
            <li>No surprise bills</li>
            <li>Top-ups from $4.99, never expire</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="rooms">
    <div class="wrap">
      <h2>Four private rooms</h2>
      <p>Each room is built for a different kind of thinking. Pick the one that fits the work.</p>
      <div class="rooms">
        <div class="room"><b>Unfiltered</b><p>Direct, unhedged answers for open questions.</p></div>
        <div class="room"><b>Deep-Logic</b><p>Slower, heavier reasoning. Draws more credit per answer because it thinks harder.</p></div>
        <div class="room"><b>Visual Analysis</b><p>Read and reason over images and charts.</p></div>
        <div class="room"><b>Creativity</b><p>Drafting, ideation, and structured creative work.</p></div>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <h2>Start with the free tier</h2>
      <p>No card, no sales call. Run your own tests, read the answers, and decide for yourself whether Crown earns a place in your workflow.</p>
      <a class="btn" href="chat.html">Open Crown</a>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <p>BlackCrown Intelligence is the AI division of BlackCrownVxJ LLC. Crown is a general purpose workspace. Nothing on this page is financial advice.</p>
    <p>Business contact: <a href="mailto:BlackCrownVxJ.LLC@outlook.com">BlackCrownVxJ.LLC@outlook.com</a></p>
  </div>
</footer>
</body>
</html>
