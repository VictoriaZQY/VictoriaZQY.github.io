# Victoria Zhu — GitHub Pages website

This is a complete static website. It has no build step, package installation, API key, or configuration value to edit.

## Publish on GitHub Pages

1. Create a **public** repository named `victoriazqy.github.io` under the `VictoriaZQY` GitHub account. You can also use any other repository name; the site's relative links work in both cases.
2. Extract this ZIP. Upload **the contents of the `victoria-github-pages` folder**, not the ZIP or the enclosing folder, to the repository's `main` branch. The repository root should contain `index.html`, `papers/`, `assets/`, `.nojekyll`, and this README.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)**. Save.
4. For the suggested repository name, the homepage will be `https://victoriazqy.github.io/` and the paper page will be `https://victoriazqy.github.io/papers/`. GitHub may take a few minutes to publish the first version.

## Add an author manuscript later

The homepage's **Read my papers** link and the `/papers/` page work immediately. The published EM-Merge paper already links to its DOI.

To add your accepted author manuscript, upload a PDF named exactly `em-merge-accepted.pdf` inside the `papers/` directory. After GitHub Pages updates, the `/papers/` page automatically shows an **Accepted manuscript → Open PDF** link. The direct PDF address will be:

`https://victoriazqy.github.io/papers/em-merge-accepted.pdf`

The PDF is not included in this package because no accepted manuscript PDF was provided. Add only a version you have permission to share, and include any required author-version notice in the PDF.

## Files

```text
index.html             Homepage
papers/index.html      Paper library and automatic PDF link
assets/style.css       Shared responsive styles
assets/favicon.svg     Site icon
.nojekyll              Publish static files as supplied
README.md              These instructions
```
