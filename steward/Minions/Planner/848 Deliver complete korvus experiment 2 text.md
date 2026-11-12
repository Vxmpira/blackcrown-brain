# Planner: Deliver complete korvus experiment 2 text ending final

Date: 2026-11-12
Task: Deliver complete Korvus Experiment 2 text, ending FINAL
For [[Steward]].

## Blocker

The prior gists are not in my context, so I can't complete the Experiment 2 text from the cut-off point without guessing at what they said. Steward needs to paste those fragments in, or confirm a fresh write from the scope and baseline given.

## Plan: Korvus Experiment 2 (korvus.industries landing only)

**Step 1. Recover source material**
- Owner: Steward
- Action: Paste the prior gist fragments and confirm Experiment 1 stays excluded.
- Done when: the full fragment text is in hand and the exclusion is confirmed in writing.

**Step 2. Lock the scope and baseline**
- Owner: Corvid
- Action: Confirm the surface is the landing section in `korvus:korvus_landing.html`, not a new page. Record the baseline: 1 signup from 94 visits over 7 days (about 1.1%).
- Done when: the surface, the baseline, and the primary metric (signups per visit) are written in one paragraph.

**Step 3. Pick one variable**
- Owner: Corvid
- Action: Choose a single element to change (headline, hero proof, or CTA framing). Hold everything else constant. Do not hardcode dollar amounts; prices inject server side from Stripe tokens.
- Done when: the variable, the control, and the variant hypothesis are each stated in one sentence.

**Step 4. Write the variant copy**
- Owner: Herald
- Action: Write the variant for that one element. No em dashes, no profit or performance claims, no trading advice. Keep the not-advice disclaimer on any product claim.
- Done when: the variant copy passes the voice and standards check and carries the disclaimer where a claim appears.

**Step 5. Write the full experiment definition**
- Owner: Planner (this plan), drafted into the vault by Steward
- Action: Produce the complete document with these sections: Hypothesis, Variable, Control and Variant, Primary Metric, Baseline, Sample Threshold, 14-Day Run Schedule, Steps, Stop Rules, Decision Rule, Readout.
- Done when: every section is present, the document is complete, and it ends with the word FINAL.

**Step 6. Verify tracking**
- Owner: Herald
- Action: Confirm outbound Korvus links carry the standing UTM tags. Confirm a per-variant split is readable. If it is not, file the instrumentation job before launch.
- Done when: a test visit shows the variant assignment and the signup can be attributed to it.

**Step 7. File and approve**
- Owner: Steward, with Regent review
- Action: File the change as one proposal stating exactly what it triggers. Owner green-lights in #boardroom. Executor applies one page per ask.
- Done when: the owner's approval is recorded and the variant is live on the landing section.

**Step 8. Run daily checks**
- Owner: Herald
- Action: Log visits and signups per variant each day for 14 days. Flag any day with a data gap.
- Done when: a daily count exists for all 14 days, or the gap is documented.

**Step 9. Day 14 readout**
- Owner: Corvid, reviewed by Steward
- Action: Compare variant against control and the 1/94 baseline. Apply the decision rule from Step 5.
- Done when: a written decision (keep, revert, or extend) is filed with the numbers attached.
