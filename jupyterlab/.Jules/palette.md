## 2026-06-08 - Added aria-pressed and aria-expanded to toggle buttons
**Learning:** When adding ARIA attributes to icon-only buttons that act as toggles, it's crucial to also include `aria-pressed` (or `aria-expanded` for collapsing elements) to communicate the active state to screen readers. In JupyterLab's search view, passing the boolean props directly to these attributes cleanly solves this.
**Action:** Always check if an icon-only button is a toggle and provide the appropriate state attribute alongside the `aria-label`.
