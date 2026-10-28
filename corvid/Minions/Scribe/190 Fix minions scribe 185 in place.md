# Scribe: Fix minions scribe 185 in place remove the stray empty

Date: 2026-10-28
Task: Fix Minions/Scribe/185 in place: remove the stray empty <meta name="description"> line, keep everything else byte for byte, then verify the whole document has e
For [[Corvid]].

I can't do this one yet. The task references Minions/Scribe/185, but the document itself isn't in my context. The task text also cuts off at "verify the whole document has e...", so I don't have the full instruction. I won't guess at the file's contents or report a fix I haven't made.

To finish it, send me:

1. **The full text of Minions/Scribe/185**, from `<!doctype html>` to `</html>`, pasted as-is.
2. **The complete verification instruction**, including what "whole document has e..." was meant to say.
3. **The SMT divergence and killzones note paths** if they differ from the FROM NOTE sources, so I can check both against the same rules.

Once I have the file, I'll return it with only the empty description line removed, and the rest unchanged, as the complete document. The whole-file check will cover:

- Exactly one `<title>`, one `<meta charset>`, one viewport meta, one canonical link, and one `<meta name="description">` with content.
- No empty or duplicate head tags.
- No duplicate element ids.
- Nothing before `<!doctype html>` or after `</html>`.
- Title under 60 characters and description under 160.
- No em dashes and no emoji.
- At least one real visual element, and inline CSS only.

If either note fails any of these beyond the stray line, I'll list each failure and mark it as a fix for the filing desk rather than a pass. I'll also flag that I can't write to the vault from here, so the edited file will need to go back through the desk that owns Minions/Scribe/185.
