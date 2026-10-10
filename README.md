# Pankaj Yadav | Portfolio

Personal portfolio website for Pankaj Yadav, built as a static GitHub Pages site.

## Overview

This repository hosts a modern portfolio website that highlights:

- software engineering experience
- core technical skills and certifications
- professional background and career progression
- selected projects and case studies
- contact information and resume link

The site is designed as a lightweight static page with custom HTML, CSS, and JavaScript, with SCSS used for styling and a simple build pipeline.

## Live Site

- Website: https://pankajy.com/
- GitHub Pages: https://github.com/pankajy-dev/pankajy-dev.github.io

## Tech Stack

- HTML5
- CSS3
- JavaScript
- SCSS
- Node.js and npm

## Project Structure

- `index.html` — main portfolio page
- `css/` — compiled CSS output
- `src/scss/` — source SCSS files
- `js/` — frontend scripts
- `images/` — images and media assets
- `libs/` — third-party libraries
- `package.json` — project scripts and dependencies
- `CNAME` — custom domain configuration
- `LICENSE.md` — license information

## Local Setup

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

4. Start a local web server:

   ```bash
   python3 -m http.server 8000
   ```

5. Open the site in a browser:

   ```text
   http://localhost:8000
   ```

## Development Scripts

```bash
npm run build:css
npm run watch:css
npm run start
```

- `build:css` compiles SCSS into the final CSS file.
- `watch:css` watches SCSS files for changes and rebuilds automatically.
- `start` runs the watch process for local development.

## Deployment

This project is configured for GitHub Pages. The repository is published from the `main` branch, making it easy to update and deploy changes directly to the live portfolio site.

## Contact

- GitHub: https://github.com/pankajy-dev
- LinkedIn: https://www.linkedin.com/in/pankajyadav84/
- Resume: available on the portfolio site

## License

This project is licensed under the MIT License. See `LICENSE.md` for details.
