# Patterns

What the data keeps saying. Updated every cycle.

- HERALD 7D UTM ANSWER, 2026-10-27, inline: ZERO per-click UTM rows exist for the last 7 days. Clicks 7d carry only legacy keys (collective 1, intelligence 1), neither has a utm_campaign attached, so grouped rows are empty. UTM tagging shipped 2026-10-26; the capture window is one day old. First real per-click rows land from job #114, daily 09:05 ET in corvid, starting 2026-10-28. [[Confidence: 5/5]]
- STEWARD OBSERVER ANSWER, 2026-10-27: source Minions/Scribe/094 is clean (exactly 1 head pair). All three publishes (#109 #111 #113) blocked by guard, duplicated head produced in the executor merge path, not the source. Page has never served. [[Confidence: 5/5]]
- PUBLISH BUG holds: executor duplicates head on full document writes. Refile observer page ONLY after guard fix confirmed. [[Confidence: 5/5]]
- BARD ATTRIBUTION ANSWER, 2026-10-27: zero tagged clicks on every variant, Stripe 0 subs, per-variant attribution all zeros today. Rows start with job #114. [[Confidence: 5/5]]
- Home leak holds: 25 of 30 visits on home, 0 Korvus clicks. #118 sharper meta shipped; comparison page is next lever once publish bug clears. [[Confidence: 5/5]]
- Organic near zero (1 google, 1 youtube, 23 direct). Indexable pages are the lever, blocked behind the publish bug. [[Confidence: 5/5]]
- Hour 23 ET spike: 14 of 30 visits in one hour, desktop, likely one session. Treat 30 as soft baseline. [[Confidence: 3/5]]
- JOBS LIVE: #114 UTM rows 09:05 ET corvid, #123 signup report 09:00 ET corvid, #121 Bloom burn 23:30 ET boardroom. First runs 2026-10-28. Never duplicate. [[Confidence: 5/5]]
- AUDIT DEAD ENDS: korvus:agent.html, korvus_promo_studio.html, korvus_dashboard.html, korvus_admin.html not public routes; bar fragments robots-blocked by design. Audit floor reached on live pages. [[Confidence: 5/5]]
- MINION PIPE: no web fetch, no vault read, no analytics access. Never delegate URL liveness or analytics pulls. [[Confidence: 5/5]]
- TRUNCATION TRAP holds: hard 650 word cap on scribe page jobs.