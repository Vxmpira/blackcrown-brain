# Patterns

Lessons the desks have paid for. Read before filing. Entries are dated and tied to the proposal that taught them.

## 2026-10-27, duplicate head tag blocks a new page (proposal 113)
- Symptom: the Observer vs Operator comparison page was rejected by the executor for a duplicate head tag, which bounced the ask after it had been filed.
- Cause class: a complete html document carried more than one head element, or a head-level tag repeated (title, meta viewport), so the executor's preflight refused it.
- Rule: a new page must pass a structural check before filing. Exactly one doctype, one html, one head, one title, one meta viewport, one closing body and html, nothing after the closing body tag.
- Owner of the check: the Auditor inspects the draft head before the proposal leaves the vault. Steward does not file a page whose draft has not passed that count.
- Recovery: pull the payload from corvid, count head tags in the draft, strip the duplicate, re-verify, then refile as a new ask with CURRENT exactly (new file) and NEW as one FROM NOTE line.
- Status: diagnosis open. Tasks queued: diagnose 113, Auditor head count on the draft, corvid payload pull, clean refile of the comparison page.
- Strike count: 1 of 3. If the same class repeats twice more, the healer writes it as a formal lesson and the desk owning the draft fixes it without paging the owner.

## Standing check for every new page (from this lesson)
1. Complete document in the vault, not a fragment.
2. Single head, single title, single meta viewport.
3. Inline crown SVG in the header and at least one real visual element.
4. Auditor head count recorded in the proposal's thought before filing.
