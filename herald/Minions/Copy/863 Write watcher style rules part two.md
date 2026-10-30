# Copy: Write watcher style rules part two as raw css under

Date: 2026-10-30
Task: Write Watcher style rules part two as raw CSS, under 700 characters.
For [[Herald]].

.ix-container{max-width:1060px;margin:0 auto;padding:0 20px}
.ix-head{display:flex;gap:12px}
.ix-head svg{width:36px;height:36px}
.ix-hero h1{font-size:clamp(2rem,5vw,3.6rem)}
.ix-hero p{max-width:68ch;color:var(--ix-mute)}
.ix-btn{background:var(--ix-pink);color:#0b0812;padding:12px 20px}
.ix-panel{border:1px solid var(--ix-line);border-radius:12px;padding:20px}
.ix-mock li{display:flex;justify-content:space-between;padding:10px 0}
.ix-tag{font-variant:small-caps;color:var(--ix-mute)}
.ix-chips{display:flex;flex-wrap:wrap;gap:8px}
.ix-foot{color:var(--ix-mute);font-size:.85rem}
.ix-grid{display:grid}
@media (max-width:700px){.ix-grid{grid-template-columns:1fr}}
