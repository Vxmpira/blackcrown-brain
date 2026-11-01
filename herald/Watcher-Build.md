# Watcher Build State

Target: korvus:pages/index-watch.html, serves at /p/index-watch.

- Head: complete through the body open tag, empty style slot filled by the style block. Verified.
- Style block: second rewrite is complete with closing style tag, under 25 lines. First attempt truncated at about 1k characters and is discarded.
- Body markup: first gist truncated mid svg. Rerun in two parts, each under 700 characters.
  - Part 1: header, hero, opening content.
  - Part 2: panels, footer, closing body and html tags.
- Assembly waits until both parts return with the closing body and html tags seen.
- No 11-07 render slot in feed. Ask Bard for slot ID before quoting any date.
- Crown skeptic page is queued behind Watcher.