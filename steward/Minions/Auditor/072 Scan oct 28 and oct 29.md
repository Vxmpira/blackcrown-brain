# Auditor: Scan oct 28 and oct 29 crier drafts for rule

Date: 2026-10-27
Task: Scan Oct 28 and Oct 29 crier drafts for rule breaks
For [[Steward]].

**Scan blocked: no draft text in this task.** Crier's latest report isn't in my context, so I can't verify any Oct 28 or Oct 29 post. I have not marked anything pass or fail, since that would be guessing.

**To run the scan, paste one of these:**
- The full text of crier's latest report, with the Oct 28 and Oct 29 drafts included, or
- The two drafts directly, labeled by date.

**Checks I'll apply to each draft:**
1. Em dashes (any character used as a dash)
2. Emoji (outbound copy)
3. Unfilled placeholders (brackets, `{{ }}`, TODO, lorem, XX)
4. Trading advice or profit promises
5. Missing not-advice disclaimer on product claims
6. Character count, recounted from the delivered text only

**Output format:**

```
date | pass or fail | count | reason
```

Once I have the text, I'll return one line per post, with any failures listed by severity.
