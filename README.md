# GNSS Multi-Station Geodetic & Kinematic Master Dashboard

Interactive GNSS dashboard, hosted with GitHub Pages.

## Publish on GitHub Pages

1. Create a new public repository on GitHub (for example `gnss-dashboard`).
2. Upload `index.html`, `.nojekyll` and this `README.md` to the root of the repository
   (Add file > Upload files, then Commit changes).
3. Open Settings > Pages. Under "Build and deployment", set Source to
   "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute or two the site is live at
   `https://<your-username>.github.io/<repository-name>/`

## Notes

- All station data is embedded in `index.html`; no server or build step is needed.
- Plotly and the Inter / JetBrains Mono fonts load from public CDNs, so viewers need an internet connection.
- `.nojekyll` tells GitHub Pages to serve the file as-is without Jekyll processing.
