# Copilot instructions for this repository

Purpose: Help an AI coding assistant be immediately productive working on this static Frontend Mentor project.

- **Primary project location:** `social-links-profile-main/` — this is the working site. Edit files inside this folder.
- **What this project is:** A static HTML/CSS solution for the "Social links profile" Frontend Mentor challenge. There is no build system, frameworks, or tests in the repo.

Key files and folders
- `social-links-profile-main/index.html` — main page to preview and edit.
- `social-links-profile-main/style-guide.md` — authoritative design tokens (colors, typography, layout widths). Use values here when implementing styles (e.g. green: `hsl(75, 94%, 57%)`, body size: `14px`, design widths: `375px` / `1440px`).
- `social-links-profile-main/assets/` — contains `images/`, `fonts/` (local font files under `fonts/static/`) and favicon assets. Example: `assets/images/favicon-32x32.png`.
- `social-links-profile-main/README-template.md` — template for the final project README. The author expects replacment of the starter README with this template-based README.
- `design/` — source design JPGs used as visual targets.

Architecture and conventions (what to know)
- Static, single-page: no JavaScript frameworks or build tools. Changes are made directly to HTML/CSS files under `social-links-profile-main/`.
- Mobile-first layout: follow the mobile-first workflow suggested in the README template. Responsive behavior should be validated between ~320px and large screens; designs are provided for 375px and 1440px.
- Semantic HTML: the starter `index.html` uses simple semantic content; prefer semantic tags (header, main, nav, section, footer) when expanding markup.
- Fonts: local fonts are provided; the project also allows linking to Google Fonts. If you change fonts, keep the weights used by the design (400, 600, 700).

Developer workflows (concrete commands)
- Quick preview (from repo root):
  - `cd social-links-profile-main && python -m http.server 8000`
  - Open `http://localhost:8000` in a browser to preview `index.html`.
- Deploy: this is a static site — deployable to GitHub Pages, Vercel, or Netlify. No build step required.

Project-specific guidance for AI edits
- Prefer minimal, focused changes. This repository is a small static site — avoid adding unnecessary tooling.
- When changing styles, consult `style-guide.md` for exact color values, font sizes, and breakpoints and reference the exact path you changed (e.g. `social-links-profile-main/index.html` and `social-links-profile-main/assets/`).
- README handling: replace the provided starter `README.md` with the `README-template.md` when producing the final project README. The template includes expected sections and a `screenshot.jpg` reference.
- Images/assets: when adding or updating images, place them under `social-links-profile-main/assets/images/` and keep filenames consistent with existing HTML references.

Examples (explicit lines to edit)
- Update the page title: edit `social-links-profile-main/index.html` `<title>` element.
- Change color token: update color usage to `hsl(75, 94%, 57%)` where applicable and prefer CSS custom properties if adding a stylesheet.
- Serve locally during edits: `cd social-links-profile-main && python -m http.server 8000` and inspect in the browser.

When unsure, ask the user for clarification rather than guessing layout intent (e.g., whether to add a new CSS file or inline styles). After any non-trivial change, include the exact file paths and a 1–2 sentence rationale in the PR description.

End of instructions — ask the repo owner if they want automated commits or a different branching policy.
