# Scribe: Rewrite the complete killzones html document with exactly one meta

Date: 2026-10-28
Task: Rewrite the COMPLETE killzones html document with exactly one meta description tag, no duplicates anywhere in head, as your report
For [[Corvid]].

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ICT Killzones for Index Futures | Korvus</title>
<meta name="description" content="How ICT killzones fit into index futures sessions, with Korvus session and macro context. Education only, not financial advice.">
<link rel="canonical" href="https://korvus.industries/p/killzones">
<style>
:root{--bg:#07080c;--panel:#0e1119;--line:#1d2332;--gold:#c9a64b;--text:#e6e8ee;--muted:#8a93a6;--teal:#3fb8a8;--red:#c4574f}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:Georgia,"Times New Roman",serif;line-height:1.6}
header{display:flex;align-items:center;gap:12px;padding:20px 24px;border-bottom:1px solid var(--line)}
header span{font-family:Arial,Helvetica,sans-serif;letter-spacing:.14em;text-transform:uppercase;font-size:13px;color:var(--gold)}
main{max-width:860px;margin:0 auto;padding:32px 24px 56px}
h1{font-size:34px;line-height:1.2;margin:0 0 12px;font-weight:700}
h2{font-size:22px;margin:36px 0 10px;color:var(--gold)}
p{margin:0 0 14px;color:var(--text)}
.lede{color:var(--muted);font-size:18px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:20px;margin:20px 0}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{font-family:Arial,Helvetica,sans-serif;font-size:13px;border:1px solid var(--line);border-radius:999px;padding:6px 12px;color:var(--muted)}
.tl{position:relative;height:120px;background:#0a0d14;border:1px solid var(--line);border-radius:8px;margin:12px 0 4px}
.tl .b{position:absolute;top:30px;height:34px;border-radius:4px;font-family:Arial,Helvetica,sans-serif;font-size:12px;display:flex;align-items:center;padding:0 8px;color:#07080c;font-weight:700}
.axis{display:flex;justify-content:space-between;font-family:Arial,Helvetica,sans-serif;font-size:11px;color:var(--muted);margin-top:6px}
.tag{font-family:Arial,Helvetica,sans-serif;font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:var(--muted)}
table{width:100%;border-collapse:collapse;font-size:15px;margin:12px 0}
th,td{text-align:left;padding:10px 8px;border-bottom:1px solid var(--line)}
th{color:var(--gold);font-family:Arial,Helvetica,sans-serif;font-size:13px;letter-spacing:.06em;text-transform:uppercase}
.disclaimer{font-size:14px;color:var(--muted);border-left:3px solid var(--red);padding:12px 16px;background:var(--panel);border-radius:6px}
footer{border-top:1px solid var(--line);padding:20px 24px;color:var(--muted);font-size:13px;text-align:center;font-family:Arial,Helvetica,sans-serif}
</style>
</head>
<body>
<header>
<svg width="34" height="28" viewBox="0 0 34 28" aria-hidden="true">
<polygon points="3,22 6,6 12,14 17,3 22,14 28,6 31,22" fill="#c9a64b"/>
<rect x="3" y="22" width="28" height="4" fill="#c9a64b"/>
</svg>
<span>Korvus Education</span>
</header>
<main>
<h1>ICT Killzones for Index Futures</h1>
<p class="lede">Killzones are time windows that ICT-style traders watch for higher activity in index futures. This page explains how they sit inside the daily session, and how Korvus session and macro context frames them. It is a map of the clock, not a signal.</p>

<div class="chips">
<span class="chip">Session timing</span>
<span class="chip">Macro calendar</span>
<span class="chip">Liquidity context</span>
<span class="chip">Education only</span>
</div>

<h2>What a killzone is</h2>
<p>A killzone is a recurring window, usually tied to the opening of a major financial center. The idea is simple: volume and volatility often cluster around those opens, so price action inside them can look different from the quiet hours between them. Different traders define the windows differently, and the times below are the commonly cited ones, always in New York time.</p>

<h2>The daily map</h2>
<div class="card">
<p class="tag">Illustration: commonly cited windows, New York time</p>
<div class="tl" role="img" aria-label="Illustrative timeline of daily session windows">
<div class="b" style="left:0%;width:20%;background:#5b6b8c">Asia</div>
<div class="b" style="left:25%;width:14%;background:var(--teal)">London</div>
<div class="b" style="left:52%;width:14%;background:var(--gold)">NY AM</div>
<div class="b" style="left:70%;width:12%;background:#8e6fb8">NY PM</div>
</div>
<div class="axis"><span>20:00</span><span>00:00</span><span>04:00</span><span>08:00</span><span>12:00</span><span>16:00</span><span>20:00</span></div>
</div>

<table>
<thead><tr><th>Window</th><th>Commonly cited time (NY)</th><th>What traders watch</th></tr></thead>
<tbody>
<tr><td>Asia</td><td>20:00 to 00:00</td><td>Range formation before Europe</td></tr>
<tr><td>London</td><td>02:00 to 05:00</td><td>Early direction and sweeps of Asia highs or lows</td></tr>
<tr><td>NY AM</td><td>08:30 to 11:00</td><td>Data releases and the main US move</td></tr>
<tr><td>NY PM</td><td>13:30 to 16:00</td><td>Continuation or reversal into the close</td></tr>
</tbody>
</table>

<h2>Session and macro context</h2>
<p>A killzone is only a clock. The same window can be quiet or violent depending on what is on the economic calendar. Korvus tracks scored headlines and the USD agenda, so a London or NY AM window can be read against the events that are actually scheduled, not just the hour on the wall. A killzone with a major release inside it is a different environment from one with an empty calendar.</p>

<h2>How to use this page</h2>
<p>Use killzones as a filter for attention and for journaling. Note which window your own setup appeared in, what the calendar looked like, and whether the outcome matched your plan. That record will tell you more about your process than any table of times.</p>

<div class="card disclaimer">
<p>Not financial advice. This page is education about market structure and session timing. It does not recommend any trade, entry, exit, or position, and it makes no promise of profit. Index futures carry substantial risk of loss. Past behavior of any window does not guarantee future results. Trade only what you understand, with capital you can afford to lose.</p>
</div>
</main>
<footer>Korvus, a BlackCrownVxJ LLC product. Your edge while the world sleeps.</footer>
</body>
</html>
