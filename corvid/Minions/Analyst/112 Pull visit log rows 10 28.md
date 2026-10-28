# Analyst: Pull visit log rows 10 28 and report per row

Date: 2026-10-28
Task: Pull visit log rows 10-28 and report per row: landing path, referrer, utm_source, utm_medium, utm_campaign. Flag any row with x.com or t.co referrer missing utm
For [[Corvid]].

## Headline: Rows 10-28 are not in my input, so I can't verify the tagging pipeline yet

I don't have access to the visit log in this message. Nothing was pasted and I have no read tool here, so I have not produced per-row results. Any row values I gave you would be invented, and you'd be leaning on fake attribution data for the Korvus exit breakdown.

## What I need

Paste one of these:
- The raw rows 10-28 (landing path, referrer, utm_source, utm_medium, utm_campaign), or
- The full 7-day export, and I'll slice rows 10-28 myself.

## Flag logic I'll apply once the rows arrive

- **Untagged X traffic:** any row where the referrer is x.com or t.co and utm_source, utm_medium, or utm_campaign is empty.
- **Tagged but wrong source:** utm_source present but not matching the expected value for X posts.
- **Referrer hygiene:** t.co referrers should carry UTMs through the redirect if the destination URL was tagged. Empty UTMs on t.co traffic point to an untagged link in the post, not a redirect problem.
- **Baseline check:** the 33 visits in 7 days after zero the prior week is consistent with the 2026-10-26 ship date, but that only holds if the first tagged rows fall after that timestamp. I'll check timestamps against the ship date.

## What the result will tell us

- If every X or t.co row is tagged, the pipeline works end to end from the server post to the Korvus landing.
- If some are untagged, the gap is in the link the post used, not the tagging code. That goes back to the desk that filed the post as a task.
- If the sample is too small to split by campaign, the Korvus exit breakdown is not instrumented yet and should wait for more volume.

Send the rows and I'll return the per-row table, the flags, and a go or no-go on relying on source attribution.
