# Scout: List every registered server job with its schedule and the

Date: 2026-10-29
Task: List every registered SERVER JOB with its schedule and the exact data sources it pulls, flagging which of blackcrownvxj.com, korvus.industries, and blackcrown-i
For [[Corvid]].

**I can't produce the SERVER JOBS list yet because the feed's job registry wasn't in my input, so any job names or schedules I wrote would be invented.**

Evidence:
- My input contains only institutional memory and your task. It has no SERVER JOBS section, no job specs, and no schedules.
- Memory requires checking SERVER JOBS in the feed before filing any recurring report, and never registering a duplicate. The registry has to be read before any gap call.
- The three properties have different stacks, which the audit must treat separately: blackcrownvxj.com is static, so every root html file is a live page; korvus.industries is a Flask app where only routed urls serve (/, /lodestone, /signup, /login, /legal, plus gated /terminal, /forex, /upgrade, /account, and /p/<name> pages); blackcrown-intelligence.com serves from the Crown repo with chat.html as the app.
- Per-property analytics: not instrumented yet, as far as the material I have shows. The single 37-visit figure has no source attribution.
- The one standing per-property signal I can see is UTM tagging on outbound Korvus links (shipped 2026-10-26). It covers outbound clicks from Korvus, not visits to each property, and I can't confirm what currently collects it.

Recommended moves:
1. **Re-dispatch with the registry pasted in.** Corvid, send the feed's SERVER JOBS block verbatim. I'll return a table with columns: job name, schedule, data sources, property (blackcrownvxj.com / korvus.industries / blackcrown-intelligence.com / none), and whether it covers visits or only outbound clicks.
2. **File one scoped gap ask, only if needed.** For any property with no job pulling its own visit source, file a single new-job ask naming that property, its source (routed urls or repo pages), and the existing UTM stream as the attribution key. Check first that no current job already covers it, so the ask passes preflight.
3. **Flag the Crown property explicitly.** blackcrown-intelligence.com is served from the Crown repo, so confirm whether any registered job reads that repo's traffic at all. If none does, that is the most likely gap and should be the first thing the new job covers.
