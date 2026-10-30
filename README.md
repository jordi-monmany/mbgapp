# mbgapp

Static site for **mbgapp**, a personal [rclone](https://rclone.org/)-based tool that copies
files from the owner's own Google Drive folders to the owner's own computer. The tool has a
single user, its owner, and runs only on the owner's hardware.

This repository exists because Google requires a public home page, a privacy policy and a
terms of service page before a personal OAuth app can be published to production. It contains
plain HTML and CSS only, with no build step and no external assets, and is served with
GitHub Pages.

Live site: <https://jordi-monmany.github.io/mbgapp/>

- Home: <https://jordi-monmany.github.io/mbgapp/index.html>
- Privacy policy: <https://jordi-monmany.github.io/mbgapp/privacy.html>
- Terms of service: <https://jordi-monmany.github.io/mbgapp/terms.html>

## Files

- `index.html` – home page
- `privacy.html` – privacy policy
- `terms.html` – terms of service
- `.nojekyll` – tells GitHub Pages to serve the files as is, without Jekyll processing

## Note

A Google Search Console verification HTML file may be added to the repository root later so
that the `jordi-monmany.github.io` domain can be verified for the Google Auth Platform.
