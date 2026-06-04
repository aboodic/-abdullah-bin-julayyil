## 2024-05-15 - Screen-reader states on toggle buttons
**Learning:** Icon-only buttons used as toggles (like "Match Case" in search) or accordions (like "Show Replace") need proper `aria-pressed` or `aria-expanded` attributes respectively, to convey their current state to screen-reader users, otherwise they just read the title without the current status.
**Action:** Always include `aria-pressed` or `aria-expanded` mapped to the component's state for interactive toggle/accordion icon buttons.
