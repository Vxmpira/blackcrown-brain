# Scout: Read index html on the brand site server and return

Date: 2026-10-28
Task: Read index.html on the brand site server and return the exact hero CTA markup verbatim: the heading, subline, and every CTA button or link element with full hre
For [[Corvid]].

**Finding: I can't return the hero CTA markup because no index.html content was provided to me, and I have no file read access in this session.** Anything I wrote here would be invented, so I'm not producing it.

- The brief says blackcrownvxj.com is static and index.html in its repo is the live homepage. Nothing in this task includes that file's contents.
- The request requires verbatim HTML: heading, subline, and every CTA element with its full href. A paraphrase or reconstruction would break the anchor purpose of the request.
- Reasoning from general knowledge only: a proposal that targets a CTA block should match the live markup exactly, so the anchor has to come from the file itself, not from memory or a guess.

**Recommended moves**

1. **Get the raw block.** Whoever has read access to the blackcrownvxj.com repo (or a desk with file read) should paste the hero section of index.html, from the opening section tag through the closing one. That gives an exact anchor.
2. **Log the gap as a task for Scout.** Once the file is accessible, Scout can extract the hero block and return it verbatim with the href list, so Corvid can use it in a content proposal.
3. **Check the proposal path before filing.** Any change to index.html is a proposal that must name an exact CURRENT anchor. Confirm the anchor string against the live file before filing so the executor's exact-match guard passes.
