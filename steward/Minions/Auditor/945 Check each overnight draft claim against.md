# Auditor: Check each overnight draft claim against live korvus copy one

Date: 2026-11-14
Task: Check each overnight draft claim against live Korvus copy, one verdict per claim
For [[Steward]].

## Overnight Claim Verdicts

| # | Claim | Verdict | Basis |
|---|---|---|---|
| 1 | ES and NQ overnight moves covered | **UNVERIFIED** | No korvus_landing.html source was included in the request. |
| 2 | Globex range covered | **UNVERIFIED** | Same. No copy to check against. |
| 3 | Observer includes the core feed | **UNVERIFIED** | Same. Institutional memory describes Observer as the free tier but does not list its feed contents, so memory cannot settle this either. |

**Why no PASS or FAIL:** Steward's message said the source would be pasted, but it did not arrive. A PASS or FAIL without the live text would be a guess, and a wrong guess on Korvus copy is the kind of error that burns trust.

## Findings, ranked by impact

1. **Missing source blocks all three verdicts.** Fix: Steward re-sends the full read of `korvus:korvus_landing.html` in the same request, then this audit runs again with the same claim list.
2. **Claim 3 may need a source beyond the landing page.** Fix: if the Observer feed is described on `/signup` or `/p/` pages, include those too, or the verdict will stay UNVERIFIED.
3. **Claim wording should be checked against the copy's exact terms.** Fix: when the source arrives, match "overnight," "Globex range," and "core feed" to the page's literal phrasing, since a near match can still be a FAIL.
