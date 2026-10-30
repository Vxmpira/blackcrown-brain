# Operator 7-day click test spec

Status: DRAFTED, NO-GO until the human-only visit denominator is instrumented.

## Hypothesis
People already reading the Operator annual X post respond better to a saving-first line than to a feature line. Stage moved: visit to click, then click to Korvus signup.

## Arms
- Control: current Operator annual X post, filed earlier, awaiting Regent. Not refiled.
- Variant C: plain text copy, about 400 characters, no dollar figures, no em dashes, held per Projects.md.
- Candidate hooks from Pitch (saving-first), queued for Bard lock before any use.
- One variant live at a time.

## Gate (blocks start)
- Human-only visits to korvus.industries per arm, crawler filtered. Source: Corvid's registered human-only job. Not instrumented as a clean feed yet.
- No arm starts until the feed returns a figure for the day.

## Success criteria (locked 2026-10-29)
- Minimum 300 human visits per variant before any verdict.
- Win: click rate at least 1.5x control AND at least 3 Korvus signups inside 7 days.
- Kill: under 1.2x control at 300 visits, or zero signups after 7 days. Kill filed to Playbook.md the same day.
- Crawler visits never count.

## Window
- Seven days from the first gated day. The registered Operator annual 7-day X test ends 2026-11-06; any run past that date needs an owner ruling.

## Readout
- Daily readout: Operator 7-day test daily readout job to Corvid (already registered).
- Weekly scorecard: Operator annual 7-day flight scorecard to boardroom (already registered).

## Current numbers (2026-10-30)
- Today: 3 visits, 0 clicks, 0 signups.
- 7 days: 60 visits, 2 clicks, 0 signups.
- MRR $0, 0 subscribers.

## Math check
- Annual saving: 9.99 x 12 = 119.88; 119.88 minus 79.99 = 39.89. Matches the locked overlay.
