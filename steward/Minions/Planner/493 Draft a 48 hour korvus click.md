# Planner: Draft a 48 hour korvus click recovery test

Date: 2026-10-29
Task: Draft a 48 hour Korvus click recovery test
For [[Steward]].

# 48 Hour Korvus Click Recovery Test

**Stage under test:** visit to click on korvus.industries
**Baseline (7d):** 56 visits, 2 clicks, 3.6% visit to click, 0 signups, MRR $0
**Rung moved:** first paying customer (Korvus Operator)

**Honest read on volume:** 56 visits a week means the 48 hour window will likely see 15 to 25 visits total, so each cell gets roughly 4 to 8. A cell cannot prove a winner at this size. This test is a direction read: it tells us which message earns a click at all, and which one to scale and retest with more traffic.

## Decision rule (set now, before results)

- A cell is a **candidate winner** only if it earns at least 2 clicks and beats control's click rate.
- A candidate winner gets a second 48 hour run at higher volume before any copy becomes standing.
- If no cell beats control, the stage problem is upstream (traffic quality or offer clarity), and the next test moves to the landing page offer, not more copy.

## Preflight (hour 0 to 2)

| Step | Owner | Done when |
|---|---|---|
| Confirm the click event fires on the Korvus CTA and reports by utm_content | Steward | A test click shows up in the reporting with its tag. If the per cell split does not read, file an instrumentation job and mark per cell clicks "not instrumented yet" until it lands. |
| Check SERVER JOBS for any existing report covering this test | Steward | No duplicate job registered. |
| Confirm UTM tagging on outbound Korvus links (standing since 2026-10-26; do not refile) | Corvid | Tagged links resolve to korvus.industries with source and medium intact. |
| Assign four utm_content values: `control`, `hook_watch`, `hook_proof`, `hook_offer` | Corvid | Values listed in this plan and the tagged links generated. |

## The cells

One variable per cell. Everything else matches control.

| Cell | Variable changed | Copy or asset | Tag | Owner | Stage moved | Readout |
|---|---|---|---|---|---|---|
| Control | None. Current X copy and current landing CTA. | Existing standing post | `control` | Corvid (tags), Herald (control copy kept as is) | Visit to click (baseline) | H48 |
| Cell 1: Watch | Hook angle: the all seeing watcher, 24/7 coverage while the trader sleeps | New X post, Herald writes, no profit language | `hook_watch` | Herald (copy), Corvid (tag) | Visit to click, via arrival intent | H48 |
| Cell 2: Proof | Lead with a concrete mechanic: Presidential Wire scored news with impact, direction, confidence, and the written Korvus read | New X post, Herald writes | `hook_proof` | Herald (copy), Corvid (tag) | Visit to click, via arrival intent | H48 |
| Cell 3: Offer | Frame the free Observer tier as the entry point, "start free, no card" | New X post, Herald writes | `hook_offer` | Herald (copy), Corvid (tag) | Visit to click, via arrival intent | H48 |
| Cell 4: Page CTA (gated) | Landing CTA label only. Prices untouched (they inject server side). | One anchor text change in korvus_landing.html | Control tag, post go-live traffic only | Corvid (drafts proposal), Regent (review), owner (green light in #boardroom) | Visit to click, on page | H48, measured against go-live window only |

**Cell 4 approval note:** the owner's green light triggers exactly one edit: the CTA anchor text on korvus_landing.html. It changes no price text, no other copy, and no structure. If the green light has not arrived by hour 8, Cell 4 drops from this test. It does not run unreviewed, and it is not carried into the next window silently.

**Copy rules for all Herald cells:** no em dashes, no emoji, no profit promises, no trading advice, the not advice disclaimer on any product claim, two hashtags max, 280 characters with each link counted at 23.

## Timeline

| Hour | Step | Owner |
|---|---|---|
| 0 to 2 | Preflight checks above | Steward, Corvid |
| 0 to 3 | Three hook drafts (watch, proof, offer) and control confirmed | Herald |
| 2 | Cell 4 proposal filed to Regent (if running) | Corvid |
| 2 | Posts scheduled: each cell gets three posts spaced 16 hours apart, rotating order so every cell hits both day and evening audiences | Steward (schedule), Herald (copy) |
| 8 | Cell 4 cutoff: green light or drop | Owner |
| 24 | Interim check only: events firing, tags reading, no anomalies. No decisions made at this readout. | Steward |
| 48 | Final readout: clicks per cell, visits per cell, click rate per cell, control compared | Steward (numbers), Corvid (stage analysis) |
| 48 | Recommendation filed: scale a candidate winner into a second 48 hour run, or move the next test upstream to the landing offer | Corvid |

## Readout template (H48)

| Cell | Visits | Clicks | Click rate | Beats control? | Candidate winner? |
|---|---|---|---|---|---|
| Control | | | | n/a | n/a |
| Cell 1 Watch | | | | | |
| Cell 2 Proof | | | | | |
| Cell 3 Offer | | | | | |
| Cell 4 Page CTA | | | | | |

Any cell with fewer than 4 visits is reported as "insufficient volume," not as a loss.

## What the owner rules on

Only one decision lands on the owner: the Cell 4 green light by hour 8. Everything else runs on the desks. The owner gets the H48 readout and the recommendation, and rules on whether a candidate winner earns the second run.
