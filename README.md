# Davidson AI Website

Static GitHub Pages landing page for **Davidson AI**, an early-stage health technology project developing an AI-powered Clinical Decision Support System and medical education platform.

## Project Overview

Davidson AI combines:

- Retrieval-Augmented Generation (RAG)
- Structured medical knowledge
- Large Language Models
- Evidence-based medicine
- Transparent citations
- Clinical reasoning support
- Medical education workflows

The project is currently in prototype/MVP development. This website is intended for startup cloud applications, potential collaborators, recruiters, and future investor conversations.

## Local Development

No build step is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/refat247/davidson-ai-website.git
   cd davidson-ai-website
   ```

2. Open `index.html` directly in a browser, or run a simple local server:

   ```bash
   python3 -m http.server 8000
   ```

3. Visit:

   ```text
   http://localhost:8000
   ```

## GitHub Pages Deployment

This repository is designed to work immediately with GitHub Pages.

1. Go to the repository on GitHub.
2. Open **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

The live site will be available at:

```text
https://refat247.github.io/davidson-ai-website/
```

## How to Customize

- Edit page content in `index.html`.
- Edit visual styling in `style.css`.
- Edit navigation and animation behavior in `script.js`.
- Update search metadata in the `<head>` section of `index.html`.
- Update `sitemap.xml` if the final GitHub username, repository name, or domain changes.

## Truthfulness Notice

The website does not claim funding, customers, FDA approval, regulatory approval, clinical deployment, or commercial availability. It clearly presents Davidson AI as an early-stage prototype/MVP project.

## License

Released under the MIT License. See `LICENSE` for details.
