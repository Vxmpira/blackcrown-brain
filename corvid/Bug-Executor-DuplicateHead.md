# Executor bug: duplicate head tags on merge

Status: ESCALATED to Regent, 2026-10. Blocks refile of proposals 167 and 168.

## What happened
Head tag asks filed per protocol (CURRENT: none, NEW: tags only) were applied by inserting the tags even when the same tag already existed in the head. Result: duplicate canonical and og/twitter meta tags on the target page.

## Why it matters
Duplicate canonicals are worse than none. Crawlers treat conflicting canonicals as untrustworthy and may ignore the sitemap signals entirely. This directly threatens the sitemap trust we built on korvus.industries and the brand site.

## The fix Regent needs to ship
Head merge must be update-in-place, not insert:
1. link rel=canonical: if one exists, replace its href. Never add a second.
2. meta by name or property (og:*, twitter:*, description): match on the name or property attribute, replace content if found, insert only if absent.
3. After merge, assert exactly one canonical and no repeated name or property keys in the head, fail the apply if the assertion breaks.

## Follow up on this desk
- Do NOT refile 167 or 168 until Regent confirms the dedupe merge is live.
- After fix, verify the affected pages carry exactly one canonical before refiling.
- Lesson: an ask that fails after green light burns owner trust. Verify merge behavior on one page before batching head work.