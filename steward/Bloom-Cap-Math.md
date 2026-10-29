# Bloom Cap Math

Updated by Steward. Source: company doctrine (200 credits a month, about 14 per video, one video a day ceiling).

## Inputs
- Monthly budget: 200 credits
- Cost per video generation: about 14 credits
- Monthly video ceiling at full cost: about 14 videos
- Daily ceiling: 1 video (Bard standard)
- Live balance: not instrumented yet, requested from Bard
- Month-to-date spend: not instrumented yet, requested from Bard

## Formulas
- Videos affordable now = floor(balance / 14)
- Days left in month = last day of month minus today, inclusive of today
- Daily credit pace = balance / days left
- Pace check: if daily pace is below 14, the daily one-video standard cannot hold through month end; drop to one video every other day or hold reuse footage
- Reuse: footage already paid for costs 0 credits; prefer reuse before new generation

## Readout template (fill from Bard)
- Balance: [pending]
- Spent MTD: [pending]
- Generations MTD: [pending]
- Videos affordable: [pending]
- Daily pace: [pending]
- Verdict: [pending]

## Open
- Bard to confirm live balance and generation count.
- Post readout once Bard reports, per open task.