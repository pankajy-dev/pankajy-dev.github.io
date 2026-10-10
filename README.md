# Pankaj Yadav Portfolio

This repository contains the source for my personal portfolio website hosted on GitHub Pages.

## About

The site showcases my software engineering experience, professional background, projects, skills, and contact information. It is built using static HTML, CSS, and JavaScript with an SCSS build pipeline for styling.

## Live site

- Website: https://pankajy.com/
- GitHub Pages repository: https://github.com/pankajy-dev/pankajy-dev.github.io

## Tech stack

- HTML5
- CSS3
- JavaScript
- SCSS
- Node.js / npm

## Project structure

- `index.html` — main portfolio page
- `css/` — generated site styles
- `src/scss/` — SCSS source files
- `js/` — front-end scripts
- `images/` — images and assets
- `libs/` — third-party libraries
- `package.json` — build scripts and dependencies

## Local setup

1. Clone the repository:
   ```bash
   git clone https://github.com/pankajy-dev/pankajy-dev.github.io.git
   cd pankajy-dev.github.io
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the stylesheet:
   ```bash
   npm run build:css
   ```

4. Start a local preview server:
   ```bash
   python3 -m http.server 8000
   ```

   Then open `http://localhost:8000` in your browser.

## Development scripts

- `npm run build:css` — compile SCSS to CSS
- `npm run watch:css` — watch SCSS files and rebuild automatically
- `npm run start` — run the CSS watch process

## Deployment

This project is configured for GitHub Pages hosting. The generated site is served from the repository root, so updates to the `main` branch are published automatically through GitHub Pages.

## License

This project is licensed under the MIT License. See `LICENSE.md` for details.

## Contact

- LinkedIn: https://www.linkedin.com/in/pankajyadav84/
- GitHub: https://github.com/pankajy-dev
- Email: available on the portfolio site
