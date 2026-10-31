# Scout: Copy the exact current hero heading and subheading text verbatim

Date: 2026-10-31
Task: Copy the exact current hero heading and subheading text, verbatim, from korvus:korvus_landing.html, plus Herald's ready hero copy referenced as 331 if it sits i
For [[Corvid]].

**Finding: I can't return the verbatim hero block. Neither the current `korvus:korvus_landing.html` source nor Herald's "331" hero copy was included in what I received, so any text I wrote now would be a guess, and a guessed anchor is exactly what preflight bounces.**

**Evidence**
- The task asks for exact current heading and subheading text, but no file contents or Herald output came through with the request. The request is also cut off mid-sentence ("if it sits i"), so I can't confirm what "331" refers to.
- Institutional memory confirms the target is `korvus:korvus_landing.html`. Korvus pricing is a section of that file, not a separate `pricing` or `home.html` page, so the anchor has to come from that file.
- Replace anchors must be exact CURRENT strings. A paraphrased or reconstructed anchor fails the safety guard, and the bounce costs owner time after a green light, which the filing rules weigh most heavily.
- The landing page injects prices server side from Stripe display tokens, so the hero copy must not hardcode dollar amounts. Any NEW hero text should be checked for that before filing.
- Not instrumented yet: I have no read on whether Herald's 331 copy is already approved or still in draft.

**Recommended moves**
1. **Re-file the copy pull with the source attached.** Corvid should send the raw hero block from `korvus_landing.html` (the heading and subheading markup, copied as-is) plus Herald's 331 text in full, with the request finished. With both in hand, I can return a matched CURRENT and NEW pair in one pass.
2. **Confirm the 331 status before the proposal.** Herald's copy should be explicitly marked approved for the hero. If it's still a draft, the proposal should wait, because the owner's green light must state exactly what it triggers.
3. **Pre-check the NEW copy against the rules.** It should contain no em dashes, no guru or profit language, no hardcoded prices, and the not-advice disclaimer should stay on any product claim. Once the anchors are verified, I can run that check on the NEW text.
