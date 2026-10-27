# Prospector: Define three visit to click test cells for the korvus

Date: 2026-10-27
Task: Define three visit-to-click test cells for the Korvus homepage with a kill rule
For [[Herald]].

# Korvus Homepage Test Cells

**Target:** korvus.industries `/` (served from korvus:korvus_landing.html)
**Rung:** signups toward the 50 korvus.industries signup quota, then first paying Operator customer.
**Watched number (all cells):** homepage visit to primary CTA click rate. Baseline 6.7 percent (2 of 30 visits, 7 days).

**Instrumentation gap:** per-cell and per-hook click counts are not instrumented yet. Until they are, each cell can only be read against the aggregate baseline, and the split will be approximate. Filing a job to tag clicks by variant is the first step (see below).

## Cell A: Five-second clarity

- **Change:** Replace the hero headline and subhead so the first screen states the product in plain terms: what Korvus is, who it is for, and that it runs 24/7. Keep the existing layout. Keep the mottos out of the headline.
- **Hypothesis tested:** visitors cannot tell what Korvus is within five seconds.
- **Minimum before verdict:** 150 visits to this cell.
- **Win:** CTA click rate at or above 13 percent (double baseline) after 150 visits.
- **Kill rule:** after 150 visits, if CTA click rate is at or below 6.7 percent, revert to the prior hero. Kill early if the first 75 visits show zero clicks.

## Cell B: Value above the fold

- **Change:** Move the feature chip strip and one data mock (labeled Illustration) into the first viewport, directly under the hero. No other copy changes.
- **Hypothesis tested:** the value proposition is buried below the fold.
- **Minimum before verdict:** 150 visits to this cell.
- **Win:** CTA click rate at or above 13 percent after 150 visits.
- **Kill rule:** after 150 visits, if CTA click rate is at or below 6.7 percent, revert. Kill early if the page shows a layout break on mobile widths at any point, since that voids the test.

## Cell C: Specific CTA wording

- **Change:** Replace the vague primary CTA label with a specific one that names the action and the free tier, for example "Start free Observer". Keep the same destination and the existing UTM tagging on outbound links.
- **Hypothesis tested:** the CTA wording is vague.
- **Minimum before verdict:** 150 visits to this cell.
- **Win:** CTA click rate at or above 13 percent after 150 visits.
- **Kill rule:** after 150 visits, if CTA click rate is at or below 6.7 percent, revert. Do not test price language here; Korvus prices inject server side and are not hardcoded on this page.

## Sequencing and reality check

- At roughly 30 visits a week, 150 visits per cell is about five weeks of traffic per cell. Run the three cells in sequence, not in parallel, unless a variant split is instrumented first.
- A verdict at this volume is directional. Treat any single cell result as a lead to confirm, not a conclusion.
- Each cell ships as its own proposal: one change, one page, exact CURRENT anchors. Regent reviews, the owner green lights in #boardroom, and the executor applies. Cell A is the first to file since it addresses the largest gap.

## Filed follow-up

1. **Job:** tag homepage CTA clicks with a variant identifier so per-cell click counts exist. Until this ships, report cell results as "not instrumented yet" for the per-variant split.
2. **Check:** confirm the current primary CTA label and destination before Cell C is written, so the proposal anchors to the exact live text.
