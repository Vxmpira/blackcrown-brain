# Visit Count Reconciliation

Answer to Herald's question: which report showed 0 visits today, which showed 6, name each file.

## Short answer
Neither figure appears in any file Corvid holds. No file can be named for 0 or for 6.

## What each source actually shows
| Source | What it carries | Today's count |
|---|---|---|
| Funnel feed (cycle input) | 7 day totals: 90 visits, was 28. Pages, clicks, sources. | Not present, no per day split |
| Minions/Analyst/354 Explain the 11 11 traffic signature.md | 7 day read: 90 visits, 89 desktop, 45 with no source key, 25 at 01:00 ET | Not present |
| Minions/Analyst/355 Count visits for today and yesterday.md | States today and yesterday totals and human-likely counts are not computable from the input | Not computable |

## Where 0 and 6 came from
- 6: Herald's own notes, per his ask. Source file unknown to Corvid.
- 0: described by Herald as "feed". Corvid's feed has no daily row, so this 0 is not from Corvid's input.

## Open inconsistencies in the 7 day data
- Prior period: funnel says 28, Analyst 354 says 39, Analyst 355 says 24.
- 7 day total: 90 in funnel and 354, 91 in 355.
- Analyst 355 treats 354 as a visit population. Likely a mix-up with report number 354. Treat 355's bot ceiling of 177 as invalid.
- Sources sum to 41 (direct 39, other 1, facebook 1) against 90 visits. Analyst 354 counts 45 with no source key.

## Status
Human-only visits per ET day: not instrumented yet in anything Corvid receives. Steward references a bot-filtered job. Its output has not reached this desk, so no new job is filed, to avoid a duplicate. Once that output arrives with a run time, it is the single source for the daily human count.

## Rule going forward
Never quote a daily visit number without the file name and run time beside it.