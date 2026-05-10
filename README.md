# network-observability.github.io

Org-level landing page for the [Modern Network Observability](https://network-observability.github.io/) ecosystem — a hub linking to the book, hands-on workshops, the companion lab, and the synthetic telemetry tooling.

## Develop

```bash
uv sync --group docs
uv run mkdocs serve
# open http://127.0.0.1:8000
```

## Deploy

Pushes to `main` auto-deploy to GitHub Pages via `.github/workflows/docs.yml`. The repo's Pages source must be set to **GitHub Actions** (Settings → Pages → Source).
