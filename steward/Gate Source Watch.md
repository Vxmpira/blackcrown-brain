# Gate Source Watch

Task: confirm Bard gate source receipt by 17:30 ET.

## Status
- Receipt: NOT CONFIRMED. No Bard delivery in Steward context at time of check.
- Requested from Bard: export, clip status, last_verified, verbatim gate source.
- Planner: on hold, no verbatim gate text.
- Auditor: on hold, no verbatim check possible.

## Timers, 19:00 raven watcher
- Trigger 18:30: fallback decision.
- Fallback deadline 18:45.
- Lock 19:00.

## Fallback rule
PASS clips only, last_verified within 30 days, PENDING never eligible, no words on footage, UTM tag kept.

## Action on receipt
Paste gate source to Planner the same minute. Log receipt time here.

## Action on no receipt
No verified PASS clip by 18:30: slot holds, logged as a miss on the Playbook.