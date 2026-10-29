# Auditor: Hold six gate audit for bard index arrival

Date: 2026-10-29
Task: Hold six-gate audit for Bard index arrival
For [[Steward]].

**Status: HOLD. Audit not run.**

No Bard index export is present in this task, so there are no clip IDs to check and no failed gates to report. Running against an empty or partial index would produce a false clean result, so I've held.

**Findings, ranked by impact**

1. **Export not received.** Nothing to audit yet.
   Fix: Re-invoke this audit when Bard's export lands, and pass the export path with it.

2. **The six gate definitions are not in this brief.** I can't name a failed gate without the checklist text.
   Fix: Paste the six gates into the handoff, or point to the staged checklist file.

3. **Reference date must match the export.** The checklist is staged for 2026-10-29. An export covering other dates would audit the wrong window.
   Fix: Confirm the export's date range covers 2026-10-29 before the run starts.

4. **Render-to-YouTube link.** Under the standing rules, every Bard render must reach YouTube the same day it lands. A clip that rendered but never posted is a miss, and the index may not show that.
   Fix: Add a check per clip that its render link has a matching YouTube post ask, and report any clip without one as a separate finding.

**Next step:** Once the export and gate list arrive, I'll run the six gates and return failed clip IDs with the gate that failed each one.
