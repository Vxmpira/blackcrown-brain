# Scout: Pull every korvus link on brand home index html exact

Date: 2026-10-29
Task: Pull every Korvus link on brand home index.html: exact href, exact surrounding anchor markup, and final landing destination for each
For [[Corvid]].

**Finding: I could not pull the Korvus links on index.html because the file contents were not included in this task.**

- **Evidence:**
  - The task gives me no index.html source, and I have no live fetch or repo access in this context.
  - Anything I listed as hrefs or anchor blocks would be invented, which would fail Regent preflight and waste the owner's time.
  - The institutional memory confirms the file is live and static, so every Korvus link on it is a real production link as soon as a push lands on main.

- **What the extraction needs:** the full text of blackcrownvxj.com/index.html at the current commit. With that, for each Korvus reference I would report:
  1. The exact href value, copied verbatim.
  2. The full enclosing anchor or button block, copied verbatim, so it can serve as a CURRENT anchor.
  3. The final destination after redirects. Plain hrefs can be resolved from the text. Any href pointing at another brand page needs a follow-up check of that page's own Korvus links.
  4. UTM status, recorded as present or absent for information only. Per the standing rule, absent UTM is not the leak unless a Korvus link truly carries none.

- **Search pattern for the desk that holds the file:** match `korvus` case-insensitively in href attributes and in visible text, and also match `signup`, `login`, `terminal`, and `upgrade`. Those paths are gated or intermediate and are the likely leak points.

**Recommended moves**

1. **Supply the file.** Have the executor or the desk that filed this task attach the current index.html text. Scout will return the link table in the format above, with no paraphrasing of the blocks.
2. **Check intermediate pages next.** If a Korvus CTA points at a brand page such as proof.html or another root html file, record that page too, since every root html file in the repo is live and its own Korvus links are part of the leak surface.
3. **Hold the fix proposal until the table exists.** The proposal's CURRENT blocks should come from that verbatim extraction, not from memory, so the preflight anchors match. Destination should be korvus.industries, with the existing UTM tagging carried through and not refiled.
