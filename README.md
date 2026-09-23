# Yilang Xu academic website

A lightweight static academic website inspired by the structure and minimalist visual language of Tong Bo's public academic homepage, optimized for very fast deployment on GitHub Pages.

## Fastest deployment

1. On GitHub, create a **public** repository named `yilangxu.github.io`.
2. Upload **all files and folders in this directory** to the repository root (do not upload the enclosing folder itself).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then **Save**.
6. Wait roughly 1–3 minutes and open `https://YOUR_GITHUB_USERNAME.github.io/`.

No Hugo, Node, Python, or GitHub Action is required.

## Optional terminal deployment

```bash
git init
git add .
git commit -m "Launch academic website"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
git push -u origin main
```

Then enable GitHub Pages from `main` / root as above.

## Important edits

- **Current status:** `index.html` currently says "Incoming Postdoctoral Fellow · Georgia Institute of Technology" and uses future tense. After the appointment begins, change this to "Postdoctoral Fellow · Georgia Institute of Technology" and update the About sentence to present tense.
- **Email:** the Email link opens a message to `yilangxu@outlook.com`.
- **Photo and research figures:** the supplied avatar and three research figures are stored locally in `assets/`, so the site does not depend on external image links.
- **CV:** replace `assets/CV-Yilang_Xu.pdf` whenever you update the PDF; no HTML edit is needed.
- **Custom domain:** if you later buy a domain, GitHub Pages can attach it under Settings → Pages → Custom domain.

## Structure

- `index.html` — homepage (About, Research, Featured Publications)
- `research.html` — research projects
- `publications.html` — full publication list
- `cv.html` — embedded PDF CV with open and download links
- `publications.bib` — BibTeX
- `assets/style.css` — all visual styling
- `assets/favicon.svg` — favicon
- `assets/avatar.jpg` — profile photo
- `assets/research-*.jpg/png` — research project images
- `assets/CV-Yilang_Xu.pdf` — downloadable CV

## Data sources used to populate the first version

Public ORCID/Scholar identifiers supplied by Yilang Xu, plus public institutional/publisher records from Johns Hopkins, MIT-WHOI, AMS, AGU/Wiley, ESS Open Archive, and ResearchGate.
