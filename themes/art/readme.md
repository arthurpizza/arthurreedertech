# art — Arthur Reeder Tech theme

The custom Hugo theme for [arthurreeder.tech](https://arthurreeder.tech).

Plain templates + one CSS file (`static/css/style.css`). No JavaScript, no build step. Dark theme in the site's brand blue (`#28abe1`), system font stack, monospace reserved for labels and nav.

Layout notes:

- `layouts/partials/header.html` opens the document, `<head>`, sticky site header, and `<main>`; `layouts/partials/footer.html` closes them. Every page layout is just header + content + footer.
- The homepage (`layouts/index.html`) renders the hero, the intro from `content/_index.md`, service cards, the commitment section, and a closing contact band.
- Page-specific SEO/social meta comes from each page's `description` front matter, falling back to `[params] description` in `hugo.toml`.

Originally based on the dead-simple Hugo starter theme by Eric Murphy.
