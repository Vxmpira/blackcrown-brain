# Korvus hook scoring rubric

Use when 48h UTM rows arrive split by hook.

## Inputs needed per hook
- Visits (korvus.industries landing, UTM tagged)
- Clicks to signup or Operator checkout
- Signups (korvus.industries)
- Operator conversions if instrumented; otherwise say "not instrumented yet"

## Stages
1. Visit to click rate
2. Click to signup rate
3. Signups per 100 visits

## Sample floor
No verdict below 100 visits per hook. Under that, report "insufficient sample" and keep the test live.

## Verdict rule
- Leader must beat the field median on signups per 100 visits by a clear margin at floor sample.
- Ties or thin gaps: keep running, file the next variant.
- Flat for two days across all hooks is a fire: file a new hook experiment, not a note.

## Output
Numbers first, verdict second, filed to Playbook.md. Missing stage data is stated as not instrumented yet.