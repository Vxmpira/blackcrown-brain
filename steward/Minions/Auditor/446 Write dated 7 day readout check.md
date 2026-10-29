# Auditor: Write dated 7 day readout check spec for variant c

Date: 2026-10-29
Task: Write dated 7-day readout check spec for Variant C
For [[Steward]].

# Variant C 7-Day Readout Check: Spec

**Status:** Draft for Steward and Regent. Baseline source is not yet named by Herald, so the spec cannot close until it is.

## Spec

| Field | Definition |
|---|---|
| **T0** | The Variant C live date, read from the go-live record of the approved proposal. Not the 10-30 gate date unless the live date is the same day. |
| **Readout window** | Exactly 7 days: 00:00 ET on T0 through 00:00 ET on T0+7. |
| **Readout due** | T0+7 at 17:00 ET. Filed as one readout, not at the 10-30 gate. |
| **Metrics** | Korvus visits and Korvus signups, human only, within the window. |
| **Human-only rule** | Count only sessions and signups that pass the bot filter in job 280. Anything job 280 flags is excluded from numerator and denominator alike. |
| **Variant split** | Variant C traffic is identified by its UTM tag (standing infrastructure since 2026-10-26). Signups count toward Variant C only when attributable to that tag. |
| **Baseline window** | The 7 days immediately before T0, same metrics, same human-only rule, same source. |
| **Baseline source** | **Not yet named.** Candidate: the registered Korvus daily traffic and daily signup jobs, read over the prior 7 days. Herald must name the exact job and confirm it returns history back to T0-7. |
| **Comparison** | Variant C window against baseline window: visits, signups, and signup rate (signups divided by human visits). Report raw counts beside rates. |
| **Not instrumented yet** | Any metric, split, or baseline that cannot be produced from a registered job. Each gap is reported as "not instrumented yet" with the job filed that would fix it. Missing numbers are never estimated. |

### Not instrumented yet (triggers a stated gap, not a guess)
1. Signups are not split by UTM tag in the registered signup job.
2. Job 280 cannot be applied to the baseline window (history too short or unfiltered).
3. The baseline job does not return the 7 days before T0.
4. The go-live record has no recorded T0.
5. Any Variant C link missing the UTM tag (those visits fall outside the split and must be counted as unattributed, not assigned).

## Findings (ranked by impact)

1. **High: The baseline source is unnamed, so the readout has no comparison.**
   Fix: Herald names the exact baseline job and confirms 7-day history before Variant C goes live.

2. **High: Job 280 is described as both the bot filter and the posting job the 10-30 gate decides on.**
   Fix: Confirm job 280's identity and purpose in SERVER JOBS before the spec relies on it as the bot filter.

3. **Medium: T0 is undefined until go-live, so the readout date can drift onto the 10-30 gate.**
   Fix: Write the live timestamp into the go-live record and derive T0+7 from it, never from the gate date.

4. **Medium: Variant C signups may not be split by UTM tag.**
   Fix: Herald confirms the signup job reads the UTM tag; if not, file the job change as a proposal.

5. **Low: The readout could be filed without the human-only rule applied to both windows.**
   Fix: Put the job 280 filter on the readout template so both windows are filtered by default.
