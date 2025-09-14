# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the Roma project repository, which appears to be related to a social enterprise/mentoring initiative. Currently, the repository contains only presentation materials and documentation:

- `Mentoría Roma _ Empresa social.docx` - Social enterprise documentation
- `Presentacion ROMA_2025.pdf` - 2025 presentation
- `Presentación comercial _ Roma.pptx` - Commercial presentation
- `image001.png` - Supporting image

## Current State

This repository contains:
- Original presentation materials and documentation in root
- **roma-website/** - Astro-based static website implementation
- **content/** - Structured markdown content extracted from documents

## Technology Stack

### Website (roma-website/)
- **Framework**: Astro v5.13.7 - Static Site Generator
- **Styling**: Custom CSS with CSS Variables
- **Deployment**: Static files (can be deployed to Netlify, Vercel, etc.)

## Development Setup

### Website Development:
```bash
cd roma-website
npm install
npm run dev          # Start development server at http://localhost:4321
npm run build        # Build for production
npm run preview      # Preview production build
```

### Design System:
The website uses a custom design system based on Roma's brand colors:
- **Primary Orange**: #FF8C00 (energy, growth)
- **Primary Green**: #228B22 (sustainability, social impact)
- **Primary Black**: #1a1a1a (professionalism, trust)

## Architecture

### Website Structure:
- `src/layouts/Layout.astro` - Base HTML template
- `src/components/` - Reusable UI components (Header, Footer, Hero)
- `src/pages/` - Route-based pages
- `src/styles/global.css` - Design system and global styles
- `public/` - Static assets (logo, images)

### Content Organization:
- Extracted and structured content from original documents
- Modular approach for easy content updates
- SEO-optimized with meta tags and structured data

### Key Components:
- **Header**: Responsive navigation with mobile menu
- **Hero**: Landing section with value proposition and stats
- **Footer**: Site links, contact info, and social impact tagline
- **Services**: Modular service cards with icons and descriptions

## Content Structure

The `content/` directory contains structured markdown files:
- `empresa.md` - Company information, values, purpose
- `servicios.md` - Service offerings and methodology
- `estrategia.md` - Growth strategy and business pillars
- `pitch.md` - Commercial presentation content
- `design-system.md` - Visual identity guidelines
- `sitemap.md` - Website architecture and page structure

## Notes for Future Development

- The repository is currently empty of source code
- Ruby 3.0.6 appears to be configured in the environment but not installed
- Consider establishing a clear technology stack before beginning development
- Add appropriate `.gitignore` file when technology stack is chosen