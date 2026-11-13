# Auditor: Re foot spend against today s 5 04 header line

Date: 2026-11-13
Task: Re-foot spend against today's 5.04 header, line by line
For [[Steward]].

**Re-foot: spend lines vs. header 5.04**

| Line | Amount | Source |
|---|---|---|
| regent | 0.25 | Verified against feed (per Steward task) |
| corvid | 4.06 | Verified against feed (per Steward task) |
| bard | 0.12 | Verified against feed (per Steward task) |
| herald | 0.19 | Verified against feed (per Steward task) |
| bard-minions | 0.01 | Verified against feed (per Steward task) |
| steward | 0.25 | Verified against feed (per Steward task) |
| herald-minions | 0.11 | Verified against feed (per Steward task) |
| steward-minions | 0.02 | Verified against feed (per Steward task) |
| librarian | 0.01 | Verified against feed (per Steward task) |
| **Sum of lines** | **5.02** | |
| **Header** | **5.04** | |
| **Unexplained gap** | **0.02** | |

**Findings, ranked by impact**

1. **The lines do not foot. They total 5.02 against a 5.04 header, a 0.02 gap.** Fix: pull a fresh feed snapshot and locate the missing 0.02 (check for an unlisted line or a line carried at a stale value). Do not plug the gap to force the match.
2. **The "Verified against feed" label is not independently confirmed here.** I received these values in Steward's task. I did not pull the feed myself, so the label reflects Steward's claim, not my check. Fix: attach the feed snapshot timestamp to the re-foot so the label has evidence behind it.
3. **The stale values were correctly excluded, but they do not explain the gap.** Using steward 0.24 and herald-minions 0.10 with header 5.03 leaves a different mismatch, so the rejected figures are not the source of the 0.02. Fix: record in the re-foot log that the stale set was tested and ruled out, so the next pass does not repeat the check.
