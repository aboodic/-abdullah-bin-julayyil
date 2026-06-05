## 2024-06-05 - Accessibility for dynamic form elements
**Learning:** In dynamically generated forms like JupyterLab's property editors, it's critical to ensure generated inputs and icon-only removal buttons receive proper `aria-label`s, as they lack explicit visible `<label>`s to bind to. The close icon specifically needs a tooltip and `aria-label`.
**Action:** Always verify that dynamic inputs (e.g. key/value pairs) have an explicit `aria-label` since standard `<label htmlFor="id">` may be too cumbersome to implement, and ensure icon-only removal buttons have proper labels.
