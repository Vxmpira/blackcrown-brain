# Analyst: Inspect the korvus repo clone on this box find the

Date: 2026-10-28
Task: Inspect the Korvus repo clone on this box: find the Flask signup route and account creation code, report with exact file paths and code excerpts whether utm_sou
For [[Corvid]].

**Headline: I can't inspect the repo from this seat, so signup-level UTM capture is still unverified. Job #219 stays blocked.**

I'm the numbers desk. I have no file access to the Korvus clone on this box, so I have no route code or excerpts to report. Any excerpt I gave you now would be invented, and that would hurt the owner's trust more than a delay would.

**What needs to happen**

- Route this to a desk with repo read access, or confirm that Analyst has been granted it. Until then, mark the check "not instrumented yet."
- Whoever runs it should answer four questions with file paths and line excerpts:
  1. Does the `/signup` handler read `utm_source`, `utm_medium`, and `utm_campaign` from `request.args`, the query string, or the session?
  2. Are those values written to a hidden form field in `korvus_signup.html` (or the template it renders)?
  3. Does the account creation POST handler persist them to the user record, or only to a session or log?
  4. Is there a schema column or table for them, and does a migration exist?

**Search targets to speed this up** (run from the repo root):

```
grep -rn "utm_" --include="*.py" --include="*.html" .
grep -rn "@app.route(.*signup" --include="*.py" .
grep -rn "def .*signup\|def create_account\|def register" --include="*.py" .
grep -rn "utm_source" --include="*.sql" --include="*.py" .
```

**What counts as confirmed:** a UTM value that enters at `/signup`, survives the form POST, and lands in a stored column on account creation. Visit-level capture from the 10-26 change does not count, since that only proves the visit was tagged, not that the signup kept it.

**Next action:** I can't file the job-219 unblock from here. The fix goes back to the desk that filed the ask, and I'm flagging it now so the blocker doesn't sit silently. Once someone posts the four answers, I can turn them into the signup attribution numbers and a verdict on whether job #219 can run.
