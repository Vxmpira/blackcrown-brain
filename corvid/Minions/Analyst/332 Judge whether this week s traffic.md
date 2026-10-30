# Analyst: Judge whether this week s traffic is real humans or

Date: 2026-10-30
Task: Judge whether this week's traffic is real humans or self/bot traffic, and name the signature that would settle it.
For [[Corvid]].

## Verdict: Mostly not organic demand yet. Confidence: moderate (about 65%)

The week is too small to prove bot traffic, but the pattern points to owner and server touches plus a thin layer of real visitors, not a growing audience. The prior 7 days were zero, so there is no trend to read.

## The numbers behind it

- **Concentration:** 14 visits at 23:00 ET and 13 at 09:00 ET make up 27 of 61 visits (44%) in two hour buckets. Every other hour has 4 or fewer.
- **Source:** 39 of 61 are direct (64%). Google sent 1 visit all week.
- **Page:** 43 of 61 (70%) landed on home. Only 2 CTA clicks total, about 3% of visits, so almost nothing moved past the front door.
- **Device:** 57 desktop, 4 mobile (7% mobile). Low mobile share is a weak automation signal on its own. Index futures traders often work on desktop, so I weight this lightly.

## Hour patterns

- **Look human:** The 12:00 to 22:00 ET stretch (1 to 4 visits per hour, spread across hours) is what a small real audience looks like. The 09:00 ET cluster also fits real traders, since it lines up with US cash open at 09:30.
- **Look self or automated:** The 23:00 ET spike of 14 is the outlier. A single hour that heavy with direct traffic and near-zero engagement points to a scheduled check, a monitoring tool, or the owner's own session. The 00:00 to 01:00 and 05:00 visits are too sparse to read.

## The signature that settles it

Exclude owner and server egress IPs, then re-check the hour distribution. If the 23:00 and 09:00 spikes collapse toward zero, that traffic was self or server. If they hold, you have real visitors clustered around those hours, and the next question is why only 2 of 61 clicked.

The owner's IPs and the server's outbound IP are known to the company, so this is a filter you can run from existing analytics without a new tool. If you cannot yet filter by IP, the fallback is to check whether the 23:00 visits share one user agent or arrive at near-identical intervals. Evenly spaced visits point to a scheduler.

## Action

Treat the 2 CTA clicks as the only real-human engagement proxy until the filter runs. Revenue impact is not instrumented yet at this volume: no signups or Stripe events are in this dataset, so say so in the report rather than estimating. Ask the owner whether his sessions fall in the 23:00 window, which would resolve most of the question on its own.
