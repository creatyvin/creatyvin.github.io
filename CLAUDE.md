# CLAUDE.md

This file provides guidance to Claude Code when working with this repository.

## Project Overview

Personal blog by Dmytro Grepan — thoughts, ideas, and projects. Built on Jekyll with GitHub Pages.

## Repository Structure

```
creatyvin.github.io/
├── _posts/                  # All blog posts
│   └── YYYY-MM-DD-title.md
├── _pages/
│   ├── about.md             # About page
│   └── tags.md              # Tags archive
├── _config.yml              # Jekyll configuration
├── _data/navigation.yml     # Site navigation
├── index.html               # Homepage (posts list)
├── Gemfile                  # Ruby dependencies
└── CLAUDE.md                # This file
```

## Commands

```bash
# Local development
bundle install
bundle exec jekyll serve --port 8004

# Site available at http://localhost:8004/
```

## Adding Content

### New blog post

Create file: `_posts/YYYY-MM-DD-title.md`

```yaml
---
title: "Post Title"
date: YYYY-MM-DD
tags: [thoughts, en]  # Include language tag: en, ru, zh
toc: true             # Optional: table of contents
---

Content here...
```

### Tag system

Use tags for filtering:
- `manifesto` — manifestos and core beliefs
- `thoughts` — general thoughts and ideas
- `projects` — project descriptions
- `journey` — personal journey updates
- `en` / `ru` / `zh` — language of the post

## Content Guidelines

- Preserve the author's voice and personal narrative style
- Posts use ISO date format: YYYY-MM-DD
- Include language tag in every post (en, ru, zh)
- Content over formatting — focus on substance

## Deployment

Push to `main` branch → GitHub Pages auto-deploys

Future URL: `https://creatyvin.github.io/`
