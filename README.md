# SUNBOYS Docs

Documentation repository for the SUNBOYS student solution autocheck platform.

The documentation site is built with MkDocs and published to GitHub Pages.

## Local Preview

```powershell
pip install -r requirements.txt
mkdocs serve
```

Open `http://127.0.0.1:8000`.

## Build

```powershell
mkdocs build --strict
```

## Publishing

GitHub Pages publishing is configured in `.github/workflows/pages.yml`.
In the repository settings, set Pages source to `GitHub Actions`.
