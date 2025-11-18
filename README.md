# Zain Garden Services

 A small static website for Zain Garden Services — HTML, CSS and static assets.

**Overview:**
This repository contains a lightweight static site for a gardening business. It's intended to be served as-is from any static hosting provider or viewed locally by opening `index.html` in a browser.

**Quick Start**
- Open in a browser: double-click `index.html` or use your browser's Open File dialog.
- Serve locally (recommended): from the project root run a simple static HTTP server (requires Python 3):

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

Alternatively, use the VS Code Live Server extension to serve with live reload.

**Files & Structure**
- `index.html` — main HTML page
- `style.css` — site stylesheet
- `public/` — static assets (images, fonts, etc.)
- Git metadata and other config files may also be present at the project root

**How to Edit**
- Edit `index.html` to change content and structure.
- Edit `style.css` to change appearance.
- Add or replace assets in `public/` and update references in the HTML/CSS.

**Deployment**
This is a static site — deploy to GitHub Pages, Netlify, Vercel (static), or any static host by pointing to the repository root.

Common deployment options:
- GitHub Pages: push to a repository and enable Pages in repository settings (use `main` branch / root).
- Netlify / Vercel: connect the repository and set the publish directory to the repository root.

**Contributing**
- Make changes on a feature branch, test locally, and open a pull request describing the change.

**License & Notes**
No license file is included. If you want to publish this project with an explicit license, add a `LICENSE` file (MIT/Apache/CC-BY, etc.).

---

If you'd like, I can also:

- add a `LICENSE` file,
- add a `.gitignore`, or
- generate deployment instructions tailored to GitHub Pages or Netlify.
