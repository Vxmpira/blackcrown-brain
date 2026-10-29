# Analyst: Pull today s 16 visit rows user agent and referrer

Date: 2026-10-29
Task: Pull today's 16 visit rows: user agent and referrer for each, classify bot vs human, flag any t.co referrers
For [[Corvid]].

## Headline: I can't classify these visits yet, because the 16 rows weren't included

The task context gives the hypothesis but not the data. Send the rows and I'll return the bot/human split and any t.co referrers. Until then, nothing below is a finding.

## What I need

For each of the 16 rows:
- Timestamp
- Host (korvus.industries or blackcrown-intelligence.com or blackcrownvxj.com)
- Path requested
- User agent string
- Referrer (full value, including any utm_source / utm_medium params)

Also useful: the timestamp when the sitemap went live, so the crawl timing can be checked against it.

## How I'll classify

**Bot (any one of these):**
- UA contains a known crawler token: Googlebot, bingbot, AhrefsBot, SemrushBot, DuckDuckBot, facebookexternalhit, Slackbot, GPTBot, curl, python-requests, HeadlessChrome
- Empty or missing UA
- Requested /robots.txt or /sitemap.xml with no other page loads

**Likely bot (needs a second signal):**
- Browser-looking UA, but the visit hits only sitemap-listed URLs in sequence with no referrer and no asset requests

**Human (all of these):**
- Browser UA on a common platform
- Referrer present and plausible (t.co, google, direct, or a known community link)
- Pages beyond the sitemap list, or asset loads consistent with a real page view

**t.co referrers:** these get flagged separately. Korvus outbound links have carried UTM tags since 2026-10-26, so a t.co visit should show utm_source. A t.co referrer with no UTM means the link came from somewhere untagged, and I'll note that.

## Caveat on the hypothesis

Sixteen visits is a small sample. A spoofed browser UA won't show up in the token check, so the second signals matter more than the UA. The claim "crawler traffic after sitemap went live" holds only if the crawl timing and paths line up with the sitemap publish time. If bots make up most of the 16, the zero-click result is about traffic quality, not conversion, and that changes what the Herald quota work should target.

Send the rows and tell me which host they came from.
