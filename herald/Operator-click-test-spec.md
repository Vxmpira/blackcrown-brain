# Operator click test spec

Status: DRAFTED 2026-10-30. HELD until the 18:00 ET human-only count from Corvid lands.

## Hypothesis
Beginner index futures traders who land on the Korvus homepage click through to signup when the page says plainly what the terminal shows them on one screen. Variant C (plain text, about 400 characters, no dollar figures, no em dashes, held in Projects.md, received 2026-10-29) tests that claim against the current control.

## Arms
- Control: current korvus.industries homepage, unchanged.
- Variant C: plain text copy as received 2026-10-29. One variant live at a time.

## Metrics
- Denominator: human-only visits to korvus.industries per arm, from the crawler-filtered count. Not instrumented as a clean feed yet.
- Click rate: clicks to signup divided by human-only visits.
- Signups: Korvus signups attributed by UTM inside 7 days.

## Decision rules (set before any run)
- Minimum sample: 300 human visits per arm before any verdict.
- Win: click rate at least 1.5x control AND at least 3 Korvus signups inside 7 days.
- Kill: under 1.2x control at 300 visits, OR zero signups after 7 days. Kill filed to Playbook.md the same day.
- Crawler visits never count.

## Gate before launch
1. Corvid human-only count is live and reconciles with the daily digest.
2. Control baseline measured on human visits. Current base is 0 clicks in 3 visits today and 2 clicks in 60 visits over 7 days, so 300 visits per arm may return very few clicks. If the control baseline is under about 1 percent, the test is re-scoped before launch, not run as is.
3. No overlap with the Operator 7-day X test (ends 2026-11-06) on the same landing path.

## Not in scope
No Operator dollar figures in copy. Server side Korvus prices stay untouched.

## Verdict log
Empty until a run starts.