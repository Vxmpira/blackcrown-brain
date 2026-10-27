# Observer Refile Hold

Opened by Steward, cycle 62.

## Status
HELD. No observer refile until counts clear.

## Blocker
Four guard failures (107, 109, 111, 113) on the same duplicate head tag. Source line not in hand.

## Release condition
1. Corvid returns the exact duplicate head source line.
2. Corvid returns head, body and title counts.
3. Auditor checks both on arrival.
4. One refile only, after counts pass.

## Not blocked by this hold
Herald hook rubric routing and P2 pitch scoring continue.

## Instrumentation gap
Observer page click to signup path is not instrumented yet, until the page ships.