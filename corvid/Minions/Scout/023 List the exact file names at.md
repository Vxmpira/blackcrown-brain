# Scout: List the exact file names at the korvus repo root

Date: 2026-10-26
Task: List the exact file names at the korvus repo root from the latest site audit, flag which ones are app or tool pages versus marketing pages
For [[Corvid]].

# Scout Report: Korvus Repo Root File Inventory

**Finding: No site audit data was attached to this task, so I cannot list exact file names with confidence. Below is what the task context itself confirms, clearly separated from inference.**

## Evidence

**Confirmed from provided context (not the audit):**
- Files follow a `korvus_` prefix convention at repo root
- `korvus_landing.html` exists and is the homepage (marketing page, should NOT be noindexed)
- A promo_studio page exists, likely `korvus_promo_studio.html` (handled separately per proposal #42)
- A dashboard page exists, likely `korvus_dashboard.html` (also handled separately)
- A main app page exists that is the noindex target, exact name unknown

**Reasoning from general knowledge (not grounded in data):**
- Common candidates for a main app page name would be `korvus_app.html`, `korvus_terminal.html`, or `korvus_main.html`. Korvus is a market terminal, so `korvus_terminal.html` is plausible, but this is a guess, not a finding
- Filing proposal #42 with a guessed file name is likely how the original edit failed. Do not refile on inference

## Recommended Moves

1. **Pull the actual file list before refiling.** Request a fresh repo root listing (`ls korvus_*` or equivalent) or re-run the site audit. One command resolves this with zero ambiguity.
2. **Verify the target page by content, not name.** Once you have the listing, confirm the main app page by checking it is not `korvus_landing.html`, not the promo_studio file, and not the dashboard file. Whatever remains with app-shell markup is the target.
3. **Add the file inventory to proposal #42 itself** so the next edit attempt has the exact path baked in and this failure mode is closed permanently.

Send me the audit output or repo listing and I will turn this around with exact names in one pass.
