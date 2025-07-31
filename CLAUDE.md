# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

AlpineJS Starter is a zero-build static site starter designed for rapid prototyping with agentic coding tools. It uses vendored Alpine.js v3.x and Tailwind CSS v4 (browser version) with no external dependencies or build process.

## Commands

No build commands needed. Development workflow:
1. Create/edit `index.html` (or any HTML file)
2. Open directly in browser or run local HTTP server: `python -m http.server 8000` or `npx serve`
3. Deploy to GitHub Pages from main branch root folder

## Architecture

### File Structure
- **elements.html** - Comprehensive demo of all Alpine.js patterns and Tailwind styling
- **alpine.js** - Alpine.js v3.x framework (vendored)
- **tailwind.js** - Tailwind CSS v4 browser version (vendored)
- **index.html** - Create this as your main page

### Alpine.js Patterns Used
All components follow these conventions:
- Inline `x-data` declarations on container elements
- Event handlers use `@click` shorthand syntax
- State management within component scope
- No external JavaScript files or script tags needed

### Component Examples in elements.html
- **Counter**: `x-data="{ count: 0 }"` with increment/decrement
- **Forms**: `x-model` binding for all input types
- **Lists**: `x-for` with filtering using computed properties
- **UI Components**: Dropdowns, modals, tabs using `x-show` and `@click.outside`
- **Shopping Cart**: Computed totals using Alpine's reactivity

### Styling Approach
- Tailwind utility classes only (no custom CSS)
- Responsive design with Tailwind breakpoints
- Consistent component styling: `bg-white rounded-lg shadow-md p-6`

### Development Guidelines
- Start from `elements.html` examples when building new components
- Keep all logic within Alpine.js directives (no separate JS files)
- Use Tailwind's utility classes for all styling
- Components should be self-contained and reusable