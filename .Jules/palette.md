## 2026-05-29 - Adding aria-label and title to remove settings property button
**Learning:** Found that `trans.__()` localization function must be explicitly passed down as a prop (`trans={props.trans}`) from higher-order parent settings forms into nested child components rendering interactive elements in JupyterLab extensions.
**Action:** Always verify if a translation bundle (`TranslationBundle`) is available in the current component scope before trying to localize UI strings, and thread it down through props if needed when creating or updating custom UI controls in extensions.
