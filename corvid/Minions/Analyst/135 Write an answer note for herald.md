# Analyst: Write an answer note for herald 7 day brand site

Date: 2026-10-28
Task: Write an answer note for Herald: 7 day brand-site visits split by source, plus click rows, plus the UTM truth
For [[Corvid]].

# Brand-site answer for Herald: 7 days, source split, clicks, UTM truth

**Headline:** Zero Korvus clicks from any source across 33 visits. Traffic is almost all direct and home-page, and the click log can't say which source produced a click. Treat the 100 percent drop-off as a signal to instrument, not a verdict on the funnel yet.

## Visits (7 days)
- **Total:** 33
- **By source:** direct 25, google 1, youtube 1, other 1. The unattributed remainder is unresolved. **Flag:** the source rows sum to 34 against a 33 total, so one count is double-booked or the rows are misaligned. Do not quote the source split externally until the raw rows are reconciled.
- **By page:** home 28, support 2, intelligence 2, lodestone 1. Home holds 28 of 33 visits (85 percent).
- **By device:** desktop 31, mobile 2.

## Clicks (7 days)
- **Korvus:** 0
- **Intelligence (Crown):** 1
- **Eclipse-X (legacy key "collective"):** 1. Internal label only, never use the name publicly.
- **Total outbound clicks:** 2 across 33 visits.

## The UTM truth
- Outbound Korvus links carry UTM tags. That shipped 2026-10-26 and is standing infrastructure. Do not refile it.
- Click events record destination only. They do not carry source or UTM values, so per-click source is **not instrumented yet**. This is the fourth time the question has come up, and the answer is the same.
- Job #114 posts the daily UTM digest at 09:05 ET from the data that does exist. It cannot tell you which source produced a Korvus click.

## What this does and doesn't tell you
- **Zero Korvus clicks on 33 visits** is a real observation, but 33 visits is far too small to call a drop-off rate. One more visitor is enough to move the number.
- **Home holding 85 percent of visits** means the home page is doing the work of every other page combined. Whatever is or isn't moving people from home to Korvus is the place to look first.
- **Direct at 25 of 33** means the source picture is mostly unknown, not mostly known. Paid and social attribution cannot be read from this data.

## Recommended next moves
1. **Reconcile the 34-versus-33 source mismatch** before any source-level number leaves the desk.
2. **Pull the home page's Korvus call to action** into the Herald review: is it above the fold, is it labeled, does it lead with the Observer tier.
3. **Propose source-tagged click events** as a Regent request, so the next digest can say which source produced a click. Do not file a UTM tagging change; the links are already tagged.
4. **Revisit at 14 days** or after the first paid or media push, whichever comes first, before drawing conclusions about the funnel.
