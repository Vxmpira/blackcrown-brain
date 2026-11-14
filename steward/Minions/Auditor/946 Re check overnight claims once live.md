# Auditor: Re check overnight claims once live copy is read

Date: 2026-11-14
Task: Re-check overnight claims once live copy is read
For [[Steward]].

## Overnight claims re-check: BLOCKED, no verdicts issued

**Verdicts:**
- ES and NQ overnight moves covered: **PENDING** (no live copy received)
- Globex range covered: **PENDING** (no live copy received)
- Observer includes the core feed: **PENDING** (no live copy received)

I have not issued PASS or FAIL on any claim. The live source from Steward's read of `korvus:korvus_landing.html` was not in this request, and a verdict without the quoted line would be a guess.

## Findings, ranked by impact

1. **High: the check cannot run yet.** No quoted copy was attached.
   Fix: Steward re-sends the landing page text, or the exact sentences containing ES, NQ, Globex, and Observer, and I rule on each one.

2. **High: "Observer includes the core feed" is not supported by institutional memory.** Memory confirms only that Observer is the free tier. It does not define what Observer includes.
   Fix: the owner or Regent confirms the Observer feature list through the brain pipeline before any copy claims it. Until then, treat the claim as unverified.

3. **Medium: no ground truth exists for "overnight coverage" or "Globex range."** Memory does not define which sessions, instruments, or data the terminal covers.
   Fix: Regent adds a one-paragraph definition of overnight and Globex coverage to the memory file, including the exact instruments and session hours, so future checks compare against a written standard.

4. **Medium: the claims need a not-advice disclaimer where they describe market data.** Memory requires the not-advice disclaimer on product claims. Overnight move and range copy reads as market commentary.
   Fix: when the copy arrives, I will also check that the disclaimer sits within the same section as these claims.

5. **Low: the request asks for a verdict before the proof exists.** Filing a PASS on unread copy would put a false audit record into the chain.
   Fix: Steward treats this audit as incomplete until item 1 lands, and does not mark the overnight claims as verified in any status report.

**Next step:** Steward sends the quoted copy. I will return one PASS or FAIL per claim, with the quoted line for each.
