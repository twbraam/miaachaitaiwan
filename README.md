# 明仔載愛呷菜 Taiwan Market Website

Static GitHub Pages site for the 明仔載愛呷菜 Taiwan Market iOS app.

Production URLs after GitHub Pages deployment from `main` / root:

- Mandarin home: `https://twbraam.github.io/miaachaitaiwan/`
- Privacy Policy: `https://twbraam.github.io/miaachaitaiwan/privacy/`
- Support: `https://twbraam.github.io/miaachaitaiwan/support/`
- English home: `https://twbraam.github.io/miaachaitaiwan/en/`
- English Privacy Policy: `https://twbraam.github.io/miaachaitaiwan/en/privacy/`
- English Support: `https://twbraam.github.io/miaachaitaiwan/en/support/`

The site is dependency-free HTML and CSS. Traditional Mandarin is the default
language at the root URLs. English pages live under `/en/`.

To preview locally:

```sh
python3 -m http.server 8080
```

GitHub Actions validates local page, stylesheet, and image references on pushes
to `main` and pull requests. GitHub Pages itself is configured to publish from
the repository root on the `main` branch.
