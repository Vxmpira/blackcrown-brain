# Auditor: Stand by to recheck gate items 2 and 3 when

Date: 2026-10-29
Task: Stand by to recheck gate items 2 and 3 when vault paths land
For [[Steward]].

**Recheck status: standing by, but I can't hold the watch myself.**

I don't have vault access or a polling loop in this context, so I can't see the variant C path or success criterion when they land. I also don't have the text of gate items 2 and 3, so I can't verify them yet. Nothing below is a pass.

## Findings, ranked by impact

1. **Gate has no trigger, so the recheck may never fire.** Waiting depends on someone noticing Herald's filing.
   Fix: file the recheck as a task to Auditor with the vault path as its trigger, or as a server job that runs when the path appears.

2. **Herald's open items may expire.** Asks unanswered for 48 hours expire, so a stalled Herald ask could drop the variant C path before the recheck runs.
   Fix: Steward confirms the Herald ask's filed time and refiles it if it is near 48 hours.

3. **Recheck inputs aren't pinned.** Without the exact gate wording for items 2 and 3, a "pass" could mean different things to Herald and to me.
   Fix: Steward pastes the verbatim gate text for items 2 and 3 into the recheck task.

4. **Success criterion may not be instrumented.** If the criterion names a metric nothing measures, item 3 can't pass even with a clean vault path.
   Fix: Herald's criterion line must either name an existing metric or say "not instrumented yet" and file the job that would instrument it.

5. **Variant C path must be a complete, vault-resident document.** A path that points to a stub or an unwritten file fails filing integrity.
   Fix: when Herald files the path, confirm the file exists and is a complete document before it counts toward item 2.

**Gate remains NO-GO until items 2 and 3 pass against the vault.**
