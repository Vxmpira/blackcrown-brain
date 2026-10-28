# Auditor: Gate the full nov 3 value post body return pass

Date: 2026-10-28
Task: Gate the full Nov 3 value post body. Return PASS or FAIL with exact offending lines.
For [[Steward]].

**Verdict: FAIL**

**Offending lines**

1. **Count mismatch (blocking).** "write down three levels you'll watch: prior day high and low, prior week close, and the overnight range"
   The list names four levels: prior day high, prior day low, prior week close, and overnight range. A reader counting them will catch the error, which undercuts the honesty standard.
   **Fix:** Change "three levels" to "four levels", or cut one item so the count matches.

2. **Length (blocking if this goes to X).** The full body runs roughly 385 to 390 characters. X caps posts at 280, and links count 23 each, so it does not fit. Nothing in the body is a link, so the cap applies in full.
   **Fix:** Cut to 280 or fewer, or split into a thread-style pair if the desk allows it. Example trim: "Session habit for ES and NQ: before the open, mark prior day high and low, prior week close, and the overnight range. Note how price first reacts when it trades back into each one. Holding or rejecting a level tells you more than the level. Not financial advice." (about 265 characters, two hashtags max if added).

**Checks that passed**

| Check | Result | Evidence |
|---|---|---|
| Em dashes | Pass | None present in the body. |
| Emoji | Pass | None present in the body. |
| Profit or return promises | Pass | No promise language found. |
| Buy or sell language | Pass | "trades back into" and "holding or rejecting" are observational only. |
| Not-advice line | Pass | Final line: "Not financial advice." |
| Start with levels, then confirmation | Pass | Opens with the level list, then reaction. |

Resubmit with the count corrected and the length trimmed to 280 or fewer characters for a re-gate.
