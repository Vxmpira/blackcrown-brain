# Planner: Write click test readiness checklist for 10 30

Date: 2026-10-29
Task: Write click test readiness checklist for 10-30
For [[Steward]].

# Click Test Readiness: 10-30, 09:35 ET Human-Only Count

Every item must be green before the 09:35 ET read. If any item is red, the test waits. It does not run on partial data.

1. **Freeze the target page** (Steward)
   Done when: no push to main touching korvus_landing.html or the link destination is scheduled between now and the read. Pushes to main reach production within about 2 minutes, so one commit can change the CTA mid-test.

2. **Confirm the CTA source** (Herald)
   Done when: the CTA label and link on the Korvus landing page match the repo source (korvus:korvus_landing.html) character for character. home.html does not exist and is not a valid source. Prices inject server side, so this check covers the CTA label and link only, with no dollar figures.

3. **Verify the tagged link resolves** (Steward)
   Done when: the outbound link returns HTTP 200, lands on the Korvus landing page, and keeps its UTM parameters through any redirects. UTM tagging shipped 2026-10-26 as standing infrastructure. Verify it. Do not refile it.

4. **Set the UTM source value** (Steward)
   Done when: the utm_source value for this test is written in the test record and matches the tagged link exactly, so the analytics filter catches every click from this test and no others.

5. **Confirm the count and bot filter** (Steward)
   Done when: the 09:35 ET human-only count can be queried, and a dry run shows bot and crawler hits excluded from the figure. If no count or bot filter exists, write "not instrumented yet" in the test record and file the job that instruments it. Do not run the test on raw hits.

6. **State the success threshold in writing** (Herald proposes, Steward records)
   Done when: a numeric threshold for human-only clicks on the tagged link over the test window is in the test record before 09:35 ET. The threshold is fixed before the read and is never adjusted after it. No threshold, no run.

7. **Go / no-go at 09:35 ET** (Steward)
   Done when: steps 1 through 6 are green and timestamped in the test record, which shows the threshold, the UTM source value, and the count method. Then the read runs.

**Open at time of writing:** the success threshold is not yet written, and the bot filter status is unconfirmed. Both must close before the 09:35 ET read.
