# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages repository containing various utility web applications and games built with HTML, CSS, and JavaScript. All applications are self-contained HTML files that can be opened directly in a browser.

## Project Structure

The repository is organized by application type:

- `gacha/` - Gacha simulation applications (React-based)
- `game/` - Various game implementations (roguelike, dungeon crawler)
- `poker/` - Poker-related games and applications
- `program/` - Programming utilities (compiler, 2D graphics)
- `timer/` - Timer applications with different themes

## Architecture

Each application is a standalone HTML file containing:
- Complete HTML structure
- Embedded CSS styling with animations and responsive design
- JavaScript functionality (may include external libraries via CDN)
- Self-contained with no build process required

### Key Technologies Used

- **Frontend**: Pure HTML/CSS/JavaScript, React (via CDN), Tailwind CSS (via CDN)
- **Styling**: Custom CSS with animations, gradients, and responsive design
- **External Libraries**: React 18, Babel standalone, Tailwind CSS
- **Deployment**: GitHub Pages (static hosting)

## Development Workflow

### Testing Applications
- Open HTML files directly in browser (no build step required)
- Test responsiveness across different screen sizes
- Verify animations and interactive elements work correctly

### Code Style
- Japanese comments and UI text are used throughout
- CSS animations are heavily utilized for visual effects
- Monospace fonts (Courier New) used for retro/terminal aesthetics
- Dark theme with neon colors (green, purple, cyan) for game interfaces

### Common Patterns
- Games use real-time rendering with requestAnimationFrame or setInterval
- State management through global JavaScript objects
- Event-driven architecture with keyboard and mouse input handlers
- Local storage may be used for persistence (check individual files)

## File Organization

Each major feature is self-contained in its own HTML file:
- No shared dependencies between applications
- Complete applications can be copied/moved independently
- All assets (styles, scripts) are embedded or loaded via CDN

## Deployment

This repository is designed for GitHub Pages deployment. All files are static and can be served directly without any build process.