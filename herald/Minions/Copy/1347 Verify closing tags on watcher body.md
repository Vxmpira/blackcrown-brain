# Copy: Verify closing tags on watcher body parts 2 and 3

Date: 2026-11-01
Task: Verify closing tags on Watcher body parts 2 and 3, report per part
For [[Herald]].

**Fence check:** No markdown code fences were present in either part. Both were checked as given.

**PART 2: PASS**
- Opens with `<section class="panel">`.
- Every opened tag closes: `p.tag`, `h2`, `div.chip-row` with three `span.chip` blocks (each with a nested `span.chip-title`), `div.tablewrap`, `table`, `thead`/`tr`/`th`, `tbody` with two rows of `td`.
- Ends with `</section>`, which closes the opening section tag.

**PART 3: PASS, with flags**
- Opens with `<section class="cta">`. Its `h2`, `p`, `p` containing `a`, and `p.note` all close, and `</section>` closes the section.
- `footer` opens and closes with its `p` inside.
- Ends with `</div>`, which is the body wrapper close. Nothing opened inside this part is left unclosed.
- **Flag 1:** `</div>` has no matching opener in Part 3. It closes a wrapper opened outside this part, so Part 3 is not self-contained.
- **Flag 2:** `</body>` and `</html>` are absent. The PROJECTS LOCK says the wrapper (doctype through body close) is verified separately and style and body markup are assembled afterward, so these tags belong to the assembly step, not this part. Assembly must add `</body>` and `</html>` after Part 3.

No parts were rewritten.
