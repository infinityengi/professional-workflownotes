# Professional Workflow Notes - Full Guide

Welcome to the full guide. This page expands the README with more details, examples, and links.

## Contents
- Overview
- Detailed steps
- Example issues for a lane detection epic
- Publishing and CI
- References

## Overview
This guide provides a practical, repeatable workflow for software projects and research publishing. Use it as the basis for project onboarding and for keeping archives of reproducible experiments.

## Example: Lane detection sprint plan
See the `issues/` folder for 8 ready-to-create GitHub issues for the "Real-time lane detection" epic. Copy and paste the markdown files into new Issues in your repository.

## Publishing docs with MkDocs
1. Install:
```bash
pip install mkdocs mkdocs-material
```
2. Structure:
- `docs/` holds the site pages
- `mkdocs.yml` configures the site
3. Local preview:
```bash
mkdocs serve
# open http://127.0.0.1:8000
```

## CI deployment
A GitHub Actions workflow is included at `.github/workflows/deploy-docs.yml`. It builds the site and publishes it to the `gh-pages` branch.

## References and further reading
- GitHub Projects
- MkDocs Material
- GitHub Actions documentation
