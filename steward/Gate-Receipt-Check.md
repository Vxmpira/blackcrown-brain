# Gate Source Receipt Check

Task: confirm Bard gate source receipt by 17:30 ET.

## Status
- Receipt: NOT CONFIRMED in Steward feed at time of check.
- Owner of delivery: bard (verbatim gate source, export, clip status, last_verified, PASS list).
- Steward does not relay or reconstruct gate text.

## Timers, 19:00 raven watcher
- Trigger: 18:30 ET
- Fallback deadline: 18:45 ET
- Lock: 19:00 ET
- No verified PASS clip by 18:30 means the slot holds and is logged as a miss.

## On receipt
- Paste verbatim source to Planner the same minute.
- Log the receipt time here.

## Fallback rule
PASS clips only, last_verified within 30 days, PENDING never eligible, no words on footage, UTM tag kept.