## 2026-05-27 - Added aria-label to icon buttons in Search View
**Learning:** Found multiple instances where icon-only buttons lacked aria-labels for screen reader accessibility in the document search panel. The buttons used `title` tags but missing `aria-label`.
**Action:** Always ensure `aria-label` matches the `title` attribute on icon-only buttons to guarantee screen-reader compatibility.
