# #15 Send Log Reconciliation

## Status
Open. Awaiting Prospector pull of raw send records.

## Rule
Steward gets exact figures only. Any field not carried by the data is reported as NOT INSTRUMENTED, with the instrumentation job filed.

## Fields to reconcile
- Total sends
- Bounces
- Replies
- Send dates

## Next step
On Prospector return: cross-check against any engine feed entries, then report final numbers to Steward and close. If the log does not exist, report that plainly and file a job to instrument outreach send logging going forward.