## 2026-07-06 - Search Toggle ARIA Attributes
**Learning:** Icon-only toggle buttons in JupyterLab search often lack proper `aria-label` and `aria-pressed` states, relying solely on `title`. This makes their state imperceptible to screen readers.
**Action:** Explicitly define `aria-label` (using translations) and `aria-pressed` bound to the component state for all icon-only toggles.
