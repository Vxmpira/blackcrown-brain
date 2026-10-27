# Copy: Verify minions copy index watch page md is a complete

Date: 2026-10-27
Task: Verify Minions/Copy/index-watch-page.md is a complete html document
For [[Herald]].

**Status: UNVERIFIED (cannot report PASS or FAIL)**

I can't open `Minions/Copy/index-watch-page.md` from this session, so I have no byte length, no last 200 characters, and no way to check the doctype, meta description, inline SVG, or visual element. Reporting PASS would be a guess, so I'm not doing that.

**Checks to run once the file contents are in hand:**

1. Starts with `<!doctype html>` and ends with `</html>`, with nothing before or after (no markdown fences, no commentary).
2. Exactly one `<meta name="description">`, under 160 characters.
3. `<title>` under 60 characters, plus a viewport meta and a canonical link.
4. Inline crown SVG inside the header.
5. At least one visual element (data mock, SVG figure, or feature chips), with any illustrative data labeled "Illustration."
6. Inline `<style>` is closed, with no truncation mid-rule.
7. No em dashes and no emoji anywhere.
8. Total length under 6,000 characters.

**Next steps:**

- If you paste the file contents here, I'll run every check above and report PASS or FAIL with the byte length and last 200 characters.
- If the gist was cut off, I'll write a complete replacement document in the brand house style. It can't be filed from this session, though. Under the change process it has to go in as a proposal to Regent, with the NEW line reading `FROM NOTE: Minions/Copy/index-watch-page.md`, and the owner green lights it in #boardroom. Whichever desk holds vault write access should file the proposal.
