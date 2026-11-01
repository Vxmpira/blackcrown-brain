# Copy: Write the watcher data panel section then closing body and

Date: 2026-11-01
Task: Write the Watcher data panel section, then closing body and html tags.
For [[Herald]].

<section class="watcher-panel" aria-labelledby="watcher-title">
  <style>
    .watcher-panel{max-width:1060px;margin:48px auto;padding:28px 24px;border:1px solid #2a2440;border-radius:14px;background:radial-gradient(circle at 85% 0%,rgba(139,92,246,.18),transparent 55%),radial-gradient(circle at 0% 100%,rgba(212,175,55,.10),transparent 50%),#0d0b14;color:#e8e4f3;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
    .watcher-top{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:12px;margin-bottom:8px}
    .watcher-tag{display:inline-block;font-size:12px;letter-spacing:.08em;text-transform:uppercase;color:#d4af37;border:1px solid rgba(212,175,55,.45);padding:4px 10px;border-radius:999px}
    .watcher-panel h2{font-size:clamp(1.3rem,2.6vw,1.8rem);margin:6px 0 8px;color:#fff}
    .watcher-panel p.lead{margin:0 0 20px;max-width:68ch;color:#b9b3cc;line-height:1.6}
    .tablewrap{width:100%;overflow-x:auto;border:1px solid #2a2440;border-radius:10px;background:#100d1a}
    .watcher-table{width:100%;min-width:640px;border-collapse:collapse;font-size:14px}
    .watcher-table th,.watcher-table td{padding:12px 14px;text-align:left;border-bottom:1px solid #221e33;vertical-align:middle}
    .watcher-table th{font-size:11px;letter-spacing:.08em;text-transform:uppercase;color:#8c85a3;background:#14101f;font-weight:600}
    .watcher-table td.time{font-variant-numeric:tabular-nums;color:#a9a3bf;white-space:nowrap}
    .watcher-table tr:last-child td{border-bottom:none}
    .chip{display:inline-block;font-size:12px;font-weight:600;padding:3px 9px;border-radius:999px;white-space:nowrap}
    .impact-high{background:rgba(212,175,55,.18);color:#f0cf68}
    .impact-med{background:rgba(139,92,246,.18);color:#c4b5fd}
    .impact-low{background:rgba(148,163,184,.14);color:#cbd5e1}
    .dir-up{color:#4ade80}
    .dir-down{color:#f87171}
    .dir-flat{color:#cbd5e1}
    .conf-bar{display:inline-block;width:72px;height:6px;border-radius:3px;background:#2a2440;vertical-align:middle;margin-right:8px;overflow:hidden}
    .conf-bar i{display:block;height:100%;background:linear-gradient(90deg,#8b5cf6,#d4af37)}
    .watcher-foot{margin-top:14px;font-size:12px;color:#8c85a3;line-height:1.6}
    @media (max-width:700px){.watcher-panel{margin:28px 12px;padding:20px 16px}}
  </style>

  <div class="watcher-top">
    <h2 id="watcher-title">Watcher: scored wire, live feed view</h2>
    <span class="watcher-tag">Illustration</span>
  </div>
  <p class="lead">Every headline the Watcher scores gets four reads: how much it can move index futures, which way, and how sure the scoring model is. The Korvus read is written for the trader, not the feed. Rows below are illustrative sample data, not live market output and not trading advice.</p>

  <div class="tablewrap">
    <table class="watcher-table">
      <thead>
        <tr>
          <th scope="col">Time (ET)</th>
          <th scope="col">Headline</th>
          <th scope="col">Impact</th>
          <th scope="col">Direction</th>
          <th scope="col">Confidence</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="time">08:30</td>
          <td>Initial jobless claims print well above consensus</td>
          <td><span class="chip impact-high">High</span></td>
          <td class="dir-down">Bearish</td>
          <td><span class="conf-bar"><i style="width:82%"></i></span>82%</td>
        </tr>
        <tr>
          <td class="time">09:10</td>
          <td>Regional Fed speaker holds rate path language steady</td>
          <td><span class="chip impact-med">Medium</span></td>
          <td class="dir-flat">Neutral</td>
          <td><span class="conf-bar"><i style="width:64%"></i></span>64%</td>
        </tr>
        <tr>
          <td class="time">09:45</td>
          <td>Services activity index beats estimate by a wide margin</td>
          <td><span class="chip impact-high">High</span></td>
          <td class="dir-up">Bullish</td>
          <td><span class="conf-bar"><i style="width:76%"></i></span>76%</td>
        </tr>
        <tr>
          <td class="time">10:30</td>
          <td>Ten-year note auction clears with softer tail demand</td>
          <td><span class="chip impact-med">Medium</span></td>
          <td class="dir-down">Bearish</td>
          <td><span class="conf-bar"><i style="width:58%"></i></span>58%</td>
        </tr>
        <tr>
          <td class="time">14:00</td>
          <td>Crude inventories build more than the prior week</td>
          <td><span class="chip impact-low">Low</span></td>
          <td class="dir-flat">Neutral</td>
          <td><span class="conf-bar"><i style="width:41%"></i></span>41%</td>
        </tr>
      </tbody>
    </table>
  </div>

  <p class="watcher-foot">Illustration: sample rows for layout only. Scores, times and headlines are not from a live feed. Korvus is an information terminal. Nothing shown here is a recommendation to buy or sell any instrument.</p>
</section>
</main>
</body>
</html>
