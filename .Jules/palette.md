## 2024-05-13 - Icon-only toggle buttons in JupyterLab
**Learning:** Icon-only toggle buttons (like "Match Case" and "Match Whole Word" in document search) often rely solely on visual styling and a `title` attribute, leaving screen reader users without explicit `aria-label` or `aria-pressed` state information.
**Action:** Always verify that icon-only buttons have an `aria-label` and, if they function as toggles, explicitly bind `aria-pressed` to their boolean state.
