## 2024-06-17 - Missing ARIA labels in icon-only buttons
**Learning:** Found multiple icon-only buttons in `@jupyterlab/documentsearch` without `aria-label`s, only `title` attributes. While `title` gives a tooltip on hover, it is often insufficient or unreliable for screen readers depending on the combination of OS and screen reader software. Additionally, toggle buttons were missing the `aria-pressed` state.
**Action:** Always ensure icon-only buttons have explicit `aria-label` attributes, and stateful toggle buttons have `aria-pressed` matching their state.
