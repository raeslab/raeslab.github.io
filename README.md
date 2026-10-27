[![pages-build-deployment](https://github.com/raeslab/raeslab.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/raeslab/raeslab.github.io/actions/workflows/pages/pages-build-deployment)

# code.raeslab.org

Placeholder landing page for **code.raeslab.org**: an overview of the Raes Lab companion websites and a link to
<https://github.com/raeslab>.

* `index.html` – single self-contained page (inline CSS, no external scripts, fonts or images; light/dark mode).
* `CNAME` – custom domain for GitHub Pages.

## Publishing with GitHub Pages

1. Create a repository (e.g. `raeslab/code.raeslab.org`) and push these files to `main` (repository root).
2. Settings → Pages → *Deploy from a branch* → `main` / `/ (root)`. The `CNAME` file sets the custom domain.
3. At the DNS provider of `raeslab.org`, add a CNAME record: `code` → `raeslab.github.io`.
4. Once the DNS check passes in Settings → Pages, tick *Enforce HTTPS*.

## Adding a project

Copy one `<article class="card">…</article>` block in `index.html`, update the title, authors, description and the
Website / GitHub / Paper links, and place it under the matching group heading.
