# Scout: Confirm the futures news page s exact repo path in

Date: 2026-10-27
Task: Confirm the futures-news page's exact repo path in the korvus audit and return the exact final content block before the closing body tag, verbatim
For [[Corvid]].

**Finding: I can't confirm the path or return the content block. Neither the korvus audit nor the file contents were in my feed, so anything I wrote here would be a guess.**

**What I could and couldn't verify**
- **Path:** Not verified. Your context says "should be" `korvus:pages/futures-news.html`. Institutional memory confirms that pages/ is the correct home for new marketing pages and that they serve at /p/<name>, so /p/futures-news matches the naming rule (lowercase, hyphens). Whether the file exists under that name is still unconfirmed.
- **Closing content block:** Not returned. I did not reconstruct it from memory or invent it, since a wrong CURRENT anchor fails preflight.
- **Audit listing:** Not in my feed. I can't say whether the file is listed.

**Why this matters**
- An anchor that doesn't match exactly will bounce in preflight, or worse, fail after the owner's green light. Filing against an unverified path burns his trust.
- Memory says never guess file names, so I'm not filling this gap.

**Recommended moves**
1. **Pull the audit entry first.** Check the korvus audit for pages/futures-news.html. If it isn't listed, stop and file a new-page proposal instead (COMPLETE document in the vault, NEW as one line, FROM NOTE: path). Don't file an insert.
2. **Return the real tail block.** Have the desk holding the repo read the last content section before `</body>` and send it back verbatim. I'll then draft the Operator CTA insert against that exact anchor, with the /signup link and the not-advice disclaimer kept on the claim.
3. **Check the price rule before writing copy.** Memory says never hardcode dollar amounts on the Korvus landing page, because prices inject server side from Stripe display tokens. The futures-news page is a different file, so the rule may not reach it. That's my reading, not confirmed doctrine. If the CTA is meant to match landing pricing, Corvid should decide whether to use the same token approach. The 9.99 monthly, 79.99 annual (annual listed first with the savings label) ladder is otherwise law.
