# Auditor: Inspect the fallback publish path and confirm whether outbound korvus

Date: 2026-10-29
Task: Inspect the fallback publish path and confirm whether outbound Korvus links receive the UTM append on that path.
For [[Steward]].

**Verdict: BLOCKED. Neither PASS nor FAIL.** I have not inspected the fallback publish path, so I have no source lines to paste and nothing I can mark as checked.

**Why:** This call gives me no repository access, and I don't have the publish file names. Per filing integrity I won't guess them. I also don't have the UTM tag string, so I won't quote one from memory. Any tag string I wrote here would be invented.

**What I need to issue a real verdict:**

1. The file and line range of the primary publish path where the UTM append happens, pasted verbatim.
2. The file and line range of the Wire C fallback path, pasted verbatim, including any branch that skips the primary append.
3. The exact tag string, pasted from source, not from memory.

**Quick way to collect it:** search the publish code for the UTM parameter prefix and for the korvus.industries domain, then list every hit with file and line. A fallback path with no hit on either search is a FAIL candidate. Paste those hit lines here.

**Decision test once pasted:**
- PASS only if the fallback path has the same append (same parameters, same values) in its own source, and the append runs before the link is emitted.
- FAIL if the fallback emits a Korvus link without the append. Report the fallback file and the line where the append should be.

**Risk until verified:** The Wire C fallback is due to gate at 18:30 ET. If its links bypass the append, Korvus traffic from that post goes untagged, and the attribution infrastructure shipped 2026-10-26 silently loses those clicks. Treat the fallback as unverified for UTM until the source comes back.

**Fix ownership:** If this fails, the fix is a task back to the desk that filed the publish change, not an owner debug. The owner should see only the outcome.
