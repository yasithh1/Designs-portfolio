# Yasith Pasindu — Design & Motion Portfolio

**Ideas, made visual.** A personal portfolio for graphic design, visual identity, and motion work.

[![Visit portfolio](https://img.shields.io/badge/Visit-Portfolio-d6ff45?style=for-the-badge&labelColor=171817)](https://yasithh1.github.io/Designs-portfolio/)
[![Deploy with GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?style=for-the-badge&logo=github)](https://github.com/yasithh1/Designs-portfolio/actions/workflows/pages.yml)

## About

A responsive, motion-led portfolio presenting Yasith’s selected graphic design and video projects. The site is built with plain HTML, CSS, and JavaScript, so it loads directly on GitHub Pages without a build step or package installation.

## What’s inside

- Animated hero section with a rotating 3D-style monogram
- Filterable gallery for video and graphic design projects
- Project detail panel with embedded Google Drive previews and source links
- About section with portrait and creative software
- Contact email and Instagram, YouTube, Facebook, and TikTok links
- Responsive layouts for desktop and mobile

## Creative tools

After Effects · Premiere Pro · CapCut · Photoshop

## Run locally

Clone the repository, open the project folder, and start a small local web server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). You can also open `index.html` directly in a browser.

## Update the portfolio

- **Profile photo:** replace `assets/profile.jpg` with the updated portrait, keeping the same filename.
- **Projects:** edit the `projects` array near the bottom of `index.html` to update titles, descriptions, categories, and Google Drive file IDs.
- **Contact and social links:** update the links in the contact section of `index.html`.
- **Publish changes:** commit and push to `main`; GitHub Actions will deploy the updated site.

Google Drive projects need to be shared so visitors with the link can view them. Drive video previews may not play until Google finishes processing the uploaded video; the detail panel also links to the original Drive file.

## Deployment

The included workflow at `.github/workflows/pages.yml` publishes the site to GitHub Pages whenever `main` or `master` is updated. GitHub Pages must use **GitHub Actions** as its build and deployment source.

**Live site:** [yasithh1.github.io/Designs-portfolio](https://yasithh1.github.io/Designs-portfolio/)

## Repository layout

```text
.
├── .github/workflows/pages.yml  # GitHub Pages deployment workflow
├── assets/headphones-ad.jpg     # Featured headphone poster
├── assets/profile.jpg           # Portfolio portrait
├── index.html                   # Site markup, styles, and interactions
└── README.md
```

## Contact

- Email: [yasithpasindu7@gmail.com](mailto:yasithpasindu7@gmail.com)
- Instagram: [@yasithppasindu](https://www.instagram.com/yasithppasindu/?hl=en)
- YouTube: [@yasithpasindu](https://www.youtube.com/@yasithpasindu)
- Facebook: [Yasith Pasindu](https://www.facebook.com/profile.php?id=100084248100649)
- TikTok: [@yasithppasindu](https://www.tiktok.com/@yasithppasindu)
