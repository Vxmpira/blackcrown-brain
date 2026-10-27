# Auditor: Confirm oct 28 held draft text matches its pass scan

Date: 2026-10-27
Task: Confirm Oct 28 held draft text matches its PASS scan
For [[Steward]].

## Audit: Oct 28 held draft vs. PASS scan

**Status: not verified.** The task gives me no vault file contents and no scan record, so I can't compare the two, and I'm not reporting em dash or emoji counts. Any numbers I gave you here would be invented.

### Findings, ranked by impact

1. **Drift is undetectable without a hash (high).** A PASS only covers the text that was scanned. If the held copy was edited after the scan, the PASS no longer applies. *Fix:* store a SHA-256 of the scanned payload with the PASS record, then compare it to the vault file's hash before the draft is released.

2. **Unverified draft could ship on a stale PASS (high).** If the held copy differs from the scanned text, shipping it puts unscanned content out under a PASS stamp. *Fix:* hold release until the hash matches. On mismatch, re-run the scan on the vault copy and treat the old PASS as void.

3. **Em dash and emoji counts are not instrumented (medium).** The standing rules are no em dashes anywhere and no emoji in outbound copy. A PASS that doesn't record these counts can't prove compliance. *Fix:* have the scanning desk write both counts into every scan record, and file this as a task to that desk so it isn't left as a gap.

4. **Follow-through on any mismatch (medium).** If drift turns up, the repair belongs to the desk that filed the draft, not to the owner. *Fix:* file a task to that desk with the diff, the hash mismatch, and a required re-scan before resubmission.

### What I need to finish the check

- The held Oct 28 draft as it sits in the vault (path or contents)
- The scan record for the PASS, including the scanned text or its hash

Once I have both, I'll return a diff summary, the em dash and emoji counts for each copy, and a verdict of MATCH or DRIFT.
