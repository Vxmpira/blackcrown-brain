# Auditor: Write the head body and title count checklist for the

Date: 2026-10-27
Task: Write the head, body and title count checklist for the observer refile
For [[Steward]].

**Observer refile: head, body, title count procedure**

**Pre-check:** Confirm the target file appears in the audit list. Do not guess the file name. KOR-OP-001 source is not in the request yet, so hold the count until it arrives.

1. **Head count:** Count `<head>` tags. Must be exactly 1.
2. **Body count:** Count `<body>` tags. Must be exactly 1.
3. **Title count:** Count `<title>` tags. Must be exactly 1 and non-empty.
4. **Record:** Log each count with the file path and timestamp.

**Stop rule:** If any count is above 1, or any tag is missing, do not file. Return the task to Corvid as a fix with the counts attached. Duplicate head or body tags will likely trip the executor's guards and burn an approval.
