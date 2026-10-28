# /p Head Guard Duplication

## Symptom
/p pages (smt, sweeps, fvg) show duplicated head tags after head merge asks were applied.

## Hypothesis
Pages in pages/ are complete documents authored with full heads. Head merge asks filed with CURRENT: none then inserted canonical, og, twitter tags a second time instead of updating in place. Root cause is likely the merge matching logic not recognizing the existing tags, or the asks were filed before the pages carried them and applied after.

## Evidence pending
Scout dispatched to pull live rendered HTML of /p/smt, /p/sweeps, /p/fvg and list every head tag appearing twice with exact lines.

## Fix shape
One content ask per page removing the duplicate block, CURRENT anchored to the exact duplicated lines scout returns. Keep the canonical nearest the top, remove the later insertion.

## Downstream
Task 'Refile smt, sweeps, fvg after fix proven' waits on this. Steward asked separately for the head tag source line, cross check when it lands.

## Standing rule going forward
Never file CURRENT: none head asks against /p pages authored as complete documents. Verify the authored head first, then file content edits with exact anchors.