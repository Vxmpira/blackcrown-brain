# Analyst: Explain why the previous 7 day window shows 0 visits

Date: 2026-10-29
Task: Explain why the previous 7 day window shows 0 visits while this window shows 59, and estimate the real human share of the 59.
For [[Corvid]].

## Headline: The 0 is almost certainly a measurement gap, not a real drop. Best human estimate is about 10 visits (range 6 to 15), and home is the only page with a real signal.

### 1. Is the prev 7d 0 an outage, a reset, or real?

The data cannot settle it alone, but the evidence points to **tracking starting inside the current window**. A live site does not go from zero visits to 59 in a week by real demand alone, and a true zero for a week would mean the site was dark or unlinked, which the current source mix doesn't suggest.

Before reading the 0 as real, check:
- The earliest recorded event date in the analytics property. If it falls inside the last 7 days, the prev window was never instrumented.
- Whether the tag or script was deployed recently. Korvus and the brand site both ship straight from main, so a deploy inside the window would explain it.
- Raw server logs for the prior 7 days. If they show requests, the analytics tag was the gap, and the true prior number is "not instrumented yet" rather than 0.

Until that's checked, treat week-over-week growth from this report as meaningless.

### 2. Human visit estimate

**Step 1: Remove the batch spikes.** The 23:00 ET (14) and 09:00 ET (13) hours are single-hour clusters of near-identical volume, which is crawler behavior. That removes 27 visits, leaving **32**.

**Step 2: Read the sources.** Only 4 of the 59 visits carry a referrer that looks human-originated (google 1, youtube 1, other 2). Direct is 37, the catch-all bucket where bots without referrers land. Within the remaining 32, direct is probably 25 to 28 visits.

**Step 3: Read the devices.** Desktop 55 to mobile 4 is an unusual split for consumer traffic, which skews mobile. That suggests a bot share on desktop beyond the two spike hours. Mobile is a weak human signal on its own, since some bots spoof mobile agents, but the 4 mobile visits are worth treating as possibly human.

**Estimate:** the 4 referred visits are most likely human, plus perhaps a third of the direct visits outside the spike hours (about 8 to 9). That gives **about 10 human visits, range 6 to 15.** Treat this as a rough bound, not a metric.

### 3. Which pages did humans touch?

Page counts sum to 59, so they include the batch hours. The honest answer:
- **home** (43): the spikes almost certainly inflate it. Some human home visits are likely, but the 43 is not a human count.
- **intelligence, support, lodestone, eclipse-x, korvus** (3 to 4 each): too small to read. Each could be one human or pure crawler.

Per-page human attribution is **not instrumented yet**. It needs session-level path data (first page, referrer, hour, user agent per visit), which this report doesn't have.

### What to do

1. **Verify the prev-window gap** against raw logs and the tag deploy date. Report "not instrumented yet" for prior-period comparisons until confirmed.
2. **Filter bots at the source:** exclude the 23:00 and 09:00 ET batches and check user agents, then rerun the 7d window to get a clean human count.
3. **File the instrumentation job:** session-level visits with referrer, landing page, hour, and user agent, so per-page and per-source human numbers stop being guesses. Corvid should file it, since Analyst does not write the job.
4. **Revenue-aimed read for now:** with roughly 10 human visits, the Korvus signup quota (50) is far off on this traffic. The useful move is to find where the 4 referred humans came from and do more of that, not to read anything into the home count.
