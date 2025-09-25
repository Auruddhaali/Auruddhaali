# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Common Commands
This is a static HTML/CSS website with no build process, tests, or linting configured.

- To preview changes: Open `auro-profile.html` in a web browser.
- For live reloading (if Node.js is available): Run `npx live-server` in the project directory.

## Code Architecture
This repository contains a simple single-page personal portfolio website.

- **Entry Point**: `auro-profile.html` - The main HTML file with navigation bar, profile section (bio and image), contact information (phone, emails, social links), GitHub profile and repositories links, and footer.
- **Styling**: `auro.css` - Defines base styles, liquid glass effects (using backdrop-filter and gradients), responsive grid layouts for contacts and GitHub links, hover animations, and color scheme with green gradients (#c7e77c to #98fb98).
- **Assets**: `images/` directory - Contains profile and other images (e.g., `Auro3 fixed.jpg`, `auro-picture.jpg`).
- **Documentation**: `README.md` - Contains a basic HTML snippet (likely an earlier version of the profile page).

The site features a modern design with glassmorphism effects, centered on presenting personal information and social/GitHub links. No JavaScript or backend components.