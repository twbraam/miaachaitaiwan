# 明仔載愛呷菜 Taiwan Market Website

Static GitHub Pages site for the 明仔載愛呷菜 Taiwan Market iOS app and MCP integration.

Production URLs after GitHub Pages deployment from `main` / root:

- Mandarin home: `https://twbraam.github.io/miaachaitaiwan/`
- Privacy Policy: `https://twbraam.github.io/miaachaitaiwan/privacy/`
- Support: `https://twbraam.github.io/miaachaitaiwan/support/`
- Terms of Use: `https://twbraam.github.io/miaachaitaiwan/terms/`
- English home: `https://twbraam.github.io/miaachaitaiwan/en/`
- English Privacy Policy: `https://twbraam.github.io/miaachaitaiwan/en/privacy/`
- English Support: `https://twbraam.github.io/miaachaitaiwan/en/support/`
- English Terms of Use: `https://twbraam.github.io/miaachaitaiwan/en/terms/`

The site is dependency-free HTML and CSS. Traditional Mandarin is the default
language at the root URLs. English pages live under `/en/`.
Support remains GitHub Issues. The site includes the publisher credit, MCP
privacy disclosures and analytics opt-out guidance; it has no usage analytics.
Publish the updated policy before enabling MCP analytics in production.

To preview locally:

```sh
python3 -m http.server 8080
```

GitHub Actions validates local page, stylesheet, and image references on pushes
to `main` and pull requests. GitHub Pages itself is configured to publish from
the repository root on the `main` branch.
