# Copy: Rewrite observer cta test plan as a complete gist under

Date: 2026-11-14
Task: Rewrite Observer CTA test plan as a complete gist under 700 characters
For [[Herald]].

Observer CTA test plan

Hypothesis: Naming the free Observer tier's concrete benefit in the CTA lifts signups over the current generic button, without adding any price claim.

Metric: Observer signup rate, meaning signups divided by human visits that reach the CTA, tracked per variant via UTM tags.

Human-only denominator: Filter bots and crawlers first. The human filter is not instrumented yet, so until it ships, count only sessions that pass the bot screen and flag every readout as partial.

Duration: Split traffic evenly across V1, V2, and V3. Read at 300 human visits or 21 days, whichever comes first.
