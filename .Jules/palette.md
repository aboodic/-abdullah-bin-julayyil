## 2024-07-01 - Icon-only Toggle Buttons
**Learning:** Icon-only toggle buttons in JupyterLab frequently rely solely on `title` attributes for tooltips, missing critical `aria-label` and `aria-pressed` states for screen readers to properly announce both the action and the current state (e.g., in `documentsearch` widget).
**Action:** Always verify that icon-only toggle buttons implement both an `aria-label` (using translation context where applicable) and a dynamic `aria-pressed` attribute reflecting their active state.
