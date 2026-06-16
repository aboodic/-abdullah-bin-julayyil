## 2024-05-24 - [A11y: Icon-only toggle buttons in JupyterLab]
**Learning:** Icon-only toggle buttons in JupyterLab components often use `title` for hover text but miss `aria-label` for screen readers and `aria-pressed` for explicit state.
**Action:** Always add `aria-label` and `aria-pressed` to these toggle buttons, using localized text.
