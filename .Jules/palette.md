## 2024-05-24 - Added ARIA attributes to search toggle buttons
**Learning:** Icon-only toggle buttons in JupyterLab search lack explicit `aria-label` and `aria-pressed` states, making it difficult for screen reader users to understand their purpose and current toggle state.
**Action:** Always verify that icon-only buttons that act as toggles have an `aria-label` and `aria-pressed` attribute bound to the underlying boolean state to ensure full accessibility.
