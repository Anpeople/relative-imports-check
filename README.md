# relative-imports-check

Cobrowse test page for relative CSS/baseURL (images, fonts). Served via **GitHub Pages** from the `docs` folder.

## View the page on GitHub Pages

1. **Push this repo** to GitHub (if you haven’t already).

2. **Turn on GitHub Pages:**
   - Open the repo on GitHub → **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment**:
     - **Source:** Deploy from a branch
     - **Branch:** `main` (or your default branch)
     - **Folder:** `/docs`
   - Click **Save**.

3. **Wait a minute or two** for the first deployment. Your page will be at:

   **`https://<your-username>.github.io/relative-imports-check/relative-css-nds.html`**

   (Replace `<your-username>` with your GitHub username.)

Relative paths (`images/test-image.jpg`, `fonts/Thelawes.otf`) work because the page and assets are served from the same origin.

## Local development

Serve the `docs` (or `public`) folder from the same origin, e.g.:

```bash
cd docs && npx serve
```

Then open `http://localhost:3000/relative-css-nds.html`.
