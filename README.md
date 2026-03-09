# Sebify

A static marketing website project inspired by the Moshify layout, built with HTML, CSS, and a small amount of vanilla JavaScript.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Parcel (dependency installed)

## Project Structure

- `index.html`: main page
- `playground.html`: alternate/dev playground page
- `css/styles.css`: main styling
- `css/normalize.css`: CSS reset/normalization
- `js/main.js`: collapsible navigation toggle behavior
- `componants/`: reusable HTML component snippets
- `images/`: project images and SVG sprites
- `dist/`: build output (generated)

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run a local dev server

Since there is no `start` script yet, use Parcel directly:

```bash
npx parcel index.html
```

Parcel will print a local URL (usually `http://localhost:1234`).

### 3. Build for production

```bash
npx parcel build index.html
```

The production build is generated in `dist/`.

## Notes

- `node_modules/`, `.parcel-cache/`, and `dist/` are ignored in Git.
- The current `npm test` script is a placeholder and does not run tests.

## Repository

GitHub: https://github.com/seba11lando/Sebify
