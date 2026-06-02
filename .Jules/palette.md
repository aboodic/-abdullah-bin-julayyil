## 2026-06-02 - Add ARIA label to LSP extension property removal button
**Learning:** Deeply nested sub-components (like `PropertyFrom` in LSP settings) often lack access to the translation context, resulting in missing or unlocalized `aria-label` attributes on icon-only buttons.
**Action:** Explicitly pass the `TranslationBundle` (e.g., `trans: TranslationBundle`) down to smaller React components to ensure all icon-only buttons can be given proper localized `title` and `aria-label` tags for screen readers.
