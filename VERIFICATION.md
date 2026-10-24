# Homework 3 verification

Checked October 24, 2026, using Chrome browser emulation and local static serving.

## Source and links

- Checked all eight HTML documents: seven portfolio/support pages and the cheese exercise.
- All local links, fragment targets, stylesheet references, images, media, and embedded document paths resolve.
- Each document has an external stylesheet. No script elements, inline style attributes, or embedded style blocks are included.
- The original Homework 2 files were compared with a SHA-256 snapshot taken before copying; they remain unchanged.
- README begins with the exact three field names in the Canvas submission table.

## Responsive layout

- At both 375px and 1280px, all eight documents had document scroll width equal to viewport width: no page-wide horizontal overflow.
- No broken images were detected at either width.
- Inspected the home and contact layouts visually. The narrow view stacks the home content, project cards, and contact sections, and wraps navigation without hiding it.
- These checks use browser emulation; a physical phone was not used.

## Keyboard and CSS-disabled versions

- Used Tab through home navigation and project links, contact inputs and textarea, and the cheese checkboxes, input, button, and link. Focused controls showed a 3px solid outline.
- The disabled contact send button remains disabled and is correctly skipped by keyboard navigation; it is the original form preview, not a messaging service.
- Confirmed that the skip link is the first focus target, becomes visible, and activates the main-content anchor.
- Loaded temporary copies of all eight documents with only their stylesheet links removed. The copies loaded zero stylesheets and retained identical HTML text, links, and form-control counts. The source HTML files were not changed for this check.
- Inspected the unstyled contact page to confirm native navigation, labels, inputs, and textarea remain available. Essential content stays in the HTML.

## Deployment

The same tracked files are packaged from the Git commit for Netlify. The existing HW3 site is updated at https://lively-marigold-eb560a.netlify.app/; the cheese exercise stays at /part1/cheese.html. The Homework 2 deployment is separate.

No course submission has been made on Gradescope. No formal WCAG audit or external HTML validation service is claimed by these checks.
