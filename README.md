# Who makes the party happen? Community festivals in Australia (FIT3179 Data Visualisation 2)

All files sit in one folder (no sub-folders), so this is ready for GitHub Pages: upload every file to the root of a repository, then turn on Pages (main branch, root). The page is `index.html`.

- `index.html` and `style.css`: the page and its style.
- `map*.json` and `chart*.json`: one readable Vega-Lite specification per map or chart (20 in total).
- Every other `.json` and `states.geojson`: the data the specifications load.

Preview locally: run `python -m http.server 8000` in this folder and open http://localhost:8000 (charts load JSON files, so double-clicking index.html will not work).
Sources are listed in the page footer.
