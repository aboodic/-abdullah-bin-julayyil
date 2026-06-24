## 2026-06-24 - Icon-only Toggle Buttons Need ARIA Labels and Pressed States
**Learning:** In JupyterLab React components, icon-only toggle buttons need both `aria-label` (for the action/purpose) and `aria-pressed` (for the active/inactive state) to ensure full screen reader support and proper communication of state.
**Action:** Always add `aria-label` (matching the title) and `aria-pressed` bound to the boolean prop when creating or modifying icon-only toggle buttons.
