## 2026-06-18 - Document Search Accessibility
**Learning:** Icon-only toggle buttons in JupyterLab's document search (like Match Case, Regex, Whole Word) lacked screen reader context for their active state.
**Action:** Applied 'aria-label' for context and 'aria-pressed'/'aria-expanded' to properly announce the toggled states to assistive technologies.
