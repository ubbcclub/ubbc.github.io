# ubbc.github.io

# UBBC Club - Static Site (GitHub Pages)

## Quick steps to deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `ubbc-club`).
2. Clone locally or upload files via the web UI.

Command-line example:

```bash
# replace with your username
git clone https://github.com/your-username/ubbc-club.git
cd ubbc-club
# create files (index.html, style.css, images/)
git add .
git commit -m "Initial UBBC club site"
git push origin main
```

3. On GitHub, go to Settings → Pages (or the Pages tab). Set source to `main` branch and `/ (root)`, then Save. Your site will be published at `https://your-username.github.io/ubbc-club/` within a few minutes.

4. To use a custom domain, add a `CNAME` file with your domain and configure DNS A/ALIAS records.

## Tips & enhancements
- Add images in an `images/` folder; update gallery markup.
- Use a `README.md` on the repo to share contact and contribution info.
- For form submissions, static sites cannot receive POST easily — use services like Netlify Forms, Formspree, or a mailto fallback (included).
- To enable HTTPS for custom domain, ensure DNS is correct and GitHub Pages provision certificate.

## Need help customizing?
Tell me what colors, logo, or sections you want — I can update the template for you.
