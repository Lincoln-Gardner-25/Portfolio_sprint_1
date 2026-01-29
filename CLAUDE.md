# CLAUDE.md - Project Documentation

This file documents the development history and context for Claude Code to reference when working on this project.

## Project Overview

**Product Management Portfolio** - A Quarto-based personal portfolio website for Lincoln Gardner showcasing product management projects and professional experience.

## Technology Stack

- **Framework**: Quarto (website project type)
- **Styling**: Custom CSS with Bootstrap theme (cosmo)
- **Icons**: Font Awesome 6.4.0
- **Deployment**: GitHub Pages

## Color Palette

The website uses a warm, creamy color scheme:

- **Cream** (`#FDF6E3`): Main background color
- **Olive Green** (`#5C6B4A`): Header/navbar, headings, primary accent
- **Olive Green Dark** (`#4A5A3A`): Hover states, emphasis
- **Tan** (`#C9A66B`): Borders, accents, decorative elements
- **Tan Light** (`#D4B88C`): Hover states on dark backgrounds
- **Ethereal** (`#F0EDE5`): Card backgrounds, subtle gradients

## File Structure

```
product-management-portfolio/
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Homepage
├── about.qmd            # About page
├── styles.css           # Custom styles
├── images/
│   └── profile.jpg      # Profile photo
├── projects/            # Individual project pages
│   ├── project-1.qmd
│   ├── project-2.qmd
│   └── ...
├── _site/               # Generated output (do not edit)
├── .github/workflows/   # GitHub Actions for deployment
└── CLAUDE.md            # This file
```

## Development Commands

Build the site locally:
```bash
/Applications/RStudio.app/Contents/Resources/app/quarto/bin/quarto render
```

Preview locally:
```bash
open _site/index.html
```

## Update History

### 2025-01-29
- Updated LinkedIn link to: https://www.linkedin.com/in/lincoln-gardner03
- Removed GitHub icon/link from homepage
- Added profile photo (images/profile.jpg)
- Implemented new color scheme (cream, olive green, tan, ethereal)
- Redesigned Featured Projects section with centered layout
- Created app-icon button for True Rate with blue/yellow "TR" letters
- Added bullet points describing True Rate app functionality
- Created CLAUDE.md for project documentation
- Changed "About" to "About Me" in navigation
- Changed "Home" to "Problems I'm Exploring" with new page
- Added tree favicon (images/tree-favicon.svg)
- Created problems.qmd page with:
  - Hero image of mountain climber
  - 4 expandable problem cards with hover effects
  - Background images that appear on hover (hazed/faded)
  - Problems: Macro tracking, Freelancer pricing, Self-awareness journaling, Communication AI

## Featured Projects

### True Rate
- **URL**: https://true-freelance-ylyl.vercel.app/
- **Description**: Freelancer pricing and project tracking tool
- **Features**:
  - Track and set profitable price tags for projects
  - Strategic insights for pricing strategies
  - Ongoing development with updates coming soon

## Notes for Future Development

- New projects should follow the app-icon button pattern established for True Rate
- Maintain the warm color palette (cream/olive/tan) for consistency
- Keep Featured Projects section centered
- Profile photo is at `images/profile.jpg`
