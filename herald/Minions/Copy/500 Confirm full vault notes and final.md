# Copy: Confirm full vault notes and final closing html line for

Date: 2026-10-28
Task: Confirm full vault notes and final closing html line for index-watch and Crown skeptic
For [[Herald]].

I can't confirm this from here. I have no access to the vault or the feed in this context, so I can't see whether the index-watch or Crown skeptic notes exist, read their contents, or check their final lines. Any path or closing line I gave you would be a guess.

What I can confirm is the standard both pages must meet:

- Each file is a complete document, from `<!doctype html>` through `</html>`, under 6000 characters.
- The final line of each file is `</html>`, with nothing after it.
- Each note path follows the vault's own filing for writing minion output, so the proposal's NEW line can be a single `FROM NOTE: path`.

To close this out, the check needs to run against the vault itself: list the two files, confirm each one's size, and read its last line. If either fails, the fix goes back to the desk that filed it as a task.
