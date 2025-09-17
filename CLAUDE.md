# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal CV repository for Karla Iveth Flores Molina containing:
- HTML-based CV template with embedded CSS styling
- Profile pictures in PNG format
- Clean, print-ready CV design optimized for A4 format

## Repository Structure

```
karla-cv/
├── cv-template/
│   └── karla_cv_template.html    # Main CV template with embedded styles
├── profile-picture/
│   ├── pic-01.png               # Profile image option 1
│   └── pic-02.png               # Profile image option 2
└── cv/                          # Directory for generated CV outputs
```

## Key Files

- **cv-template/karla_cv_template.html**: Complete standalone CV template (lines 1-353)
  - Self-contained HTML with embedded CSS (lines 7-214)
  - Professional layout with header, sidebar, and main content areas
  - Print-optimized styling with A4 dimensions (210mm × 297mm)
  - Responsive design with professional color scheme

## Development Notes

- This is a static HTML project with no build system or dependencies
- The CV template is designed for both web viewing and print output
- Profile images should be placed in the designated profile-picture directory
- The template includes placeholder text that can be customized for content updates

## Common Tasks

Since this is a simple static HTML project, common tasks include:
- Editing content in `cv-template/karla_cv_template.html`
- Replacing profile images in the `profile-picture/` directory
- Opening the HTML file directly in a browser for preview
- Printing or converting to PDF for distribution

## Architecture

The CV uses a two-column layout:
- **Header**: Full-width section with profile image and name/title
- **Sidebar**: Contact info, languages, and skills (280px fixed width)
- **Main Content**: Professional profile and experience (flexible width)

The design uses semantic HTML structure with CSS Grid and Flexbox for layout, ensuring clean print output and web compatibility.