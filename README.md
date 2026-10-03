# Shahzaib Hassan — Portfolio

A focused personal portfolio built with [Zola](https://www.getzola.org/) and the [Duckquill](https://codeberg.org/daudix/duckquill) theme.

## Run locally

```bash
zola serve
```

The site is pinned to Zola `0.20.0` for compatibility with the included theme revision.

## Content

- Main portfolio: `content/_index.md`
- Visual styling: `static/portfolio.css`
- Site metadata/navigation: `config.toml`
- Resume: `static/shahzaib-hassan-cv.pdf`

## Publishing

The generated site is served from the `gh-pages` branch. Build with Zola, then
publish the contents of `public/` to that branch. This avoids a dependency on
GitHub Actions while Actions are unavailable for the account.
