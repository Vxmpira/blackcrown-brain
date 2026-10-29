# Analyst: Convert x snowflake post ids 2115613024790683956 and 2115639195154657756 to exact

Date: 2026-10-29
Task: Convert X snowflake post ids 2115613024790683956 and 2115639195154657756 to exact UTC creation timestamps
For [[Corvid]].

## Snowflake timestamps: both posts converted to UTC

**Post 1 (2115613024790683956):** `2026-10-29 01:13:45.956 UTC`
**Post 2 (2115639195154657756):** `2026-10-29 02:57:45.457 UTC`

Both fall on 2026-10-28 in ET, as expected. Post 1 is 21:13:45.956 EDT and Post 2 is 22:57:45.457 EDT.

## The math

Formula: `ms = (id >> 22) + 1288834974657`

Shifting right 22 bits equals floor(id / 4,194,304). I divided in three floored steps (÷4, ÷1024, ÷1024), which gives the same result as one floored division.

**Post 1**
- id ÷ 4 = 528,903,256,197,670,989
- ÷ 1024 = 516,507,086,130,538 (remainder 77)
- ÷ 1024 = 504,401,451,299 (remainder 362)
- That is the `id >> 22` value. Add the epoch offset:
- 504,401,451,299 + 1,288,834,974,657 = **1,793,236,425,956 ms**
- = 1,793,236,425.956 s since Unix epoch
- = 2026-10-29 01:13:45.956 UTC

**Post 2**
- id ÷ 4 = 528,909,798,788,664,439
- ÷ 1024 = 516,513,475,379,555 (remainder 119)
- ÷ 1024 = 504,407,690,800 (remainder 355)
- Add the epoch offset:
- 504,407,690,800 + 1,288,834,974,657 = **1,793,242,665,457 ms**
- = 1,793,242,665.457 s since Unix epoch
- = 2026-10-29 02:57:45.457 UTC

**Cross-check:** the gap between the two posts is 6,239.501 s, or 1h 43m 59.5s. 01:13:45.956 + 1:43:59.501 = 02:57:45.457, which matches.

**Unix-to-calendar check:** 1,700,000,000 is 2023-11-14 22:13:20 UTC. Adding 1,793,236,425 − 1,700,000,000 = 93,236,425 s gives 1079 days plus 3:00:25. That lands on 2026-10-29 01:13:45 UTC.

**Ledger note:** the snowflake timestamp is the creation time, and it has millisecond precision. Use the UTC values above in the brand post ledger, and keep the ET labels as display only.
