# Copy: Write watcher style block part two container max width 1060px

Date: 2026-10-31
Task: Write Watcher style block part two: container (max-width 1060px, centered, side padding), clamp() headings, prose max 75ch, .chips, .panel, figure, .tablewrap, 
For [[Herald]].

<style>
/* Watcher style block, part two: layout, type, data, and action components */

.wt-container {
  width: 100%;
  max-width: 1060px;
  margin: 0 auto;
  padding: 0 clamp(16px, 4vw, 32px);
  box-sizing: border-box;
}

.wt-h1 {
  font-size: clamp(2rem, 5.2vw, 3.4rem);
  line-height: 1.08;
  letter-spacing: -0.02em;
  font-weight: 800;
  color: #e9ebf2;
  margin: 0 0 0.6em;
}

.wt-h2 {
  font-size: clamp(1.45rem, 3.4vw, 2.1rem);
  line-height: 1.15;
  letter-spacing: -0.015em;
  font-weight: 700;
  color: #e9ebf2;
  margin: 2.2em 0 0.5em;
}

.wt-h3 {
  font-size: clamp(1.1rem, 2.4vw, 1.3rem);
  line-height: 1.25;
  font-weight: 650;
  color: #e9ebf2;
  margin: 1.6em 0 0.4em;
}

.wt-prose {
  max-width: 75ch;
  color: #e9ebf2;
  font-size: clamp(1rem, 1.6vw, 1.0625rem);
  line-height: 1.7;
}

.wt-prose p {
  margin: 0 0 1.1em;
}

.wt-prose strong {
  color: #ffffff;
  font-weight: 650;
}

.wt-prose a {
  color: #ff2d8f;
  text-decoration: underline;
  text-underline-offset: 3px;
}

.wt-prose a:hover,
.wt-prose a:focus-visible {
  color: #ff6fae;
}

/* Chips: small rounded pills */

.wt-chips {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0 0 1.4em;
  padding: 0;
  list-style: none;
}

.wt-chips li,
.wt-chip {
  display: inline-flex;
  align-items: center;
  padding: 5px 12px;
  border-radius: 999px;
  border: 1px solid rgba(255, 45, 143, 0.45);
  background: rgba(255, 45, 143, 0.08);
  color: #e9ebf2;
  font-size: 0.8rem;
  font-weight: 600;
  letter-spacing: 0.02em;
  line-height: 1.2;
  white-space: nowrap;
}

/* Panel: data mock surface, slightly lighter than the background */

.wt-panel {
  background: #161a24;
  border: 1px solid rgba(233, 235, 242, 0.08);
  border-radius: 14px;
  padding: clamp(16px, 3vw, 24px);
  box-sizing: border-box;
  color: #e9ebf2;
  box-shadow: 0 18px 40px rgba(0, 0, 0, 0.35);
}

.wt-panel-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  flex-wrap: wrap;
  margin: 0 0 14px;
  font-size: 0.85rem;
  font-weight: 600;
  color: rgba(233, 235, 242, 0.7);
}

.wt-panel-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 12px;
}

.wt-stat {
  background: #1d2231;
  border-radius: 10px;
  padding: 14px;
}

.wt-stat-label {
  font-size: 0.75rem;
  color: rgba(233, 235, 242, 0.6);
  margin-bottom: 6px;
}

.wt-stat-value {
  font-size: clamp(1.1rem, 2.6vw, 1.4rem);
  font-weight: 700;
  color: #ffffff;
  font-variant-numeric: tabular-nums;
}

/* Figure: full container width, labeled Illustration */

.wt-figure {
  width: 100%;
  margin: 2em 0;
  padding: 0;
}

.wt-figure figcaption {
  margin-top: 10px;
  font-size: 0.8rem;
  color: rgba(233, 235, 242, 0.6);
  letter-spacing: 0.02em;
}

.wt-figure figcaption .wt-tag {
  display: inline-block;
  margin-right: 8px;
  padding: 2px 8px;
  border-radius: 999px;
  border: 1px solid rgba(255, 45, 143, 0.45);
  color: #ff2d8f;
  font-weight: 600;
  font-size: 0.72rem;
}

/* Table rail: spans the full container, scrolls on narrow screens */

.wt-tablewrap {
  width: 100%;
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  border-radius: 12px;
  border: 1px solid rgba(233, 235, 242, 0.08);
  background: #161a24;
  margin: 1.6em 0;
}

.wt-table {
  width: 100%;
  border-collapse: collapse;
  min-width: 520px;
  font-size: 0.92rem;
  color: #e9ebf2;
}

.wt-table th,
.wt-table td {
  text-align: left;
  padding: 12px 16px;
  border-bottom: 1px solid rgba(233, 235, 242, 0.07);
  white-space: nowrap;
}

.wt-table th {
  font-size: 0.75rem;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: rgba(233, 235, 242, 0.6);
  font-weight: 650;
  background: #1a1f2c;
}

.wt-table td.wt-num,
.wt-table th.wt-num {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

.wt-table tr:last-child td {
  border-bottom: none;
}

/* CTA: solid pink button with dark text */

.wt-cta {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 14px 26px;
  border-radius: 10px;
  border: none;
  background: #ff2d8f;
  color: #0b0d12;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.01em;
  text-decoration: none;
  cursor: pointer;
  transition: background 0.2s ease;
}

.wt-cta:hover,
.wt-cta:focus-visible {
  background: #ff5aa5;
}

.wt-cta-row {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 14px;
  margin: 1.4em 0 0;
}

.wt-cta-note {
  font-size: 0.85rem;
  color: rgba(233, 235, 242, 0.65);
}

/* Narrow screens: collapse grids and keep the rhythm */

@media (max-width: 700px) {
  .wt-panel-grid {
    grid-template-columns: 1fr;
  }

  .wt-cta {
    width: 100%;
  }

  .wt-cta-row {
    flex-direction: column;
    align-items: stretch;
  }

  .wt-h2 {
    margin-top: 1.8em;
  }
}
</style>
