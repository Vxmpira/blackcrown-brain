# Auditor: Write 19 00 gate check spec with trigger and fail

Date: 2026-10-29
Task: Write 19:00 gate check spec with trigger and fail rules
For [[Steward]].

## 19:00 Gate Check Spec: Korvus Watcher Creative, Bloom render, ledger #274

**Status at spec time:** Wire C source item from Herald: PENDING (not received). Bloom package and ledger #274 contents: PENDING (no vault access from Steward feed).

### Gate table (all times ET)

| Item | Owner | Due | Pass rule | Fail rule |
|---|---|---|---|---|
| Wire C source text received from Herald | Herald | 18:30 | Full source text is filed in ledger #274 and marked RECEIVED | Not received at 18:30: run fallback path at 18:45. Missing source alone does not fail the gate; it moves the gate to fallback. |
| Source verbatim check (overlay lines and caption quotes vs. Herald text) | Auditor, reviewed by Steward | 18:30 (confirm path), re-run 19:00 | Every quoted line matches the source exactly: characters, numbers, punctuation, casing | Any mismatch, paraphrase, or quote with no source line fails the gate |
| Bloom package present | Bard | 18:30 | Render link, overlay field, and caption are all filed in ledger #274 | Any element missing at 19:00 fails the gate |
| Fallback path defined and filed | Steward (definition), Bard (render) | 18:45 | Fallback creative spec is filed and cites no unreceived wire material | Fallback not filed by 18:45: gate cannot lock at 19:00 |
| Em dash scan on caption and overlay | Auditor | 18:30 and 19:00 | Zero em dash characters in caption, title, and overlay | Any em dash found fails the gate |
| Hype scan on caption and overlay | Auditor | 19:00 | No term from the banned hype list appears (list PENDING from Steward) | Any banned term fails the gate; empty list means this check cannot pass, so Steward must file it first |
| No-text law on footage | Bard critic | 18:45 | Critic records that generated footage carries no words, letters, numbers, logos, or typography | Any text visible in footage fails the gate |
| Compliance: no profit promise, no trading advice, not-advice disclaimer on product claims | Auditor | 19:00 | All three hold; disclaimer present where a product claim appears | Any profit claim, advice language, or missing disclaimer fails the gate |
| Owner approval state | Steward (flags), owner (rules in #boardroom) | Checked by 18:45 | Approval is recorded in #boardroom and states what it triggers | Not visible or not approved at 19:00: item holds, nothing locks. Approval state is PENDING from my side. |
| Gate lock | Steward | 19:00 | All rows pass, or fallback path is filed and passes; ledger #274 status set to LOCKED | Any row fails: status set to HELD with the failing row named. No partial locks. |

### Findings, ranked by impact

1. **Single point of failure on Wire C.** The gate depends on an unreceived source with no filed fallback. Fix: Steward files the fallback spec now so 18:45 is a switch, not a scramble.
2. **Hype scan has no banned list.** A check with no list cannot pass or fail honestly. Fix: Steward files the banned hype term list before 18:30.
3. **Owner approval is not a gate row until now.** Fix: keep the approval row above and have Steward confirm the #boardroom state by 18:45.
4. **Ledger #274 and Bloom package are unverified from my side.** Fix: Bard confirms the package link in ledger #274 by 18:30; until then both stay PENDING.
