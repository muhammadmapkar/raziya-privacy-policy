# Privacy Policy & Terms of Service — Raziya Adam Perfumes

Static, framework-free HTML pages (Privacy Policy + Terms of Service) for the
Instagram automation app, meant to be hosted publicly via GitHub Pages so they
can be linked in Meta's App Review / App Dashboard settings.

> **IMPORTANT:** This subfolder must be pushed to its **own separate PUBLIC
> GitHub repo** — do NOT push it as part of the main `pas-content-engine`
> repo, which is PRIVATE. Meta requires the privacy policy URL to be publicly
> accessible, so it cannot live in a private repo.

## Setup Steps

1. **Create a new, separate PUBLIC GitHub repo for just this subfolder**
   (e.g. `raziya-adam-perfumes-privacy-policy`). Copy the contents of this
   `privacy-policy/` folder (`index.html`, `terms-of-service.html`) into that
   new repo — do not include it inside the main private repo.

2. **Push the new repo to GitHub:**
   ```bash
   cd raziya-adam-perfumes-privacy-policy
   git init
   git add .
   git commit -m "Add privacy policy and terms of service"
   git branch -M main
   git remote add origin https://github.com/<your-username>/raziya-adam-perfumes-privacy-policy.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:** In the new repo, go to
   **Settings → Pages → Build and deployment → Source**, select
   **Deploy from a branch**, choose branch **main** and folder **/(root)**,
   then Save.

## Resulting URL

Once GitHub Pages is enabled, your pages will be live at:

```
https://<your-username>.github.io/<repo-name>/
https://<your-username>.github.io/<repo-name>/terms-of-service.html
```
