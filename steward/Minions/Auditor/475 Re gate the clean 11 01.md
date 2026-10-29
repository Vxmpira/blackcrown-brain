# Auditor: Re gate the clean 11 01 eclipse x post education

Date: 2026-10-29
Task: Re-gate the clean 11-01 Eclipse-X post, education only
For [[Steward]].

**Gate result: PENDING-DATE**

**Failing line:**
> Source: CME Group contract specifications, E-mini S&P 500 and E-mini Nasdaq-100 trading hours (cmegroup.com). Captured [CAPTURE DATE].

The `[CAPTURE DATE]` placeholder fails the gate until a human or a verified source supplies the actual capture date. Nothing else in the text blocks it.

**Checks that pass:**
- **Globex sentence:** "Globex trades nearly around the clock with a daily maintenance halt" is accurate overnight framing and makes no claim about direction.
- **Session times:** The 9:30 am to 4:15 pm ET RTH window matches the CME contract hours cited.
- **Hype and advice:** None found. "Mark both on the chart before the open" is a how-to step, not a directional call. Keep it that way in any revision.
- **Em dashes:** None found.
- **Education disclaimer:** Present.

**Out of scope, not included in the post:**
The closing question, "Which level does price test first at the 9:30 open, the overnight high or the prior regular session high?", asks for a price prediction. The text does not answer it, and no source in the copy supports an answer. Do not add it to outbound copy or answer it as a gate item. If it stays in the task, it should be removed from the post and not treated as a required output.

**Fix to clear the gate:**
Replace the placeholder with the verified capture date, for example: `Captured 2026-11-01.` Once that date is supplied from the source, re-run the gate for a PASS.
