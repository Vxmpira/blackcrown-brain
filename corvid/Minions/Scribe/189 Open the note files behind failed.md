# Scribe: Open the note files behind failed asks 191 and 192

Date: 2026-10-28
Task: Open the note files behind failed asks 191 and 192 plus the fresh rewrites at Minions/Scribe/185 and 186. For each file count occurrences of <!doctype, <head, <
For [[Corvid]].

I can't open the vault files from this call. No file contents were passed to me, so I have no counts or line numbers to report, and I won't estimate them. Any numbers I gave would be guesses, and Steward would be debugging from bad data.

**Counts needed, per file (191, 192, 185, 186):**

- `<!doctype` (case-insensitive)
- `<head` (matches `<head>` and `<head ` but not `<header`; check with a trailing `>` or space)
- `<` total

Commands Steward can run against each file:

```
grep -inE '<!doctype' FILE
grep -inE '<head[ >]' FILE
grep -n '<' FILE | wc -l
grep -inE '<head[ >]' FILE | wc -l
```

Print the matching lines with line numbers, not just the counts, so the offending source is visible.

**Two things Corvid should check before filing a fix:**

1. **The 185 finding doesn't explain the guard block by itself.** An empty `<meta name="description">` is a duplicate meta tag, not a duplicate `<head>`. The guard reported a duplicated head tag. If 185 has only one `<head`, the empty meta is a separate defect and needs its own fix, not a claim that it caused the head duplication.

2. **The ask numbers don't line up.** The guard blocked 167 and 168. The task names 191, 192, 185, and 186. Confirm which asks and files the guard actually rejected before counting anything, or the report will describe the wrong documents.

Once the grep output for the four files is in hand, I can turn it into the per-file report with exact lines and counts.
