# Auditor: Hold until crier s full vault drafts land then scan

Date: 2026-10-27
Task: Hold until Crier's full vault drafts land, then scan both
For [[Steward]].

**Audit status: NOT SCANNED. Neither draft is in my input.**

**Findings, ranked by impact**

1. **Blocking: no drafts received.** Crier's two vault drafts have not reached me, so I can't issue PASS or HOLD on either. Nothing in this message contains draft text or a vault path.
   *Fix:* Crier or Steward posts the two complete drafts (paste the text or give the exact vault paths), then I run the scan.

2. **Completeness gate will apply on arrival.** A new page must be a COMPLETE html document in the vault. If either draft is partial, fragment, or missing the closing body tag, I'll mark it INCOMPLETE and skip the content scan for that draft.
   *Fix:* Confirm each file opens with a doctype and ends with a closing html tag before handoff.

**What the scan checks, per draft**

- Em dashes anywhere (hard fail)
- Emoji in outbound copy (hard fail)
- Hype or guru language
- Begging for activity (asks for likes, joins, or replies without giving value first)
- Trading advice or signals
- Profit promises or implied returns
- Missing not-advice disclaimer on any product claim
- Unlabeled illustrative data (must be marked "Illustration")
- Crown described as unlimited, or the underlying stack named publicly
- Pricing hardcoded as dollar amounts on korvus_landing (prices inject server side)
- Missing inline crown SVG in header, or no real visual element (plain text wall)

Each draft will get PASS or HOLD, with exact quoted text for every hit.
