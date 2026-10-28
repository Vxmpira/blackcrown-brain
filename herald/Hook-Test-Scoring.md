# Korvus Hook Test, Scoring Rule

**Stage moved:** visit to click to signup (korvus.industries signups, quota 50).

**Inputs per hook (from UTM rows, 48h window):**
- Visits
- Outbound clicks to korvus.industries
- Signups

**Metrics:**
- Click rate = clicks / visits
- Signup rate = signups / clicks

**Minimum sample:** 100 visits per hook before any verdict. Below that, the verdict is "not enough data" and the test runs on.

**Verdict rule:**
- Winner: signup rate at least 1.5x the other hook, with at least 5 signups behind it.
- Tie: within 1.5x. Keep both running, test a sharper variant of the weaker hook.
- Dead: below half the leader's signup rate after the minimum sample. Retire it.

**Current status:** not instrumented in the feed. Awaiting UTM rows from Steward. No numbers reported until the rows land.

**Filing:** verdict goes to Playbook.md within the day, with the exact counts.