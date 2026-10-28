# Analyst: Break down the 32 brand home visits from the last

Date: 2026-10-28
Task: Break down the 32 brand home visits from the last 7 days: by source, device, and hour, and estimate how many are one repeat direct desktop client versus distinc
For [[Corvid]].

## Headline: Hypothesis not confirmed or killed. The aggregates can't test it.

The 7-day totals don't support a per-source, per-device, or per-hour breakdown, and the hypothesis doesn't add up on its own numbers.

## The numbers available

| Metric | Count | Share of 37 |
|---|---|---|
| Total visits | 37 | 100% |
| Direct | 29 | 78% |
| Desktop | 35 | 95% |
| At 23 ET | 14 | 38% |

Derived from those, the direct desktop share is at least 27 of 37 (73%), since 29 direct and 35 desktop overlap by at least 27. The 23 ET cluster is 14 visits, not 23.

## Why the hypothesis fails as written

- **The arithmetic doesn't close.** If the 14 visits at 23 ET are self or agent traffic, 23 visits remain outside that hour. A 3 to 5 visit cold sample requires roughly 18 to 20 of those 23 to also be self or agent traffic. Nothing in the aggregates shows that.
- **"32" and "37" disagree.** The task says 32 visits; the context says 37. I used 37. Confirm which window and filter produced each number before anyone acts on either.
- **Repeat versus distinct can't be estimated.** No visitor identifier (cookie, hashed IP, session) appears in the totals, so one repeat client and several distinct visitors look identical here.

## What would settle it

Pull the raw visit log for the same window with per-visit timestamp, referrer, user agent, and a visitor key (cookie or salted IP hash). From that:

1. Group by visitor key to get distinct versus repeat counts.
2. Flag known self and agent user agents, and check whether the 23 ET visits share one user agent and one visitor key.
3. Re-run the cold sample as visits from distinct, non-flagged visitors outside the self and agent set.

Status: the per-visit breakdown is **not instrumented yet** from these totals. Corvid should file a request for the raw export, with the visitor key added to the logging if it's missing, before the cold-sample number is used for any decision.
