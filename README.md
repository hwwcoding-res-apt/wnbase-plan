# plan.wnbase.com

Static planner app — single file, no build step. Deploy `index.html` as-is
(e.g. GitHub Pages, root of the repo).

Config to check before deploying (top of the `<script>` in `index.html`):
- `FILES_ORIGIN` — should point at `https://files.wnbase.com`
- `ALLOWED_FILES_ORIGINS` — origins allowed to postMessage a file ID back
  into this app after "+ Add File" is used
