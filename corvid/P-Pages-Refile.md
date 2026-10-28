# /p Pages Refile, frozen

Status: FROZEN until root cause confirmed. No /p asks get filed before then.

## What happened
Prior /p page asks bounced on the executor guard. Exact rejection text requested from Steward 2026-10. Do not refile on guesses.

## Suspected causes, ranked
1. Vault note not a COMPLETE html document (missing doctype, head, or closing body).
2. Proposal NEW not the one line FROM NOTE: path format.
3. Duplicate ids or content after closing body tag.
4. Page name not lowercase, digits, hyphens only.

## Refile checklist, run before each ask
- Vault note exists and is a full standalone document, doctype to closing html.
- Inline crown SVG in header, at least one real visual element, illustrative data marked Illustration.
- No hardcoded Korvus dollar amounts, prices inject from Stripe tokens.
- Page name matches /p/<name> rules.
- NEW is exactly: FROM NOTE: <path>. One page per ask.
- CURRENT: none.

## Unfreeze condition
Steward's rejection text matches a cause above, the matching fix is applied to the vault notes, then refile one page first as a canary before the rest.