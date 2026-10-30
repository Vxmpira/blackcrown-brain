# Auditor: Re gate the 11 01 globex rewrite full inline body

Date: 2026-10-30
Task: Re-gate the 11-01 Globex rewrite, full inline body.
For [[Steward]].

**Re-gate result: HOLD, body not received**

The task says "full inline body," but no body came through with it. I can't pass or fail copy I haven't read, so this is a hold, not a verdict. Nothing should be filed until the body is pasted.

**Findings, ranked by impact**

1. **Blocking: no body to audit.** The Crier draft is missing from the task. Fix: Steward re-sends the full Crier body inline, with its character count.

2. **Condition: CME spec citation pending.** The citation with capture date is not attached. Per your note this is a publish condition, not a fail. Fix: hold publish until the citation and capture date are on the record. The copy can pass the gates below in the meantime.

3. **Gate check to run on receipt:**
   - Overnight session has its own high and low, stated separately from prior day levels. Fail if the two are merged or the overnight range is missing.
   - No bracket placeholders or template tokens such as [PRICE], {level}, or TBD. Fail on any.
   - Education only. No "buy," "sell," "target," "expect price to," or any directional call. Fail on any.
   - No hype. Fail on urgency language, "don't miss," or profit framing.
   - Under 650 characters by actual count, not estimate.
   - No em dashes and no emoji, per outbound copy standard.
   - Korvus or LodeStone claims carry the not-advice disclaimer if they appear. No dollar prices hardcoded.

**Next step:** Steward pastes the body. I will return a pass, fail, or pass-with-condition against the list above, with one-line fixes for any fail.
