# WeeTools

**Tiny tools. Massive impact.**

WeeTools is a software company based in Tallinn, Estonia, building compact and powerful software solutions. This repository contains the official website and product showcase.

## Overview

This is the frontend repository for [weetools.net](https://weetools.net) - a modern, responsive marketing website featuring company services and product pages.

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - Lightweight interactivity
- **Google Fonts** - JetBrains Mono, Segoe UI

No build tools or npm dependencies required.

## Project Structure

```
wt-frontend/
├── index.html          # Main company website
├── terman.html         # TerMan product page
├── assets/
│   └── terman_image.png
└── README.md
```

## Features

### Main Website
- Responsive navigation with mobile hamburger menu
- Animated hero section with particle effects
- Services showcase (Software Development, Process Automation, Data Solutions, Telecommunication)
- Contact form
- SEO optimized with Open Graph and Schema.org markup

### TerMan Product Page
- macOS terminal organizer showcase
- Feature grid with Free/Pro tier indicators
- System requirements and download section
- Dark theme design

## Services

| Service | Description |
|---------|-------------|
| Software Development | Web apps, mobile apps, APIs, cloud solutions |
| Process Automation | Workflow automation, task scheduling, integrations |
| Data Solutions | Analytics, dashboards, ETL pipelines, visualization |
| Telecommunication | Voice calls, virtual numbers, SMS, VoIP |

## Products

### TerMan
A macOS terminal session organizer.

- **Version**: 1.0.4
- **Requirements**: macOS 12+, Apple Silicon or Intel, 50MB disk space
- **Features**: Multiple sessions, tags, themes, export, sync

## Local Development

No build process required. Simply open the HTML files in a browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then visit `http://localhost:8000`

## Deployment

Static files can be deployed to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any static file server

## Design System

### Colors
| Color | Hex |
|-------|-----|
| Primary Purple | `#7B2D8E` |
| Accent Pink | `#D14B8F` |
| Light Purple | `#9B4BA8` |
| Dark Purple | `#5A1F6A` |

### Typography
- **Primary**: Segoe UI
- **Monospace**: JetBrains Mono

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

- **Email**: info@weetools.net
- **Location**: Tallinn, Estonia
- **Hours**: Mon-Fri 9:00-18:00 EET
- **LinkedIn**: [WeeTools](https://linkedin.com/company/weetools)

## License

Copyright WeeTools OÜ. All rights reserved.
