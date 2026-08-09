# Frog Information Website

A lightweight, static information site for Frog. It includes:

- Home and animated rarity showcase using the supplied R, SR, SSR, and MR icons
- Feature overview
- Searchable command reference
- Player guides
- Privacy notice
- Rules and terms

## Publish with GitHub Pages

Upload **the contents of this folder** to the root of the `frog-privacy` repository. The repository root should contain `index.html`, the `assets` folder, and each page folder.

In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and `/ (root)` folder. The site will be available at:

`https://ayumimiii.github.io/frog-privacy/`

Useful page links:

- Privacy: `https://ayumimiii.github.io/frog-privacy/privacy/`
- Terms: `https://ayumimiii.github.io/frog-privacy/terms/`
- Guides: `https://ayumimiii.github.io/frog-privacy/guides/`

## Customize

Colors and layout live in `assets/styles.css`. Shared animation and command search behavior live in `assets/script.js`. No framework, account connection, database, or build command is required.

The browser-tab and header logo use `assets/frogstamp.png`. Rarity artwork uses the four `assets/rarity-*.png` files; replacing those files while keeping their filenames preserves the website animations.
