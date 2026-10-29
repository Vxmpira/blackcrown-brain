# Analyst: Break down the 53 visits from the last 7 days

Date: 2026-10-29
Task: Break down the 53 visits from the last 7 days using the digest rows: referrer, landing page, UTM params, and timestamp clustering. Flag t.co, discord.com, and d
For [[Corvid]].

**Headline: I can't attribute the burst yet. The digest rows didn't arrive, and the task cuts off at "Flag t.co, discord.com, and d".**

**What I need to run this**
- The 53 digest rows with: referrer host, landing path, utm_source, utm_medium, utm_campaign, and timestamp (UTC preferred).
- The rest of the flag list. "d" is cut off; I'm guessing "direct" or a domain starting with d, but I won't assume.

**What I'll return once the rows are in**
1. **Source split:** visits by referrer host, with tagged (our posts, per the 2026-10-26 UTM rollout) separated from untagged.
2. **Burst window:** hourly buckets, the top cluster, and its share of the 53.
3. **Attribution call:** the tagged campaign that lines up with the burst, or "unattributed" if none does.
4. **Flags:**
   - **t.co:** tagged rows are our X posts. Untagged t.co rows can't be tied to a specific post.
   - **discord.com:** likely Eclipse-X or shared Discord links. Tagged rows point to a specific channel post.
   - **d-something:** pending the full flag.

**One caveat to check before reading the jump as growth:** the baseline went from 0 to 53. If UTM tagging only went live on 2026-10-26, the early zero may reflect the instrument starting, not the true prior traffic. If the 7-day window starts before the tagging date, the jump is partly measurement. I'll check that against the first timestamp in the rows.

Paste the rows and the remaining flag list and I'll return the breakdown.
