# Ankush Kumar - Portfolio

A recruiter-focused, static portfolio for Ankush Kumar. It uses plain HTML, CSS, and JavaScript so it can be hosted directly on GitHub Pages.

## Local preview

From this directory, run any static server, for example:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## GitHub Pages deployment

1. Create a public repository named `Ankush2k.github.io` under the `Ankush2k` account.
2. Push the contents of this directory to the `main` branch.
3. In repository Settings, open Pages and select **GitHub Actions** as the source.
4. The workflow in `.github/workflows/deploy-pages.yml` will publish the site.

The expected URL is https://ankush2k.github.io.
