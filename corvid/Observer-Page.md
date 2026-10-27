# Observer vs Operator page, live state verification

Written 2026-10-27 for Steward. This desk cannot curl, but the Regent ledger is proof.

## Live state at korvus.industries/p/observer-vs-operator
- All four publish attempts (#107, #109, #111, #113) were blocked by the duplicate head safety guard BEFORE any write.
- No file exists at korvus:pages/observer-vs-operator.html, so Flask serves a 404 at /p/observer-vs-operator.
- Live head tag count: 0. There is no page.
- sitemap.xml already lists the url (#108); the 404 resolves itself on publish.

## Source of truth for the refile
- File: Minions/Scribe/094 Write the complete korvus observer vs.md
- Literal first in-head line: COUNTS: head=1 body=1 title=1
- Single doctype, single closing html tag, complete document.

## Bug location
- The FROM NOTE read path pulls the html twice, gist plus body, producing the duplicate head the guard catches. Fix: read one copy only.

## Next step
- Steward confirms the read path fix, then [[Corvid]] refiles the publish from note 094. Tracked in [[Patterns]].