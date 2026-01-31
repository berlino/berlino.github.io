# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal academic portfolio website built with Jekyll using the al-folio theme. It deploys to GitHub Pages at https://berlino.github.io.

## Build and Development Commands

### Local Development (Ruby)
```bash
bundle install              # Install Ruby dependencies
bundle exec jekyll serve    # Start dev server at http://localhost:4000
bundle exec jekyll build    # Build site to _site/
```

### Docker Development
```bash
docker compose up                              # Full image at http://localhost:8080
docker compose -f docker-compose-slim.yml up   # Lightweight image
```

### Code Formatting (Required for CI)
```bash
npm install                 # Install Prettier and Liquid plugin
npx prettier --write .      # Format all files
npx prettier --check .      # Check formatting (used by CI)
```

## Project Structure

- `_config.yml` - Main site configuration (personal info, plugins, features)
- `_posts/` - Blog posts in `YYYY-MM-DD-title.md` format
- `_projects/` - Portfolio project pages
- `_bibliography/papers.bib` - Academic publications in BibTeX format
- `_pages/` - Static pages (about, publications, CV, etc.)
- `_news/` - Announcements displayed on homepage
- `_includes/` - Reusable Liquid template components
- `_layouts/` - Page layout templates
- `_sass/` - SCSS stylesheets
- `assets/` - Static files (images, PDFs, JSON data)
- `assets/json/resume.json` - CV/resume data in JSON Resume format

## Key Configuration

Site settings in `_config.yml`:
- Personal info: `first_name`, `last_name`, `email`, social links
- Scholar settings under `scholar:` for bibliography formatting
- Feature flags: `enable_math`, `enable_masonry`, `enable_medium_zoom`, etc.
- Blog settings: `blog_name`, `pagination`, `related_blog_posts`

## Content Workflows

**Blog post**: Create `_posts/YYYY-MM-DD-title.md` with YAML front matter
**Project**: Create `_projects/project-name.md`
**Publication**: Add BibTeX entry to `_bibliography/papers.bib`
**News item**: Create `_news/announcement.md`
**CV update**: Edit `assets/json/resume.json`

## CI/CD

Pushes to `master`/`main` trigger GitHub Actions workflow that:
1. Builds Jekyll site with `bundle exec jekyll build`
2. Runs PurgeCSS to remove unused styles
3. Deploys to `gh-pages` branch

PRs run Prettier formatting checks via `.github/workflows/prettier.yml`.
