# Frontend Mentor – Blog preview card

Pixel-close implementation of the **Blog preview card** using **semantic HTML** and **Tailwind CSS (CLI, v4)**. Mobile-first, accessible focus states, and an offset shadow to match the design.

## Overview

Users can:

- See **hover** and **focus** states on interactive elements
- View a clean, centered card layout on any screen size

## Screenshot

<!-- Replace with your own -->

![Screenshot](./screenshot.png)

## Links

- Solution URL: https://www.frontendmentor.io/solutions/REPLACE
- Live Site URL: https://comfy-mandazi-66d166.netlify.app

## Built with

- Semantic **HTML5**
- **Tailwind CSS v4 (CLI)**
- **Mobile-first** workflow
- **Flexbox** centering

## What I learned (highlights)

- Tailwind v4 tokens via `@theme` and using them with CSS vars:
  ```css
  /* src/styles/input.css */
  @theme {
    --color-yellow: hsl(47 88% 63%);
    --color-gray-950: hsl(0 0% 7%);
    --color-gray-500: hsl(0 0% 42%);
    --font-sans: "Figtree", sans-serif;
  }
  ```
  project/
  ├─ index.html
  ├─ src/styles/input.css
  ├─ dist/styles.css # generated (gitignored, dev)
  ├─ publish/ # manual deploy output (gitignored)
  └─ assets/images/
