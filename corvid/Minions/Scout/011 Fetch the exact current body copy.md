# Scout: Fetch the exact current body copy of the korvus news

Date: 2026-10-25
Task: Fetch the exact current body copy of the Korvus news terminal page, the main hero or intro block as it exists right now, verbatim, plus the exact repo file path
For [[Corvid]].

# Scout Report: Korvus News Terminal Page Body Copy Fetch

**One-line finding:** Cannot complete as asked. I have no repo access, no crawl data, and no page source was provided in this task, so I cannot return verbatim current copy or a file path without fabricating it.

## Evidence

- No page source, repo snapshot, or crawl export was attached to this task. The context block only references "head tag proposal 37" as pending, it does not include the page content itself.
- I have no live fetch capability in this session. Anything I produced as "verbatim" body copy would be invented, which is exactly the wrong input for a content swap anchor. A fabricated anchor would cause the swap to silently fail or, worse, match the wrong block.
- Same problem for the file path. I could guess a plausible structure (something like a `pages/` or `src/content/` path for a terminal product page), but that is general-knowledge reasoning, not grounded data, and a swap filing needs the exact path.

## Recommended moves

1. **Re-dispatch this task with the raw input attached.** Corvid should include either (a) a repo file listing plus the candidate file contents, or (b) a fresh crawl/HTML dump of the Korvus news terminal page. With that in hand I can extract and return the main hero/intro block verbatim with the confirmed path.
2. **Pull the anchor from the same source proposal 37 used.** Since a head tag proposal is already pending against this page, whoever filed it had an exact file reference. Reusing that reference guarantees the body swap and head swap target the same file revision and avoids a split-source conflict.
3. **Request content at a pinned commit, not just "current."** Ask for the file at a specific commit hash so the swap anchor stays valid even if the page changes between filing and merge.

Flagging clearly: no claims above are drawn from provided data, because none was provided. That gap is the finding.
