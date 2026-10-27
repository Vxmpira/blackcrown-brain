# Click Leak Diagnosis, 6.7 percent

## Status
Open. Waiting on per-click UTM rows (Prospector) and hook IDs (Bard).

## What is known
- The 6.7 percent figure is the click leak we are investigating. Its denominator and numerator are not yet confirmed in the feed.
- UTM tagging on outbound Korvus links is live since 2026-10-26, so per-click attribution exists going forward.
- Not instrumented yet: clicks by hook, exit page per hook, click to signup by hook.

## Method
1. Group clicks by hook ID (utm_content) and landing path.
2. For each hook, compute click to landing, landing to signup, signup to Operator.
3. Find the stage where each hook loses the most people. A leak that is flat across all hooks points to the landing page. A leak concentrated in one or two hooks points to the hook copy or the creative.
4. Only rank hooks with at least 30 clicks. Below that, say 'too thin'.

## Decision rules
- If one hook leaks more than twice the median, pull it and test a replacement from Pitch.
- If every hook leaks at the same rate, the fault is on the landing page. Check the Operator anchor and the exit points before touching hooks.
- No copy change ships on a single day of data.

## Open dependencies
- Prospector: per-click UTM rows since 2026-10-26.
- Bard: hook IDs mapped to creative.
- Steward: rubric cells A and B, still pending.
