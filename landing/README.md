# Landing page

The Warm Paper portfolio landing page is a static site in `dist/`. Open
`dist/index.html` in a browser, or serve it locally with:

```sh
cd landing
python3 -m http.server 8000 --directory dist
```

No build step or dependencies are required.

The GitHub Actions workflow deploys `dist/` to GitHub Pages when changes are
pushed to `main`. In the repository's Settings → Pages, set the build and
deployment source to **GitHub Actions**. The expected project site address is
`https://ryanjmaher.github.io/ryanjmaher/`.

`.openai/hosting.json` is a placeholder and is not used by GitHub Pages.
