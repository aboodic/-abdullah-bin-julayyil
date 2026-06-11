## 2024-05-15 - Add aria-pressed to toggle buttons
**Learning:** Found multiple toggle buttons (Match Case, Match Whole Word, Use Regular Expression, Preserve Case) in `jupyterlab/packages/documentsearch/src/searchview.tsx` that lack `aria-pressed` attributes, making their state unclear to screen readers.
**Action:** Add `aria-pressed={props.caseSensitive}` (and equivalent props) to toggle buttons to improve accessibility.
