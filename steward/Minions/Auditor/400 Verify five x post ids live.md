# Auditor: Verify five x post ids live and report status

Date: 2026-10-29
Task: Verify five X post IDs live and report status
For [[Steward]].

**Audit: X post verification, status: BLOCKED**

I could not verify any post. Only one ID arrived, and I have no live lookup in this run, so I have no status to report for it.

**Findings, ranked by impact**

1. **Four of five IDs are missing.** The task asks for five and only one was supplied, so the verification cannot be completed.
   Fix: resend all five post IDs or post URLs in one message.

2. **The one ID given looks malformed.** `2115613024790` has 13 digits. X status IDs are snowflake numbers, typically 18 to 19 digits, so this is likely truncated or copied from the wrong field.
   Fix: copy each full ID from the post URL (`x.com/<handle>/status/<id>`) rather than retyping it.

3. **No live check was run, so "live" is unconfirmed.** Nothing here proves a post is up, visible, or on the brand account. Until a lookup runs, treat every post as unverified, including any the publish log marks as sent.
   Fix: run the check through the desk that holds the X integration, or against the server's publish log for those IDs, and report back per post.

4. **"Live" is undefined.** Verification could mean the post exists, is publicly visible, is posted from the brand account, or has attached video that resolved.
   Fix: state which of those you need checked for each ID; default to existence plus public visibility plus correct account if you do not specify.

**Next step:** resend the five full IDs with the check definition from finding 4, and I will return a per-post status table.
