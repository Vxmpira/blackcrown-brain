# Auditor: Verify five x post ids live with full 19 digit

Date: 2026-10-29
Task: Verify five X post IDs live with full 19-digit values
For [[Steward]].

## X Post ID Verification: Not Live-Verified

I could not confirm live status or author handles. This session has no X fetch access, and an ID alone doesn't reveal either. Nothing below is a live result.

| # | Post ID | Digits | Decoded created (UTC, approx.) | Live status | Author handle |
|---|---|---|---|---|---|
| 1 | 2115736627536441693 | 19 | ~2026-10-29 | Unverified | Unverified |
| 2 | 2115736629574869419 | 19 | ~2026-10-29 | Unverified | Unverified |
| 3 | 2115736862782362088 (10-29 #262) | 19 | ~2026-10-29 | Unverified | Unverified |
| 4 | 2115767314846998656 (10-29 #265) | 19 | ~2026-10-29, about 2 hrs after #1 | Unverified | Unverified |
| 5 | 2115767317803991422 (10-29 #266) | 19 | ~2026-10-29, about 2 hrs after #1 | Unverified | Unverified |

## Findings, ranked by impact

1. **Live status and handles are missing.** Nothing here proves a post exists, is public, or belongs to the brand account. Fix: run a live lookup against the X API with the brand account's keys from the server, and record HTTP status, `author_id`, `username`, and `created_at` per ID.
2. **Author handle cannot come from the ID.** Snowflake IDs encode time, not account. Fix: take the handle from the API response's `includes.users`, not from the ID, and compare it to the brand account handle in #blackcrown-links.
3. **Timestamps are consistent with the labels.** The IDs decode to about 2026-10-29, which matches the #262, #265, and #266 labels. Fix: none needed; this supports the batch but does not confirm liveness.
4. **All five IDs are 19 digits.** No truncation this time, so the earlier short-run problem is not repeating. Fix: none needed.

Filing this as a task back to the desk that ran the previous attempt: the live lookup needs to be re-run against all five IDs and returned with the fields above.
