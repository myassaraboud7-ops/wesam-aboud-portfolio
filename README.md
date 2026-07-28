[README.md](https://github.com/user-attachments/files/30481850/README.md)
# Wesam Abdelrahman Aboud — Founder Portfolio

Single-page bilingual (EN/AR) portfolio site. Static HTML/CSS/JS — no build step, no dependencies to install.

## Publish on GitHub Pages

1. Create a new repository on github.com (e.g. `wesam-aboud-portfolio`). Do **not** initialize it with a README.
2. On your machine, from this folder:
   ```
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. In the repo on GitHub: **Settings → Pages → Source → Deploy from a branch → `main` / root → Save**.
4. Your site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Editing content

All copy — English and Arabic — lives in the `translations` object at the bottom of `index.html`. Edit the `en` and `ar` values in place; nothing else needs to change.

The portrait is `assets/portrait.png`, cropped from the original source image.
