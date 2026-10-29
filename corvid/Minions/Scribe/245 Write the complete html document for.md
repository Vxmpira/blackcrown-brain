# Scribe: Write the complete html document for a new page korvus

Date: 2026-10-28
Task: Write the COMPLETE html document for a new page, korvus:pages/smt-divergence.html, serving at korvus.industries/p/smt-divergence
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>SMT Divergence for Index Futures: A Beginner Guide</title>
<meta name="description">
<link rel="canonical" href="https://korvus.industries/p/smt-divergence">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0a0c;color:#e6e6ec;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.65;font-size:17px}
a{color:#ff2d8f;text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:760px;margin:0 auto;padding:0 22px}
header{border-bottom:1px solid #1f1f26;padding:18px 0}
.brand{display:flex;align-items:center;gap:12px;font-weight:600;letter-spacing:.04em;color:#f4f4f8}
.brand svg{width:36px;height:33px}
.brand span{font-size:16px}
nav{margin-left:auto;font-size:14px}
nav a{color:#9a9aa6;margin-left:18px}
h1{font-size:34px;line-height:1.2;margin:48px 0 14px;color:#fff;font-weight:700}
h2{font-size:22px;margin:44px 0 12px;color:#fff;font-weight:650}
p{margin:0 0 16px;color:#c9c9d3}
.kicker{font-size:13px;letter-spacing:.14em;text-transform:uppercase;color:#ff2d8f;margin-bottom:10px}
ul,ol{margin:0 0 18px 22px;color:#c9c9d3}
li{margin-bottom:8px}
.panel{background:#121217;border:1px solid #23232c;border-radius:10px;padding:22px;margin:26px 0}
.panel .tag{font-size:12px;letter-spacing:.12em;text-transform:uppercase;color:#7d7d8a;margin-bottom:12px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.chip{border:1px solid #2c2c36;border-radius:999px;padding:5px 12px;font-size:13px;color:#b8b8c4}
.chip.hot{border-color:#ff2d8f;color:#ff2d8f}
svg.fig{width:100%;height:auto;display:block}
.cap{font-size:13px;color:#7d7d8a;margin-top:10px}
.note{border-left:3px solid #ff2d8f;padding:10px 16px;background:#121217;color:#b8b8c4;margin:24px 0}
.close{margin-top:52px;padding:26px;border:1px solid #23232c;border-radius:10px;background:#101015}
.btn{display:inline-block;margin-top:8px;padding:11px 20px;border:1px solid #ff2d8f;border-radius:8px;color:#ff2d8f;font-weight:600}
.btn:hover{background:#ff2d8f;color:#0a0a0c;text-decoration:none}
footer{border-top:1px solid #1f1f26;margin-top:56px;padding:26px 0 40px;font-size:14px;color:#7d7d8a}
footer p{font-size:14px;color:#7d7d8a}
</style>
</head>
<body>
<header>
<div class="wrap brand">
<svg viewBox="0 0 36 33" fill="none" stroke="#ff2d8f" stroke-width="2" stroke-linejoin="round" aria-hidden="true">
<polyline points="4,28 4,12 12,20 18,6 24,20 32,12 32,28 4,28"/>
<line x1="4" y1="32" x2="32" y2="32"/>
</svg>
<span>Korvus</span>
<nav>
<a href="/p/liquidity-sweeps">Liquidity Sweeps</a>
<a href="/signup">Sign up</a>
</nav>
</div>
</header>

<main class="wrap">
<div class="kicker">Beginner guide</div>
<h1>SMT divergence for index futures</h1>
<p>Smart money technique, or SMT, is a read on relative strength between correlated markets. For index futures, it is one of the simplest ways to see when the market is failing to agree with itself. This guide explains what it is, how it looks on ES and NQ, and how to review it after the fact.</p>

<div class="note">Education only. Nothing here is trading advice, a signal, or a promise of any result. Markets carry real risk.</div>

<h2>What SMT divergence is</h2>
<p>SMT divergence happens when two correlated index futures do not confirm each other at a key level.</p>
<p>The simple version: one index makes a new high or a new low. The correlated index does not.</p>
<p>The idea rests on correlation. ES (S&amp;P 500) and NQ (Nasdaq 100) usually move together. When they stop moving together at a level that matters, the gap is information. It tells you the move may lack broad support.</p>
<p>SMT is a observation, not a prediction. It describes what happened. It does not tell you what happens next.</p>

<h2>The basic structure</h2>
<ul>
<li>Both markets approach a prior high or low.</li>
<li>One market takes the level and prints a new extreme.</li>
<li>The other market stops short, or prints a lower high or higher low.</li>
<li>That disagreement is the divergence.</li>
</ul>

<div class="panel">
<div class="tag">Illustration</div>
<svg class="fig" viewBox="0 0 560 220" role="img" aria-label="Illustrative ES and NQ divergence, not real data">
<rect x="0" y="0" width="560" height="220" fill="#0d0d12"/>
<line x1="20" y1="60" x2="540" y2="60" stroke="#2a2a34" stroke-dasharray="4 4"/>
<text x="24" y="54" fill="#7d7d8a" font-size="12">Prior high</text>
<polyline points="30,170 90,130 140,150 200,95 260,120 320,62 380,88 440,58 500,70" fill="none" stroke="#8fa7ff" stroke-width="2.5"/>
<polyline points="30,160 90,122 140,140 200,88 260,112 320,78 380,96 440,80 500,104" fill="none" stroke="#ff2d8f" stroke-width="2.5"/>
<circle cx="440" cy="58" r="4" fill="#8fa7ff"/>
<circle cx="440" cy="80" r="4" fill="#ff2d8f"/>
<text x="452" y="52" fill="#8fa7ff" font-size="12">ES new high</text>
<text x="452" y="96" fill="#ff2d8f" font-size="12">NQ fails to confirm</text>
</svg>
<div class="chips">
<span class="chip">ES: blue</span>
<span class="chip hot">NQ: pink</span>
<span class="chip">Bearish SMT, illustrative</span>
</div>
<div class="cap">Illustration only. Not real market data. Shapes show the structure, not a price path.</div>
</div>

<h2>ES vs NQ, a worked example</h2>
<p>Here is the structure in plain words. Numbers are placeholders, not a recorded session.</p>
<ol>
<li>ES and NQ both rally into the afternoon. Each approaches its morning high.</li>
<li>ES trades above the morning high. It prints a new session high.</li>
<li>NQ stalls below its morning high. It prints a lower high instead.</li>
<li>The two no longer agree on the high. That is the SMT divergence.</li>
</ol>
<p>The mirror case works for lows. ES breaks a prior low. NQ holds above its prior low. The disagreement shows on the downside.</p>
<p>Notice what the example does not say. It does not say price will reverse. Divergence can resolve in several ways. Price can continue. It can chop. It can reconcile over hours. The read stays descriptive.</p>

<h2>How to review SMT after the fact</h2>
<p>Review is where this technique earns its keep. Live reads are hard. Reviewed reads teach you how the pattern behaves.</p>
<ul>
<li>Mark the level both markets were approaching. Use the same timeframe for both.</li>
<li>Note which market made the new extreme, and which failed to confirm.</li>
<li>Write down the exact time of the divergence on both charts.</li>
<li>Record what happened over the next session, in plain terms. Do not score it as a win or loss.</li>
<li>Track how often divergences at the same type of level resolved one way or another.</li>
</ul>
<p>Keep the log honest. Include divergences that failed. A log of only good examples teaches you nothing true.</p>

<h2>Common mistakes beginners make</h2>
<ul>
<li>Treating every small gap as a signal. Not every disagreement matters.</li>
<li>Ignoring the level. SMT at a random price means little.</li>
<li>Comparing mismatched timeframes or sessions.</li>
<li>Reading divergence as a promise of reversal.</li>
</ul>

<h2>Where this fits</h2>
<p>SMT is one lens among many. It pairs well with liquidity concepts, such as sweeps of prior highs and lows. For that companion read, see <a href="/p/liquidity-sweeps">Liquidity Sweeps</a>.</p>

<section class="close">
<div class="kicker">On Korvus</div>
<h2 style="margin-top:6px">Cross index SMT, tracked</h2>
<p>Korvus tracks cross index SMT on its terminal. Reads are logged as they form, so you can review the pattern against the session that followed, without rebuilding the chart by hand.</p>
<p>Korvus is market intelligence and education. It does not give trading advice, and it does not promise outcomes.</p>
<a class="btn" href="https://korvus.industries/signup">Sign up at korvus.industries</a>
</section>
</main>

<footer>
<div class="wrap">
<p>Education only. Not financial advice. Past reads do not predict future results. Trading index futures involves substantial risk of loss.</p>
<p style="margin-top:10px"><a href="/p/liquidity-sweeps">Back to Liquidity Sweeps</a> &middot; <a href="/">Korvus home</a> &middot; <a href="/legal">Legal</a></p>
</div>
</footer>
</body>
</html>
