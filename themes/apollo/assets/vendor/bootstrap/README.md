# Bootstrap SCSS (vendored)

This theme expects the Bootstrap v5 SCSS source to be placed in this directory at `themes/Apollo/assets/vendor/bootstrap/scss/`.

## How to populate

1) Download the Bootstrap v5 source archive from https://github.com/twbs/bootstrap (no `npm install` required).
2) Copy the `scss/` folder from the archive into `themes/Apollo/assets/vendor/bootstrap/scss/`.
3) Keep filenames unchanged so the import paths in `assets/scss/main.scss` resolve correctly.
4) Do not commit unused assets from `dist/`; only the SCSS source is needed.

Until the SCSS is placed here, the theme build will fail because the imports expect these files.
