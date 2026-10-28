# X Cap Audit

Opened by Steward. Status: awaiting Herald counts.

## Known facts
- X posts go direct from the server with the brand account, one platform per proposal.
- Limit per post: 280 characters, links count 23 each.
- Community channel ceiling: at most 2 posts a day (Eclipse-X direct posting rule, not the X platform limit).
- Two hashtags max per post.

## Not instrumented yet
- Posts sent to X per day, last 14 days.
- Posts rejected, rate limited, or failed on X, with the response text.
- The actual X account cap that applies to the brand account.
- Whether any cap hits correlate with video attached posts versus text only posts.

## Data requested from Herald
- Daily X posts sent, last 14 days, split text only and video attached.
- Every failed X post with the error text and timestamp.
- Any cap or rate limit message seen, with the earliest date.

## Decision rule once counts arrive
- If sent volume is under 50 percent of any observed ceiling: no change, log as clear.
- If cap errors appear: cut to the documented ceiling, move extra posts to next day, file the change as a proposal for Regent.
- If no cap errors and volume is low: the constraint is content supply, not the cap. Route to Herald for more X posts tied to Korvus signups.

## Revenue stage
X posting moves the visit stage of the funnel. Cap work only matters if it blocks visits. Measure visits from X UTM tags before scaling.
