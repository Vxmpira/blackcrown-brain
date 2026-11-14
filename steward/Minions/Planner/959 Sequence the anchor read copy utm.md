# Planner: Sequence the anchor read copy utm tag and test steps

Date: 2026-11-14
Task: Sequence the anchor read, copy, utm tag and test steps
For [[Steward]].

# Plan: Korvus CTA Anchor, UTM Content, and Test

**Goal rung:** First paying customer (Korvus Operator). Each CTA tagged by `utm_content` lets Herald see which anchor drives signups.

**Source of truth:** `korvus:korvus_landing.html`. Anchor text and href come only from this file, read in task mode.

## Steps

1. **Read the source (Corvid or Herald, task mode)**
   - Open `korvus:korvus_landing.html` and list every outbound Korvus CTA.
   - For each, record the exact anchor text, the full href, and the surrounding element.
   - **Done when:** a table exists with one row per CTA, copied verbatim with no paraphrase.

2. **Verify existing UTM tagging (Steward)**
   - Check each href from step 1 for the standing UTM parameters shipped 2026-10-26.
   - Do not refile the UTM infrastructure. If a CTA lacks the standing parameters, record it as a finding for Steward.
   - **Done when:** every CTA is marked tagged or untagged, with the untagged ones listed.

3. **Assign `utm_content` values (Herald)**
   - Derive one lowercase, hyphenated slug per CTA from its exact anchor text.
   - Each slug must be unique across the page.
   - **Done when:** a mapping of anchor text to `utm_content` value exists and has no duplicate values.

4. **Confirm copy (Herald)**
   - The copy is the anchor text from step 1. Do not write new copy for this task.
   - **Done when:** Herald confirms the copy list matches the step 1 table exactly.

5. **Source-match gate (Regent)**
   - Compare every proposed anchor string against the step 1 source, character for character.
   - Scan for placeholders and em dashes. Reject any `PENDING` text.
   - **Done when:** every anchor matches source. Nothing moves to step 6 until this passes.

6. **Write the test spec (Corvid)**
   - For each CTA, the test asserts two things: the rendered anchor text equals the source string, and the href carries the matching `utm_content` value from step 3.
   - Expected values come only from the step 1 and step 3 tables.
   - **Done when:** the spec lists each CTA with its expected anchor text and `utm_content`.

7. **File the test (Steward), only after step 5 passes**
   - Any page change goes as a proposal. Regent reviews, the owner green lights it in #boardroom, and the executor applies it with exact CURRENT anchors.
   - Pushes to main are production. Boxes pull within about 2 minutes, so the test runs against the live page after deploy.
   - **Done when:** the test is filed and its first run passes against the live Korvus page.

8. **Measure clicks by content (Herald)**
   - Attribute clicks and signups by `utm_content`.
   - If no per-anchor attribution exists yet, record "not instrumented yet" and file the job that would instrument it.
   - **Done when:** either per-anchor numbers are reported or the instrumentation job is filed.

9. **Report (Steward)**
   - Summarize the CTA table, the tagged and untagged findings, the test result, and the measurement status.
   - **Done when:** Steward has the report and the Korvus signup quota (50) is linked to the results.
