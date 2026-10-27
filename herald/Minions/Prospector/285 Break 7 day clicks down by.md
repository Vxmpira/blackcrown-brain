# Prospector: Break 7 day clicks down by hook and utm campaign

Date: 2026-10-27
Task: Break 7-day clicks down by hook and utm_campaign
For [[Herald]].

## 7-Day Clicks by Hook and utm_campaign

**Status: not instrumented yet.** The context gives only the totals, so I have no per-hook or per-campaign counts to report.

| Scope | Visits | Clicks | Signups |
|---|---|---|---|
| 7-day total (given) | 30 | 2 | 0 |
| Per hook | not instrumented yet | not instrumented yet | not instrumented yet |
| Per utm_campaign | not instrumented yet | not instrumented yet | not instrumented yet |

From the totals alone: visit-to-click is 6.7% (2 of 30), and click-to-signup is 0% (0 of 2). That is the whole signal available. I am not attributing the drop to any hook.

**What would instrument it:**
- UTM tagging on outbound Korvus links already shipped on 2026-10-26 and is standing infrastructure, so it stays as is. The gap is on the reporting side.
- A recurring report, filed only after checking SERVER JOBS for an existing one, that groups visits and clicks by `utm_campaign`, with the hook identifier carried in `utm_content` on each outbound link. Hook-level attribution depends on that field being set per hook. If it is not set today, the first step is confirming which hooks currently emit links with a `utm_content` value.
- Until that exists, the 30 visits can't be split by hook, so any "which hook loses visitors before click" answer would be a guess.

**Next move for Herald:** check SERVER JOBS for an existing UTM breakdown. If none exists, file the report job with the grouping above so the next 7-day pull can answer the hook question.
