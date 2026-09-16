# Aria Darvish — CV Website

A responsive personal website for Aria Darvish, a backend developer specializing in C#/.NET, ASP.NET Core, APIs, databases, and monitoring systems.

## Run locally

This is a dependency-free static site. Serve the repository with any static web server, for example:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish with GitHub Pages

The repository includes a GitHub Actions workflow that deploys this static site
to GitHub Pages whenever the `main` branch is updated.

1. Push the `main` branch to a GitHub repository.
2. In the repository, open **Settings → Pages** and set **Source** to
   **GitHub Actions** (this only needs to be done once).
3. Open the **Actions** tab and wait for the **Deploy GitHub Pages** workflow
   to finish. The deployment URL will appear in that workflow's summary.

You can also run the workflow manually from **Actions → Deploy GitHub Pages →
Run workflow**.
