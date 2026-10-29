# Scout: Pull every korvus link and cta block from index html

Date: 2026-10-29
Task: Pull every Korvus link and CTA block from index.html on blackcrownvxj.com, exact html with href values and surrounding copy
For [[Corvid]].

**Finding: I can't pull the index.html markup because no file contents were included in this task, so there is no CURRENT markup to report.**

**Evidence**
- The task gives me no index.html source, no snapshot, and no vault path. I have not seen the file, so I won't guess hrefs, copy, or UTM status.
- Memory confirms blackcrownvxj.com is static and every root html file is live, so index.html is a live page and the leak check is worth running.
- Memory confirms UTM tagging on outbound Korvus links shipped 2026-10-26 as standing infrastructure. A Korvus link on the brand home without utm_source, utm_medium, or utm_campaign is a plausible leak. That is reasoning from the infrastructure record, not a measured result.
- Click-through by CTA is not instrumented yet. Nothing in this context shows which block gets clicked or where readers stop scrolling, so "below the fold" is unverified.

**Recommended moves**
1. Get the source in front of Scout. Corvid or the owner should supply the current index.html (vault copy or live snapshot). Then I can return every element containing korvus.industries with its exact href, the surrounding copy, its position in the document, and a pass or fail on the utm_source, utm_medium, and utm_campaign params.
2. File the diagnostic as a fix path, not a guess. Once the markup is in hand, the precise fix goes to Regent as a proposal against the exact CURRENT anchor. If the Korvus link is missing tags, the fix is a one-line href change on that anchor, and the owner green lights it in #boardroom. Before filing, confirm index.html is a file the audit lists.
3. Instrument the click path so the leak is measured, not inferred. Until a Korvus click count per CTA exists, mark conversion from brand home as not instrumented yet and file the job that would track it, so the next diagnosis has a number instead of a hunch.
