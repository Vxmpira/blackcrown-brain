# Planner: Draft day 1 operator click readout template

Date: 2026-10-27
Task: Draft Day 1 Operator click readout template
For [[Steward]].

# Day 1 Operator Click Readout Template

**Offer:** Korvus Operator (Ladder rung: first paying customer)
**Readout date:** ____________
**Window:** Day 1 since variant launch
**Baseline:** 7 days, 30 visits, 0 clicks (control)

## Readout Table

| Variant | Link source | Visits | Clicks | Signups | Source | Flag |
|---|---|---|---|---|---|---|
| Baseline | Pre-test links | 30 (7d) | 0 (7d) | not instrumented yet | Site analytics | Baseline locked |
| KOR-OP-002 | UTM tag as shipped | | | | | |
| KOR-OP-001 | UTM tag as shipped | | | | | |

**Flag rules:**
- Leave a number blank and write `not instrumented yet` in the flag column when the figure cannot be read from a real source.
- Never estimate or back-fill a missing value.
- Write `Illustration` on any example data, never on live numbers.

## Readout Line Format

One line per variant, in this order:

`[Variant] | visits: [n] | clicks: [n] | signups: [n or not instrumented yet] | source: [UTM source] | flag: [none or reason]`

## Day 1 Read Rules

1. Compare each variant against the baseline visit and click rate, not raw counts alone.
2. Day 1 is directional only. No winner call before the owner-set window closes.
3. If a variant shows zero clicks on matching visits, flag it for Herald review.
4. Close with one line: the next action and the rung it moves.

## Execution Steps

1. **Steward:** Confirm both variant links carry the standing UTM tags and that click events are recorded. Done when both links resolve and tagged traffic is visible. If a click count cannot be read, file the instrumentation job and mark `not instrumented yet`.
2. **Herald:** Pull Day 1 visits, clicks, and signups per variant into the table above. Done when every cell is filled or flagged.
3. **Steward:** Post the completed readout to the vault under Minions/Planner. Done when the file contains all three rows and the closing action line.
4. **Herald:** Propose the next variant or placement based on the read. Done when the proposal names the change and the metric it should move.
