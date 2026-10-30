# Planner: Map fallback a cta gate into dated steps and owners

Date: 2026-10-30
Task: Map Fallback A CTA gate into dated steps and owners
For [[Steward]].

**Scope note:** "Fallback A" is not defined in institutional memory. I've treated it as the alternate CTA path when the primary gate is blocked. Steward, confirm that before this runs. Dates are relative to the lock day (D0) because no calendar date was given.

**Target:** Korvus Operator annual, 79.99 a year, annual listed first with the computed savings label. Ladder rung: first paying customer.

| # | When | Owner | Action | Done-condition |
|---|------|-------|--------|----------------|
| 1 | D-1, morning | Herald | Draft the CTA body for Operator annual. Price stays server-injected, never hardcoded. Korvus links carry the standing UTM tags. | Draft is a complete file in the vault. No em dashes, no emoji, not-advice disclaimer present, no profit promises. |
| 2 | D-1, afternoon | Auditor | Clear the body against the claim, price, and disclaimer rules. | Clearance logged against the checklist. Any rejection returns to Herald as a task with the exact line that failed. |
| 3 | D0, by 18:00 ET | Human count (owner or named reviewer) | Human count of the cleared body and CTA placement before lock. | Count recorded with a timestamp. Lock is blocked until this exists. |
| 4 | D0, after 18:00 ET | Corvid | Lock the CTA and set the placement. If it touches a repo page, file a proposal (one page per ask, NEW as a single line, FROM NOTE pointing at the vault document). | Locked version matches the cleared draft. Proposal, if any, is green-lit in #boardroom and the approval states what it triggers. |
| 5 | D0 to D+7 | Herald | Watch UTM-tagged clicks and Operator annual purchases from the CTA. | Click and purchase counts reported daily. If per-variant attribution is missing, report "not instrumented yet" and file the job that adds it. |

**Fallback A, as mapped:** if the 18:00 ET count is missed, the lock moves to the next day's count and the CTA runs D+1. Nothing ships unlocked. This is my assumption, not a ruling.

**First step to fail: Step 3, the 18:00 ET human count.** It is the only gate that is both clock-bound and dependent on a person, and it sits after two desk handoffs, so a draft or clearance that slips by even a few hours misses the window. Steps 1 and 2 can fail too (a hardcoded price or a missing disclaimer would be caught at Auditor), but those failures surface earlier and cost only a revision.
