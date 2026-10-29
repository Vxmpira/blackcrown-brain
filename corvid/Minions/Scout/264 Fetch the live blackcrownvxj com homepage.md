# Scout: Fetch the live blackcrownvxj com homepage and copy the exact

Date: 2026-10-29
Task: Fetch the live blackcrownvxj.com homepage and copy the exact home CTA block verbatim: heading, supporting line, button text, and button href, character for char
For [[Corvid]].

**Finding: I can't fetch the live homepage from this run, so I have no CTA text to copy. Nothing below is a verbatim capture.**

- No fetch or browser tool is available to me in this run, so I haven't seen the live blackcrownvxj.com homepage. I won't reconstruct the heading, supporting line, button text, or href from memory or guesswork, because a wrong CURRENT anchor would fail preflight after the owner's green light.
- The rendered DOM is the wrong source for an anchor anyway. The executor matches exact CURRENT anchors against the repo file's bytes, and rendered markup can differ from source (attribute order, whitespace, entities, any injected elements). The anchor has to come from the file as stored.
- Memory says every root html file in the brand site repo is live, so the homepage is a root html file. The exact filename isn't in my memory and I shouldn't guess it. Whoever holds repo access should confirm it.

**Recommended moves**

1. **Pull the anchor from source, not the render.** Have a desk with repo read access open the homepage file in the blackcrownvxj.com repo and copy the CTA block byte for byte, including surrounding indentation and any line breaks. Return it as a single literal block. Scout can then check it for uniqueness: the anchor must appear exactly once in the file.
2. **Hold the rewrite proposal until the anchor is in hand.** Filing the proposal now would put an unverified CURRENT anchor in front of the owner, which is the failure the filing-integrity rules exist to prevent. Once the anchor is confirmed, Regent can file the proposal, and the executor's preflight can run on it.
3. **Give Steward's deadlock a clean handoff.** If the read is stuck because no desk can fetch the live page, the missing capability is the real gap. Filing a task for a fetch-capable desk to return the homepage source, with the filename confirmed first, would unblock this and future anchor work.
