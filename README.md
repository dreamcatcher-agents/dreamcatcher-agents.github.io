# Dreamcatcher Agents homepage

No-build static GitHub Pages site for `agents.dreamcatcher.ai`.

## Files

- `index.html` — standalone homepage markup
- `styles.css` — static CSS, no framework/build tool
- `assets/*.svg` — local brand/diagram SVGs
- `CNAME` — GitHub Pages custom domain: `agents.dreamcatcher.ai`
- `.nojekyll` — bypasses Jekyll processing

## GitHub Pages

This repository is intended to be served from the `main` branch at `/` using GitHub Pages' deploy-from-branch mode. There is no package manager, bundler, or build step.

## DNS

Create or update this record at the `dreamcatcher.ai` DNS zone:

```text
Type: CNAME
Name/Host: agents
Value/Target: dreamcatcher-agents.github.io
TTL: automatic or 300s
```

The fully qualified record is `agents.dreamcatcher.ai` → `dreamcatcher-agents.github.io`.
