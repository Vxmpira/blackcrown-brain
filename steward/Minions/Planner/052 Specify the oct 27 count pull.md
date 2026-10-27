# Planner: Specify the oct 27 count pull for corvid

Date: 2026-10-27
Task: Specify the Oct 27 count pull for Corvid
For [[Steward]].

## Oct 27 Count Pull: Spec for Corvid

**Owner:** Corvid (vault access; Auditor and Crier do not have it)
**Rung:** First paying customer, and the Herald quotas (50 Korvus signups, 100 new Eclipse-X joins)
**Done when:** One line per metric below is written to the vault record for 2026-10-27, each with a value, a prior-day comparison, and a source. Any metric without a source reads "not instrumented yet."

### Steps

1. **Pull Eclipse-X head count.** Total members at snapshot time, plus the new-join count since Oct 26. Source: Discord server member count. Track the running total against the 100-join quota.
2. **Pull korvus.industries signups.** Total Observer accounts at snapshot time and the delta since Oct 26. Track the running total against the 50-signup quota. Source: Korvus account records.
3. **Pull Operator conversions.** New Operator subscriptions since Oct 26, split monthly and annual. Source: owner-supplied only. Agents never touch billing, so do not query Stripe; if the owner has not supplied it, record "owner-supplied, pending."
4. **Pull Crown signups.** New free-tier accounts (no card) and any new Crowned subscriptions since Oct 26. Source: Crown account records.
5. **Pull LodeStone sales.** Tradovate one-time sales ($149) and TradingView subscriptions ($19.99/mo) since Oct 26, kept as separate lines. Source: owner-supplied only, same rule as step 3.
6. **Pull UTM-tagged Korvus link clicks** by utm_source for Oct 27 against Oct 26. UTM tagging is live infrastructure. If the analytics view is not reachable, record "not instrumented yet" and flag it for Steward.
7. **Pull reply counts.** Three lines: Server AI answers delivered in #server-ai (member questions used, weekly cap of 10 per member); inbound email to BlackCrownVxJ.LLC@outlook.com; and support-form submissions received via the SES relay. Mark any source that cannot be read as "not instrumented yet."
8. **Write the vault record.** Post all lines in the format below under a single heading for 2026-10-27, then mark the task complete.

### Line format

```
2026-10-27 | metric name | value | Oct 26: prior | delta: +/-N | source
```

Example shape only (values are not from this spec):
```
2026-10-27 | eclipse-x head count | [value] | Oct 26: [value] | delta: +N | discord member count
```

### Notes
- Record what is actually read. Do not estimate or carry forward a prior value as today's.
- Source-gated metrics (Operator, LodeStone) stay "owner-supplied, pending" until the owner provides them. That is not a gap in Corvid's work.
- If any source is missing, file the instrumentation job through Steward rather than working around it.
