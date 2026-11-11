# Akanksh Shetty Portfolio

A single-page portfolio (HTML, CSS, vanilla JavaScript). No build step.

## Files
- `index.html` the whole site
- `Akanksh_Shetty_Resume.pdf` the Download Resume button
- `.nojekyll` tells GitHub Pages to serve files as they are

## Publish on GitHub Pages
1. Create a repository named `Akanksh171717.github.io` (or any name).
2. Upload these files to the repository root.
3. Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save.
4. Your site appears at `https://akanksh171717.github.io/` within a minute or two.
5. Delete the old `app.js`, `style.css`, `projects.html` and `src/` if they are still in the repo. The new site does not use them.

## Things to edit
- **Your "why the USA" story:** in `index.html`, find `EDIT YOUR STORY HERE`. Change the `story` and `points` text of stage 3 (The Crossing).
- **Email:** search for `akankshshetty@worksmail.in` and replace it with the address you want public.
- **Resume:** replace `Akanksh_Shetty_Resume.pdf` with a newer file of the same name.
- **Case study findings:** edit the `CASES` list near the bottom of `index.html`. Add real numbers only where you are comfortable sharing them.

## Live floating scene
A small animated panel floats beside the page and changes as you scroll: data pipeline (hero), one scene per career stage (circuit, analytics loop, crossing, database, valve network), thinking engine ring, KPI bars, reconciliation, forecast chart, capability graph, and a closing pulse.
- All scenes are drawn in SVG and use illustrative sample data only. Nothing is connected to real company data.
- Visitors can hide it with the Hide button. It is hidden automatically on phones, and animation is switched off for visitors who prefer reduced motion.
- Scene text lives in the `CAP` and `DESC` lists inside the `LIVE FLOATING SCENE` block of `index.html`.
