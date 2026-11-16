# Customer Hierarchy Selector — Design Guidelines

Documentation for the **Customer Hierarchy Selector**, a page-level control in Business AI 360
that lets a user switch the company entity in focus — viewing data for the global parent or any
subsidiary their account can access — without changing filters on individual tables, cards, or charts.

The guidelines are a single self-contained page (`index.html`) styled after the
[SAP Fiori Design System](https://www.sap.com/design-system/fiori-design-web) documentation.

## Contents

- **Overview** — what the selector is and the problem it solves
- **Scope Hierarchy** — the canonical page-level pattern, deprecated alternatives, and a migration table
- **Anatomy** — closed and open states with element specs
- **Behavior** — default state, interaction flow, scope of effect, persistence rules, empty state
- **When to Use** — do / don't guidance
- **Accessibility** — keyboard, ARIA, screen-reader, focus, and contrast requirements
- **Related Components** — Dynamic Page Header, Popover, Drop-Down, and filter alternatives

## Viewing

Open `index.html` in a browser, or view the published page via GitHub Pages:

- Settings → Pages → Source: **Deploy from a branch**, branch `main` / root
- Published at `https://boyanpetkovsap.github.io/customer-hierarchy/`

## Source

The selector is reproduced in HTML/CSS using tokens from the Business AI — Tab Figma file
(Dynamic Page Header, node `12946:41970`).
