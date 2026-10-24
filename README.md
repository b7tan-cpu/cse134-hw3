| Field | Value |
| --- | --- |
| Repository URL | https://github.com/b7tan-cpu/cse134-hw3 |
| Part 1 Deployed URL | https://lively-marigold-eb560a.netlify.app/part1/cheese.html |
| Part 2 Deployed URL | https://lively-marigold-eb560a.netlify.app/ |

# CSE 134 — Homework 3

Author: Binteng Tan

## Part 1: Cheese

`part1/cheese.html` links to `part1/cheese.css`. The stylesheet includes inherited typography, element/class/ID selectors, rem headings, the box model, hover/focus styles, and a commented source-order cascade example.

## Part 2: Personal portfolio

The existing Homework 2 personal portfolio is copied to the repository root. All seven HTML pages link to the shared, hand-authored `styles.css`:

- `index.html`: introduction and featured project concepts.
- `about.html`: background, education, skills, and interests.
- `projects.html`: the two original planning-stage projects.
- `contact.html`: email and the existing non-submitting form preview.
- `experiments.html`: existing HTML and media demonstrations.
- `sitemap.html`: navigation to the existing pages.
- `embed.html`: the supporting embedded document.

The stylesheet uses shared custom properties, rem typography, em button padding, Flexbox navigation, Grid layouts, a narrow-screen media query, and visible keyboard focus. Required comments identify the attribute selector and two combinators. System fonts and existing assets are used; there are no CSS frameworks or JavaScript dependencies.

The Homework 2 console and canvas scripts are omitted from the Homework 3 copy. Their existing examples remain in the experiment page with brief explanations that they do not run in this CSS-only version. The Homework 2 source and deployment remain unchanged.

## Preview and deployment

This is a buildless static website. Publish the repository root (`.`), without a build command. `netlify.toml` records that setting. The homepage opens at `/`; the cheese exercise opens at `/part1/cheese.html`.

For local preview, run `python3 -m http.server 8080` from this directory and open `http://localhost:8080/`.

## Verification

See `VERIFICATION.md` for the completed checks and their limits. The repository and Netlify deployment are updated together; no ZIP or screenshot is needed for the course submission.
