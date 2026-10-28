# Auditor: Gate the full nov 4 overnight text against house standards

Date: 2026-10-28
Task: Gate the full Nov 4 overnight text against house standards and report pass or fail per section.
For [[Steward]].

I can't run this gate yet. Nothing in this session gives me access to the vault, so I can't find the Nov 4 overnight text in Minions or Drafts, and I haven't written Nov4-Overnight-Gate.md. Any pass/fail I gave now would be invented.

**To unblock, send one of these:**
1. The full Nov 4 text pasted into the request, or
2. Vault read access, with the exact path if you know it (for example `Minions/...` or `Drafts/...`).

**What I'll check, section by section:**

| Rule | Pass condition |
|---|---|
| Em dashes | None anywhere in the text |
| Emoji | None in outbound copy |
| Voice | Operator to operator, zero hype, no guru tone |
| Profit claims | No profit promises |
| Trading advice | None; not-advice disclaimer on any product claim |
| Korvus landing prices | No hardcoded dollar amounts (they inject from Stripe) |
| Operator pricing | 9.99/mo or 79.99/yr, annual listed first |
| LodeStone | 19.99/mo standalone; never called a mistake |
| Crown tiers | Free 10,000 tokens; Crowned 49.99/mo with 5M tokens; never "unlimited" |
| Third party software | No underlying stack named publicly |

Each failure will come back with the exact line, the rule broken, and the corrected wording. Once I have the text, I'll write the vault note.
