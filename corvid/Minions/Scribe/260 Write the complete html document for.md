# Scribe: Write the complete html document for a new korvus page

Date: 2026-10-29
Task: Write the COMPLETE html document for a new Korvus page, korvus:pages/futures-news-terminal.html, serving at korvus.industries/p/futures-news-terminal, targeting
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Futures News Terminal for Index Traders | Korvus</title>
<meta name="description" content="A futures news terminal that scores headlines and reads the board, SMT and session context into one directional read. Built for index traders. Not advice.">
<link rel="canonical" href="https://korvus.industries/p/futures-news-terminal">
<link rel="icon" href="/favicon.ico">
<meta property="og:title" content="Futures News Terminal for Index Traders | Korvus">
<meta property="og:description" content="Scored news, futures board, cross index SMT and session context in one terminal. Your edge while the world sleeps. Not financial advice.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://korvus.industries/p/futures-news-terminal">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07070a;color:#e8e6ee;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;font-size:16px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:960px;margin:0 auto;padding:0 20px}
header{border-bottom:1px solid #1d1b26;padding:18px 0;background:#0a0a0f}
.brand{display:flex;align-items:center;gap:12px;color:#fff;font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:15px}
.brand svg{width:36px;height:33px}
.brand a{color:#fff}
nav{margin-left:auto;display:flex;gap:18px;font-size:14px}
nav a{color:#b9b5c6}
.hero{padding:72px 0 56px}
.kicker{color:#ff2d8f;font-size:13px;letter-spacing:.14em;text-transform:uppercase;margin-bottom:14px}
h1{font-size:40px;line-height:1.15;color:#fff;margin-bottom:18px;font-weight:750}
h2{font-size:26px;color:#fff;margin:0 0 14px}
h3{font-size:18px;color:#fff;margin:0 0 8px}
p{margin-bottom:14px;color:#c9c6d4}
section{padding:48px 0;border-top:1px solid #1d1b26}
.lede{font-size:19px;color:#dedbe8;max-width:720px}
.btns{display:flex;flex-wrap:wrap;gap:12px;margin-top:24px}
.btn{display:inline-block;padding:13px 22px;border-radius:8px;font-weight:600;font-size:15px;border:1px solid #ff2d8f}
.btn.solid{background:#ff2d8f;color:#07070a}
.btn.ghost{color:#ff2d8f;background:transparent}
.btn:hover{text-decoration:none;opacity:.9}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px;margin-top:20px}
.card{background:#0e0e15;border:1px solid #1d1b26;border-radius:10px;padding:20px}
.card p{font-size:14px;margin:0}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.chip{border:1px solid #2b2838;border-radius:999px;padding:5px 12px;font-size:13px;color:#cfcbe0;background:#0e0e15}
.panel{background:#0c0c12;border:1px solid #2a2635;border-radius:12px;padding:20px;margin-top:24px}
.panel-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:14px;font-size:13px;color:#9a96ab}
.tag{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:4px;padding:2px 8px;font-size:11px;letter-spacing:.1em;text-transform:uppercase}
.row{display:grid;grid-template-columns:1fr 70px 80px 90px;gap:10px;align-items:center;padding:12px 0;border-top:1px solid #1d1b26;font-size:14px}
.row:first-of-type{border-top:0}
.hl{color:#f1eff7}
.score{font-weight:700;color:#fff}
.bar{height:6px;background:#1d1b26;border-radius:3px;margin-top:6px;overflow:hidden}
.bar span{display:block;height:100%;background:#ff2d8f}
.up{color:#7de2b0}
.down{color:#ff6b8a}
.neutral{color:#b9b5c6}
.head-row{font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:#7b778c}
.steps{counter-reset:s;list-style:none}
.steps li{counter-increment:s;padding:14px 0 14px 46px;position:relative;border-top:1px solid #1d1b26;color:#c9c6d4}
.steps li:before{content:counter(s);position:absolute;left:0;top:14px;width:30px;height:30px;border:1px solid #ff2d8f;border-radius:50%;text-align:center;line-height:28px;color:#ff2d8f;font-weight:700}
.steps strong{color:#fff}
.disc{font-size:13px;color:#8f8ba0;border:1px solid #2a2635;border-radius:10px;padding:18px;background:#0a0a0f}
footer{border-top:1px solid #1d1b26;padding:28px 0;font-size:13px;color:#7b778c}
footer a{color:#b9b5c6}
@media(max-width:640px){h1{font-size:30px}nav{display:none}.row{grid-template-columns:1fr 56px 70px;}.row>div:nth-child(4){display:none}}
</style>
</head>
<body>
<header>
  <div class="wrap brand">
    <svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2.4" stroke-linejoin="round" stroke-linecap="round"><path d="M4 24 L4 9 L12 16 L18 5 L24 16 L32 9 L32 24 Z"/><path d="M8 28 L28 28"/></svg>
    <a href="/">Korvus</a>
    <nav>
      <a href="/">Home</a>
      <a href="/lodestone">LodeStone</a>
      <a href="/signup">Sign up</a>
    </nav>
  </div>
</header>

<main>
<div class="wrap hero">
  <div class="kicker">Futures news terminal</div>
  <h1>One terminal for the wire, the board and the session.</h1>
  <p class="lede">Korvus is a futures news terminal for index traders. It scores incoming headlines, reads the futures board, checks cross index SMT divergence and frames the current session. Then it puts all of it into one directional read you can check against your own chart.</p>
  <div class="btns">
    <a class="btn solid" href="/signup">Start free with Observer</a>
    <a class="btn ghost" href="/lodestone">See LodeStone</a>
  </div>
  <div class="chips">
    <span class="chip">Scored news wire</span>
    <span class="chip">Futures board</span>
    <span class="chip">Cross index SMT</span>
    <span class="chip">Session context</span>
    <span class="chip">24/7 watch</span>
  </div>
</div>

<section>
<div class="wrap">
  <h2>What a futures news terminal does</h2>
  <p>A futures news terminal is a single screen that watches the news flow for the markets you trade and turns it into something you can act on. Not a feed. A filter with structure. It tells you what hit, how big it is, which way it leans for the instrument in front of you, and how sure the system is about that read.</p>
  <p>For index futures, the useful version also knows the board. It knows where ES, NQ, YM and RTY are trading against each other, whether they agree, and what session you are in. A headline at the open means something different than the same headline at 3 a.m.</p>
</div>
</section>

<section>
<div class="wrap">
  <h2>Why raw headlines fail beginners</h2>
  <p>Most new traders do not have a news problem. They have a tab problem. Twelve sites, a chat room, a push alert, and a chart. Every source says it is urgent. Nothing says how urgent, or whether it matters for the contract on screen.</p>
  <div class="grid">
    <div class="card"><h3>Everything looks urgent</h3><p>Without a score, a minor revision and a rate shock sit in the same list at the same size.</p></div>
    <div class="card"><h3>No direction</h3><p>A headline does not say which way the index is pressed. Beginners guess, then argue with themselves.</p></div>
    <div class="card"><h3>No context</h3><p>The same print can mean nothing in the middle of the day and a lot at the open. Raw feeds do not know the clock.</p></div>
    <div class="card"><h3>No check</h3><p>Nothing asks whether the other index agrees. Divergence is where many false reads start.</p></div>
  </div>
</div>
</section>

<section>
<div class="wrap">
  <h2>How Korvus builds one read</h2>
  <p>Korvus runs four inputs through one pipeline and shows the result on one screen. Each input is visible, so you can see the reasoning, not just the verdict.</p>
  <ol class="steps">
    <li><strong>Scored wire.</strong> Each headline gets an impact score, a direction for the affected index futures, and a confidence level. The score is a read of the event, not a promise about price.</li>
    <li><strong>Futures board.</strong> Live levels for the main index contracts, so the news sits next to where the market already is.</li>
    <li><strong>Cross index SMT divergence.</strong> When one index makes a new high or low and another fails to confirm, the terminal flags it. Divergence is a structure to study, not a signal to trade blind.</li>
    <li><strong>Session context.</strong> Which session is open, what time it is in the market timezone, and how the current hour usually behaves. Context changes the weight of every other input.</li>
  </ol>
  <p>The output is a directional read: what the wire says, what the board confirms, whether the other index agrees, and how the session affects it. You decide what to do with it.</p>
</div>
</section>

<section>
<div class="wrap">
  <h2>What the wire looks like</h2>
  <p>This is a layout sample. The values are made up to show how the fields sit together.</p>
  <div class="panel" role="img" aria-label="Illustration of a scored news wire with impact, direction and confidence">
    <div class="panel-head"><span>Scored wire, index futures</span><span class="tag">Illustration</span></div>
    <div class="row head-row"><div>Headline</div><div>Impact</div><div>Direction</div><div>Confidence</div></div>
    <div class="row">
      <div class="hl">Services activity print lands above the survey median</div>
      <div><span class="score">7.4</span><div class="bar"><span style="width:74%"></span></div></div>
      <div class="up">Up</div>
      <div>High</div>
    </div>
    <div class="row">
      <div class="hl">Central bank speaker repeats prior language, no new guidance</div>
      <div><span class="score">3.1</span><div class="bar"><span style="width:31%"></span></div></div>
      <div class="neutral">Flat</div>
      <div>Medium</div>
    </div>
    <div class="row">
      <div class="hl">Energy inventory draw larger than expected, mixed read for risk</div>
      <div><span class="score">5.2</span><div class="bar"><span style="width:52%"></span></div></div>
      <div class="down">Down</div>
      <div>Low</div>
    </div>
    <div class="row">
      <div class="hl">Index divergence flag: RTY not confirming ES high</div>
      <div><span class="score">6.0</span><div class="bar"><span style="width:60%"></span></div></div>
      <div class="neutral">Watch</div>
      <div>Medium</div>
    </div>
  </div>
</div>
</section>

<section>
<div class="wrap">
  <h2>Start with Observer, move up when you need the full terminal</h2>
  <p>Observer is free. It gives you the core feed so you can judge the output yourself before you pay anything.</p>
  <p>Operator is 9.99 a month or 79.99 a year. It opens the full terminal, including the LodeStone TradingView indicator at no extra cost. Annual is the better value if you plan to use it through the year.</p>
  <p>LodeStone is also sold on its own. See <a href="/lodestone">the LodeStone page</a> for its features and how it sits on your chart.</p>
  <div class="btns">
    <a class="btn solid" href="/signup">Create a free account</a>
    <a class="btn ghost" href="/">Back to Korvus</a>
  </div>
</div>
</section>

<section>
<div class="wrap">
  <h2>Questions traders ask</h2>
  <h3>Is this a signal service?</h3>
  <p>No. Korvus organizes news and market structure so you can read it faster. It does not tell you what to buy or sell.</p>
  <h3>Does it work outside the US session?</h3>
  <p>The wire runs around the clock. Session context changes how each read should be weighted, so check which session is active before you apply any read.</p>
  <h3>Can I see it before I pay?</h3>
  <p>Yes. Observer is free and needs no card. Test the output against your own charts for as long as you like.</p>
</div>
</section>

<section>
<div class="wrap">
  <div class="disc">
    <p><strong>Not financial advice.</strong> Korvus is market intelligence and education software. Scores, directions, confidence levels, divergence flags and session notes are analysis tools, not recommendations to buy, sell or hold any instrument. Futures carry substantial risk and can lose more than you deposit. Past readings do not guarantee future results. No profit is promised or implied. Trade only with capital you can afford to lose.</p>
  </div>
</div>
</section>
</main>

<footer>
  <div class="wrap">
    <p>Korvus, a product of BlackCrownVxJ LLC. <a href="/">Home</a> &middot; <a href="/lodestone">LodeStone</a> &middot; <a href="/signup">Sign up</a> &middot; <a href="/legal">Legal</a></p>
    <p>Business contact: BlackCrownVxJ.LLC@outlook.com</p>
  </div>
</footer>
</body>
</html>
