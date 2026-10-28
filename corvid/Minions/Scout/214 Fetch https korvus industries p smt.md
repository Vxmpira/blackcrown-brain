# Scout: Fetch https korvus industries p smt rendered html list every

Date: 2026-10-28
Task: Fetch https://korvus.industries/p/smt rendered HTML, list every head tag appearing more than once with exact lines in document order, then repeat for /p/sweeps 
For [[Corvid]].

**Finding: I could not fetch either page, so I have no duplicate head tags to report yet.** I have no live fetch access in this session, and I won't reconstruct the HTML from memory or guess at line numbers.

**Evidence and status**
- Not fetched: `https://korvus.industries/p/smt` and `https://korvus.industries/p/sweeps`. No rendered HTML is in my context.
- Not verified: the suspected head merge. Nothing here confirms or rules out canonical, og, or twitter duplication.
- Standing context: korvus.industries is a Flask app, and `/p/<name>` serves files from the repo's `pages/` folder. The source files for the rendered output should be `pages/smt.html` and `pages/sweeps.html`, so a source-level check is also possible without a fetch.
- Price injection is server side on the landing page only, so it should not explain head duplicates on these `/p` pages.

**Recommended moves**
1. **Run the extraction on a fetch-capable desk.** Use `curl -s https://korvus.industries/p/smt | python3 -c "..."` to parse the head, count each tag by its normalized form (rel=canonical, property=og:*, name=twitter:*, title, meta description), and print every duplicate with its line number and order. Repeat for `/p/sweeps`. Save both outputs so the removal proposal can anchor on exact lines.
2. **Check the source files in the repo before proposing removal.** Grep `pages/smt.html` and `pages/sweeps.html` for `rel="canonical"`, `og:`, and `twitter:`. If the duplicates are already in source, the fix belongs in the page file. If they appear only in the rendered output, the head merge is the cause and the fix belongs in the merge step. This tells Regent which proposal to file.
3. **Tie the removal to the sitemap rule.** Once fixed, confirm both pages still resolve and remain in step with the sitemap. Keep in mind that a removal proposal must name exact current anchors, and it should be filed only after the duplicate lines are confirmed.
