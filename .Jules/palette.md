## 2024-07-05 - Search Toggle Buttons Accessibility
**Learning:** Icon-only toggle buttons in the document search view were missing the `aria-pressed` attribute, causing their on/off state to not be announced by screen readers. Furthermore, explicit `aria-label` attributes are needed alongside `title` for robust screen reader support on icon-only buttons.
**Action:** Add `aria-label` and `aria-pressed` explicitly to icon-only toggle buttons to ensure the state and description are announced correctly.
