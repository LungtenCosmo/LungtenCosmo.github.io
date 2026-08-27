# Lungten Dorji — Portfolio Website

A lightweight static portfolio designed for GitHub Pages.

## Files
- `index.html` — website content
- `styles.css` — visual design and mobile layout
- `script.js` — navigation and subtle scroll animations
- `assets/` — place your portrait, project photos, CV and PDFs here

## Add your portrait
Save your photo as:

`assets/profile.jpg`

Then replace the `placeholder-photo` div in `index.html` with:

```html
<div class="hero-photo" style="background:url('assets/profile.jpg') center/cover no-repeat;"></div>
```

## Add your CV
Place your CV at:

`assets/Lungten_Dorji_CV.pdf`

## Update contact details
Search `index.html` for:

`YOUR-EMAIL@example.com`

and replace it with your preferred professional email.

Update the Google Scholar, ORCID, ResearchGate, LinkedIn and GitHub links near the bottom of the page.

## Publish on GitHub Pages
1. Create a new public GitHub repository, e.g. `lungtendorji.github.io`.
2. Upload all files in this folder to the repository root.
3. Commit the files.
4. If the repository is named `lungtendorji.github.io`, GitHub Pages normally serves it from that address. Otherwise enable Pages in the repository settings and deploy from the main branch.

## Recommended next additions
- Replace gradient project images with your own field photographs.
- Add individual project pages under a `/projects/` folder.
- Replace sample research-output titles with exact publications and links.
- Add a custom domain when ready.
