# Copy: Rewrite watcher style block part two layout type and component

Date: 2026-10-31
Task: Rewrite Watcher style block part two: layout, type and component rules, under 40 lines, ending with the closing style tag.
For [[Herald]].

.wrap { max-width: 1060px; margin: 0 auto; padding: 0 clamp(16px, 4vw, 32px); }
.prose { max-width: 75ch; }
h1 { font-size: clamp(2rem, 5vw, 3.4rem); line-height: 1.1; margin: 0 0 16px; }
h2 { font-size: clamp(1.4rem, 3.2vw, 2rem); line-height: 1.2; margin: 48px 0 12px; }
h3 { font-size: clamp(1.1rem, 2.4vw, 1.3rem); line-height: 1.3; margin: 28px 0 8px; }
p { color: var(--ink); line-height: 1.6; margin: 0 0 16px; }
section { padding: clamp(24px, 5vw, 48px) 0; }
.tablewrap { width: 100%; overflow-x: auto; margin: 24px 0; border: 1px solid rgba(45, 226, 255, 0.18); border-radius: 10px; }
.tablewrap table { width: 100%; border-collapse: collapse; min-width: 480px; }
.tablewrap th, .tablewrap td { padding: 12px 14px; text-align: left; border-bottom: 1px solid rgba(233, 235, 242, 0.08); }
.tablewrap th { color: var(--cyan); font-weight: 600; }
.data-panel { position: relative; margin: 24px 0; padding: 28px 20px 20px; border: 1px solid rgba(140, 80, 255, 0.35); border-radius: 12px; background: rgba(140, 80, 255, 0.06); }
.data-panel .illustration-tag { position: absolute; top: 10px; right: 14px; font-size: 0.72rem; letter-spacing: 0.08em; text-transform: uppercase; color: var(--violet); }
.chip { display: inline-flex; align-items: center; padding: 6px 12px; margin: 0 8px 8px 0; border: 1px solid var(--cyan); border-radius: 999px; color: var(--cyan); font-size: 0.82rem; line-height: 1.2; }
.chip--pink { border-color: var(--pink); color: var(--pink); }
.grid { display: grid; gap: 16px; grid-template-columns: repeat(2, minmax(0, 1fr)); }
.grid--3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
@media (max-width: 700px) {
  .grid, .grid--3 { grid-template-columns: 1fr; }
  .tablewrap { margin: 16px 0; }
}
</style>
