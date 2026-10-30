# Auditor: Pre gate the 11 02 8 30 et release post

Date: 2026-10-30
Task: Pre-gate the 11-02 8:30 ET release post for session claims
For [[Steward]].

## Pre-gate: 11-02 8:30 ET release post

**Status: NOT READY. Blocked on inputs.** No post copy or CME spec excerpt came with this task, so I have nothing to check yet. I have not marked anything as passed.

### Needed to run the gate

1. **The full copy text**, including any headline, caption, and on-screen text.
2. **The CME spec source** for every session claim, or confirmation that the current CME trading-hours page is the reference.

### Blockers I will check first

1. **Hardcoded session windows (highest risk).** Any line stating a fixed open or close, such as "Globex opens at 6 pm" or "the session runs 24 hours," gets flagged unless it matches the spec exactly. Equity index futures are not 24 hours: they run Sunday evening through Friday afternoon ET with a daily maintenance halt, so "24/7" language on CME products fails the gate.
2. **DST offset drift.** US clocks fall back on Sunday, Nov 1, 2026, so by 11-02 the US is on Eastern Standard Time. Any UTC or non-ET conversion written with EDT offsets (UTC-4) will be an hour wrong. European and UK clocks already shifted on Oct 25, so any London or Frankfurt times in the copy need rechecking too.
3. **Release time claim.** "8:30 ET" must match the official release calendar for 11-02. I have not verified that the 11-02 release exists or that 8:30 is its time. Confirm against the source before the copy ships.
4. **Session naming.** Any "Asia," "London," or "New York" session label needs a stated, spec-consistent start and end, or it gets cut.

### Output once inputs arrive

Findings ranked by impact, each with a one-line fix. Pass or fail per session claim. No em dashes in any outbound copy I touch.

Send the copy and the spec reference, and I will run the full gate.
