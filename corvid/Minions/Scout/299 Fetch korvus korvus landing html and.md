# Scout: Fetch korvus korvus landing html and return verbatim the exact

Date: 2026-10-30
Task: Fetch korvus:korvus_landing.html and return verbatim the exact HTML block between the pricing section and the footer, plus the first lines of the footer, so I h
For [[Corvid]].

**Finding: I can't return the verbatim landing HTML because no file contents were provided to me and I have no fetch tool in this run. I have not guessed at any markup.**

**Evidence**
- The target is correct. Korvus pricing is a section of `korvus:korvus_landing.html`, not a separate pricing file, so the anchor search belongs in that file.
- The exact CURRENT block has to come from the live file. Pulling it from memory or a summary would risk a failed anchor after the owner's green light, which the filing rules treat as a trust cost.
- Korvus landing prices inject server side from Stripe display tokens. The CURRENT anchor should sit on structural markup near the pricing section and should not depend on any hardcoded dollar amount, since none should exist there.
- Before filing, the two guide pages need to exist as COMPLETE documents in the vault. Their paths would be `/p/es-hours-guide` and `/p/smt-guide` (lowercase, digits, hyphens). Each is served by the Flask app from the pages/ folder, so the links must match those routes exactly.
- Nothing in my context confirms either guide page exists yet. I can't verify that from here.

**Recommended moves**
1. Have the executor or Regent pull the live `korvus:korvus_landing.html` and extract the exact text between the pricing section and the footer, plus the opening footer lines. That is the only safe source for the CURRENT anchor. If a fetch tool is available to the desk, it should be used on this run.
2. Before filing the links block, confirm that the ES hours guide and SMT guide each exist as complete HTML documents in the vault, with their NEW lines as FROM NOTE paths. If either is missing, a writing minion authors it first, and the links ask waits. Filing links to pages that don't serve would fail on the owner's green light.
3. Make the links block a structural insert with a unique id, placed outside the pricing section so it doesn't disturb the server side price injection. Once the live anchor is in hand, I can draft the exact insert text and check it against the safety guards (no duplicate ids, nothing after the closing body tag).
