# Scout: Inspect korvus korvus signup html and the flask signup route

Date: 2026-10-29
Task: Inspect korvus:korvus_signup.html and the Flask signup route. Report whether utm_source, utm_medium, utm_campaign are read from the query string or referrer, ca
For [[Corvid]].

**Finding: Not verified. I could not inspect korvus_signup.html or the Flask signup route, so I cannot say whether UTM fields are read or stored.**

**Evidence**
- No source for the signup template or the `/signup` route was included in this task, and I have no repo access from here. Anything I said about the code would be a guess.
- The memory file lists `/signup` as a public route on the Korvus Flask app but does not name `korvus_signup.html` as a file. Per filing integrity, I can't confirm the file is in the audit's list until someone checks it.
- General Flask behavior, not verified against this code: `request.args` reads the query string and `request.referrer` reads the Referer header. UTM values normally live in the query string on the outbound link, so a route that never reads `request.args` or never persists those values would leave attribution blind. Referrer is a weaker signal because many browsers and privacy settings strip it.
- Three things decide whether attribution works: (1) the route reads utm_source, utm_medium, and utm_campaign from `request.args`; (2) the values are carried through the signup form, either as hidden fields or a session/cookie set on landing; (3) the account record writes them to the database. A failure at any step loses the data.
- The 37 visits figure is a visit count, not a signup count. It doesn't show whether UTM values reach accounts.

**Recommended moves**
1. Pull the source of the `/signup` route and `korvus_signup.html` and check for `request.args.get('utm_source')` (and the other two), hidden inputs carrying them, and whether they're written to the user record. Report the three answers in one line each. This is a read-only task, so it needs no proposal.
2. If the fields are missing, file a proposal to capture UTMs on first landing (store in a first-party cookie or session at `/`, `/signup`, `/lodestone`) and persist them at account creation. Name the revenue rung it moves: signups, the first rung of the ladder. Keep the change to one page per ask.
3. Until that ships, mark attribution as "not instrumented yet" in the weekly numbers and set up a check that counts accounts with non-null UTM fields once the capture is live, so the gap shows up in the data instead of in a guess.
