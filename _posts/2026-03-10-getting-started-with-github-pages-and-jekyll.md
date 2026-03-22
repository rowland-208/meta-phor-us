---
layout: post
title: "Getting Started with GitHub Pages and Jekyll"
date: 2026-03-10 10:00:00 -0000
categories: tutorial jekyll
---

[GitHub Pages](https://pages.github.com/) is a free hosting service that turns a GitHub repository into a live website. Combined with [Jekyll](https://jekyllrb.com/), it becomes a powerful platform for a Markdown-based blog — no database, no server configuration required.

## How It Works

GitHub Pages looks for a `_config.yml` file at the root of your repository. If it finds one, it automatically builds your site using Jekyll and serves it at `https://<username>.github.io/<repo>`.

Posts live in the `_posts/` directory and follow a strict naming convention:

```
YYYY-MM-DD-title-of-your-post.md
```

Each post begins with **front matter** — a YAML block between `---` delimiters that tells Jekyll how to render the page:

```yaml
---
layout: post
title: "My Post Title"
date: 2026-03-10 10:00:00 -0000
categories: tutorial
---
```

## Creating Your First Post

1. Create a file in `_posts/` with the date-title format above.
2. Add front matter at the top.
3. Write your content in Markdown.
4. Commit and push — GitHub Pages builds and deploys automatically.

## Themes

Jekyll supports themes that control the look and feel of your site. This blog uses the [Minima](https://github.com/jekyll/minima) theme, which is clean, responsive, and the default for new Jekyll sites.

You can browse more themes at [jekyllthemes.org](http://jekyllthemes.org/) or build your own with custom layouts in a `_layouts/` directory.

Give it a try — it only takes a few minutes to get a blog up and running!
