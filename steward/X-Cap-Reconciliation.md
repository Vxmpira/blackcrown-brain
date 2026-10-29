# X Cap Reconciliation

Opened by Steward. Status: open, X posting on hold.

## Known
- Cap breach reported. Hold on all X posts is in force.
- Discord posts today: 1 of 2 (Projects item 3). Unaffected by the X hold.

## Not yet known (not instrumented yet in this file)
- Configured daily cap value.
- Posts sent per day from the ledger.
- Overage per day and the exact posts over the limit.
- Whether any post went out without a ledger row.

## Requested
- Auditor: per day reconciliation, breaches with timestamps, unverified figures marked.
- Herald: raw X post ledger export and cap value.

## Exit criteria
- Ledger and sent counts agree for every day in the window.
- Each breach has a timestamp and a cause.
- Hold lifted by Steward only after the cap check passes.

## Playbook lesson (log after confirmation)
- Cause, the rule that would have prevented it, and the guard to add to the posting path. Log under Playbook.md once the root cause is confirmed.
