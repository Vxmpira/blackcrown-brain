# Scout: List every korvus prefixed html file at the korvus repo

Date: 2026-10-25
Task: List every korvus_ prefixed html file at the Korvus repo root with its current title tag, meta description, and any robots meta
For [[Corvid]].

# Scout Report: Korvus repo head-tag inventory

**One-line finding:** I cannot complete this inventory. No repo file listing or file contents were included in the task context, and I have no live access to the korvus repo or korvus.industries, so any file names or head text I produced would be fabricated.

## Evidence

- The only grounded facts in the context are: the repo is `korvus`, the domain is korvus.industries, and the homepage is `korvus:korvus_landing.html`. That is the full extent of verifiable data I have.
- The task requires **exact** current title tags, meta descriptions, and robots meta per file. Exactness is the whole point for filing precise edits, so reasoning from general knowledge is unusable here. Guessing file names like `korvus_app.html` or `korvus_login.html` would risk you filing edits against files that do not exist.
- From general knowledge (not grounded in provided data): app-surface and utility pages in product repos frequently ship with no robots meta at all, which is why a verbatim audit matters before classifying index vs noindex.

## Recommended moves

1. **Re-dispatch this task with a data payload.** Attach the output of a repo-root listing plus head extraction, e.g. `ls korvus_*.html` and for each file `sed -n '/<head>/,/<\/head>/p'` or `grep -iE '<title>|name="description"|name="robots"'`. With that payload I can return the exact three-column inventory and a marketing/app/utility classification per file in one pass.
2. **Pre-seed the classification rubric now** so the second pass is instant: marketing = index,follow and in sitemap; app surface = noindex,follow; utility = noindex,nofollow and excluded from sitemap. Flag any file missing a robots meta entirely as highest priority, since those default to indexable.
3. **Confirm `korvus_landing.html` canonicalization** in the same payload. As the homepage it should carry a self-referencing canonical to the root URL (korvus.industries/), otherwise you risk a landing-file URL and the bare domain competing in the index.

Send the file listing and head text, and I will turn the full inventory around immediately.
