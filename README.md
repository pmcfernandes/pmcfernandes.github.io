# pmcfernandes.github.io

This repository holds the source for my personal website, deployed on Netlify.

The site is a static frontend (HTML, CSS, JS) located in the repository root and the `assets/` folder.

## Repository structure

- `index.html` — main page
- `assets/` — static assets
  - `css/styles.min.css` — compiled CSS
  - `img/` — images used by the site
  - `js/script.min.js` — compiled JavaScript
- `robots.txt` — robots rules for crawlers

## About

This is my personal website for sharing projects, blog posts, and contact information. It's intentionally lightweight and optimized for performance using minified styles and scripts.

## Local preview

To preview the site locally you can open `index.html` in your browser directly. For a better local server experience (and to avoid issues with some browser features when opening files via the `file://` protocol), use a simple static server.

Node.js + http-server:

```powershell
npx http-server -p 8000
# Then open http://localhost:8000
```

## Editing and maintenance

- Keep source assets (images, unminified CSS/JS) in a clear place while editing, then update the minified files in `assets/` before committing.
- Optimize images for the web (WebP or compressed JPG/PNG) to keep page load fast.
- Use semantic HTML and accessible markup when adding content.

## License

See the `LICENSE` file in the repository for licensing details.

## Contact

If you want to reach me, use the contact details on the website or open an issue on this repository.

---

Last updated: 2025-11-09
