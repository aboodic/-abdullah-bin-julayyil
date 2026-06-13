## 2026-06-13 - Added aria-label to Search component
**Learning:** Search components acting as filter boxes often lack visible labels, making them inaccessible to screen readers without an explicit aria-label fallback.
**Action:** Always provide an aria-label fallback (like the placeholder or 'Search') for input widgets that don't have associated <label> elements.
