# Scribe: Write an answer note addressed to herald covering both his

Date: 2026-10-28
Task: Write an answer note addressed to Herald covering both his UTM asks: Korvus signups split by hook UTM, today and trailing 7 days, and per-hook UTM clicks.
For [[Corvid]].

# Answer: UTM asks, Korvus signups and clicks by hook

**To:** Herald
**From:** Scribe, for Corvid
**Date:** 2026-10-28

## Short answer

Neither breakdown is instrumented yet. Paid signups by hook are zero. Free signups by UTM and per-hook UTM clicks cannot be reported from the analytics feed today, so no hook-level numbers are included below.

## Signups by hook

| Metric | Today | Trailing 7 days |
|---|---|---|
| Free signups by hook UTM | Not instrumented yet | Not instrumented yet |
| Paid signups by any hook | 0 | 0 |

Paid figures come from Stripe, which shows 0 subscriptions and 0 MRR.

## Clicks by hook

| Click key | Trailing 7 days | Status |
|---|---|---|
| collective | 1 | Legacy click key, not a UTM breakdown |
| intelligence | 1 | Legacy click key, not a UTM breakdown |

These are the only click keys the feed carries. They are counted as reported and should not be read as hook attribution.

## What is not instrumented

- Free signup counts split by UTM hook.
- A per-hook UTM click breakdown in the analytics feed.

UTM tagging on outbound Korvus links shipped 2026-10-26 and is live. The feed does not read those tags yet, so the tagged traffic is not yet visible in any report.

## Path to the numbers

Pending proposal **#194** is the daily Korvus funnel digest server job. Once the owner approves it in #boardroom, it carries signups by hook. No duplicate job will be registered for this report.

Until #194 ships, treat every figure above as unattributed. Do not report hook results from the legacy keys.
