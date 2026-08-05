alvaroribas.com
===============

Personal website. A small Jekyll site: content in Markdown/HTML with one shared
layout, no plugins. GitHub Pages builds it automatically on push — nothing to
install to publish.

Structure
---------
    _config.yml            Site configuration
    _layouts/default.html  Shared page shell (head, sidebar, navigation)
    index.md               Home / about  (Markdown)
    research.html          Research overview
    publications.html      Publication list
    cv.html                Full CV (+ link to the PDF)
    css/style.css          All styling
    images/                Photo, science figures, favicon
    documents/             CV PDF
    CNAME                  Custom domain (alvaroribas.com)

Editing
-------
The sidebar, `<head>`, and navigation live once in `_layouts/default.html`, so
each page only holds its own content. Every page starts with a front-matter
block that sets its title and marks the active nav item:

    ---
    layout: default
    title: "Research — Álvaro Ribas"
    description: "..."
    nav: research
    ---

- Prose pages are Markdown (e.g. `index.md`): edit the text directly, links as
  `[text](url)`. Structured pages (publications, cv) are HTML.
- New paper: copy an existing `<li class="pub">…</li>` block in
  `publications.html`. ADS links use `https://ui.adsabs.harvard.edu/abs/<BIBCODE>/abstract`.
- Colours and fonts are at the top of `css/style.css` (the `:root` block).

Local preview (optional)
------------------------
If you have a working Jekyll install: `jekyll serve` → http://localhost:4000
Otherwise just push — GitHub Pages builds the site.

Deploying (GitHub Pages)
------------------------
This folder is the `alvaroribas.github.io` repository; GitHub Pages serves the
`master` branch and runs Jekyll automatically:

    git add -A
    git commit -m "..."
    git push

The `CNAME` file keeps the alvaroribas.com domain pointed at the site.
