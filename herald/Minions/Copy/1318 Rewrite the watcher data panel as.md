# Copy: Rewrite the watcher data panel as one section under 40

Date: 2026-11-01
Task: Rewrite the Watcher data panel as one section under 40 lines. Start with <section class="panel" aria-label="Watcher data panel"> and end with </section>. No inl
For [[Herald]].

<section class="panel" aria-label="Watcher data panel">
  <header class="panel-head">
    <h2>Watcher Feed</h2>
    <p class="panel-tag">Illustration</p>
  </header>
  <p class="panel-lede">Scored headlines from the Presidential Wire, sampled for layout. Not live data. Not financial advice.</p>
  <div class="tablewrap">
    <table class="data-table">
      <thead>
        <tr>
          <th scope="col">Time</th>
          <th scope="col">Headline</th>
          <th scope="col">Impact</th>
          <th scope="col">Direction</th>
          <th scope="col">Confidence</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>08:30 ET</td>
          <td>Retail sales print lands above consensus</td>
          <td><span class="chip chip-high">High</span></td>
          <td>Bullish</td>
          <td>72%</td>
        </tr>
        <tr>
          <td>09:45 ET</td>
          <td>Fed speaker signals patience on rate path</td>
          <td><span class="chip chip-med">Medium</span></td>
          <td>Neutral</td>
          <td>58%</td>
        </tr>
        <tr>
          <td>10:15 ET</td>
          <td>Treasury auction draws softer than expected demand</td>
          <td><span class="chip chip-med">Medium</span></td>
          <td>Bearish</td>
          <td>61%</td>
        </tr>
        <tr>
          <td>11:00 ET</td>
          <td>Jobless claims revised lower for prior week</td>
          <td><span class="chip chip-low">Low</span></td>
          <td>Bullish</td>
          <td>49%</td>
        </tr>
        <tr>
          <td>13:20 ET</td>
          <td>Energy inventories show a larger than forecast build</td>
          <td><span class="chip chip-med">Medium</span></td>
          <td>Bearish</td>
          <td>66%</td>
        </tr>
        <tr>
          <td>14:05 ET</td>
          <td>Headline risk flagged on trade policy talks</td>
          <td><span class="chip chip-high">High</span></td>
          <td>Mixed</td>
          <td>44%</td>
        </tr>
      </tbody>
    </table>
  </div>
  <p class="panel-foot">Scores are illustrative. Live scoring runs 24/7 inside Korvus.</p>
</section>
