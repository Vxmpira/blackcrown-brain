# Auditor: Hold verdicts until verbatim sentences arrive then rule per sentence

Date: 2026-11-14
Task: Hold verdicts until verbatim sentences arrive, then rule per sentence
For [[Steward]].

## Auditor Review: Overnight Draft Claims (Verdicts on Hold)

**Status: no verdicts issued.** The draft's three claims have no quoted live copy attached, so there is nothing to rule against. Ruling now would be a guess, and the brand does not publish guesses.

### Findings, ranked by impact

1. **High: Three product claims have no source text.** The draft says ES and NQ moves are covered overnight, the Globex range is covered, and Observer includes the core feed. None of these is established in institutional memory. Memory confirms only that Observer is the free tier and that Operator is $9.99/month or $79.99/year with LodeStone included. Nothing on record defines Observer's feed contents, overnight coverage, or Globex range.
   **Fix:** Steward pastes the verbatim sentence(s) from korvus:korvus_landing.html for each claim, with the section heading, and I rule each one PASS or FAIL against that exact line.

2. **High: Claims about feed coverage are unverifiable product promises.** Even if the landing copy says "overnight ES and NQ coverage," the claim must still match what the terminal delivers. A landing line that outruns the product is a trust failure, and the brand's edge is honesty.
   **Fix:** Before any PASS, confirm the live `/terminal` or `/forex` routes actually show the overnight coverage named in the copy. Record the check beside the verdict.

3. **Medium: Missing not-advice disclaimer on product claims.** Feature claims about market coverage must carry the standing not-advice disclaimer.
   **Fix:** Each PASS is conditional on the disclaimer appearing on the same surface as the claim. If it is absent, the verdict is FAIL regardless of accuracy.

4. **Medium: Pricing text can drift from the Stripe display tokens.** Korvus landing prices inject server side. Any dollar figure quoted in the draft should be checked against the injected live value, not hardcoded copy.
   **Fix:** Quote the rendered price line, not a number from memory. Do not rule on any price from the draft alone.

5. **Low: Process hygiene.** Verdicts should be per sentence and per quoted line, so a single bad sentence cannot sink or rescue the whole draft.
   **Fix:** Steward sends one sentence per row, in the format: claim, verbatim live line, source section.

### Next step
Steward returns the verbatim sentences. I will then rule each one PASS or FAIL, quote the line beside the verdict, and flag any copy that needs an owner-approved proposal to change.
