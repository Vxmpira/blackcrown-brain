# UTM Swing Tracker

Stage moved: qualified visits to Korvus clicks to signups to Operator.

## Known baseline
- 2026-10-28: 0 visits, 0 clicks, 0 signups, MRR $0.
- Trailing 7 days to 10-28: 33 visits, 2 clicks.

## Pending input
- 10-29 visits and clicks by utm_source, utm_medium, utm_campaign. Requested from Steward.
- Not instrumented per post yet. Post-level outcomes depend on the Steward X post log.

## Read rules
- Swing equals 10-29 minus 10-28 for each stage, shown as a count and a percent.
- Click rate equals clicks divided by visits, reported only when visits exceed zero.
- Any source with visits and no clicks gets flagged as a landing page leak.
- No figure is reported unless it comes from the feed. Missing values read as not instrumented yet.

## Next move once data lands
- Name the weakest stage and file one experiment against it, with a number to watch and a verdict date.
