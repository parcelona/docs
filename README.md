# Parcelona docs

The user docs for [Parcelona](https://parcelona.app), the Mac app that prices, writes and posts listings to eBay and Facebook. Built with [Mintlify](https://mintlify.com) and served at https://docs.parcelona.app.

Pages are MDX files with YAML frontmatter. `docs.json` holds the navigation, theme, colors and logo. The logo and favicon are copies of `site/logo.svg`, `site/logo-white.svg` and `site/mark.svg` in [parcelona/inertia](https://github.com/parcelona/inertia).

## Preview

```sh
npm i -g mint
mint dev                 # http://localhost:3000
mint validate            # before you push
mint broken-links
```

Merging to `main` deploys the site.
