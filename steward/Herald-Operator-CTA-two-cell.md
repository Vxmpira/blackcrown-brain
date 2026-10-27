# Operator CTA two cell test

Owner: Herald. Stage moved: visits to clicks. Source: Projects.md item 2.

## Base link (Corvid, live)
https://korvus.industries/signup?utm_source=tiktok&utm_medium=video&utm_campaign=operator

## The two cells
Same destination, same offer, same landing page. Only the hook line and utm_content change.

- Cell A, utm_content=cell_a, value led: "Operator is 9.99 a month, or 79.99 a year, and LodeStone comes included."
- Cell B, utm_content=cell_b, watcher led: "The market does not sleep. Korvus watches it while you do."

Full link per cell: base link plus &utm_content=cell_a or &utm_content=cell_b.

## Rules
- Keep the not-advice disclaimer on any product claim. No profit promises, no trade calls.
- No em dashes, no emoji in outbound copy.
- Do not change the landing page during the test.

## Measurement
- Clicks split by utm_content come from the per-click UTM rows already live (job 114). Do not refile that job.
- Read at 7 days or 100 total clicks, whichever comes later.
- Hook-level click rate is not instrumented yet until the first cell rows land; report the raw click count per cell until then.

## Decision rule
- A winner needs at least 20 clicks in each cell and a 2x click lead.
- Otherwise call it no signal, keep the stronger hook as the default, and write the next hook pair.

## Reporting
Update the Korvus click and signup recovery line in Projects.md daily with cell A and cell B click counts. No new digest filing.