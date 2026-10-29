# Analyst: Pull all rows with referrer t co from today s

Date: 2026-10-29
Task: Pull all rows with referrer t.co from today's 09:30 analytics digest. List user agent, timestamp, landing path for each. Flag non-browser agents and sub-second 
For [[Corvid]].

**Headline: I can't produce the row-level proof yet. No 09:30 digest or log rows came with this task, so I have nothing to classify.** I won't reconstruct rows from memory or estimate counts.

**What I need to run it**
- The 09:30 analytics digest export, or first-party access-log lines for today filtered to `referrer` containing `t.co`.
- Per row: timestamp (with timezone), user agent, landing path, and ideally client IP hash and any JS-fired pageview or event ID. Without the last one, I can't measure dwell time.

**If the digest doesn't carry those fields, that's the first gap:** referrer and UA are the minimum. Per the infrastructure rules, the fix is to file a request to the desk that owns the analytics digest for a raw export, not to guess at it.

**How I'll classify once the rows land**

*Non-browser agent flags (any match):*
- Empty or missing UA
- Known crawler or preview strings (Twitterbot, facebookexternalhit, Slackbot, Discordbot, LinkedInBot, TelegramBot, Googlebot, bingbot)
- HTTP libraries and headless tools (curl, wget, python-requests, Go-http-client, node-fetch, HeadlessChrome, PhantomJS)
- Any UA that does not include a common browser token (Mozilla, Chrome, Safari, Firefox, Edg)

*Sub-second flag:*
- A t.co row whose session has no follow-up hit (no JS pageview, no second request) within 1 second of the landing timestamp. This is the prefetch signature: the redirect fires, the page loads once, and nothing else happens.
- Same-IP-hash, same-path repeats within 1 second of each other, which point to card or preview crawlers.

**What the test proves**
X counts a click at the redirect. Site analytics usually counts a visit only when JavaScript executes. So some gap is expected even with zero bots. The hypothesis holds if flagged rows (non-browser plus sub-second) account for most of the delta between X's 16 clicks and the 3 visits. If they explain only a small share, prefetch isn't the main cause and the gap is probably in JS load or consent blocking, which would be a separate instrumentation fix.

**Next step:** send the export or log slice to this task and I'll return the classified table (timestamp, UA, path, flags) plus the delta breakdown. This matters for the Korvus signup and Eclipse-X join quotas: if the clicks are mostly crawlers, the real top-of-funnel number is smaller than X shows, and the campaign reporting should use the verified visit count.
