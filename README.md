# Jubara Akram Mohsen — Portfolio Site

A single-page, bilingual (EN/RU) portfolio built from the project profile document.
Static HTML/CSS/JS — no build step, no dependencies to install.

## What's inside

```
index.html          the whole site (one page, language toggle EN/RU top-right)
assets/img/          project screenshots + QR codes
README.md            this file
```

## Publish it for free on GitHub Pages

1. **Create a new repository** on GitHub (e.g. `portfolio`), public.
   - Do NOT initialize it with a README (you already have one here).

2. **Upload these files.** Two options:

   **Option A — via the GitHub website (no command line needed)**
   - Open your new repo → "Add file" → "Upload files"
   - Drag in `index.html`, `README.md`, and the whole `assets` folder
   - Commit the changes

   **Option B — via git on your computer**
   ```bash
   cd path/to/this/folder
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. **Turn on GitHub Pages**
   - In your repo: Settings → Pages
   - Under "Build and deployment" → Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → Save

4. **Wait ~1 minute**, then your site will be live at:
   ```
   https://<your-username>.github.io/<your-repo>/
   ```
   (GitHub shows the exact link at the top of the Pages settings page once it's ready.)

## Using your own domain (optional)

If you want it at a custom domain (e.g. `portfolio.yourname.com`):
- Add a `CNAME` file in the repo root containing just your domain name
- Add a `CNAME` record at your DNS provider pointing to `<your-username>.github.io`
- Set the custom domain in Settings → Pages → Custom domain

## Editing content later

Everything is in `index.html`. Each block of text has a `.lang-en` and
a matching `.lang-ru` version right next to it — edit whichever language
you need. Images live in `assets/img/`; replace a file and keep the same
name, or update the `src=` path if you rename it.
