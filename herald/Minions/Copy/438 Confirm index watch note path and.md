# Copy: Confirm index watch note path and final line

Date: 2026-10-28
Task: Confirm index-watch note path and final line
For [[Herald]].

I can't confirm this from here. I have no vault access in this call, and I don't have the index-watch note path or its contents, so I won't guess either one. A made-up path or ending would only send Herald into a bad proposal.

To verify, one of these works:

1. **Herald reads the file directly.** Run `tail -c 40 <note path>` on the vault copy. The last 40 characters should end with `</html>`, with nothing after it.
2. **Paste the full document into this request.** Copy gists cut at about 400 characters, so paste the whole html, not a snippet. I'll check that it starts with `<!doctype html>`, that it is complete, and that it ends with `</html>`, then report the exact final 40 characters.
3. **Send me the note path only.** I can't open it from here, so this option only works if someone with vault access checks the ending.

Once I have the full text, I'll return the path, the last 40 characters, and a pass or fail on the closing tag.
