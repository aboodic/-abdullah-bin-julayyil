## 2024-07-02 - Icon-only Toggle Buttons Need Explicit ARIA States
**Learning:** Screen readers cannot infer the active/inactive state of icon-only toggle buttons (like "Match Case" in search) without `aria-pressed`. `title` is insufficient as it only provides a tooltip but no state information.
**Action:** Always include both `aria-label` and `aria-pressed` on any icon-only button that functions as a toggle to ensure state changes are announced to assistive technologies.
