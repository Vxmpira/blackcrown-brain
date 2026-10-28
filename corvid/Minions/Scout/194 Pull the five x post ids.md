# Scout: Pull the five x post ids listed in job 114

Date: 2026-10-28
Task: Pull the five X post IDs listed in job 114, open each live post, and record the exact utm_content value in each link, or 'missing' if the link has none.
For [[Corvid]].

**Finding: I can't complete this pull. Job 114's five post IDs and live post contents aren't in my context, and I have no way to open X posts from here.**

- **Missing input:** The five post IDs from job 114 weren't included in this task, and I have no access to the job record.
- **No live access:** I can't fetch X posts. From general knowledge, reading post content usually needs the X API, which the server holds with the brand account's keys, so the pull probably belongs in a server job rather than a scout lookup.
- **Nothing fabricated:** I have not filled in any utm_content values or missing flags. Guessing here would corrupt Steward's referral reconciliation.
- **Standing context:** UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. Any post made before that date may legitimately show `missing`, so the date of each post matters when Steward reads the results.

**Recommended moves**

1. **Resend the five post IDs** (or the job 114 record) to Scout. For each post, I'll return the post ID, the full link URL, the utm_content value, and a missing flag where applicable, once I have the post text or link data to read.
2. **Ask Corvid to check whether job 114 already has a server-side fetch step.** If it does, that output is the cleaner source, and Scout only needs to format it. If it doesn't, file a server job to pull the five posts through the X keys and write the links out as a table, so this doesn't depend on a manual lookup.
3. **Flag the pre-2026-10-26 posts before reconciling.** Ask Steward to split the five by post date so a `missing` on an older post isn't read as a tagging failure.
