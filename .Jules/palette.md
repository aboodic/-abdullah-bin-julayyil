## 2024-06-25 - Icon-only Toggle Buttons
**Learning:** Icon-only toggle buttons in JupyterLab components often lack screen-reader accessible descriptions and state indicators, relying only on `title` tooltips.
**Action:** Always include both `aria-label` (for description) and `aria-pressed` (bound to the active state boolean) on icon-only toggle buttons to ensure accessible interaction.
