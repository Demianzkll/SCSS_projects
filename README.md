# SCSS Projects

A collection of projects demonstrating **SCSS** (Sass) capabilities — variables, mixins, nesting, and partials.

## Projects

### SCSS — Navigation Menu

A styled navigation menu built with SCSS, featuring:
- Custom **variables** for colors
- A reusable **flex mixin** (`@mixin flex`)
- Nested selectors and hover effects

### SCSS_2 — Contact Page Layout

A more complete page layout (header + contact section) with:
- **Partial files** (`_variables`, `_header`, `_mainsection`, `_normalize`)
- Navigation bar with logo and call-to-action button
- Contact information section with SVG icons
- Language switcher (UA)

## Tech Stack

- **SCSS / Sass** — CSS preprocessor
- **HTML5** — page structure

## Project Structure

```
├── SCSS/
│   ├── _variables.scss    # color variables
│   ├── style.scss         # main stylesheet with mixins
│   └── index.html         # navigation menu page
│
└── SCSS_2/
    ├── _variables.scss    # color variables
    ├── _header.scss       # header styles
    ├── _mainsection.scss  # main section styles
    ├── _normalize.scss    # CSS reset
    ├── style.scss         # main entry point
    ├── img/               # logo & images
    └── index.html         # contact page
```

## Compilation

Compile SCSS to CSS using any Sass compiler:

```bash
# Using sass CLI
sass style.scss css/style.min.css --style compressed

# Or watch for changes
sass --watch style.scss:css/style.min.css
```
