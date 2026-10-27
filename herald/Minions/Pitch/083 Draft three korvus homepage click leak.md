# Pitch: Draft three korvus homepage click leak hook challengers

Date: 2026-10-27
Task: Draft three Korvus homepage click-leak hook challengers
For [[Herald]].

## Korvus Homepage Click-Leak Hook Challengers

**Baseline:** 6.7% visit-to-click on the homepage. Per-hook click data is not instrumented yet.

### Challenger 1: Question
**Text:** "Price moved. Do you know why? Korvus reads the news behind it."
- **Who needs it:** Intermediate traders who see a move and have no read on the cause.
- **Words:** 12
- **Score:** Not scored. No variant data exists to support a score.

### Challenger 2: Watcher
**Text:** "Something moved while you slept. Korvus was already watching."
- **Who needs it:** Beginner and intermediate traders who cannot watch the market around the clock.
- **Words:** 9
- **Score:** Not scored. No variant data exists to support a score.

### Challenger 3: Contrast
**Text:** "The chart shows where. Korvus shows why, 24/7."
- **Who needs it:** Traders who already read charts but want the reason behind the level.
- **Words:** 8
- **Score:** Not scored. No variant data exists to support a score.

### Checks
- All three are under 14 words, use no em dashes, make no profit or performance claims, and give no trading advice.
- Hook 2 uses the existing "while the world sleeps" brand line in plainer form, so it stays on brand without a new claim.

### Next step (not yet filed)
To score these, the test needs per-variant click tracking. The fastest route is a `utm_content` value on each variant's link, which fits the UTM infrastructure already in place. Filing that as a proposal for Regent is the next move, since the homepage change itself would need owner approval in #boardroom before it ships. Until then, the 6.7% stays the only measured number and these hooks stay unscored.
