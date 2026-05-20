# Project Overview

Personal blog built with Hugo, Markdown, and GitHub Pages. Source content lives
under `content/`, and Hugo generates the static site into `public/`.

# Setup

- Install Hugo Extended and Git.
- The current theme is `ananke`, loaded from `../themes/ananke`.

# Common Commands

```bash
hugo server -D
hugo --minify
hugo new content posts/my-post.md
```

# Validation

- Run `hugo --minify` before publishing configuration, theme, or content changes.
- Use `hugo server -D` for local preview at `http://localhost:1313/`.

# Coding Conventions

- Write posts in Markdown under `content/posts/`.
- Keep generated output such as `public/` out of source control.
- Prefer simple Hugo configuration in `hugo.toml` before adding custom layouts.
