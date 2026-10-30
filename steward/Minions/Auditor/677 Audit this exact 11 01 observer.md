# Auditor: Audit this exact 11 01 observer draft and return claims

Date: 2026-10-30
Task: Audit this exact 11-01 Observer draft and return claims list, per-claim verdicts, PASS or FAIL
For [[Steward]].

**Audit: Observer draft (11-01), exact text**

**Overall: FAIL** (3 claims fail, 4 pass)

| # | Claim | Verdict | Basis / one-line fix |
|---|---|---|---|
| 1 | "Index futures move on headlines before most traders finish reading them." | **FAIL** | Market generalization with an unmeasured audience claim ("most traders"). Nothing in the data supports it. Fix: "Index futures can move on headlines within seconds."
| 2 | "Korvus Observer scores each news item for impact, direction and confidence" | **FAIL** | Scoring with impact, direction and confidence is documented for the Presidential Wire in Eclipse-X, not confirmed for Observer. "Each news item" is an absolute the data doesn't carry. Fix: confirm Observer's feed exposes these fields, then write "Korvus scores news for impact, direction and confidence," or drop the scoring line. |
| 3 | "24/7" | **PASS** | Korvus is a 24/7 market intelligence terminal. |
| 4 | "Free tier" | **PASS** | Observer is the free tier. |
| 5 | "no card" | **FAIL** | "No card" is documented for Crown's free tier, not Korvus Observer. Fix: remove it, or confirm the Korvus signup takes no card and then keep it. |
| 6 | "Not financial advice." | **PASS** | Required disclaimer present. |
| 7 | "korvus.industries" | **PASS** | Correct domain. |
| 8 | "#IndexFutures #DayTrading" | **PASS** | Two hashtags, within the X limit. |

**Checks that passed across the whole text:**
- No trading advice or profit promises.
- No em dashes or emoji.
- Length is roughly 245 characters with the link counted at 23, under the 280 limit.

**Ranked by impact:**
1. Claim 2 (feature attribution the data does not confirm, central to the post).
2. Claim 5 ("no card" unverified for Korvus, a conversion promise).
3. Claim 1 (unsupported audience generalization, lowest risk but easy to fix).

Audit only. Nothing gated or filed.
