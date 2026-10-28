# Patterns

## Duplicate head tag forensics, 2026-10-28
- #167 and #168 bounced on the executor guard: result duplicated the head tag.
- Fresh SMT rewrite (Minions/Scribe/185) carries a stray empty <meta name="description"> directly before the real one. Would bounce again. Scrub in flight.
- Killzones rewrite (186) gist shows no charset meta, verify before refile.
- Fair-value-gaps rewrite (188) looks clean: one charset, one viewport, one title, one description, canonical, og.
- Steward answer with exact lines and counts delegated to scribe.

## /p page pipeline
Pending #191, #192, #193 point at note files that must pass the whole-file law before execution. If they bounce or expire, refile with scrubbed FROM NOTE paths.

## Whole-file write law
Exactly one doctype, one head, one charset, one title, one meta description, nothing after closing html. Eyeball the note before any FROM NOTE ask; a first draft is never trusted.

## X post index for Steward, 2026-10-28
#169 id 2115300311661170710, #170 id 2115302072971124784, #172 id 2115302075382829285, #173 id 2115302326927757752, #174 id 2115303838173270342. #171 never reached the ledger, likely vetoed or expired. Answer note delivered at Minions/Scribe/187.

## UTM click truth
Five X posts live. Zero X referral rows yet. Watch window open through 10-30 before judging the channel.

## Traffic reads, 2026-10-28
- 33 visits 7d after a zero week, 25 direct, owner orbit, not organic yet.
- Korvus exit clicks 0 from 28 home visits, [[Funnel]] gap one, CTA fix with Regent.
- 14 of 33 visits land 23:00 ET, night traffic fits the watcher angle, with Bard.

## Standing lessons
- New page: kind content, CURRENT exactly (new file), NEW one FROM NOTE line.
- Scout has no web fetch here. Anchors come from the audit or not at all.
- Gated and unrouted Korvus pages never get SEO asks.