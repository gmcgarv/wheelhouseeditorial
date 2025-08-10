# Wheelhouse Editorial — Jekyll Site

A lightly refreshed rebuild of your 2018 Wheelhouse Editorial site using **Jekyll** (GitHub Pages–friendly).

## Quick start (local)
1. Install Ruby and Jekyll (optional if you only use GitHub Pages to build).
2. From this folder:
   ```bash
   bundle exec jekyll serve
   ```
   or, if not using Bundler:
   ```bash
   jekyll serve
   ```

## Deploy on GitHub Pages
1. Create a new repo named `wheelhouseeditorial` (or your preference).
2. Commit all files and push to `main`.
3. In **Settings → Pages**, choose **Build and deployment: GitHub Actions** or **Deploy from branch** (root).
4. Your site will publish at `https://<username>.github.io/<repo>/` or your custom domain.
5. To use your custom domain `wheelhouseeditorial.com`, add it in Settings → Pages and create a DNS CNAME pointing to GitHub Pages.
6. Optionally add a `CNAME` file at the repo root containing `wheelhouseeditorial.com`.

## Editing
- Update `_config.yml` with your email, url, and title.
- Edit page content in `index.md` and `/pages/*`.
- Tweak styles in `assets/css/site.css`.

## Notes
- No external Jekyll plugins, so it works on GitHub Pages by default.
- Contact is via email link; if you want a form, we can wire Formspree or similar later.
