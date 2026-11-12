# Planner: Deliver korvus experiment 2 complete text untruncated

Date: 2026-11-12
Task: Deliver Korvus Experiment 2 complete text, untruncated
For [[Steward]].

*Note: I'm working from the brief's parameters (korvus.industries landing only, baseline 1 signup from 94 visits over 7 days, 14-day run). The prior gists aren't in my context, so Steward should reconcile this against them before filing.*

# Korvus Experiment 2: Landing Page Signup Conversion

## Hypothesis
If the korvus.industries landing page leads with the all seeing watcher promise (24/7 market intelligence while the trader sleeps) and puts one clear path to the free Observer tier above the fold, then the share of landing visitors who sign up will rise above the current baseline. This is a conversion test, not a traffic test.

## Scope
- **In scope:** the public landing page at korvus.industries (/) only. One section of copy and one call to action area may change.
- **Out of scope:** every other page, the Stripe pricing display (it injects server side and is never hardcoded), Eclipse-X, Crown, LodeStone, and any new traffic channel. Outbound Korvus links keep their standing UTM tagging, which is already live and is not refiled.

## Metric
**Primary:** signup conversion rate = landing signups divided by unique landing visits, measured over the 14-day window.

**Guardrail:** the page must render correctly on desktop and phone widths, and no claim may promise profits or read as trading advice.

## Baseline
- Visits: 94 over 7 days
- Signups: 1
- Conversion: about 1.1 percent (1 divided by 94)

Not instrumented yet: per source conversion. Steward files the instrumentation job if the per source split is needed for the readout.

## Success Rule
- Read the result only after at least 150 landing visits, or at Day 14, whichever comes first.
- Success: conversion at or above 2.0 percent across the window.
- Honest caveat: at this traffic volume a single signup moves the rate a lot. Treat the result as directional and decide on the next experiment, not on the number alone.

## 14-Day Run

| Day | Step | Owner | Done when |
|---|---|---|---|
| 0 | Confirm baseline numbers and the window start date | Steward | Dates and baseline logged in the experiment record |
| 0 | Write the complete variant section copy (hero line and CTA area only): no dollar amounts, no dashes, one claim per line, not advice disclaimer kept | Corvid | Full variant text sits in the vault as a complete section |
| 0 | File the single section change as a proposal | Corvid | Proposal filed with the exact section named |
| 0 | Owner green light in #boardroom, stating exactly what it triggers: the live landing copy on / changes for the test window | Owner | Approval recorded in #boardroom |
| 1 | Executor applies the change; confirm it is live within about 2 minutes | Steward | Live page checked on desktop and phone widths |
| 1 to 14 | Drive traffic to / only, through existing channels, with tagged links; no new channels | Herald | Daily traffic log kept |
| 1 to 14 | Record visits and signups each day | Steward | 14 daily entries in the experiment log |
| 7 | Mid run checkpoint: visits, signups, conversion so far | Herald | Written checkpoint posted to the log; no mid run copy changes unless a doctrine issue appears |
| 14 | Compute final conversion against baseline and the success rule | Steward | Written readout with the number, sample size, and caveat |
| 14 | Recommendation: keep, revert, or next experiment | Planner | Recommendation filed as an ask for the owner |
| 14 | Owner ruling in #boardroom | Owner | Ruling recorded; any revert filed as its own proposal |

## Revenue Link
Korvus is income source number one. Each signup moves the company toward the first paying customer rung through the Observer to Operator path, and this test shows whether the landing page itself is the constraint.

END OF DEFINITION
