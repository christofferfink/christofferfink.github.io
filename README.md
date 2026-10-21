# christofferfink.github.io

My personal website: **[christofferfink.github.io](https://christofferfink.github.io)**

I'm Christoffer Fink, a Software Technology student at DTU and DevOps intern at Bang & Olufsen. The site has my experience, projects and skills, and how to get in touch.

## How it's built

Plain HTML, CSS and a little JavaScript, with no frameworks or build step.

- Light and dark mode, following your system setting with a toggle in the header
- Works on phones and desktops
- Deployed to GitHub Pages by a GitHub Actions workflow on every push to `main`

```
index.html          The page
404.html            Shown for missing URLs
css/style.css       All styling
js/theme.js         Applies light/dark mode before the page loads
js/main.js          Theme toggle and mobile menu
assets/             Images and favicon
.github/workflows/  Deploy workflow
```

## Running it locally

```sh
git clone https://github.com/christofferfink/christofferfink.github.io.git
cd christofferfink.github.io
python -m http.server 8000
```

Then open http://localhost:8000.

## Contact

- Email: christo.fink.1@proton.me
- LinkedIn: [Christoffer Fink](https://www.linkedin.com/in/christoffer-f-76949721b)
