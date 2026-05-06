# invinciberry.github.io

Personal website for Zheming Zhang, hosted on GitHub Pages at [zhemingzhang.com](https://www.zhemingzhang.com).

Built with [Jekyll](https://jekyllrb.com) using the [no-style-please](https://github.com/riggraz/no-style-please) theme.

## Structure

| Path | Purpose |
|------|---------|
| `_config.yml` | Site settings (title, author, theme config) |
| `_data/menu.yml` | Homepage content — bio and links |
| `_posts/` | Blog posts (filename format: `YYYY-MM-DD-title.md`) |
| `index.md` | Homepage entry point (`layout: home`) |
| `archive.md` | Full post listing |
| `logo.png` | Site favicon |
| `CNAME` | Custom domain config |

## Making Changes

**Update bio or links** — edit [`_data/menu.yml`](_data/menu.yml)

**Add a blog post** — create a file in `_posts/` following the naming convention:
```
_posts/YYYY-MM-DD-post-title.md
```

With frontmatter:
```yaml
---
layout: post
title: Your Post Title
slug: your-post-slug
---
```

**Show recent posts on homepage** — uncomment the `post_list` block at the bottom of `_data/menu.yml`

## Deploying

Push to the `main` branch — GitHub Pages builds and deploys automatically.
