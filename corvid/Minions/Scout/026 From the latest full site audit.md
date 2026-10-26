# Scout: From the latest full site audit name the exact korvus

Date: 2026-10-26
Task: From the latest full site audit, name the exact korvus repo file that contains the Korvus signup or account creation flow, and copy the exact markup of its sign
For [[Corvid]].

# Scout Report: Korvus signup flow file and exact markup

**One-line finding:** Cannot deliver. No site audit data or repo file contents were provided in this task, so I have no source from which to quote exact markup, and fabricating it would break Regent's edit.

## Evidence

- The task context lists file naming conventions (korvus_ prefix, root level) and three known app pages: `agent.html`, `korvus_promo_studio.html`, `korvus_dashboard.html`. None of these is identified as the signup page, and no file contents were attached.
- Note the inconsistency in the provided list itself: `agent.html` lacks the korvus_ prefix. If the prefix rule is strict, the signup file is likely named something like `korvus_signup.html`, `korvus_register.html`, or `korvus_account.html`, but this is reasoning from general naming-convention knowledge, not from audit data.
- Signup flows also commonly live inside a dashboard or landing page as a modal or inline form rather than a standalone file. If that is the case here, the markup would sit in `korvus_landing.html` or `korvus_dashboard.html`. Again, this is inference, not evidence.
- Quoting "exact CURRENT text" requires the current file contents. Anything I produce without them would be invented markup, and Regent applying a tracking edit against invented markup will fail or corrupt the file.

## Recommended moves

1. **Re-run or attach the audit output.** Have Corvid pass me the audit's file list plus the raw HTML of candidate files (`korvus_landing.html`, `korvus_dashboard.html`, `agent.html`, and any korvus_ file with signup/register/account in the name). I can then confirm the file and quote the exact signup block verbatim.
2. **Quick grep before escalating.** A repo-side search for `sign up`, `signup`, `register`, `create account`, and `type="email"` across korvus_ files will pinpoint the flow in seconds and is safer than any inference.
3. **Flag the prefix inconsistency.** `agent.html` breaking the korvus_ naming rule is worth a cleanup ticket regardless, since inconsistent naming is exactly how audits miss files like this one.
