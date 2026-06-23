# OSL Incubator Documentation Site

This repository contains the source for the OSL Incubator public documentation site built with **MkDocs** and the **Material for MkDocs** theme.

## Prerequisites

- **Python 3.8+** (recommended to use a virtual environment)
- **pip** (Python package installer)

## Setup

```bash
# Clone the repository (if not already)
git clone https://github.com/esloch/osl-incubator-program.git
cd osl-incubator-program

# Create a virtual environment (optional but recommended)
python3 -m venv .venv
source .venv/bin/activate   # on Windows use `.venv\Scripts\activate`

# Install MkDocs and the Material theme
pip install mkdocs-material
```

## Build the site

```bash
# Generate the static site into the `site` directory
mkdocs build
```

The built site will be available in the `site/` folder.

## Serve locally (for preview)

```bash
# Start a local development server (auto‑reload on changes)
mkdocs serve
```

Open your browser at <http://127.0.0.1:8000> to view the documentation.

## Deploy to GitHub Pages

The repository is configured to publish the `site/` folder to **GitHub Pages**. Follow these steps to push a new version:

1. **Commit your changes**
   ```bash
   git add mkdocs.yml *.md
   git commit -m "Update documentation site"
   ```
2. **Push to the main branch**
   ```bash
   git push origin main
   ```
3. **GitHub Actions (optional)** – If a workflow is set up to build and deploy automatically, the site will be updated after the push. Otherwise, you can deploy manually:
   ```bash
   mkdocs gh-deploy --force
   ```
   This command builds the site and pushes the `site/` directory to the `gh-pages` branch, which GitHub Pages serves.

## Quick reference commands

| Action               | Command                              |
|----------------------|--------------------------------------|
| Install dependencies | `pip install mkdocs-material`        |
| Build site           | `mkdocs build`                        |
| Serve locally        | `mkdocs serve`                        |
| Deploy to GitHub Pages| `mkdocs gh-deploy --force` (or CI) |

---

*The documentation source files are located in the repository root (`mkdocs.yml`, `index.md`, `lifecycle.md`, `apply.md`, `criteria.md`, `ecosystems.md`). Any changes to these files will be reflected after rebuilding the site.*

