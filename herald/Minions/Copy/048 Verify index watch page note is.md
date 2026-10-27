# Copy: Verify index watch page note is complete and ship ready

Date: 2026-10-27
Task: Verify index-watch page note is complete and ship-ready
For [[Herald]].

I can't verify this one yet. The task context stops mid-sentence at "Confirm doctype through the closing", and I don't have read access to Minions/Copy/index-watch-page.md from here. Any verdict I gave without the file would be a guess, and a bad ship verdict costs the owner trust.

To finish the check, paste the file contents or re-file the task with the full text. I'll verify these:

1. **Document boundaries:** starts with `<!doctype html>` and ends with `</html>`, with nothing before or after, and no markdown fences or commentary.
2. **Head:** a title under 60 characters, a meta description under 160, a viewport meta, a canonical link, and inline CSS.
3. **Brand rules:** no em dashes, no emoji, and the inline crown SVG logo in the header.
4. **Visuals:** at least one real visual element (data mock, SVG figure, or feature chips), with illustrative data labeled "Illustration".
5. **Claims:** no profit promises, no trading advice, the not-advice disclaimer on product claims, no "unlimited" for Crown, and prices that match the ladder (Operator 9.99 a month or 79.99 a year; LodeStone TradingView 19.99 a month; LodeStone Tradovate $149 one time). No hardcoded dollar amounts on the Korvus landing page.
6. **Completeness:** every section written in full, no placeholders, no unclosed tags, and the closing tags intact.
7. **Routing:** if this is a new Korvus page, it is destined for pages/ and serves at /p/<name>, with a lowercase, digits, and hyphens name. If it is a brand site page, it is a root html file, which is live on push to main. Pushes to main are production, so I'll flag that before anything is filed.
8. **Preflight:** no server job already covers the report, and the platform is wired (youtube is the only wired video platform).

Once I have the file, I'll return a pass or fail on each item, with exact line-level fixes for anything that fails. If it passes, I'll write the one-line proposal for Regent in the form NEW: FROM NOTE: Minions/Copy/index-watch-page.md, so the owner can green light it in #boardroom.
