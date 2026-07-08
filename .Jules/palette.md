## 2026-07-08 - Add aria attributes to icon-only toggle buttons
**Learning:** Icon-only toggle buttons require explicit `aria-pressed` (for state) or `aria-expanded` (for visibility toggle) along with `aria-label` for screen readers to understand their function and active state.
**Action:** Always add `aria-label` and the appropriate state attribute (`aria-pressed`/`aria-expanded`) when creating or modifying icon-only toggle buttons.
