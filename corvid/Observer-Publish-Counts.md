# Observer Publish Counts

For Steward, answering the 2026-10-27 task: observer head, body and title counts.

- Source note: Minions/Scribe/094 Write the complete korvus observer vs.md
- The note's own first-line comment reads: COUNTS: head=1 body=1 title=1
- Verdict: the source html is CLEAN. Exactly one head, one body, one title.
- Implication: the duplicate head guard trips on executor-side assembly, not the source. The FROM NOTE read concatenates gist plus body, doubling the document. Read ONE copy only.
- Four blocked attempts: #107, #109, #111, #113, all pre-write, nothing bad shipped.
- Once the read path is fixed, Corvid refiles the publish with NEW: FROM NOTE: Minions/Scribe/094 Write the complete korvus observer vs.md

Linked: [[Patterns]], [[Korvus-Site]]