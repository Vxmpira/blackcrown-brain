# Planner: Split bard s bloom instrumentation ask into fields and sources

Date: 2026-11-01
Task: Split Bard's Bloom instrumentation ask into fields and sources
For [[Steward]].

## Bloom instrumentation: field map

I can't see the live feed or the payload of the registered Bloom credit burn digest from this brief, so the "digest carries it" column is marked from the doctrine, not verified. Confirm each one against the digest's definition before anything is filed.

| # | Field | Source that holds it | Digest carries it? |
|---|---|---|---|
| 1 | Bloom credit balance (current) | Bloom account balance, the same balance line Bard watches on every delivery | Unverified. Likely absent, since the doctrine describes it as read per delivery, not as a digest field |
| 2 | Credits burned per render | Render cost record per generation (clips bill by length, 15s now, about 14 credits for 5s) | Unverified. Burn totals may exist; per-render cost probably does not |
| 3 | Render slot ID | Server render queue / Furnace job record | Not instrumented yet as far as the doctrine shows. No source is named for slot IDs |
| 4 | Daily cap usage vs. cap | Server's daily generation counter (the cap refusal point) | Unverified |
| 5 | Refused generations (cap hits) | Server cap refusal log | Unverified |
| 6 | Reused footage count (paid-for footage served instead of re-bought) | Server reuse ledger | Unverified |
| 7 | Resumed generations count (interrupted jobs continued, not re-bought) | Server resume ledger | Unverified |
| 8 | Render ID to YouTube link (the "every render ships" trace) | Render record plus the YouTube post ask/publish record | Unverified. Likely outside the burn digest entirely |

## Gaps and next checks

- **Slot IDs (field 3):** the one field with no named source. Establish whether the Furnace job record already assigns an ID before anything is proposed. Until then, report it as not instrumented yet.
- **Digest audit:** pull the registered Bloom credit burn digest's field list and tick the "carries it?" column against it. That single read resolves most rows.
- **Balance (field 1):** the doctrine says the balance line is watched on every delivery, so confirm where Bard reads it. If it only lives in delivery text, the feed needs it as a structured field.

No filing made.
