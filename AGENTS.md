# AGENTS.md

## Project overview
This repository is a static HTML/CSS landing page for a fictional online library. There is no package manager, build step, or test suite in the root workspace.

## Key files
- `index.html` and `styles.css`: the main root landing page currently being edited.
- `FES Library - CSS/`: a fuller, older reference implementation with its own `index.html`, `styles.css`, and assets.
- `README.md`: project-level context if additional documentation is needed.

## Workflow conventions
- Treat this as a plain static front-end project unless a task explicitly adds framework tooling.
- Prefer small, targeted HTML and CSS edits over broad rewrites.
- Keep markup semantic and accessible. Use descriptive alt text and avoid unnecessary wrappers.
- Reuse the existing design language: blue-themed library branding, clean nav/header layout, minimal utility classes, and responsive spacing.

## Asset and path guidance
- Relative asset paths are case-sensitive on some systems, especially Windows.
- Several folders/files contain spaces in their names (for example `FES Library - CSS/`), so path handling must remain exact.
- When comparing examples across folders, confirm whether the task targets the root page or the reference project before editing assets or links.

## Validation
- There is no automated build/test command in this repo.
- To validate visual changes, open the relevant HTML file in a browser or use a local preview extension such as Live Server.
- If a change touches the reference implementation in `FES Library - CSS/`, make sure the assets and CSS references still match the directory structure.

## Avoid
- Do not introduce a framework or bundler without explicit instruction.
- Do not rename folders or move assets unless the task specifically requires it.
- Do not assume the root project and the `FES Library - CSS/` folder are identical; they are separate variants.
