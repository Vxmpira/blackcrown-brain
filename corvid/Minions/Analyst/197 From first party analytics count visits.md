# Analyst: From first party analytics count visits with referrer t co

Date: 2026-10-28
Task: From first-party analytics, count visits with referrer t.co or utm_source=x per day since 10-24, note landing pages and which hit korvus signup
For [[Corvid]].

## Headline: X traffic is real but unmeasured by day and by signup

The feed I received has only a 7-day total: **33 visits from X since 10-24, up from 0 the prior period.** I don't have the raw session rows, so I can't give you the per-day split, landing-page breakdown, or signup attribution without guessing. I won't fill those in.

## What the numbers support

- **33 visits in 7 days** is the only verified figure.
- **"Up from 0"** means the prior-period ratio is undefined, so there is no growth rate to report yet. Treat 33 as a baseline.
- **Attribution is split across two signals.** Referrer `t.co` catches clicks from X that carry no tags. `utm_source=x` only works on Korvus links tagged after the UTM rollout on **2026-10-26**. Visits from 10-24 to 10-25 can only be counted through referrer, so the two signals will not sum cleanly across the whole window.

## What is not instrumented yet

| Question | Status |
|---|---|
| Visits per day since 10-24 | Not instrumented in this feed |
| Landing page breakdown | Not instrumented in this feed |
| Visits that reached korvus.industries/signup | Not instrumented in this feed |
| Signups attributed to X | Not instrumented (needs session source joined to signup event) |
| Lift from posts 189, 197, 198 | Cannot measure until they publish |

## What to do

1. **Pull the raw rows.** Re-run the analytics pull with daily grouping on referrer host and `utm_source`, plus landing path. Attach it so the per-day table can be built from data, not summary.
2. **Check SERVER JOBS before filing anything.** If a daily X referral report already runs, use it. If not, file one recurring server job that writes daily X visits, landing paths, and `/signup` hits to the vault through 10-30. Don't register a duplicate.
3. **Add a signup join.** Without a session-to-signup join, the 50-signup Herald quota can't be tied to X. That join is the metric that moves the Korvus rung.
4. **Mark the pre-10-26 window as referrer-only** in every report so the owner doesn't read a tagging gap as a traffic drop.
5. **Baseline the three pending posts.** Once 189, 197, and 198 go live, compare their visit windows against the 33-visit baseline, using the same daily grouping.

Rung moved: Korvus first paying customer, via signup volume from X. Measurement is the blocker, not the traffic.
