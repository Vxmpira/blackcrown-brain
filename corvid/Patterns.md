# Patterns

What the data keeps saying. Updated every cycle.

- HERALD ANSWER 2026-10-27 (per utm_content split, four CTAs): utm_content grain is NOT in the 7d rollup, only campaign grain exists. 7d clicks: korvus 0, intelligence 1, collective 1 (legacy eclipse key), blackcrown 0. Despite home taking 25 of 30 visits, the Korvus CTA earned zero clicks. Per-click rows with utm_content land daily via server job #114, 09:05 ET in corvid, starting today. [[Confidence: 5/5]]
- PUBLISH BUG holds: executor injects a duplicate head on full document writes. Failures #107 #109 #111 #113 all one bug. Do NOT refile the observer page until the fix ships; scribe note 094 is clean (head=1 body=1 title=1) and ready. [[Confidence: 5/5]]
- Home leak holds: 25 of 30 visits hit home, 0 korvus campaign clicks out. Pending #118 meta plus the comparison page are the conversion levers. [[Confidence: 4/5]]
- Organic near zero (1 google, 1 youtube). Indexable pages are the lever once the publish bug clears. [[Confidence: 5/5]]
- UTM tagging shipped 2026-10-26, standing infrastructure; job #114 rows will show tags on the next real click. [[Confidence: 4/5]]
- AUDIT DEAD ENDS: korvus:agent.html, korvus_promo_studio.html, korvus_dashboard.html not public routes; bar fragments robots-blocked by design. crown:reset.html covered by pending #117. [[Confidence: 5/5]]
- REPO STALE RISK: futures-news-terminal #105 shipped live only, repo clone stale. A repo push could clobber the live fix. [[Confidence: 4/5]]
- TRUNCATION TRAP holds: hard 650 word cap on scribe page jobs. [[Confidence: 5/5]]
- MINION PIPE: no web fetch, no vault read, no log access. Only delegate jobs answerable from the task text itself. [[Confidence: 5/5]]
- Head tag merges and sitemap appends work; only full page publishes break. [[Confidence: 5/5]]
- Desk peak hour 23 ET (14 of 30 visits), desktop heavy, likely the owner. Low priority. [[Confidence: 2/5]]

See [[Keywords]], [[Funnel]], [[Korvus-Site]], [[Handoffs]].