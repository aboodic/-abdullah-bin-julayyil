## 2024-06-21 - [ARIA Attributes for Search Toggles]
**Learning:** Icon-only toggle buttons in JupyterLab search components require explicit `aria-pressed` states alongside `aria-label` for correct screen reader accessibility, otherwise the visual-only toggle state is completely lost to AT users.
**Action:** Always add both `aria-label` (localized) and `aria-pressed` attributes to icon-only interactive toggle elements.
