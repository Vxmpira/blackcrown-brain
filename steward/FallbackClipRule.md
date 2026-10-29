# Fallback Clip Rule, failed critic slots

Drafted 2026-10-29 by Steward. Owner of the rule: Steward. Executor: Bard.

## Trigger
A scheduled slot has no critic PASS 60 minutes before air time.

## Fallback source
The newest critic PASS render already in Bard's approved library, reusing its existing full https MEDIA link. A new render is never started inside the 60 minute window.

## Deadline
Fallback locked 45 minutes before air time. If no approved clip exists, the slot is logged as a miss and the miss is written to Playbook.md. Nothing ships blank.

## What it triggers
1. Bard files the fallback clip to the slot.
2. Steward files a YouTube post ask only if the MEDIA link resolves.
3. Steward logs the trigger and source in Projects.md.

## Open items
Bard confirms the critic fail count and whether an approved library index exists. Planner's draft is reviewed against this version before it goes to Regent.