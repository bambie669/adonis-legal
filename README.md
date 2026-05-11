# adonis-legal

Static legal pages for **Adonis Ads Intelligence** — landing, Terms of Service, and Privacy Policy.
Hosted via GitHub Pages and used as the public-facing URLs required by social-media developer platforms (TikTok, Meta, etc.).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page describing the product (shown as the Website URL) |
| `tos.html`   | Terms of Service |
| `privacy.html` | Privacy Policy |
| `styles.css` | Shared styling (no external dependencies, no CDNs) |

## Publishing on GitHub Pages

1. Create a new public repository on GitHub named `adonis-legal`.
2. From this folder:

   ```bash
   git init
   git add .
   git commit -m "Initial legal pages"
   git branch -M main
   git remote add origin https://github.com/<YOUR_USER>/adonis-legal.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Source → Deploy from branch → `main` / `/ (root)`** → Save.
4. After ~1–2 minutes, the site is live at:

   - Landing:   `https://<YOUR_USER>.github.io/adonis-legal/`
   - ToS:       `https://<YOUR_USER>.github.io/adonis-legal/tos.html`
   - Privacy:   `https://<YOUR_USER>.github.io/adonis-legal/privacy.html`

Paste those exact URLs into the corresponding fields in the TikTok Developer Portal.

## Updating

Edit the relevant HTML file, bump the `Last updated` date inside the `<span class="meta">`, commit and push. Pages redeploy automatically.
