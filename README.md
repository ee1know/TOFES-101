# Field Care Form (v4.7)

Static single-file HTML optimized for GitHub Pages.

## How to deploy
1. Create a new public repo on GitHub (or use an existing one).
2. Add these files to the root of the default branch:
   - `index.html`
   - `.nojekyll` (empty file)
3. Commit & push.
4. In **Settings → Pages**, set:
   - Source: **Deploy from a branch**
   - Branch: **main** / **master** (root)
5. Wait for Pages to build, then open the site URL.

## Notes
- Primary language: Hebrew (RTL).
- Bottom sticky bar: **שמירה כ-PDF** button.
- Works entirely offline; no external dependencies.
- Print to PDF via the browser print dialog (button triggers `window.print()`).

