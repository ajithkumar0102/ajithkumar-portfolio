# Ajith Kumar Puli — Portfolio

A static portfolio built with semantic HTML, CSS, and vanilla JavaScript. There is no build step or package dependency.

## Run locally

Open `index.html` in a browser, or start a local server from this folder:


Google Fonts (Montserrat and Instrument Serif) are loaded remotely. System-font fallbacks are defined for offline use.

## Project structure

```text
index.html       Page content and semantic structure
css/style.css    Design tokens, layout, components, responsive rules, and animations
js/main.js       Preloader, particle portrait, navigation, scroll effects, comparisons, and canvas animation
images/          Before-and-after examples for the underwater image project
```

## Content to customize

- **Hero portrait:** `HERO_PORTRAIT` at the top of `js/main.js` contains the embedded transparent PNG data URI. Replace it with another PNG data URI to change the particle portrait.
- **Underwater comparison:** replace the four images in `images/` while keeping their current filenames, or update the image paths in `index.html`.
- **Library preview:** the catalogue panel in `index.html` is an illustrative mockup, not a live application screenshot.
- **Project links and credentials:** review the links and profile details in `index.html` before publishing.

## Refactoring notes

- Kept the existing styling hooks and section IDs so the page layout and interactions remain consistent.
- Added an accessible label to the main navigation, explicit button types, and pressed-state announcements for the comparison tabs.
- Moved the contact introduction's inline styling into the stylesheet.
- Kept the site dependency-free and retained the embedded portrait and supplied project images.
