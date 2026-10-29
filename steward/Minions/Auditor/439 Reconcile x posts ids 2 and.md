# Auditor: Reconcile x posts ids 2 and 3 against ledger text

Date: 2026-10-29
Task: Reconcile X posts IDs 2 and 3 against ledger text
For [[Steward]].

## Reconciliation status: NOT RECONCILED

I have no access to the 10-29 ledger, the approved proposal text, or the live X post data. The task context includes only the two IDs, so I cannot report a match or mismatch for either post. Brand X should stay closed.

## Findings, ranked by impact

1. **Blocking: no source data to compare.** Nothing here confirms what was approved or what went live.
   Fix: paste the ledger entries for both IDs (approved text, proposal ID, approval timestamp) and the live posted text with `created_at` from X, or grant read access to both.

2. **High: possible double publish.** The two IDs differ by about 2.96 billion. X IDs are snowflake-style, where the timestamp sits in the high bits, so that gap works out to roughly 0.7 seconds of creation time. Two posts that close together may be one approved post sent twice, or two different posts fired at once. This is an inference from the ID math and needs confirmation against `created_at`.
   Fix: check whether both posts are the same text, and if so, file a task to the posting desk to find which trigger fired twice before X reopens.

3. **Medium: standards check on each post.** A mismatch on the live brand account costs trust, so the diff should cover more than word-for-word text:
   - Character count at or under 280, with links counted at 23 each
   - Two hashtags maximum
   - No em dashes and no emoji
   - Not-advice disclaimer present on any product claim
   - UTM tagging intact on Korvus links
   Fix: run this checklist on both posts alongside the text diff and record pass or fail per item.

4. **Process: ownership of any miss.** If either post mismatches, the fix belongs to the desk that filed the post, not to the owner.
   Fix: on any mismatch, file a fix task to the posting desk with both texts and both IDs attached; surface to the owner only if the direction itself is in question.

## Report format once data arrives

For each ID: approved text, posted text, match or mismatch, `approved_at` and `created_at` timestamps, time gap, checklist result. Then one line on whether X can reopen.
