# Scout: In the korvus repo locate the signup flow exact file

Date: 2026-10-26
Task: In the korvus repo, locate the signup flow: exact file path of the signup or register page and the exact code block that handles the signup form submit, plus an
For [[Corvid]].

**Finding: I cannot complete this task as specified because I have no access to the korvus repo in this session, so I cannot report an exact file path or verbatim submit handler code.**

**Evidence:**
- No repo contents, file listings, or code snippets were included in the task context. The only grounded facts I have are: pages live at repo root with a `korvus_` prefix, the homepage is `korvus:korvus_landing.html`, and there is no `index.html`.
- Fabricating a path or code block would be worse than useless here, since Corvid needs verbatim CURRENT code to propose a safe diff for the signup tracking call. Guessed code could lead to a broken or misplaced edit.
- Reasoning from general knowledge, not from the repo: given the naming convention, the signup page is most likely something like `korvus_signup.html` or `korvus_register.html` at repo root, and the submit handler is likely an inline `<script>` or a form `onsubmit`/`addEventListener('submit', ...)` block in that file or a shared JS file. Tracker presence would show as a `gtag.js`/`googletagmanager.com` script tag, a `gtag('config', ...)` call, or another tracker snippet in the page `<head>`. None of this is verified.

**Recommended moves:**
1. Re-dispatch this task with repo access or paste the file listing of the korvus repo root. A simple `ls` plus `grep -ril "signup\|register\|submit" .` output would let me pin the exact file in one pass.
2. Once the file is identified, send me its full contents. I will extract the verbatim submit handler block and scan the `<head>` and script tags for `gtag`, `googletagmanager`, or other trackers, then report whether the tracking call can be added inline or needs the gtag loader added first.
3. If Corvid wants to move fast in parallel, have the tracking snippet drafted as a standalone block (`gtag('event', 'sign_up', {...})` guarded by `typeof gtag !== 'undefined'`) so it slots in the moment the handler location is confirmed.
