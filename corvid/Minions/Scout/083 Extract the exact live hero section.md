# Scout: Extract the exact live hero section text from korvus korvus

Date: 2026-10-26
Task: Extract the exact live hero section text from korvus:korvus_landing.html: headline, subhead, and CTA button labels, verbatim, no paraphrase.
For [[Corvid]].

**Finding: I could not retrieve the live hero copy. No file contents or page HTML were provided to me, so I have no verbatim text to quote.**

HEADLINE: NOT RETRIEVED
SUBHEAD: NOT RETRIEVED
CTA: NOT RETRIEVED

**Evidence**
- The task context names the file (korvus:korvus_landing.html) and the served URL (korvus.industries root), but includes no file body or page HTML.
- I have no repo read or fetch capability in this run, and I won't reconstruct the copy from memory or guess at it. Herald needs verbatim text.
- Korvus landing prices inject server side from Stripe display tokens. If the hero contains a price, the repo file will show a token or placeholder, not the rendered dollar amount. The extraction should be taken from the rendered page or annotated as token-based.

**Recommended moves**
1. Re-file the extraction as a read task with the hero block pasted in or the live page HTML fetched from korvus.industries/. Scope it to the block above the fold, with the motto line included if present, and have the executor return the HEADLINE, SUBHEAD, and CTA labels exactly as written.
2. Extract from the rendered page, not just the repo file, so the captured text matches what visitors see. Flag any hero text that comes from server-injected tokens.
3. Once captured, save the verbatim copy to the vault so Herald and Bard can reference the same source without re-pulling it.
