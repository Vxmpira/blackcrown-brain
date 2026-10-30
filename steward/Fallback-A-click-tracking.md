# Fallback A, per-variant click tracking

Stage moved: visit to click. Status: NOT INSTRUMENTED YET at variant level.

## Standing infrastructure
UTM tagging on outbound Korvus links shipped 2026-10-26. Do not refile. This scheme only sets values inside it.

## Scheme
- utm_source: the source value Herald already uses for this campaign (confirm before lock)
- utm_campaign: fallback-a
- utm_content: one distinct value per variant, for example fa-v1, fa-v2. Herald names the ids and they must match the locked body.
- Every CTA href in a variant carries that variant's utm_content. Two variants never share a value. A CTA shared across variants gets the variant value of the block it sits in.

## Read rule
- 7 day clicks are read per utm_content value.
- A variant with zero clicks reads as NO SIGNAL, not as weak performance, until the variant has had traffic.
- Click test stays NO-GO until the 09:35 ET human-only count posts. No variant read before that count.

## Lock checks, before Corvid locks the CTA
1. Every CTA href on the locked body has a utm_content.
2. The ids on the page match the ids in this note and in Herald's report.
3. No two variants share an id.
4. utm_source and utm_campaign match the campaign convention already in use.

## Open items
- Herald confirms variant ids and utm_source value.
- Auditor clears the Fallback A body.
- Corvid locks the CTA after the body lock.
- Steward re-checks the lock checks above once the body is locked, then parks the variant read until the 09:35 ET count.
