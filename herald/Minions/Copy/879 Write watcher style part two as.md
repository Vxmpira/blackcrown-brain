# Copy: Write watcher style part two as raw css under 700

Date: 2026-10-30
Task: Write Watcher style part two as raw CSS, under 700 characters, no style tags, no em dashes
For [[Herald]].

.ix-container{max-width:1060px;margin:0 auto;padding:0 20px}
.ix-container h1{font-size:clamp(1.6rem,4vw,2.6rem)}
.ix-panel{background:#0d0f16;border:1px solid var(--ix-line);border-radius:12px;padding:22px}
.ix-label{font-size:.72rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ix-pink)}
.ix-mock{font-family:monospace;line-height:1.7}
.ix-chips{display:flex;flex-wrap:wrap;gap:8px}
.ix-chip{border:1px solid var(--ix-pink);border-radius:99px;padding:4px 12px;font-size:.8rem}
.ix-foot{font-size:.8rem;color:#889}
.ix-crown{width:40px;height:40px;flex:none;margin-right:12px}
@media (max-width:700px){.ix-grid{grid-template-columns:1fr}}
