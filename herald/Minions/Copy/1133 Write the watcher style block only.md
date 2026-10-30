# Copy: Write the watcher style block only one style tag under

Date: 2026-10-30
Task: Write the Watcher style block only: one style tag, under 40 lines, covering .wrap, .hero, .panel, .chips and .chip.
For [[Herald]].

<style>
.wrap {
  max-width: 1060px;
  margin: 0 auto;
  padding: 0 clamp(16px, 4vw, 32px);
  box-sizing: border-box;
}
.hero {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: clamp(20px, 4vw, 40px);
  align-items: center;
  padding: clamp(40px, 8vw, 88px) 0 clamp(28px, 5vw, 56px);
  font-size: clamp(16px, 2.2vw, 18px);
  line-height: 1.6;
  color: var(--text);
}
.panel {
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.03), rgba(255, 255, 255, 0.01));
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: clamp(18px, 3vw, 26px);
  color: var(--muted);
  box-sizing: border-box;
}
.chips {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 16px;
}
.chip {
  display: inline-flex;
  align-items: center;
  padding: 6px 12px;
  border: 1px solid var(--line);
  border-radius: 999px;
  font-size: 13px;
  letter-spacing: 0.02em;
  color: var(--muted);
  white-space: nowrap;
}
@media (max-width: 699px) {
  .hero {
    grid-template-columns: 1fr;
  }
}
</style>
