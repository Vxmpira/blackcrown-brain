# Escalations

## 2026, proposal 113 executor merge bug
- Proposal 113 was green lit but the executor's merge step failed to apply it correctly.
- This is server infrastructure, not a filing error, exact CURRENT anchor rules were followed.
- Escalated to Steward to diagnose the merge path and confirm the live file is not corrupted.
- Hold rule: do not refile 113 or similar merge dependent asks until Steward confirms the executor is healthy, a second failure after green light burns owner trust.
- Once fixed, verify the 113 change actually landed on the live file before closing the loop.