# Aruna's Academy — R Programming Interactive Notes

An interactive, single-page course site covering all 9 R Programming modules — built for GitHub Pages.

## What's inside
- `index.html` — the entire site (HTML + CSS + JS, no build step needed)
- `logo_small.png` — Aruna's Academy logo, used in the header, hero, and footer

## Features
- 9 modules, 27 topics, 27 case studies (easy / moderate / challenging)
- Light & dark mode toggle (remembers your choice, also respects system preference)
- Syntax-highlighted R code blocks with one-click "Copy"
- Per-topic checkboxes — track what you've learned, saved automatically in your browser
- Sidebar course map with live progress rings per module + overall progress in the top bar
- Smooth, Apple-style scroll reveals and transitions
- Fully responsive (sidebar collapses into a slide-out menu on mobile)

## How to host on GitHub Pages
1. Create a new GitHub repository (e.g. `r-programming-notes`).
2. Upload both `index.html` and `logo_small.png` to the **root** of the repository (keep them in the same folder — the page loads the logo as `logo_small.png`).
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, choose the `main` branch and `/ (root)` folder, then **Save**.
5. Wait a minute, then visit the URL GitHub gives you (something like `https://yourusername.github.io/r-programming-notes/`).

That's it — no build tools, frameworks, or dependencies required.

## Customizing
- All course content (topics, code, output, case studies) lives in the `DATA` array near the top of the `<script>` tag in `index.html` — edit it directly to add/change modules.
- Colors and fonts are controlled by CSS variables at the top of the `<style>` tag (`:root` for light mode, `[data-theme="dark"]` for dark mode).
