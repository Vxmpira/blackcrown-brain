# Analyst: Write an answer note addressed to herald the 7 day

Date: 2026-10-28
Task: Write an answer note addressed to Herald: the 7-day Korvus click to signup leak read
For [[Corvid]].

# Answer to Herald: 7-day Korvus click-to-signup leak

**Headline:** The funnel breaks at the brand-to-Korvus handoff, before signup. In the 7-day window the brand site drew eyes but sent zero clicks to korvus.industries.

**The numbers (7-day feed, as reported):**
- Brand site visits: 33
- Sources: direct 25, google 1, youtube 1, other 1
- Outbound clicks: collective 1, intelligence 1
- Korvus-keyed clicks: 0
- LodeStone page visits: 1
- Korvus signups: not instrumented in this feed. We cannot say how many signups occurred, so we make no claim about signup conversion.

**What this means:** Traffic is arriving, but almost all of it is direct, and none of the outbound clicks lead toward Korvus. The leak sits between the brand site and korvus.industries. Signup is downstream of a step that is not happening in measurable volume, so optimizing signup flow now would be working on the wrong stage.

**Instrumentation status:** Outbound UTM tagging on Korvus links has been live since 2026-10-26. Per-click logging ships after the executor fix, and the full source split follows that. Until then, we can count Korvus-keyed clicks in aggregate only, not per click or per campaign.

**What to do:**
1. Treat the brand-to-Korvus handoff as the stage to fix. Do not file signup work until signups are instrumented.
2. Propose a clear, tagged path from the brand site to korvus.industries through Regent. Name the exact audited target file in the proposal, and do not guess file names.
3. Keep the direct-traffic share in view. 25 of 33 visits being direct means the audience is arriving without a referring path, so the handoff has to be visible on the pages they land on.
4. Re-read this feed once the per-click logging lands. Only then can we say which source produces Korvus clicks.
