# Northfold Product Page — Agent Instructions

## Project Goal

Reproduce the Northfold Stoneware Mug product page as faithfully as possible using the supplied desktop and mobile reference screenshots.

Treat the screenshots as the source of truth. This is a screenshot-replication task, not a redesign.

## Required Deliverables

The final deliverables must be:

- `index.html`
- `styles.css`
- `favicon.ico`

Use semantic HTML5 and vanilla CSS3 only. Do not use JavaScript, frameworks, CSS libraries, icon libraries, package dependencies, or build tools.

## Reference Assets

Inspect `Desktop.png`, `Mobile.png`, and any supplied product HTML and image assets before implementation.

Treat extracted HTML as a reference for content, structure, and image sources. Remove Tailwind utility classes and all framework-specific styling.

Do not use the screenshots as page backgrounds. Do not stretch images or silently substitute unrelated product photography.

## HTML and Accessibility

- Use semantic HTML5 elements, including `header`, `nav`, `main`, `section`, `form`, and `footer`.
- Use exactly one H1 and maintain a logical heading hierarchy.
- Provide appropriate alt text for product images.
- Associate visible labels with every form control.
- Implement the Oat, Slate, and Moss options as native radio inputs inside a fieldset with a legend.
- Select Oat by default.
- Include a labelled quantity input with a minimum and initial value of 1.
- Give icon-only interactive controls accessible names.
- Ensure keyboard navigation and visible focus indicators.
- Keep Add to Cart non-functional. Do not add JavaScript.

## CSS and Responsive Design

- Put all CSS in `styles.css`.
- Use CSS Grid and Flexbox where appropriate.
- Define reusable colours, spacing, typography, borders, and radii as CSS custom properties.
- Match the supplied screenshots' layout, typography, image proportions, spacing, and colours.
- Use a two-column product layout above 750px and a single-column layout below 750px.
- Prevent horizontal scrolling at 360px.
- Implement dark mode using `prefers-color-scheme: dark`.
- Preserve the screenshot's appearance in light mode.

## Icons and Favicon

Use inline SVG for the shopping cart, mobile menu, and benefit icons. Do not use emoji, Unicode icon substitutes, icon fonts, or external icon libraries.

Generate a valid `favicon.ico` file. Do not rename an SVG file to `.ico`.

## Visual Verification

When browser tooling is available, render the implementation at desktop and mobile viewport sizes and compare the results with the reference screenshots.

Correct visual discrepancies before considering the task complete.

Verify responsive behaviour, keyboard accessibility, form labels, image alternatives, light and dark themes, and the absence of horizontal overflow at 360px.

Run Lighthouse accessibility auditing if available, targeting a score of 95 or higher.

Do not claim to have performed checks that were not actually completed.

## Git and Deployment

Inspect the existing Git status before making changes.

If authorized, create at least three meaningful commits with clear messages. Do not overwrite unrelated work, rewrite existing history, or commit unrelated files.

Prepare for GitHub Pages deployment, but do not push commits, publish the repository, or change remote settings without authorization.

## Working Method

Inspect the workspace and existing files before modifying anything. Preserve useful existing assets and avoid unnecessary changes.

Implement the page directly in the project, verify it where possible, and report any outstanding limitations.

Do not add features or content that are absent from the reference or explicitly required by the task.
