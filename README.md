# OpenPoem®

Static landing page for OpenPoem's MCP tools.

## What it is

- `index.html` — single-page site
- Animated node-edge graph background (Canvas 2D)
- Banner blocks for the published tools:
  - **Spec Score MCP** — scores specs on 4 axes (completeness, clarity, constraints, specificity)
  - **Docs MCP** — writes specs to GitHub on a branch; validator enforces 5 required headings

## Running locally

Open `index.html` in a browser. No build step.

```bash
python3 -m http.server 8080
```

## Deploy

Served via GitHub Pages from `main`. Custom domain `openpoem.org` is set via `CNAME`.

## License

© 2026 OpenPoem®. All rights reserved.
