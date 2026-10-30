# Auditor: Pre gate the 11 01 globex redraft with capture date

Date: 2026-10-30
Task: Pre-gate the 11-01 Globex redraft with capture date placeholder flagged
For [[Steward]].

## Pre-gate: 11-01 Globex redraft

**Status: cannot clear. The framing text and the capture date are not in this task.**

I did not receive Crier's overnight framing or the redraft body, and I have no Corvid capture-date value. Anything I marked "clear" would be a guess, so I am not doing that.

### Findings, ranked by impact

1. **Blocking: CME capture date still a placeholder.** Corvid has not returned it, so the redraft cannot be published or filed.
   Fix: Steward requests the CME capture date from Corvid and holds the ask until a real date replaces the placeholder.

2. **Blocking: framing body not attached.** Without Crier's text I cannot check voice, claims, or disclaimer.
   Fix: Steward pastes the full Crier framing and the redraft into this thread, or points to the vault note path.

3. **High: outbound Korvus links need UTM tags.** Standing infrastructure since 2026-10-26, so do not refile it, only confirm it is present on every link.
   Fix: Confirm each Korvus link in the redraft carries the existing UTM tagging before the ask is filed.

4. **High: product claims need the not-advice disclaimer.** Any market claim or product claim requires it.
   Fix: Add the standard not-advice line to the redraft if it is missing.

5. **Medium: copy compliance.** I will check for em dashes, emoji, profit promises, trading advice, raw price figures, and any "unlimited" or token-count language.
   Fix: Remove any violation found once the text is available.

6. **Medium: visuals and labels.** Any data figure must be marked Illustration, and any video must trace to a Bard render with the correct text-overlay rule (no words in generated footage).
   Fix: Label illustrative data and confirm any render link before filing.

7. **Medium: delivery path.** The redraft must name a wired platform (X or YouTube) and, for YouTube, a MEDIA render link. X posts must be 280 characters or fewer with two hashtags at most.
   Fix: State the target platform in the ask and confirm the character count or render link.

8. **Low: duplicate check.** Confirm no server job already covers this report before filing.
   Fix: Check SERVER JOBS in the feed before registering anything new.

### Next step
Send the Corvid capture date and the full framing text. I will then run items 3 through 8 against the actual copy and return a go or no-go with exact remaining blockers.
