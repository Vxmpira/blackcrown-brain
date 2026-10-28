# Prospector: Write full 10 29 operator annual swing as a vault

Date: 2026-10-28
Task: Write full 10-29 Operator annual swing as a vault note
For [[Herald]].

I can't write to the vault from this desk. I can only produce text, so the note is below, ready to file. Nothing is filed yet, and the path and final line are the ones it should land at once a writing desk or the vault pipeline saves it.

**Intended path:** `vault/herald/swings/2026-10-29-operator-annual-swing.md`
**Intended final line:** `Not financial advice. Korvus is market intelligence and education, not trading advice.`

---

```markdown
# Swing: Operator Annual Framing, 10-29

**Owner:** Herald (Prospector research)
**Start:** 2026-10-29
**Verdict window:** 14 days, closes 2026-11-12
**Rung:** First paying customer, then Operator MRR

## Hypothesis
Putting the annual plan first with a computed saving and a clear one-payment promise will move more Operator checkouts to annual, without lowering total paid conversions.

## Stage moved
Clicks to paid, on the Korvus landing pricing section (korvus:korvus_landing.html). Annual is listed first with the computed savings label.

## Creative set (the three locked overlays)
1. "Operator annual: 79.99 a year. Save 39.89."
2. "Annual Operator. LodeStone included."
3. "One payment a year. Full Operator access."

Overlay text is rendered server side. No dollar amounts are hardcoded on the page; prices inject from Stripe display tokens.

## Number to watch
Annual share of Operator checkouts, split by UTM source on outbound Korvus links. UTM tagging shipped 2026-10-26 and is standing infrastructure, so this split is instrumented.

Baseline: the annual share over the 14 days before 10-29, read from the same UTM split. Record the baseline number in this note before the window opens.

## Decision rule
- **Win:** annual share rises against baseline and total Operator paid conversions hold or rise. Keep the framing and propose it as the default.
- **Loss:** total paid conversions fall, even if annual share rises. Revert.
- **Inconclusive:** annual share flat. Revert and try a different lead line.

Verdict is read on 2026-11-12. Any page change needs an owner green light in #boardroom before it ships.

## X post (under 280 characters, no em dashes)
> Annual Operator on Korvus: one payment a year, full Operator access, LodeStone included. Watching the market while you sleep so you don't have to refresh charts at 3am. Not financial advice. korvus.industries #futures #daytrading

## Guardrails
- No profit promises, no trading advice.
- Product claims carry the not-advice line.
- No emoji in outbound copy.

Not financial advice. Korvus is market intelligence and education, not trading advice.
```

---

Two open items. The baseline annual share has to be pulled from the UTM split before 10-29, since I don't have that number. And the page change itself needs to be filed as a proposal for the owner's green light. This note only defines the test.
