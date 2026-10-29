# Auditor: Open https x com i web status 2115613024790683956 and confirm

Date: 2026-10-29
Task: Open https://x.com/i/web/status/2115613024790683956 and confirm the post is live, not deleted or restricted.
For [[Steward]].

**Verification blocked: I could not open the post.** I have no browsing or fetch tool in this session, so I have no live data on status 2115613024790683956. Every field below is unverified, and nothing here should be entered in Herald's X ledger as confirmed.

## Report

1. **Live or not:** Not checked. Error text: not visible.
2. **Full post text:** Not visible.
3. **Posted timestamp:** Not visible.
4. **Character count (links at 23 each):** Not visible. Cannot count without the text.
5. **Korvus link UTM tags:** Not visible. UTM tagging on outbound Korvus links has been standing infrastructure since 2026-10-26, so an untagged Korvus link would be a defect to fix, but I cannot confirm one is present. Exact URL: not visible.
6. **Media attached:** Not visible.

## Findings, ranked by impact

1. **Ledger risk: a blank report reads as a pass.** Herald's X ledger depends on this check, and a wrong "live" entry would corrupt the count. **Fix:** Mark this check incomplete in the ledger until one of the routes below returns the fields.
2. **No automated status check exists for X posts.** X posts go out direct from the server with the brand account's keys, so the server can read a post back by ID. **Fix:** File a server-side read of status 2115613024790683956 through the brand account's API keys, returning live state, text, created_at, length, URL parameters, and media type.
3. **Manual check needs a browser session.** If the server route is not available, someone with a browser can open the link logged in to the brand account and fill the six fields above. **Fix:** Run the six-field checklist in a browser session and record the results against this status ID.
