# Dragonfly Tattoo Co. Website

A dark, editorial, responsive static website for Dragonfly Tattoo Co. in Adrian, Michigan.

## Stack
- HTML5
- CSS3
- Vanilla JavaScript
- No build step
- No external framework required

## Project structure

```text
dragonfly-tattoo-co/
├── index.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── .nojekyll
├── .gitignore
├── LICENSE
├── README.md
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── images/
└── .github/workflows/pages.yml
```

## GitHub Pages

GitHub Pages can publish static HTML/CSS/JS directly from a repository. This project includes a GitHub Actions workflow so pushes to `main` deploy the site.

1. Create a GitHub repository, for example `dragonfly-tattoo-co`.
2. Upload all files in this folder.
3. Commit and push to `main`.
4. In GitHub: **Settings → Pages → Source: GitHub Actions**.
5. Wait for the workflow to finish, then open the Pages URL.

## Customize
- Replace gallery placeholders in `index.html` with real tattoo photos.
- Put images in `assets/images/`.
- Update the Instagram and booking links if the shop provides a preferred booking system.
- Add a `CNAME` file if using a custom domain.

## Important
This is a static front-end package. A real appointment form needs a form/booking provider or backend service.
