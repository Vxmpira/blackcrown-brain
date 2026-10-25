# Site-Audit

Current audit standing, worst first. Target: every page at 100. Updated 2026-10-25.

## blackcrownvxj.com (DOWN at last check, 10s timeout)
- [[proof.html]] 74: short title, short meta (filed #10), no og:image (waits on asset), missing from sitemap (filed #11)
- disclaimer.html 83: short title, no og:title, no og:image
- support.html 83: short title, no og:title, no og:image
- privacy.html 87: no og:title, no og:image
- [[collective.html]] 91 after #9: body expansion package ready in Minions
- sitemap.xml: six entries added via #6, proof.html still missing

## korvus.industries (up, 170ms)
- 82: title 74 chars, meta 186 chars. Blocked on exact repo path, see [[Patterns]]

## blackcrown-intelligence.com (up, 185ms)
- 82: meta 213 chars, no og:image. Same repo path blocker

## Cross cutting
- og:image asset approved, not built. Once built, batch apply to every page, closes the biggest shared gap.
- Proven edit method: CURRENT none, full tags in NEW, Regent merges.

Links: [[Patterns]], [[Strategy]], [[Funnel]].