# Design system guidelines
These guidelines outline our approach to creating and maintaining a unified design system across our brands and services.

## Guidelines
Use a component-based approach with a single folder per component
- markup
- styles
- mock data
- tests

A component should not bleed styles or functionality into other parts of the DOM

Use linters and formatters to get a common style for all code
- prettier
- eslint
- sass-lint

Design reviews
- Components should have a visual regression test (story)
- Designer should review visual changes
- Developer should review code changes
- Chromatic

Cross-site focus
- Sizes and colors should always be themed
- These variables come from a separate theme package

## Practical solutions
File structures
- /packages/labrador-resources/view/content/ - components with mustache templates
- /packages/shared/components/ - components without mustache templates
- /packages/themes/ - theme-specific variables

Variables
- Styled-components themes initialize css variables
- These variables can be used in components regardless of technology

Conventions
- use 10-base rems
- every sass-based component should contain a single block
- all the variables exist in all the themes
- we do not introduce new variables lightly
