## 2026-06-23 - Accessibility of icon-only toggles in JupyterLab Search
**Learning:** In JupyterLab's Search and Replace widgets, icon-only toggle buttons (like Match Case, Whole Word, Regex) need both explicit `aria-label` (since they have no visible text) and `aria-pressed` explicitly bound to their boolean component state props to properly announce their toggled state to screen readers.
**Action:** Always check the component interface definition to explicitly bind `aria-pressed` to the exact boolean property name representing the toggle state.
