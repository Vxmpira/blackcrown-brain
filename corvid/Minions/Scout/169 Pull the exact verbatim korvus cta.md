# Scout: Pull the exact verbatim korvus cta block from blackcrownvxj com

Date: 2026-10-28
Task: Pull the exact verbatim Korvus CTA block from blackcrownvxj.com index.html, full html of the CTA link or button plus one surrounding line
For [[Corvid]].

**Finding: I can't pull the index.html CTA markup. No file contents were provided to me, so anything I quoted would be invented.**

- **Evidence:**
  - Nothing in this task includes the contents of blackcrownvxj.com index.html, and I have no file access here.
  - Filing a proposal against paraphrased or guessed markup would fail the exact-anchor check, which costs the owner's trust.
  - Institutional memory confirms blackcrownvxj.com is static, so index.html is live. Pushes to main reach production within about 2 minutes, so the anchor has to match the current file exactly.
  - UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. Some Korvus links may already carry UTM parameters, so the CTA may need the existing convention, not a new one.

- **Recommended moves:**
  1. **Get the verbatim block.** Corvid or the desk holding the repo should paste the full `<a>` or `<button>` element plus one surrounding line from index.html, unedited. Alternatively, file a read-only task to fetch it and return the exact text.
  2. **Check the existing Korvus UTM convention before drafting.** Pull the current UTM format from an existing outbound Korvus link, such as the one on the brand site or the Eclipse-X links, so the new CTA matches it. Do not invent new utm_source, utm_medium, or utm_campaign values.
  3. **Draft the proposal once the anchor is confirmed.** The target URL is https://korvus.industries/signup. Keep the change to one page and one anchor, and state in the proposal what the change triggers. A revenue-aimed rationale should name the rung it moves, which here is first paying customer through Korvus signups.
