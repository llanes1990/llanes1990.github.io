# AGENTS.md

## Cursor Cloud specific instructions

This is a static HTML/CSS personal portfolio site (PauloLlanes.com) hosted on GitHub Pages. There is **no build system, no package manager, no dependencies, no tests, and no linter**.

### Running locally

Serve the site with any static file server from the repository root:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

### Project structure

- `index.html` — Home page
- `resume.html` — Resume download page
- `contact.html` — Contact page
- `style.css` — Shared stylesheet (dark theme, CSS variables, responsive)
- `images/` — Static image assets
- `resume/` — Resume files (PDF, DOCX)
- `CNAME` — GitHub Pages custom domain config (`paulollanes.com`)
- `OLD/` — Archived previous version of the site

### Notes

- No linting or automated tests exist. Validate changes by visual inspection in the browser.
- The CSS imports Google Fonts (`Inter`) at runtime, so internet access is needed for full font rendering.
