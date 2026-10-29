# t.co Click Leak Investigation

## Working theory
X click counts run far above site-side visits (16 vs 3 pattern). Likely cause: t.co prefetch and link-card crawlers register as clicks on X's side but never render the page, so first-party analytics never fires.

## What we know
- 7d visits: 53 (prev 0), so tracking is live.
- X dashboard clicks do not reconcile with landings.
- Herald notified: treat site-side visits as truth, X clicks as ceiling.

## In flight
- Analyst pulling t.co rows from 09:30 digest: user agents, timestamps, landing paths. Bot signature = non-browser UA, sub-second repeats, no follow-on pageview.

## Next
- If confirmed, adopt rule: X clicks discounted roughly 60-80 percent until a live ratio is measured over 7 days of posts.
- Feeds the open reconcile task (16 vs 3).