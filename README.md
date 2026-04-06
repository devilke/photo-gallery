# Photo Gallery

A beautiful photo gallery website built with Hugo.

## Quick Start

### Local Development

```bash
hugo server -D
```

Then visit http://localhost:1313

### Adding Photos

1. Create a new album folder in `content/album/`
2. Add your photos to the folder
3. Create an `index.md` file with metadata:

```markdown
---
title: "Album Name"
date: 2026-04-06
---
```

### Building for Production

```bash
hugo
```

This generates the static site in `public/` directory.

### Deployment

#### GitHub Pages
Push to GitHub and enable Pages in repository settings.

#### Netlify/Vercel
Connect your repo and deploy automatically on every push.

## Configuration

Edit `hugo.toml` to customize:
- Site title
- Colors/theme
- Author info
- Base URL

## Theme

Using [hugo-theme-gallery](https://github.com/nicokaiser/hugo-theme-gallery) - optimized for photo galleries with responsive images and EXIF support.
