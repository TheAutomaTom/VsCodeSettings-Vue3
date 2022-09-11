# Quick links to common minor issues

## General Editor Settings
- Bracket pair and guide colors

    Reference: https://neutrondev.com/vs-code-colored-bracket-pair-guides/
    
- Linting and Formetting advice

    Reference: https://vueschool.io/articles/vuejs-tutorials/eslint-and-prettier-with-vite-and-vue-js-3/

---

## Tailwind & Scss
- `@apply` warning squiggles
           
> ... you need to disable the lint rule of unknownAtRules.
   
1. Create file `/vscode/settings.json` if it does not exist.
1. Add `{ "scss.lint.unknownAtRules": "ignore" }`.

    _This could be set in local global settings, but then it wouldn't get checked into the repo._

    Reference: https://github.com/tailwindlabs/tailwindcss/discussions/5258

---