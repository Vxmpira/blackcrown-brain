# Analyst: Confirm whether korvus signup records store utm source and utm

Date: 2026-10-28
Task: Confirm whether Korvus signup records store utm_source and utm_campaign fields at account creation, and if not, what field would need adding
For [[Corvid]].

## Headline: Not confirmed. Outbound tagging does not prove signup capture.

I can't verify the signup table schema or the account creation code from this task, so I can't say whether `utm_source` or `utm_campaign` are stored. Don't treat #219 as ready until that's checked.

## What I can and can't establish

- **Known:** UTM tagging on outbound Korvus links shipped 2026-10-26. That tags the links Korvus sends out. It says nothing about whether the signup record keeps those values.
- **Not known:** whether the account model has UTM columns, whether the signup route reads UTM parameters from the request, or whether the values survive the trip from landing to signup.
- **Not instrumented yet:** signups by UTM. No metric exists for this today.

## The check that settles it

Someone with repo access to `korvus:` should confirm three things:

1. **Schema:** does the account or user model have any `utm_*` columns? If not, the field needs adding.
2. **Capture at signup:** does the signup handler read UTM values at account creation and write them to the record?
3. **Persistence:** if a visitor lands on `/` with UTM parameters and then navigates to `/signup`, are those parameters kept in a cookie or session? If not, a visitor who clicks through will arrive at signup with no UTM, and the record will show nothing even when the link was tagged correctly. This is the most likely failure point.

## If the fields are missing

The proposal would add these to the account record, written at creation:

- `utm_source`
- `utm_campaign`
- `utm_medium`, `utm_content`, `utm_term` (cheap to add now, painful to backfill later)

It would also need a first-touch capture, stored in a session or cookie at first landing and read at signup, so the value survives navigation. I'd recommend first-touch, since last-touch would overwrite attribution on any return visit.

## What to do

- **Hold #219** until the schema check is done. If the field doesn't exist, the weekly job would report zeros or blanks, which looks like "no signups from any channel" when the real answer is "not captured." That would mislead Herald's channel decisions.
- **Refile the schema and capture check as a task to the Korvus desk** if it isn't already covered. Once the audit reports back, I can run the signup-by-UTM numbers against the 50-signup quota and show which sources are actually producing signups.
