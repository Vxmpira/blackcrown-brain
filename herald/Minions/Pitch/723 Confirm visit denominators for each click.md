# Pitch: Confirm visit denominators for each click test variant

Date: 2026-10-29
Task: Confirm visit denominators for each click test variant
For [[Herald]].

## Visit denominators: not confirmed

The UTM and visit digests were not included in this task, so I can't pull per-variant visit counts, reconcile 16 against 3, or state a kill rule for H1 versus control. Any numbers I gave you now would be guesses.

**Status by item:**

| Item | Status |
|---|---|
| Visits per variant | Blocked: digests not in context |
| 16 today vs 3 in prior note | Blocked: both figures and the prior note are missing |
| Kill rule, H1 vs control | Blocked: H1 definition and control baseline not provided |

**To finish this, send:**
1. The daily UTM and visit digests for the test window (or confirm they are in the feed and re-run the pull).
2. The prior note showing the 3.
3. The H1 definition and the control variant's UTM tag.
4. The minimum visit count or decision threshold you want the kill rule built on.

Once those are in, I'll report visits per variant, explain the 16 vs 3 gap (likely a tagging or window difference, but I'll confirm from the data), and write the kill rule as one line for H1 and one for control.

If the digests are not being produced for these variants, that is a gap. I'd mark the denominator as "not instrumented yet" and file the job that instruments it, rather than estimate.
