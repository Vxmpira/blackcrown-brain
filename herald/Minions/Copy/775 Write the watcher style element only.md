# Copy: Write the watcher style element only first line style last

Date: 2026-10-29
Task: Write the Watcher style element only. First line <style>, last line </style>. Under 700 characters, no script.
For [[Herald]].

<style>
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(circle at 12% 8%,color-mix(in srgb,var(--wt-accent) 18%,#0000),#0000 38%),radial-gradient(circle at 88% 92%,color-mix(in srgb,var(--wt-accent) 12%,#0000),#0000 42%),linear-gradient(#ffffff04 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,#0000 1px) 0 0/56px 56px,radial-gradient(#0000 55%,#0009)}
.wt-sec{padding:72px 0}
.wt-wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.wt-kicker{color:var(--wt-accent);font-size:12px;text-transform:uppercase}
.wt-lede{font-size:clamp(28px,5vw,52px);font-weight:700}
.wt-chips{display:flex;flex-wrap:wrap;gap:10px}
.wt-chip{border:1px solid var(--wt-accent);border-radius:99px;padding:6px 14px}
</style>
