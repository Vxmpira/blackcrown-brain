# Auditor: Re gate crier s 11 01 globex rewrite for publish

Date: 2026-10-30
Task: Re-gate Crier's 11-01 Globex rewrite for publish readiness
For [[Steward]].

**Verdict: HOLD.** The rewrite text and source line were not in the packet, so I cannot confirm the placeholder check, the capture date, or the dash rule. Findings are ranked by impact.

1. **Blocker: source citation not verifiable.** No CME citation or capture date appears in what I received. Fix: paste the full source line with the CME trading hours URL and capture date (YYYY-MM-DD), then re-gate.

2. **High: the window reads as Globex's full hours.** Globex equity index trading runs 6:00 pm to 5:00 pm ET the next day, with a daily halt from 5:00 to 6:00 pm ET. The 6:00 pm to 9:30 am window is the overnight range, not the whole session. Fix: add the scope clause "Globex trades 6:00 pm to 5:00 pm ET; this overnight range runs to the 9:30 am cash open."

3. **High: "produces its own high and low" is stated as a fact about market behavior.** Fix: define the measurement instead: "the overnight high and low are measured from 6:00 pm to 9:30 am ET, separate from prior regular session levels." This keeps it education and makes no claim about what the levels do.

4. **Medium: dash scan not possible from here.** Fix: run a search for em dashes on the final text before filing, and replace any with commas, colons, or periods.

5. **Medium: destination channel not stated.** If this goes to X, the 280 character cap applies with links counted at 23 each, and it should carry no more than two hashtags. If it goes to YouTube, it needs the owner's Make publisher and a MEDIA link. Fix: name the channel in the ask so preflight can confirm it is wired.

6. **Low: citation covers one product only.** Fix: cite the trading hours spec for both E-mini S&P 500 (ES) and Nasdaq-100 (NQ), since the post names both.

Clear finding 1 and Crier can fix findings 2 and 3 in one pass. Re-gate after that.
