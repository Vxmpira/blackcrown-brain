# Planner: Draft six gate text for the 19 00 raven watcher

Date: 2026-10-29
Task: Draft six-gate text for the 19:00 raven watcher run, ready to receive the Bard index export.
For [[Steward]].

## Raven Watcher 19:00 ET Run: Gate Text

**Stage:** Visits to clicks. Clicks are the success metric for this run; visits are reported but do not qualify a clip.

**Timing**
- **Fallback deadline:** 18:45 ET. If the Bard index export has not landed by then, the run does not lock on partial data. Steward is notified.
- **Lock:** 19:00 ET. Nothing enters or leaves the set after lock.

**Six gates (applied in order to every clip in the index export)**

1. **PASS only.** The clip's gate status must read PASS. Any other status is excluded.
2. **Fresh verification.** last_verified must fall within 30 days of the lock time. Older entries are excluded.
3. **PENDING is never eligible.** A clip still marked PENDING is excluded regardless of other fields, even if every other gate reads clean.
4. **No words on footage.** Generated footage contains no text, letters, numbers, or logos. Words appear only through the overlay field, as exact literal lines baked on by the forge. Any clip with text in the footage itself is excluded.
5. **UTM tag kept.** The outbound Korvus link keeps its UTM tagging intact. A clip whose link lost or altered the tag is excluded.
6. **Critic PASS required.** Bard's critic must have passed the direction. No critic PASS, no entry.

**Auditor step:** Auditor runs all six gates on arrival, at export receipt, not at lock. Each clip is logged as passed or excluded with the gate number that failed it.

**Owner and desk handoffs**

| Step | Owner | Done when |
|---|---|---|
| Export delivered to Auditor | Bard | Index export lands before 18:45 ET |
| Gates run on arrival | Auditor | Every clip has a pass or excluded record with gate number |
| Set locked | Steward | Run locks at 19:00 ET with the passed set only |
| Captions and angles pulled, if needed | Bard (from Herald and Corvid) | Requests resolved before lock |

**Note on the 11:00 template:** I built this from the six gates and timing you gave me. The 11:00 slot template is not in my working context, so if it carries fields beyond these (report destinations, approval wording, or the lock-state line), paste it and I will align the 19:00 text to it exactly.
