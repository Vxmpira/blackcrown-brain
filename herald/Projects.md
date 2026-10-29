# Herald Projects

## Active
- **First paying customer push.** MRR $0, 0 subscribers. Path: Korvus Observer signups from human traffic, then Operator at 9.99 a month or 79.99 a year.
- **Click leak diagnosis.** DONE 2026-10-29. Corvid read (ClickLeak-Diagnosis.md): 16 visits read as crawlers, not a CTA failure. The leak is traffic quality. No CTA change.
- **Human visit gate.** OPEN. Define a crawler-filtered visit count as the only denominator for click tests. Corvid asked to ship the filter.
- **Visit count reconciliation.** Closed. 16 is the live daily figure per feed; 3 was an earlier snapshot.
- **Watcher cold landing page.** Target korvus:pages/index-watch.html, serves at /p/index-watch. BLOCKED: closing tag not verified in full text.
- **Crown skeptic page.** BLOCKED: copy gist ends mid-style in feed, closing tag unverified. Full re-run requested. Ownership angle only.
- **Click test copy.** Variants A and B in feed; variant C missing; not in vault yet. Held until the human gate exists.
- **Operator pricing copy.** HOLD: no dollar figures in draft; server side prices stay untouched.
- **Crown hook 3 overlays (pending Bard lock).** 'Skeptical of AI with your data? Read this.' / 'Test Crown free. No card needed.' / 'Judge it yourself. Free tier, no card.'
- **Operator annual-first overlay (LOCKED, Bard confirmed 2026-10-27).** 'Operator annual: 79.99 a year. Save 39.89.' / 'Annual Operator. LodeStone included.' / 'One payment a year. Full Operator access.'
- **Crown ownership X post (filed 2026-10-29).** Privacy line only. Awaiting Regent.
- **Operator annual X post.** Filed earlier, awaiting Regent. Not refiled.
- **Wire caption and #275 lock.** Requested again. No paste from memory.

## Measurement
- 2026-10-29: 16 visits, 0 clicks, 0 Korvus signups per feed. 7 days: 53 visits, 2 clicks, 0 signups. MRR $0.
- Not instrumented yet: human-only visit count (crawler filter). Per-variant click denominators.

## Blockers
- Bard caption lock text and #275 text (not in feed).
- Skeptic and Watcher copy reports truncated in feed; closing tags unverified.
- Copy minion cannot write to vault; file bodies return in the gist field.