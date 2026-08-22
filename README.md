
# Bosong Qi's Academic Homepage

This repository hosts the personal academic website of Bosong Qi, built with GitHub Pages and Markdown-based content management. It is used to present my profile, research interests, publications, awards, and academic achievements.

## Overview

The website is organized as follows:

- `contents/`: homepage content, publications, awards, and site configuration
- `static/`: CSS, JavaScript, images, and other static assets
- `index.html`: main page entry for GitHub Pages

## Personal information

I am currently a Ph.D. student in the iMAP Lab at Wuhan University, focusing on photogrammetry, robotic sensing, and 3D reconstruction. My research centers on sensor calibration, SLAM, and feed-forward 3D reconstruction.

## Main editable files

To update the site, the most commonly used files are:

1. `contents/config.yml` — page title, subtitle, copyright, and website metadata
2. `contents/home.md` — profile and introduction
3. `contents/publications.md` — publication list and research output
4. `contents/awards.md` — awards and honors
5. `static/assets/img/` — profile photo and background images

## Local preview

You can preview the site locally by opening the project in a browser or by serving the repository via a simple local web server.

```bash
git clone https://github.com/mepoisson/mepoisson.github.io.git
cd mepoisson.github.io
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Deployment

This repository is designed for GitHub Pages. After editing the content, commit and push to the repository:

```bash
git add .
git commit -m "Update homepage content"
git push
```

Then the site will be published at:

- `https://mepoisson.github.io`

## Notes

This site is a customized academic homepage for my own research and personal information. If you want to reuse the template for another academic profile, the structure and content files are easy to adapt with minimal changes.

## License

This project is based on an academic personal website template and is used for personal academic presentation. The site content is maintained by Bosong Qi and may be customized as needed.
# BosongQi
