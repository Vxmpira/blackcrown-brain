# Projects

Updated 2026-10-28 by Steward.

## Board

### 1. Duplicate head tag guard (P1 BLOCKED)
- Goal: pages with a duplicated head tag pass the safety guard and ship, starting with the SMT divergence and ICT killzones keyword pages and the Observer page.
- Owner: corvid (source line and live counts), steward (ledger and routing).
- Status: blocked. Guard hits: Observer 107, 109, 111, 113; keyword pages 157, 158; rewrites 164, 165, 167, 168. Ledger shows 168 FAILED, no DONE line since.
- Corvid asked for full detail text of 167 and 168. Steward holds only the ledger result, not the detail text, so it is not sent. Steward asked Corvid for the source line and live counts, which unblock both.
- Next step: Corvid returns the head tag source line and live counts in one message. Steward confirms, then one refile of 167 and 168. No refile before that.

### 2. Rubric rescoring handoff (P1 BLOCKED, due 19:00 ET)
- Goal: hook rubric cells A and B reach Bard so Herald can rescore hooks.
- Owner: herald (writes literal cells to vault), bard (confirms receipt and vault path), steward (routing only).
- Status: blocked. No vault path named yet.
- Next step: Herald writes cells A and B to the vault and names the path. Bard reports the path it checked. Steward confirms before 19:00 ET.

### 3. Korvus signup lift (P1 REVENUE)
- Goal: move Korvus signups off zero. Today 0 visits, 0 clicks, 0 signups. 7 days: 33 visits, 2 clicks, 0 signups. Weakest stage is visit to click.
- Owner: herald (test and copy), corvid (landing and UTM verification), steward (routing and read-out).
- Status: open. Test not yet named.
- Next step: Herald names one signup test for today, with the stage it moves and the number it must beat.

### 4. Index-watch and Crown skeptic copy routing (P2)
- Goal: Herald gets complete copy for the index-watch request without Steward retyping it.
- Owner: crier (variants A and B in gist), herald (names vault path), steward (routing).
- Status: open. Herald path pending.
- Next step: Herald names the vault path. Steward routes the Crier variant file there.

### 5. Eclipse-X Nov 2 and Nov 3 posts (Community, signup and reply stage)
- Goal: two value posts in the Nov 2 and Nov 3 windows, each gated by Auditor on a complete vault file.
- Owner: crier (complete bodies to vault), auditor (gate on vault file), steward (scheduling).
- Status: blocked on vault access. Minions report no vault write or read in this session. Nov 3 clean body is saved in Community.md. Nov 2 body is not in the vault and needs a complete re-delivery from Crier.
- Next step: Crier re-delivers the full Nov 2 body. Steward files it. Auditor gates both files inside their windows.

## Standing rules
- Steward routes and never decides owner rulings. Titles, prices and direction go to Regent for the owner.
- A page that fails four times on the same guard is a P1 blocker, not a queue item.
- Recurring digests are server jobs. Check SERVER JOBS first.
