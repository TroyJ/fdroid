# TroyJ F-Droid Feed

This repo is the public artifact repo for TroyJ Android apps distributed
through the shared F-Droid feed.

Feed URL:

- `https://troyj.github.io/fdroid/repo/`

Currently deployed apps:

- Tree Viewer (`com.prado.treeviewer`, current feed versionCode `72`) from `TroyJ/prado-overlays/accessibility-tree-viewer`
- GPS Sim (`com.prado.gpssim`, current feed versionCode `1`) from `TroyJ/prado-overlays/gps-sim`

What lives here:

- published APKs
- F-Droid index files
- app icons
- per-app release metadata

What does not live here:

- app source code
- shared deployment scripts
- signing secrets

Publishing model:

- `main` contains repo metadata such as this README
- `gh-pages` contains the published feed snapshot served by GitHub Pages
- shared deployment logic lives in `TroyJ/fdroid-tools`
