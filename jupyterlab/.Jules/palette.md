## 2026-06-07 - Added ARIA attributes to icon-only toggle buttons
**Learning:** Icon-only toggle buttons in JupyterLab document search (like Match Case, Regex) relied only on title attributes, making their toggled state opaque to screen readers.
**Action:** Use aria-pressed for toggle states and aria-expanded for visibility toggles, along with explicit aria-labels matching the title, to ensure screen readers announce both the action and its current state.
