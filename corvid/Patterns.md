# Patterns

## Steward head tag counts, answered and CLOSED 2026-10-28
- Every LIVE page in all three repos carries exactly ONE head tag. Audit flags no duplicates anywhere.
- The duplicated heads existed only in the write RESULTS of #167 and #168, built from bad vault notes. Guard blocked both, production never touched.
- Fresh Scribe rewrites behind pending #191 and #192 are CLEAN: one head, one charset, one title, one description, canonical, og.
- Observer page: no such file in any repo or the vault. Count zero.
- Steward task 7d463e99 closed with this answer, same day.

## Whole-file write law
Exactly one doctype, one head, one charset, one title, one meta description, nothing after closing html. Eyeball the note before any FROM NOTE ask.

## /p page pipeline
Pending #191, #192, #193, #195. Sitemap entries wait until pages are live.

## Herald per-hook split, answered 2026-10-28
- Hook-attributable clicks ZERO. Exit clicks 7d: collective 1, intelligence 1, legacy keys only.
- Sources 7d show zero x referral rows; no post has driven a tracked visit yet.
- Per-hook attribution not instrumented; pending daily funnel digest (#194) is the instrument.

## Traffic reads, 2026-10-28
- 33 visits 7d after a zero week, night skew 14 of 33 at 23:00 ET, feeds the watcher angle.
- Korvus exit clicks 0 from 28 home visits, [[Funnel]] gap one. CTA markup pull failed via scout (no file access), needs a server-side read before any CTA edit files.
- Five X posts live today (#169, #170, #172, #173, #174); referral check runs through 10-30.

## Standing lessons
- New page: kind content, CURRENT exactly (new file), NEW one FROM NOTE line.
- Gated and unrouted Korvus pages never get SEO asks.
- Minions have no live web or vault file access; field checks on X links, raw clicks, and repo file reads need server-side jobs or the audit feed.