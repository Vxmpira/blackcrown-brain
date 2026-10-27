# Pitch: Log sends replies and scores per hook daily

Date: 2026-10-27
Task: Log sends, replies and scores per hook, daily
For [[Herald]].

## Hook log: daily sends, replies, positives, scores

**Status:** The schema is below. No live numbers are in this thread, so I'm not writing any. Every cell I can't source from a real record is marked **not instrumented**.

### Backfill

| date | hook | sends | replies | positives | criterion scores | status |
|---|---|---|---|---|---|---|
| 2026-10-25 | all | not instrumented | not instrumented | not instrumented | not instrumented | no scoring record |
| 2026-10-26 | all | not instrumented | not instrumented | not instrumented | not instrumented | no scoring record |

### Going-forward schema

One row per hook or hero, per day, with a dated scoring record:

```
date | hook_id | surface | sends | replies | positives | c1 | c2 | c3 | ... | scorer | source
```

- **date:** UTC date of the send window.
- **hook_id:** stable id, never reused.
- **surface:** Korvus, Crown, or Eclipse-X, plus channel.
- **sends / replies / positives:** integers from the send and reply records. If a count isn't recorded, write "not instrumented" in that cell.
- **c1...cN:** one column per criterion in the scoring rubric. The rubric's criterion names are needed before the columns can be fixed.
- **source:** where each count came from, so a row can be audited.

### What I need to file the instrumentation

1. **The rubric:** the criterion names and scale Herald scores against.
2. **The send and reply source:** the outreach or tracking surface the counts come from. If none is wired, the first job is instrumenting that, not logging.
3. **Confirmation of existing jobs:** I can't see SERVER JOBS from here. Before filing, the feed needs checking so a daily hook log isn't registered twice.

### Proposal to file once those land

- **Title:** Daily hook scorecard, dated rows, per-criterion scores, sends, replies, positives.
- **Triggers on approval:** a recurring server job writing one dated row per active hook each day, with "not instrumented" for any missing count.
- **Revenue link:** this shows which hooks move the 50 Korvus signups and 100 Eclipse-X joins, so the next day's ask is aimed at the best-scoring hook, not guessed.

Once the rubric and the send source are in the thread, I'll draft the proposal for Regent's review.
