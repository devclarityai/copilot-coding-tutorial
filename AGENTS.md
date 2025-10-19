# Repository Guidelines

## Project Structure & Module Organization
- `web-app/` contains the public site. Key files: `index.html` (landing page), `features.html` (feature deep-dive), `styles.css` (global styling), and `scripts.js` (animations for the landing page grid).
- Keep additional assets alongside their consumers (e.g., images under `web-app/assets/` and referenced with relative paths). Duplicate the existing HTML structure when adding new pages so navigation stays consistent.

## Build, Test, and Development Commands
- Serve locally with `cd web-app && python3 -m http.server 8000` to preview all pages at `http://localhost:8000`.
- For quick checks, you can also open `web-app/index.html` directly in a browser, but the HTTP server route keeps relative links working as expected.

## Coding Style & Naming Conventions
- HTML uses two-space indentation, semantic sectioning tags (`header`, `main`, `section`), and lowercase filenames.
- CSS classes follow kebab-case (`.feature-card`, `.learn-more-btn`) grouped by page sections with concise comments for context.
- JavaScript sticks to modern syntax (`const`, `let`, arrow functions) and guards behavior by pathname (see `scripts.js`). Inline comments should explain non-obvious logic only.

## Testing Guidelines
- There is no automated test suite; perform manual verification in the browser.
- Confirm navigation links resolve correctly, hero/feature animations trigger once on `index.html`, and layout remains responsive around 375px, 768px, and 1280px widths.
- When adding interactions, test both the targeted page and other pages to ensure scripts remain scoped.

## Commit & Pull Request Guidelines
- Follow the existing history: concise, sentence-case summaries in present tense (e.g., `Update feature animation`) and reference issues with `(#ID)` when relevant.
- Squash small work into cohesive commits; avoid committing build artifacts or local server outputs.
- Pull requests should state the goal, highlight visual changes with screenshots or GIFs, and list manual verification steps (e.g., “Viewed in Safari/Chrome, mobile + desktop”).
