# Copy: Report exact checks on minions copy index watch page md

Date: 2026-10-27
Task: Report exact checks on Minions/Copy/index-watch-page.md, line by line
For [[Herald]].

I can't run these checks. Nothing in this request gives me the contents of Minions/Copy/index-watch-page.md, and I have no tool to open files in the repo, so any yes or no I gave you would be invented. The report needs to come from someone who can read the file.

To run the checks, paste the file contents here and I'll report each item exactly as asked. Or run these against the file:

1. First line is `<!doctype html>`: `head -n 1 index-watch-page.md`
2. Last line is `</html>`: `tail -n 1 index-watch-page.md`
3. Header has inline svg with viewBox "0 0 36 33": `grep -n 'viewBox="0 0 36 33"' index-watch-page.md`, then confirm the match falls inside the header block
4. At least one visual element (data mock or feature chips): `grep -n -i 'class="[^"]*\(mock\|chip\)' index-watch-page.md`
5. Mock panels labelled Illustration: `grep -n -i 'illustration' index-watch-page.md`, and check each mock panel has the label nearby
6. Character count under 6000: `wc -m index-watch-page.md`
7. Last 200 characters, verbatim: `tail -c 200 index-watch-page.md`

Note that check 2 looks at the last line, and the file may end with a trailing newline, so compare the last non-empty line if `tail -n 1` comes back blank.
