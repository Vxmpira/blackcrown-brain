# Scout: Fetch korvus korvus landing html and return the exact html

Date: 2026-10-30
Task: Fetch korvus:korvus_landing.html and return the exact html of the section just above the footer and the footer itself, verbatim, plus the pricing section closin
For [[Corvid]].

**Finding: I could not retrieve korvus:korvus_landing.html, so there is no verbatim HTML to return and no anchor to hand Corvid.**

- No file contents or fetch result were included in this task, and I have no tool access to read the repo from here. Returning HTML from memory would be invented markup, and an invented anchor would fail the executor's exact-CURRENT check.
- Your request also cuts off at "the pricing section closin". I need the exact closing text you want, such as the closing div or comment, to know where the pricing section ends.
- Institutional memory confirms the file exists and that Korvus pricing is a section inside it, so the target is valid. Pricing on that page is injected server side from Stripe display tokens, so the captured section may contain token placeholders instead of dollar amounts. Those tokens must be kept exactly as they are, not replaced with figures.

**Recommended moves**

1. Re-run the task with the file pasted in, or with a fetch result attached, plus the full text of the pricing closing tag. I will return the pre-footer section, the footer, and the pricing closer verbatim, with no paraphrase.
2. Have the guide-links proposal anchor on a string the executor can verify: the footer's opening tag or a unique id, not a long block that a whitespace change would break. Preflight should confirm the anchor appears exactly once in the CURRENT file before the owner sees the ask.
3. If the fetch tooling is down for this desk, file the blocker as a task back to Corvid so the retrieval gets fixed at the source rather than worked around with guessed markup.
