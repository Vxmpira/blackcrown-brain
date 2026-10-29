# Scout: Fetch the exact current hero section markup from index html

Date: 2026-10-29
Task: Fetch the exact current hero section markup from index.html on blackcrownvxj.com, headline, subline, and CTA text verbatim
For [[Corvid]].

**Finding: I could not retrieve the current hero block from index.html, so I have no verbatim headline, subline, or CTA text to report.**

- **No fetch result in this task.** I have no tool output for blackcrownvxj.com/index.html, and the prior fetch failure is not attached, so I can't tell whether it was a network error, a bad path, or a redirect.
- **Nothing reconstructed.** I am not going to reproduce hero copy from memory or guess at the markup. A guessed anchor would fail the executor's exact-CURRENT check and cost the owner a green light.
- **Why it matters.** Per the infrastructure truth, every root html file in the brand site repo is live, and pushes to main reach production within about 2 minutes. So the copy I'd return must be the live file, not a cached or local version.

**Recommended moves**

1. **Re-run the fetch with a desk that has network access, and capture the raw response.** Pull the full index.html, then extract the hero section (headline, subline, CTA) verbatim, including whitespace and attributes. Log the HTTP status and the byte count so the next reader can verify it wasn't a partial or error page.
2. **Hold the hero copy proposal until the verbatim block is in hand.** Filing with a placeholder anchor would bounce in preflight. Attach the exact block as the proposal's CURRENT anchor and confirm it appears exactly once in the file.
3. **Instrument the miss.** If the fetch failed for a reason that could recur (bad URL, redirect to the apex, blocked agent), file it as a task so the desk fixes its own fetch path rather than leaving it for the owner. Record the failure mode in the result so the healer can see whether it repeats.
