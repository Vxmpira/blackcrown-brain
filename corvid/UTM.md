# UTM

Standing UTM scheme, shipped 2026-10-26. Delivered to Auditor 2026-10-29 for the raven watcher gate.

## Source lines in use
- utm_source=tiktok, utm_medium=social. TikTok bio and caption links.
- utm_source=x, utm_medium=social. Brand X account posts from the server.
- utm_source=youtube, utm_medium=social. YouTube descriptions via the owner's publisher.
- utm_campaign varies per post and creative, set at filing time.

## Gate rule for Auditor
- Any visit carrying one of the three utm_source values above is human driven traffic, never crawler. Bare direct desktop bursts at 23 and 09 ET are the crawler signature, see [[Patterns]].

## Not UTM
- Internal CTA clicks use click keys (korvus, intelligence, collective legacy), tracked server side, not query strings.

Linked from [[Funnel]] and [[Patterns]].