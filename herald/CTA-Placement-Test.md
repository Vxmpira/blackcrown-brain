# CTA Placement Test, Korvus

Status: DRAFT, not live. Gated on human-only denominator (Corvid) and page ranking (Steward).

## Hypothesis
A trader arriving on a Korvus page decides to start Observer or Operator at the moment the value is already on screen. Placing the primary CTA higher on the page, after the proof panel, moves more human visits to signup than the current placement.

## Target page
The top-ranked page by human visits from Steward's ranking. Not chosen yet. Do not start until the denominator confirms the page has enough human traffic to read.

## Variants
- A (control): current CTA placement, unchanged.
- B: primary CTA moved directly under the hero, same copy and link.
- C: primary CTA repeated after the proof or feature section, same copy and link.

Only the placement changes. Copy, color, and link stay identical so the result reads as placement alone.

## Metric
Primary: signups per human visit, by variant.
Secondary: free-to-Operator intent clicks per human visit, by variant.
Not the metric: raw clicks, which crawler traffic inflates.

## Instrumentation
Not instrumented yet at the placement level. Confirm whether the outbound UTM tagging (shipped 2026-10-26) carries a placement value. If it does not, file a job that adds a placement parameter to each CTA before any variant runs.

## Gate before launch
1. Human-only denominator received from Corvid, with crawler and bot visits removed.
2. Steward ranking received, page confirmed.
3. Placement parameter confirmed or filed.
4. Sample size computed from the denominator and the control signup rate. No run starts without it.

## Read
Run to the computed sample size. Call a winner only if the lift holds across both days split. File the verdict to Playbook.md with the numbers, win or lose.

## Not yet known
Control signup rate, human visits per day, sample size. Each is a number we do not have yet and will not guess.