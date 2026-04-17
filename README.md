# Personal Landing Page

This repository contains the Hugo site for [aidanmaurinjones.com](https://aidanmaurinjones.com).

## Overview

The site is intentionally small:

- a custom landing page
- a styled contact page
- a custom theme component in `themes/aidan-landing-theme`

## Project Structure

- `content/` — page content
- `static/` — static assets such as favicons
- `themes/aidan-landing-theme/` — custom theme layouts, styles, and shortcodes
- `archetypes/` — Hugo content templates
- `hugo.toml` — site configuration

## Local Development

Requirements:

- Hugo Extended

Run the local dev server:

```bash
hugo server
```

Build the site:

```bash
hugo
```

Clean build output and rebuild:

```bash
hugo --cleanDestinationDir
```

## Notes

- The generated site output is written to `public/` when you run `hugo`.
- Hugo may also regenerate `resources/` for asset processing caches.
- The homepage and contact page styling live in `themes/aidan-landing-theme/assets/scss/home-refresh.scss`.
