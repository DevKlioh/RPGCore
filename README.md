# RPGCore Wiki · v0.0.1

Static documentation website for RPGCore by Klioh_.

## Preview locally

Open `index.html` in a modern browser. The site uses static HTML, CSS and JavaScript with no build process.

## Publish to GitHub Pages

1. Create a GitHub repository, e.g. `RPGCore-Wiki`.
2. Upload `index.html`, `styles.css`, `app.js`, `data.js` and `.nojekyll` to the repository root.
3. Open **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Visit the GitHub Pages URL after deployment.

## Editing the wiki

- `app.js` contains the page content, navigation, class/quest explorer and search.
- `styles.css` controls colors and responsive layout.
- `data.js` is generated from the RPGCore v0.0.1 Quest Rotation source archive and contains class, quest and configuration reference data.

This website documents the supplied Quest Rotation source archive. It is not a live-server test report.


## Interactive Class Encyclopedia
Select one of seven class paths, inspect all three class ranks, and choose any of 147 active skills. The level 1–10 simulator uses damage, targeting, and healing settings extracted from the bundled `skills.yml` and the RPGCore skill damage formula. Values are estimates excluding allocated character stats and passive boosts.
