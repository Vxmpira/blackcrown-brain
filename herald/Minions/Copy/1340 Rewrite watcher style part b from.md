# Copy: Rewrite watcher style part b from the first line closing

Date: 2026-11-01
Task: Rewrite Watcher style part B from the first line, closing tag required
For [[Herald]].

<style>
body::after {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  z-index: -1;
  background: radial-gradient(ellipse at center, transparent 55%, rgba(0, 0, 0, 0.55) 100%);
}

.chip-row {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.chip {
  flex: 1 1 220px;
  min-width: 0;
  border: 1px solid #2a2f3a;
  background: #0f1218;
  color: #e8eaf0;
  border-radius: 10px;
  padding: 12px 14px;
  font-size: 14px;
  line-height: 1.5;
}

.chip-title {
  display: block;
  color: #9fb4ff;
  font-size: 15px;
  font-weight: 700;
  margin-bottom: 4px;
}

@media (max-width: 699px) {
  .chip-row {
    flex-direction: column;
  }

  .chip {
    flex: 0 0 auto;
    width: 100%;
  }
}
</style>
