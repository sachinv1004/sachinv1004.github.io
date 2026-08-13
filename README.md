# Sachin Vishwakarma — Portfolio

Single-page portfolio site, ready for GitHub Pages.

## Before you deploy

1. **Add your résumé**: drop a file named `resume.pdf` into this folder (the "download résumé" button already links to it).
2. **Fill in project links**: in `index.html`, search for `TODO: replace #` and swap in your real GitHub/demo URLs for the Ticket Assignment Classifier and YouTube Sentiment Analyzer projects.
3. **Update the OG image URL** (optional, for nicer link previews on LinkedIn/Slack): search for `og:image` in `index.html` and point it at a real screenshot you host, or remove the tag.

## Deploy to GitHub Pages

1. Create a new repository on GitHub. For a personal site at `https://<username>.github.io`, name the repo exactly `<username>.github.io`. For a project page instead (`https://<username>.github.io/<repo-name>`), any repo name works.
2. Push these files to the repo's default branch (`main`):
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Under **Branch**, select `main` and folder `/ (root)`, then **Save**.
6. Wait 1–2 minutes, then visit the URL GitHub shows at the top of the Pages settings page.

## Custom domain (optional)

If you want a custom domain instead of `github.io`:
1. Add a `CNAME` file to this repo containing just your domain, e.g. `sachin.dev`.
2. In your domain registrar's DNS settings, add a `CNAME` record pointing to `<username>.github.io`.
3. Back in **Settings → Pages**, enter the custom domain and enable **Enforce HTTPS** once it's verified.
