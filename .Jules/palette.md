## 2026-06-29 - Added ARIA attributes to Search Widget Buttons
**Learning:** Icon-only toggle buttons in JupyterLab components often use `title` for tooltips but lack `aria-label` and `aria-pressed`, which are essential for communicating active/inactive states to screen readers.
**Action:** Always verify icon-only buttons include `aria-label` (matching tooltip text) and `aria-pressed` (bound to boolean props).
