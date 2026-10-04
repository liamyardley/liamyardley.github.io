# liamyardley.github.io

The source of my personal site: **https://liamyardley.github.io/**

It is built with Jekyll, which GitHub Pages runs automatically, so there is nothing to install.

## Everyday changes (all on github.com, no software needed)

| I want to... | Edit this |
|---|---|
| Write a blog post | Add a file to `_posts/` (see [POST-TEMPLATE.md](POST-TEMPLATE.md)) |
| Add or change a project card | `_data/projects.yml` (copy an existing block) |
| Change the introduction on the home page | `index.html`, the `hero-lede` and `hero-sub` lines |
| Change the About page | `about.md` |
| Add LinkedIn or email to the footer | `_config.yml`, the `linkedin` and `email` lines |
| Add a picture | Upload it to `assets/img/` |
| Change the colour theme | `_config.yml`, the `colour_theme` line: `pastel`, `mist`, `notebook` or `nebula` |

To edit a file on github.com: open it, click the pencil icon, make the change, then click **Commit changes**. The site updates in a minute or two.

## How the projects fit in

Each project lives in its own repository with GitHub Pages switched on, so it appears under this site's address automatically, for example
https://liamyardley.github.io/The-Calculus-Chronicles/. This site only links to them.

## Files

- `_config.yml`: site title, description and contact links
- `_data/projects.yml`: the project cards
- `_posts/`: blog posts, one Markdown file each
- `_layouts/`, `_includes/`: page templates
- `assets/css/base.css`: the layout. `assets/css/theme-*.css`: the colour themes (pastel, mist, notebook, nebula)
- `index.html`, `writing.html`, `about.md`, `404.html`: the pages

Content © Liam Yardley. Projects carry their own licences.
