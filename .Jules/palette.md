## 2026-06-01 - Add localized aria-labels to icon buttons
**Learning:** In JupyterLab React components, when adding ARIA labels or tooltips to icon-only buttons, string literals must be localized. This often requires updating the child component's props interface to accept a `TranslationBundle` and passing `props.trans` down from the parent so we can call `props.trans.__('Text')`.
**Action:** When creating UI components or adding accessibility strings in JupyterLab extensions, always trace the translation bundle down to the target component.
