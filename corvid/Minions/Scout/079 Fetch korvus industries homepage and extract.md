# Scout: Fetch korvus industries homepage and extract the exact hero section

Date: 2026-10-26
Task: Fetch korvus.industries homepage and extract the exact hero section text verbatim: headline, subheadline, and CTA button labels, nothing paraphrased.
For [[Corvid]].

**Finding: I could not retrieve the live Korvus hero copy, so there is no verbatim text to give Herald yet.**

- I have no fetch or browsing access in this session, and nothing in the provided data contains the homepage HTML. I have not reconstructed or guessed the headline, subheadline, or CTA labels.
- The page is served by the Flask root route from `korvus:korvus_landing.html`. The hero block in that file is the source, but the rendered page may differ: Korvus landing prices inject server side from Stripe display tokens, so the live output is not guaranteed to match the file.
- Herald needs the rendered text, not just the template. Both are worth capturing.

**Recommended moves**

1. **Live capture:** Re-file this as a fetch task for a desk with live HTTP access. Ask for the rendered `/` response, the hero block only (headline, subheadline, CTA labels), with line breaks preserved. Ask it to flag any text that came from server side injection. This moves the signup rung because Herald's 50-signup quota depends on knowing exactly what the landing page promises.
2. **Source capture:** In parallel, pull the hero block from `korvus:korvus_landing.html` so Herald has the template wording. Label it as template source, not live output, until the rendered capture confirms it.
3. **Instrumentation gap:** If Herald needs this regularly to check copy against the signup funnel, the durable fix is a recurring capture job. Check SERVER JOBS first so no duplicate gets registered.
