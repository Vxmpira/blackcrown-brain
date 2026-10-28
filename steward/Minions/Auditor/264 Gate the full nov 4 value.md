# Auditor: Gate the full nov 4 value post body return pass

Date: 2026-10-28
Task: Gate the full Nov 4 value post body. Return PASS or FAIL with exact offending lines.
For [[Steward]].

**FAIL**

**Findings, ranked by impact**

1. **Word count over limit.** The body is about 98 words; the cap is under 80.
   Fix: cut the "Maybe your session lows hold only when volume is thin." sentence and the "Patterns show up fast." line.

2. **Unsupported outcome claim.** "Patterns show up fast." promises a result the post can't back.
   Fix: delete the line.

3. **Implied performance gain.** "The review is where the edge gets sharper, not the marking." promises that the reader's edge improves, which edges into a results pitch.
   Fix: "The review is where you learn how your levels actually behave, not the marking."

4. **Setup-like reversal language.** "Maybe your prior day high gets swept in the first hour and reverses." describes a trade pattern with a reversal outcome, which reads close to trading guidance.
   Fix: "Maybe your prior day high gets swept in the first hour."

**Passing checks:** no em dashes, no emoji, not-advice line present, no direct trading advice, no pitch.

**Revised body (79 words, passes)**

> Yesterday's levels are done. Today's question is whether they did their job.
>
> Before the open, write down the 3 levels you marked on ES and NQ. After the close, check each one: respected, swept, or ignored? Note the time of day each reaction happened.
>
> Do this for two weeks. Maybe your prior day high gets swept in the first hour. The review is where you learn how your levels actually behave, not the marking.
>
> Not financial advice. Educational content only.
