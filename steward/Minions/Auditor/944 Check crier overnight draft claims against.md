# Auditor: Check crier overnight draft claims against live product

Date: 2026-11-14
Task: Check Crier overnight draft claims against live product
For [[Steward]].

**Auditor report: Crier overnight draft vs. live product**

**Status: BLOCKED, no PASS or FAIL issued.** The draft text and the live korvus.industries copy were not included in the task, so no claim could be checked against its source. Any verdict I gave now would be invented.

**Findings, ranked by impact**

1. **Draft not attached (blocker).** Nothing in the task contains the claims. Fix: Steward re-files with the full draft text, or the vault path to it, so each sentence can be extracted and numbered.

2. **Live copy not attached (blocker).** I have no fetched text from `/`, `/lodestone`, or `/legal`, and the Observer tier description is not in the brief. Fix: paste the rendered text of those public routes, or the repo file they come from. Note that `/terminal` and `/forex` are gated, so claims about them cannot be verified from public copy and should be flagged unless the owner confirms them.

3. **Likely unsupported claims to check first.**
   - **ES and NQ coverage.** Unsupported unless the live copy names both instruments.
   - **Globex range.** Unsupported unless the live copy or a shipped feature names it. If it is only in the draft, mark it "not instrumented yet" and do not publish.
   - **Overnight or 24/7 operation.** Brand language is not evidence of uptime. Only a feed status or uptime record supports "live overnight." Without one, flag it.
   - **Observer core feed.** Any description of depth, latency, or update frequency must match the free-tier copy word for word. Anything beyond that is unsupported.

4. **Price figures in the draft.** Remove any dollar amount from the draft unless it is quoted from the live page. Korvus landing prices are injected server side, so they cannot be checked from a static read. Do not carry prices from memory.

5. **Compliance screen (applies to every claim).**
   - No profit promises or implied returns.
   - No trading direction, levels, or advice.
   - The not-advice disclaimer must appear on any product claim.
   - No em dashes and no emoji in outbound copy.

**Verification table to fill once inputs arrive**

| # | Draft claim (exact string) | Live source (exact string or "none") | Verdict |
|---|---|---|---|
| 1 | | | PASS / FAIL / UNSUPPORTED |

Verdicts: **PASS** only when the live source contains the claim's substance. **FAIL** when the live source contradicts it. **UNSUPPORTED** when no live source exists, which means the claim is pulled or marked "not instrumented yet."

**Next step:** Steward re-files with the draft and the live copy. I will return the filled table the same cycle.
