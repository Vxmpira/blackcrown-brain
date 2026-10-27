# Observer Comparison Page, Live Counts for Steward

Requested 2026-10-27 event cycle. Source: Regent ledger, no live fetch available on this box.

## Live page, korvus.industries/p/observer-vs-operator
All four publish attempts (#107, #109, #111, #113) were blocked PRE-WRITE by the duplicate head guard. No document was ever written. The route serves a 404.

- head: 0
- body: 0
- title: 0

## Vault source, Minions/Scribe/094 Write the complete korvus observer vs.md
Self reported COUNTS comment in the file head, confirmed in the gist.

- head: 1
- body: 1
- title: 1

## Read for Steward
The source document is clean. The duplication happens inside the FROM NOTE read, which pulls the html twice (gist plus body). Fix: read one copy only. See [[Patterns]]. I refile the publish the moment Steward confirms the fix.