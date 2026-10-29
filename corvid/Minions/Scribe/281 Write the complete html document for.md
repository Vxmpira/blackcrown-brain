# Scribe: Write the complete html document for a new korvus guide

Date: 2026-10-29
Task: Write the COMPLETE html document for a new Korvus guide page: futures margin explained for beginners, doctype through closing html tag, no placeholders
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Futures Margin Explained for Beginners | Korvus</title>
<meta name="description">
<meta name="description" content="Futures margin explained in plain language: initial vs maintenance margin, why brokers raise requirements, what a margin call means, and day trade margin on ES and MES.">
<link rel="canonical" href="https://korvus.industries/p/futures-margin-explained">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#07060b;--panel:#0f0d16;--line:#2a2535;--ink:#ece8f2;--mute:#a79fb6;--pink:#ff5fa2;--violet:#8b5cf6}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.65}
body{min-height:100vh;position:relative;overflow-x:hidden;background:
radial-gradient(900px 500px at 15% -5%,rgba(255,95,162,.16),transparent 60%),
radial-gradient(800px 520px at 95% 15%,rgba(139,92,246,.14),transparent 62%),
radial-gradient(700px 480px at 50% 110%,rgba(255,95,162,.10),transparent 60%),
var(--bg)}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;
background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);
background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:0;
background:radial-gradient(ellipse at center,transparent 45%,rgba(0,0,0,.65) 100%)}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;gap:14px;padding:26px 0 18px;border-bottom:1px solid var(--line)}
header svg{width:44px;height:36px;flex:0 0 auto}
.brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px}
.brand span{color:var(--pink)}
.tag{margin-left:auto;color:var(--mute);font-size:13px}
main{padding:56px 0 40px}
.eyebrow{color:var(--pink);font-size:13px;letter-spacing:.14em;text-transform:uppercase;font-weight:600}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:12px 0 18px;font-weight:800}
h2{font-size:clamp(21px,3vw,28px);margin:44px 0 12px;font-weight:700}
h3{font-size:clamp(17px,2.4vw,20px);margin:22px 0 8px;font-weight:700;color:#fff}
.lede{font-size:clamp(17px,2.2vw,19px);color:var(--mute);max-width:66ch}
.prose{max-width:68ch}
.prose p{margin:0 0 14px;color:#d9d3e3}
.prose ul{margin:0 0 16px 20px;color:#d9d3e3}
.prose li{margin-bottom:6px}
strong{color:#fff}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0 8px}
.chip{border:1px solid var(--line);background:rgba(15,13,22,.8);border-radius:999px;padding:7px 14px;font-size:13px;color:var(--mute)}
.chip b{color:var(--pink);font-weight:600}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin:20px 0}
.card{background:linear-gradient(180deg,rgba(255,95,162,.06),rgba(15,13,22,.95));border:1px solid var(--line);border-radius:14px;padding:20px}
.card h3{margin-top:0}
.card p{color:#cfc8dc;font-size:15px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:22px;margin:28px 0;box-shadow:0 0 0 1px rgba(255,95,162,.06),0 20px 60px rgba(0,0,0,.45)}
.panel-head{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;margin-bottom:14px}
.panel-head h3{margin:0;font-size:17px}
.badge{font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:var(--violet);border:1px solid rgba(139,92,246,.45);border-radius:6px;padding:3px 8px}
table{width:100%;border-collapse:collapse;font-size:15px}
th,td{text-align:left;padding:11px 10px;border-bottom:1px solid var(--line)}
th{color:var(--mute);font-weight:600;font-size:13px;text-transform:uppercase;letter-spacing:.06em}
td{color:#e6e1ef}
td.num{color:var(--pink);font-variant-numeric:tabular-nums}
.bars{margin-top:18px;display:grid;gap:10px}
.bar-row{display:grid;grid-template-columns:150px 1fr;gap:12px;align-items:center;font-size:14px;color:var(--mute)}
.bar{height:14px;border-radius:7px;background:rgba(255,255,255,.05);overflow:hidden}
.bar i{display:block;height:100%;background:linear-gradient(90deg,var(--violet),var(--pink));border-radius:7px}
.note{font-size:13px;color:var(--mute);margin-top:14px}
.callout{border-left:3px solid var(--pink);background:rgba(255,95,162,.06);padding:16px 18px;border-radius:0 12px 12px 0;margin:24px 0;max-width:68ch;color:#e6e1ef}
.cta{margin:52px 0 10px;background:linear-gradient(135deg,rgba(255,95,162,.14),rgba(139,92,246,.12));border:1px solid rgba(255,95,162,.35);border-radius:18px;padding:30px;text-align:left}
.cta h2{margin-top:0}
.btn{display:inline-block;margin-top:8px;background:var(--pink);color:#140a12;font-weight:700;text-decoration:none;padding:13px 22px;border-radius:10px}
.btn:hover{filter:brightness(1.08)}
.fine{font-size:12px;color:#7f7790;margin-top:18px;max-width:72ch}
footer{position:relative;z-index:1;border-top:1px solid var(--line);padding:22px 0 40px;color:var(--mute);font-size:13px}
footer a{color:var(--pink);text-decoration:none}
@media (max-width:700px){
  .grid{grid-template-columns:1fr}
  .tag{display:none}
  .bar-row{grid-template-columns:1fr;gap:6px}
  th,td{padding:9px 6px;font-size:14px}
  .panel{padding:16px}
  .cta{padding:22px}
}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <svg viewBox="0 0 44 36" role="img" aria-label="Korvus crown mark">
      <polygon points="2,30 6,8 16,20 22,4 28,20 38,8 42,30" fill="#ff5fa2"/>
      <rect x="2" y="30" width="40" height="4" rx="1" fill="#ff8fbf"/>
    </svg>
    <div class="brand">Kor<span>vus</span></div>
    <div class="tag">Market intelligence for index futures</div>
  </header>

  <main>
    <div class="eyebrow">Beginner guide</div>
    <h1>Futures margin, explained without the jargon</h1>
    <p class="lede">Margin is the most misunderstood word in futures. It is not a loan and it is not a fee. This guide walks through what margin is, the two numbers you will see, why brokers change them, and what a margin call actually means.</p>

    <div class="chips">
      <span class="chip"><b>Initial</b> margin</span>
      <span class="chip"><b>Maintenance</b> margin</span>
      <span class="chip">Margin <b>calls</b></span>
      <span class="chip">Day trade margin on <b>ES</b> and <b>MES</b></span>
    </div>

    <h2>What margin is</h2>
    <div class="prose">
      <p>When you trade a futures contract, you do not pay the full value of what you control. You post a performance bond, a good faith deposit that shows you can cover the day to day swings of the position. Your broker holds that deposit against your open trades.</p>
      <p>Think of it as a security deposit, not a down payment. The deposit comes back to you as the trade closes, adjusted by whatever profit or loss the trade produced.</p>
    </div>

    <h2>Initial margin and maintenance margin</h2>
    <div class="prose">
      <p>You will usually see two figures for each contract:</p>
      <ul>
        <li><strong>Initial margin</strong> is the amount you need on deposit to open a new position.</li>
        <li><strong>Maintenance margin</strong> is the minimum you must keep in the account while the position stays open. It is lower than initial margin.</li>
      </ul>
      <p>The gap between the two is a buffer. A position can drift against you and still stay open, as long as your account value stays above maintenance. Once it falls below, the broker expects you to restore the account.</p>
    </div>

    <div class="grid">
      <div class="card">
        <h3>Initial margin</h3>
        <p>The cash required to enter. Checked when you place the order.</p>
      </div>
      <div class="card">
        <h3>Maintenance margin</h3>
        <p>The floor your account must hold while you stay in the trade. Checked continuously.</p>
      </div>
    </div>

    <div class="panel" aria-label="Illustrative margin layout for one contract">
      <div class="panel-head">
        <h3>How the two numbers sit in one account</h3>
        <span class="badge">Illustration</span>
      </div>
      <div class="bars">
        <div class="bar-row"><span>Account balance</span><div class="bar"><i style="width:100%"></i></div></div>
        <div class="bar-row"><span>Initial requirement</span><div class="bar"><i style="width:72%"></i></div></div>
        <div class="bar-row"><span>Maintenance floor</span><div class="bar"><i style="width:60%"></i></div></div>
        <div class="bar-row"><span>Open loss zone</span><div class="bar"><i style="width:28%;background:linear-gradient(90deg,#6b5b86,#c44a85)"></i></div></div>
      </div>
      <p class="note">Illustration only. Bar lengths are not to scale with any real broker or contract. Your broker publishes the actual figures.</p>
    </div>

    <h2>Why brokers ask for more</h2>
    <div class="prose">
      <p>Margin requirements are not fixed forever. Brokers and exchanges raise them when risk rises. The common triggers are:</p>
      <ul>
        <li><strong>Volatility.</strong> When prices move more sharply, the same contract can swing further in a day, so the deposit goes up.</li>
        <li><strong>Scheduled events.</strong> Major data releases and central bank days can prompt temporary increases.</li>
        <li><strong>Position size.</strong> More contracts means more exposure, which means more required deposit.</li>
        <li><strong>Broker policy.</strong> Each broker sets its own floor on top of exchange minimums, and can change it with little notice.</li>
      </ul>
      <p>None of this is a signal about direction. It is a statement about how much money the system wants held against open risk.</p>
    </div>

    <h2>What a margin call means</h2>
    <div class="prose">
      <p>A margin call happens when your account value drops below maintenance margin. The broker will ask you to bring the account back up to the required level. In practice that means depositing more funds or reducing the position.</p>
      <p>If the account is not restored in time, the broker can close positions for you without asking first. This is called liquidation, and it can lock in losses at prices you did not choose. Read your broker's margin agreement before you trade, so you know its timing and its rules.</p>
    </div>

    <div class="callout">
      The practical rule for a beginner: size positions so that a normal move against you does not come close to the maintenance floor. Margin is there to protect the system. You are the one who has to live inside it.
    </div>

    <h2>Day trade margin on ES and MES</h2>
    <div class="prose">
      <p>ES is the E-mini S&amp;P 500 futures contract. MES is the Micro E-mini S&amp;P 500, the same underlying index at one tenth the size. Each full point of ES moves the contract value by 50 dollars. Each full point of MES moves it by 5 dollars.</p>
      <p>Many brokers offer a lower day trade margin for positions opened and closed within the same session. That rate usually applies only during set hours, and the broker typically raises it to the overnight rate close to the session end. If a position is still open when that window ends, the higher requirement applies. Confirm the exact cutoff times with your broker, because they differ.</p>
    </div>

    <div class="panel" aria-label="Illustrative size comparison between ES and MES">
      <div class="panel-head">
        <h3>ES vs MES, same index, different size</h3>
        <span class="badge">Illustration</span>
      </div>
      <table>
        <thead>
          <tr><th>Contract</th><th>Value per full point</th><th>Notional at 5,000 index</th></tr>
        </thead>
        <tbody>
          <tr><td>ES</td><td class="num">50 dollars</td><td class="num">250,000 dollars</td></tr>
          <tr><td>MES</td><td class="num">5 dollars</td><td class="num">25,000 dollars</td></tr>
        </tbody>
      </table>
      <p class="note">Illustration only. Index level is a round example, not a forecast. Actual margin for either contract is set by your broker and changes over time, so check the current figure before you size a trade.</p>
    </div>

    <h2>A short checklist before you trade</h2>
    <div class="prose">
      <ul>
        <li>Find your broker's current initial and maintenance figures for the contract you plan to trade.</li>
        <li>Know the cutoff time for day trade margin and what happens if a position is still open after it.</li>
        <li>Work out how far the market can move against you before your account touches maintenance.</li>
        <li>Read how your broker handles margin calls and liquidation.</li>
        <li>Start with fewer contracts than you think you can afford.</li>
      </ul>
    </div>

    <section class="cta">
      <div class="eyebrow">Free to start</div>
      <h2>Watch the market while you learn the mechanics</h2>
      <p class="prose">Korvus Observer is the free tier of the Korvus market intelligence terminal for index futures traders. Create an account to follow scored market news and the daily economic agenda, with no card required.</p>
      <a class="btn" href="https://korvus.industries/signup">Create your free Observer account</a>
    </section>

    <p class="fine">Educational content only. Nothing on this page is financial advice, a recommendation to buy or sell any contract, or a promise of any result. Margin figures, contract specifications and broker rules change; verify them with your broker and the exchange before trading. Futures trading involves substantial risk, and you can lose more than you deposit.</p>
  </main>
</div>

<footer>
  <div class="wrap">
    Korvus, a BlackCrownVxJ LLC product. <a href="https://korvus.industries/legal">Legal</a> · <a href="https://korvus.industries/">Home</a>
  </div>
</footer>
</body>
</html>
