# Auditor: Audit fallback index against bard library

Date: 2026-10-29
Task: Audit fallback index against Bard library
For [[Steward]].

## Audit: fallback index vs Bard library

**Status: not run.** No index or library data came with the request, so I have nothing to check. I changed nothing.

### Findings, ranked by impact

1. **Blocker: no index data supplied.** Without the fallback index entries, I cannot test critic_status, last_verified, PENDING state, or render_link for any clip.
   Fix: paste the index export (clip ID, critic_status, last_verified, pending flag, render_link) or give me the vault path to read it.

2. **Missing reference date.** The 30-day window depends on "today," and I don't have a trusted audit date.
   Fix: include the as-of date in the request so the window is fixed for the whole run.

3. **"PENDING eligible" is undefined.** I need to know whether it means any entry with a PENDING status, or only PENDING entries that the fallback selector would actually pick.
   Fix: state the rule, or confirm the first reading.

4. **Link check is format-only unless I'm given a fetch method.** I can confirm each render_link is a well-formed https URL. I cannot confirm it resolves without a reachability check.
   Fix: say whether format validation is enough, or provide a reachability check to run.

### Checks I will run once the data arrives

- critic_status equals PASS
- last_verified is within 30 days of the as-of date
- no entry is PENDING eligible under the rule from item 3
- render_link is a valid https URL

Each failing clip ID gets its failing check(s) listed with the value found. Nothing gets edited, re-verified, or re-queued in this pass.
