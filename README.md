SM Enterprises — Build & Preview

Quick steps to build/preview this static site locally.

- Open browser: double-click `index.html` in the project folder to preview locally.

- Run a local static server (recommended for correct routing/assets):

  - With Python 3 (works on Windows PowerShell / CMD):

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

  - With Node (if installed):

```bash
npx http-server -p 8000
# or
npx serve -s . -l 8000
```

- VS Code: Install the "Live Server" extension and click "Go Live" to preview with auto-reload.

Notes:
- The repository is a simple static site. No build tools or dependencies are required.
- Files created: `index.html` and `style.css` (copied from `index.html.txt` and `style.css.txt`).

If you want, I can:
- Add a simple `package.json` with a `preview` script.
- Set up a GitHub Pages deploy workflow.
