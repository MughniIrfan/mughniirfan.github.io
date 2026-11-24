# Mughni Irfan — Academic Website

Static, responsive academic portfolio inspired by [Zubair Irshad's open-source website](https://github.com/zubair-irshad/zubair-irshad.github.io). Content adapted from the provided resume. No publication images are used.

## Preview
Open `index.html` in a browser or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Add your photo
Place a photo at `assets/profile.jpg`. In `index.html`, replace the `<div class="photo-placeholder" ...>...</div>` with `<img class="profile-photo" src="assets/profile.jpg" alt="Mughni Irfan">`. Add CSS: `.profile-photo{width:220px;height:245px;object-fit:cover;border-radius:12px;display:block;margin:0 auto 27px}`.

## Before publishing
- Replace the Google Scholar and LinkedIn placeholder links with your actual profile URLs.
- Check publication review statuses and semester dates as they change.
- Update the PDF in `resume/` whenever your resume changes.

## GitHub Pages
Create a public repository named `MughniIrfan.github.io` under your GitHub account, upload the **contents** of this folder to its root, and enable GitHub Pages under Settings > Pages (deploy from the main branch). Your site should then be available at `https://mughniirfan.github.io/` (GitHub Pages URLs are case-insensitive).

No build process, analytics, or third-party JavaScript dependencies are required. Google Fonts is optional.
