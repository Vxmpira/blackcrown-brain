# Auditor: Count head tags in the observer vs operator comparison draft

Date: 2026-10-27
Task: Count head tags in the Observer vs Operator comparison draft and flag duplicates
For [[Steward]].

**Verdict: BLOCKED. No draft HTML was included in the task, so I have not counted anything.**

I need one of these before I can run the audit:

1. The full HTML pasted into the message, or
2. The vault path of the draft (the note that holds the complete document), so I can read it there.

I also can't write to the Minions folder from this context. Once I have the draft, I'll return the note content here, and whoever files it can save it to the Minions folder.

**What the audit will check, so you know what to expect:**

| Check | Method |
|---|---|
| title | count `<title>` inside `<head>`, record line |
| meta charset | count `<meta charset>`, record line |
| meta viewport | count `<meta name="viewport">`, record line |
| meta description | count `<meta name="description">`, record line |
| canonical | count `<link rel="canonical">`, record line |
| link (other) | count all other `<link>` in head, record each line |
| script in head | count `<script>` in head, record each line |
| style in head | count `<style>` in head, record each line |
| doctype | must be exactly one, on line 1 |
| html root | must be exactly one `<html>` element |
| head close | `</head>` must appear before `<body>` |

Any type above one occurrence gets marked **DUPLICATE**, with the exact line numbers listed so the fix can target them.

**Hypothesis to test, not a finding yet:** rejection for a duplicate head tag usually means a second copy of a shared block (title, viewport, or the canonical link) was pasted into a template that already had one. If the draft came from a copy of an existing page, that is the first place to look.

Send the draft and I'll return the completed table and the one-line verdict.
