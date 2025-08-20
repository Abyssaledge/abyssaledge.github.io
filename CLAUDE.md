# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is Lue Fan's personal academic homepage - a static website built using the Cayman GitHub Pages theme. The site showcases academic research, publications, and contact information.

## Development Commands

### Build and Development
- `grunt` or `grunt default` - Start development server with live reload and watch for file changes
- `npm install` - Install all dependencies

### Manual Build Tasks
- `grunt sass` - Compile SCSS to CSS
- `grunt postcss` - Apply autoprefixer to CSS
- `grunt watch` - Watch for file changes without browser sync

## Project Structure

- `index.html` - Main homepage content with academic profile and research papers
- `scss/cayman.scss` - Source SCSS file for styling
- `css/cayman.css` - Compiled CSS output
- `images/` - Contains research paper teaser images and academic content
- `Gruntfile.js` - Build configuration using Grunt task runner
- `package.json` - Node.js dependencies and project metadata

## Key Technologies

- **Build System**: Grunt with live reload via BrowserSync
- **Styling**: SCSS compiled to CSS with autoprefixer
- **Theme**: Based on Cayman GitHub Pages theme
- **Static Site**: No backend, pure HTML/CSS/JS

## Development Workflow

1. Run `npm install` to install dependencies
2. Use `grunt` to start development server with live reload at localhost
3. Edit SCSS files in `scss/` directory - changes auto-compile and reload
4. Modify `index.html` for content changes - browser auto-refreshes
5. Add new images to `images/` directory as needed

## File Modification Guidelines

- Academic content updates should be made in `index.html`
- Styling changes go in `scss/cayman.scss`
- Never directly edit `css/cayman.css` - it's auto-generated
- Image assets should maintain consistent naming pattern matching paper references