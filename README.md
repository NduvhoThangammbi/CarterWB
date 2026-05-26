# Joe's Plumbing Website - Part 1 Complete

## Student Information
- Student Number: ST10500383
- Name: Nduvho Thangammbi

## Project Overview
Small business plumber website for lead generation/traffic.

## Website Goals and Objectives
- Increase traffic 20% KPI.
- Generate leads via enquiry form.

## Key Features
5 pages, responsive nav, form, map.

## Sitemap
![Sitemap](images/sitemap.svg)

## Timeline
Part 1: Complete.

## Budget
Dev free, hosting $5/mo.

## Proposal
See proposal.html

## Changelog
- Initial multi-page site structure created: index.html, about.html, services.html, enquiry.html, contact.html
- Linked external stylesheet (css/style.css) across all pages for consistent desktop styling
- Implemented desktop-first CSS: theme variables, reset/base typography, cards/sections, form styling, footer styling
- Added interactive pseudo-class states for navigation links and buttons (:hover, :focus-visible, :active)
- Implemented responsive design breakpoints in css/style.css:
  - max-width: 900px (tablet layout adjustments)
  - max-width: 520px (mobile header/nav + spacing adjustments)
- Fixed services.html semantics to include a proper dl/dt/dd block so CSS applies correctly
- Updated contact.html to use a real embedded Google Maps iframe instead of a placeholder map URL

## Part 2: Designing the visuals (CSS Styling + Responsive)
### Desktop CSS implementation
- Created external stylesheet: `css/style.css`.
- Added base styles/reset, typography styles, and desktop layout structure (sticky glass header, container width, grid-based hero section).
- Styled common components across pages: sections/cards, description list (`dl/dt/dd`), navigation links, forms, buttons, and footer.
- Implemented interactive states for navigation and buttons using pseudo-classes (`:hover`, `:focus-visible`, `:active`).

### Responsive design (Tablet + Mobile)
- Added media queries:
  - `max-width: 900px` (tablet): hero switches to single-column.
  - `max-width: 520px` (mobile): header stacks vertically and navigation spacing adjusts.
- Used responsive techniques:
  - fluid typography via `clamp()`
  - relative padding/font sizes
  - responsive images (`max-width: 100%`) and full-width iframe sizing.

### What changed in this Part
- Linked stylesheet on all pages: `index.html`, `about.html`, `services.html`, `enquiry.html`, `contact.html`.
- Fixed `services.html` to include a proper `<dl>` wrapper so desktop CSS for `dl/dt/dd` can apply correctly.


## References (IEEE Style)
[1] S. Johnson, "Plumbing Industry Trends," Plumbing Assoc. J., vol. 45, pp. 12-20, 2023.
[2] Stats SA, "Construction Report," 2024 [Online]. Available: https://statssa.gov.za
[3] W3C, "HTML Best Practices," 2023.
[4] LocalBiz, "SMB KPIs," 2024.
[5] J. Ramirez, "Joe's Plumbing History," Internal Doc, 2010.
