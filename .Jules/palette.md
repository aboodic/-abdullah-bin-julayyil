## 2026-06-26 - ARIA Attributes for Icon-Only Toggle Buttons
**Learning:** Icon-only toggle buttons require explicit `aria-label` for screen readers and `aria-pressed` bound to the component's boolean state to properly communicate the active/inactive state.
**Action:** Always include both `aria-label` and `aria-pressed` attributes when creating or modifying icon-only toggle buttons in React components.
