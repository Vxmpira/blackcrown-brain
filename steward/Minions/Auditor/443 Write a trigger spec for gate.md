# Auditor: Write a trigger spec for gate item 2 and 3

Date: 2026-10-29
Task: Write a trigger spec for gate item 2 and 3 recheck
For [[Steward]].

## Auditor findings, ranked by impact

1. **The 7-day signup criterion cannot be judged at the 17:00 ET 10-30 recheck.** A 7-day window starts when the page goes live, so the recheck can only read leading indicators. Fix: split the gate into a go/no-go at 17:00 (item 2 landed, item 3 instrumented) and a dated 7-day readout that files its own check.
2. **The 280 click baseline has no source in institutional memory.** The 1.5x target (420 clicks) is meaningless until the baseline is confirmed. Fix: Herald names the query or report that produced 280 and its date window before the recheck runs; otherwise mark the click criterion "not instrumented yet."
3. **"Human visits" is undefined.** Bot filtering and the measurement source are not specified. Fix: define human visits as the analytics count with bot and crawler traffic excluded, and name the source; if that source does not exist, mark it "not instrumented yet" and file the job that would instrument it.
4. **No fallback owner exists.** A recheck that fails silently at 17:00 wastes the owner's attention. Fix: the fallback below routes the miss back to Herald as a task, per filing integrity.

## Trigger spec: Gate recheck, items 2 and 3

**Gate items**
- **Item 2:** Variant C vault path and copy filed by Herald.
- **Item 3:** Success criterion, measured on Variant C traffic:
  - 300 human visits
  - Click rate at least 1.5x the 280 baseline (target: 420 clicks, pending baseline verification)
  - 3 signups within 7 days of go-live

**Trigger condition (fires the recheck)**
The recheck runs when all of the following are true before 17:00 ET 10-30:
- A Variant C file exists in the vault as a COMPLETE html document (not a stub, not a fragment).
- The filing names the exact vault path and is linked to the gate item.
- The Variant C copy passes the brand law: no em dashes, no emoji in outbound copy, no profit promises, disclaimer present, no memory-gap claims in any Crown copy.
- The platform and target page are wired (for Korvus, a routed or pages/ path under /p/<name>).

The trigger fires on the first filing that meets all four conditions. A filing that fails any condition does not fire the trigger; it returns to Herald as a task with the failed condition named.

**Recheck evaluation (at trigger)**
1. Item 2: confirm the path resolves and the copy passes the checks above.
2. Item 3, visits: report human visits since go-live. If the source is not instrumented, report "not instrumented yet."
3. Item 3, clicks: report clicks against the verified baseline. If the baseline is unverified, report "baseline unverified."
4. Item 3, signups: report 0 at the 17:00 recheck with the 7-day window open, and schedule the dated readout for go-live plus 7 days.
5. Output a single pass, hold, or fail per item to Steward.

**Fallback at 17:00 ET 10-30**
If the trigger has not fired by 17:00 ET:
- Gate item 2 is marked MISSED for this recheck. Item 3 is marked NOT EVALUATED.
- Auditor files a task back to Herald naming the missing Variant C path and the failed condition. The fix lands on Herald, not the owner.
- Steward is notified that the gate slipped. The owner is not paged; he rules on direction only if the slip changes the direction of the gate.
- The recheck re-arms automatically on the next qualifying filing. It does not expire into a new ask unless the 48 hour expiry applies.

**Not in scope of this spec**
- Billing or Stripe changes.
- Any copy that claims profit or trading results.
- Any change to the 19.99 LodeStone TradingView price or the Korvus Operator ladder.
