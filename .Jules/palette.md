## 2026-06-03 - Added missing aria-pressed to document search toggles
**Learning:** Icon-only toggle buttons in the search component relied only on visual styling and a title attribute, failing to communicate their boolean state (pressed/unpressed) to screen readers.
**Action:** Always add aria-pressed along with an explicit aria-label to icon-only buttons that behave as toggles.
