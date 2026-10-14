# Moci Hu — Portfolio website

This is one unified, static website with three pages:
- `index.html` — main portfolio
- `projects/vanguard.html` — Vanguard A/B Test case study
- `projects/spotify.html` — Spotify recommendation system case study

Both pages share `style.css` and the same navigation. Clicking the Vanguard project card on the homepage opens the case study **on the same website**, not GitHub. The case study links to the project GitHub repository separately.

## Preview
Open `index.html` in a browser or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Publish with GitHub Pages
Upload the **contents** of this folder to your portfolio site's GitHub repository (preserve the `projects/` folder). In GitHub Settings → Pages, publish from the main branch and root directory.

The case study will be at `/projects/vanguard.html` on the same domain as the portfolio.

## Content notes
The case study is an independent collaborative analysis based on the available experimental data; it is not a commissioned Vanguard project. The business recommendations are conditional on business priorities. Before publishing, verify the number of collaborators in the Project Background (the provided presentation lists four contributors).

Four responsive sage-green SVG charts have been added under the relevant Key Insights on projects/vanguard.html. Charts are stored in assets/.
