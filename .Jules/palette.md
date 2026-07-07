## 2026-07-07 - Add aria-pressed to icon-only toggle buttons
**Learning:** Icon-only toggle buttons relying solely on visual active classes fail to communicate their state to screen readers. `aria-pressed` (or `aria-expanded`) is crucial for binary state buttons.
**Action:** Always pair `aria-label` with `aria-pressed` (or `aria-expanded`) for boolean toggle buttons in toolbars.
