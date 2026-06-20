## 2026-06-20 - Add aria-pressed to icon-only toggle buttons
**Learning:** Icon-only toggle buttons in search UIs often lack `aria-pressed` states, making it impossible for screen reader users to know if a filter (like Match Case or Regex) is currently active.
**Action:** Always add `aria-pressed={isActive}` to toggle UIs, particularly icon-only buttons that rely on visual state changes (like active classes) to convey information.
