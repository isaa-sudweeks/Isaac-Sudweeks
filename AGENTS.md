# Repository Guidelines

## Project Structure & Module Organization
- Root HTML pages: `index.html`, `work.html`, `experience.html`, `writing.html`, `contact.html`.
- Shared styling lives in `styles.css`.
- Static assets (images) live under `assets/`, currently `assets/projects/`.
- Reference docs and notes: `README.md`, `plan.md`, and a personal folder `Isaac's Stuff/` (non-site artifacts).

## Build, Test, and Development Commands
This is a static site with no build step.
- Open `index.html` directly in a browser to preview the site.
- For a simple local server (avoids file:// quirks), run:
  - `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Coding Style & Naming Conventions
- Use 2-space indentation in HTML and CSS.
- Prefer semantic HTML elements (`header`, `nav`, `main`, `section`, `footer`).
- Keep filenames lowercase and descriptive (e.g., `work.html`, `styles.css`).
- Favor simple class names that reflect layout or component intent (e.g., `.project-grid`).

## Testing Guidelines
- No automated tests are configured.
- Manually verify pages in a browser after changes and check for broken links and missing images.

## Commit & Pull Request Guidelines
- Commit messages follow a short, imperative style (e.g., "Add writing page", "Update site content").
- PRs should include:
  - A brief summary of changes.
  - Screenshots for any UI/content updates.
  - Linked issues if applicable.

## Assets & Content Notes
- Add new images under `assets/projects/` and reference them with relative paths.
- Keep image filenames lowercase and hyphenated (e.g., `mini-mars-rover.jpg`).
