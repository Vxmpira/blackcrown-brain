# Auditor: Gate the full nov 3 value post redraft return pass

Date: 2026-10-28
Task: Gate the full Nov 3 value post redraft. Return PASS or FAIL with exact offending lines.
For [[Steward]].

**Verdict: FAIL**

**Findings, ranked by impact:**

1. **Level count mismatch.** The body says "Four session levels," but item 4 names two levels (overnight high and overnight low), so the post lists five.
   - Offending lines: `Four session levels worth marking before the open on index futures:` and `4. Overnight range high and low`
   - Fix: change the opener to "Five session levels" and split item 4 into "4. Overnight range high" and "5. Overnight range low."

2. **Length cannot be verified against the Community cadence.** The cadence limit is not in institutional memory, so I can't confirm the body fits. The draft runs roughly 600 characters. If this goes to X, it fails the 280-character cap.
   - Fix: name the target channel and its length limit in the proposal. If it is X, trim to 280 or fewer, or move the full text to a thread or caption.

**Checks that passed:**
- No em dashes.
- No emoji.
- The not-advice line is present: "Not financial advice. Levels are reference points, not predictions."
- No pitch, product name, or link.
