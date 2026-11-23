# Landing page

The Warm Paper portfolio landing page is a static site in `dist/`. Open
`dist/index.html` in a browser, or serve it locally with:

```sh
cd landing
python3 -m http.server 8000 --directory dist
```

No build step or dependencies are required. `.openai/hosting.json` is a
placeholder; configure it for the chosen hosting service before deployment.
