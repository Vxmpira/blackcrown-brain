# Scout: Fetch blackcrownvxj com home page report exact file name plus

Date: 2026-10-29
Task: Fetch blackcrownvxj.com home page, report exact file name plus every Korvus link or CTA block verbatim: full anchor tags, hrefs, surrounding markup
For [[Corvid]].

**Finding: Not verified. I have no fetch or repo access in this run, so I cannot report the exact file name or the Korvus markup from blackcrownvxj.com.**

**What I could not do**
- I did not fetch the live home page, so I have no verbatim anchors, hrefs, or CTA blocks.
- I did not open the blackcrownvxj.com repo, so I cannot confirm which root html file is the home page. Memory says every root html file is a live page, but it does not name the home file, and I won't guess. Naming a file wrong would send the proposal to the wrong target.
- Nothing below is a finding about the page. It is a method.

**How to get the data (any of these closes the gap)**
- Run `curl -s https://blackcrownvxj.com/ | grep -n -i "korvus"` to get every line that mentions Korvus, with line numbers. Then `curl -s https://blackcrownvxj.com/ | grep -n -i "<a "` to see the anchors.
- Check each Korvus href for `utm_source`, `utm_medium`, and `utm_campaign`. Any Korvus link without them is the leak candidate, since UTM tagging shipped 2026-10-26 and should already be on every outbound Korvus link.
- Look for a CTA that sits below the fold, is a plain text link, or has an href pointing to the root (`korvus.industries/`) instead of `/signup`. Those are the usual buried-CTA patterns.
- Once the raw markup is in hand, I can build the exact-anchor content proposal Corvid needs.

**Recommended moves**
1. Get a repo read or the raw HTML of the brand home page into this task. The owner-facing fix depends on the exact CURRENT anchor text, so this is the blocker.
2. Once the markup is in, file the UTM check as its own item: count Korvus links with and without UTM params. If any are missing them, the fix goes back to the desk that filed the link, not to the owner.
3. Compare the home CTA destination with the Korvus signup path (`/signup`). If the home page sends traffic to `/` instead, that is a likely click leak and a candidate for a one-line href change proposal.
