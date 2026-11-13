# Bridge Not Bills — campaign website

A complete, responsive, static advocacy website for GitHub Pages. No build tooling, database, or mock petition backend is used.

## Publish with GitHub Pages
1. Create a new **public** GitHub repository (e.g. `bridge-not-bills`).
2. Upload **all** files and the `assets` directory from this package to the repository root, preserving paths.
3. In the repository, open **Settings → Pages**. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Wait for GitHub to show the live URL, typically `https://USERNAME.github.io/bridge-not-bills/`.
5. Check the mobile layout and all images. The site uses relative URLs and works at repository subpaths.

## Before public launch
- Connect a real petition provider. The page intentionally does **not** collect signatures or claim any have been received.
- Fact-check op-ed claims, meeting recollections, donor reporting, and financing numbers; add source links.
- Independently reconcile the official IBR financing plan against the alternative and evaluate feasibility, pledge timing, and legal authority.
- Decide campaign name, contact address, privacy policy, and custom domain (optional).

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit `http://localhost:8000`.
