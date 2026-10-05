# CARMA Lab Website

Static website for **CARMA Lab — Clinical AI for Reliable Medical Analytics**.
No build step, no dependencies. Publish with GitHub Pages.

## Publish to GitHub Pages

1. Log in to GitHub: `gh auth login` (or create the repo at github.com/new).
2. Create a repository, e.g. `carma-ai-lab` (or `carma-ai-lab.github.io` if you want it as your main lab domain).
3. From this folder, run:

```bash
git remote add origin https://github.com/<your-username>/carma-ai-lab.git
git branch -M main
git push -u origin main
```

4. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. The site will be live at `https://<your-username>.github.io/carma-ai-lab/` within a minute or two.

## Custom domain (optional)

If you register `carma-ai-lab.org`, add a file named `CNAME` in this folder
containing just the domain name, then point the domain's DNS A records at
GitHub Pages (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153).

## Files

- `index.html` — the whole site (About, Research, Publications, People, Contact)
- `assets/css/style.css` — all styling
- `assets/img/logo-light.png` — logo mark for light backgrounds
- `assets/img/logo-dark.png` — logo mark for dark backgrounds
