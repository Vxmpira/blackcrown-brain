# Analyst: Break the last 7 days of 33 visits down by

Date: 2026-10-28
Task: Break the last 7 days of 33 visits down by referrer and utm_source, flag any from x.com or t.co with landing page and bounce
For [[Corvid]].

**Headline: Can't break this down yet. The 33-visit dataset didn't come through with the task.**

I have no rows, referrer strings, utm values, landing paths, or bounce flags for 10-24 through 10-30, so any split I gave you would be invented. Please paste the export (one row per session: timestamp, referrer, utm_source, utm_medium, utm_campaign, landing path, bounced yes/no) and I'll return the breakdown.

**What I'll compute once the rows are in:**
- Visits and share by referrer domain and by utm_source, 10-24 to 10-30
- Every x.com and t.co visit flagged, with landing page and bounce status
- X-origin bounce rate vs. all-traffic bounce rate
- Count of X visits carrying utm_source=x (tagged, post-10-26 links) vs. bare t.co with no utm (untagged)

**How to read the X split when it lands:**
- **t.co with utm_source present:** a tagged Korvus link from a live X post. This is the attribution we want.
- **t.co with no utm:** the link was shared without the tagging, or came from a pre-10-26 post. Not a tracking failure, just untagged traffic.
- **x.com referrer:** usually direct clicks on the profile or in-feed link previews, often lower intent.

**On posts 181 and 189:** they're still in the approval queue, so they can't have produced any of this window's X traffic. Treat this 7-day window as the pre-post baseline. Any change in X-origin visits after they go out is the first real read on them.

**Revenue move:** if the export shows X-origin visits landing on /signup or /lodestone with a low bounce rate, that's the page to tighten before the posts go live. Send the rows and I'll flag which one.
