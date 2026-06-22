## 2026-06-22 - Missing ARIA attributes on stateful icon buttons
**Learning:** Icon-only toggle buttons in JupyterLab search often rely solely on `title` for tooltips, missing critical `aria-label` for screen readers and `aria-pressed` to communicate their active/inactive state.
**Action:** Always add explicit `aria-label` and `aria-pressed` boolean attributes to icon-only toggle buttons (like Match Case, Whole Word) to ensure screen readers announce their state correctly.
