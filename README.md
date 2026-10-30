# Teagan McGinn | Marketing Portfolio

Personal portfolio website for Teagan McGinn, Marketing Professional (Digital Marketing and Brand Strategy).

A single static page with no build step: plain HTML, CSS and JavaScript, plus the images and videos in `media/`.

## Contents

```
index.html   The whole site (markup, styles and scripts)
media/       Photos, reels, logos and video clips used on the page
```

## Preview locally

Open `index.html` in a browser. Videos autoplay most reliably when the page is served, so for a full preview run:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository (files at the top level of the repo).
2. In the repo, go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

To use a custom domain, add it under **Settings > Pages > Custom domain** and point the domain's DNS to GitHub Pages.

## Editing

- Text, links and contact details are in `index.html`.
- To swap a photo or video, replace the file in `media/` with one of the same name.
- Fonts load from Google Fonts (Plus Jakarta Sans and Playfair Display).
