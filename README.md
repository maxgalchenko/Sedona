# Sedona

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Gulp](https://img.shields.io/badge/Gulp-CF4647?style=for-the-badge&logo=gulp&logoColor=white)
![Babel](https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=000)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=000)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

</div>

## Overview

Responsive static website for the “Sedona” travel theme. Built with a lightweight Gulp pipeline that compiles Sass, bundles/transpiles JS, optimizes images (including WebP), and outputs production files to `docs/` for GitHub Pages hosting.

## Key Features

- Separate mobile/tablet/desktop styles with minified CSS bundles
- JS transpilation and bundling (Babel + Webpack) with minified output
- Image optimization and WebP generation for smaller payloads

## Tech Stack

HTML5, Sass, Gulp 4, Babel 7, Webpack 4, PostCSS (autoprefixer, cssnano), Node.js 18

## Architecture

Gulp tasks handle Sass → CSS, Babel + Webpack for JS, HTML minification, and image optimization (JPEG/PNG/WebP). Source files live in `src/`; production artifacts are written to `docs/` (suitable for GitHub Pages).

## Performance & Accessibility

Minified CSS/JS, compressed images with WebP outputs, and straightforward semantic HTML for accessible, responsive layouts.

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/Sedona.git
cd Sedona
npm install
```

## Quick Start

```bash
npx gulp dev
# Production
npx gulp build
# Open ./docs/index.html
```

Open http://localhost:3000

## Available Scripts

- `npm run test` – placeholder test script (prints a message and exits)
- `npx gulp dev` – start local dev server with live reload (BrowserSync)
- `npx gulp build` – build optimized assets into `docs/`

## Screenshots

![Home](./src/img/screenshots/homepage-desktop.png)
![Form](./src/img/screenshots/form-page-desktop.png)
![Photos](./src/img/screenshots/photo-page-desktop.png)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
