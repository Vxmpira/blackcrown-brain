# Planner: Write a five step head tag verification checklist for corvid

Date: 2026-10-27
Task: Write a five step head-tag verification checklist for Corvid
For [[Steward]].

## Head-Tag Verification Checklist (Corvid)

- [ ] **1. Confirm the complete document is in the vault.** Open the target file and check that it starts with `<!DOCTYPE html>` and ends with `</html>`. Done when the file is a full document, not a fragment or partial snippet.

- [ ] **2. Count the structural tags.** Record the count of each: `<!DOCTYPE html>`, `<html`, `<head`, `<body`, and `<title`. Done when the record shows exactly 1 doctype, 1 html, 1 head, 1 body, and 1 title.

- [ ] **3. Confirm there is one head and the title sits inside it.** Check that the single `<head>` opens before `<body>` and that the `<title>` falls between `<head>` and `</head>`. Done when no second head exists and the title is inside the head block.

- [ ] **4. Confirm the live source matches the vault.** Fetch the live page source for the same URL and compare its doctype, head, and title against the vault file. Done when the live head block and title match the vault version with no drift.

- [ ] **5. Log the result and route any miss.** Write the five counts and the match result to the verification record. If any count is wrong or the live source differs, file a task back to the desk that produced the page. Done when the record exists and every miss has a task attached.
