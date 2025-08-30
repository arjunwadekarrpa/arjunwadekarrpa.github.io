# GitHub Pages Portfolio Starter

This is a minimal, fast, and responsive personal portfolio you can host free on GitHub Pages.

## Quick start

1. Rename this repository to `your-username.github.io` (exactly your GitHub username).
2. Edit `index.html` and `style.css` with your details.
3. Push to `main`. Your site will be live at `https://your-username.github.io`.

## Customize

- Replace text in the **hero**, **Projects**, **Skills**, **About**, and **Contact** sections.
- Add more projects by duplicating a `<article class="project">` block in `index.html`.
- Update colors by changing CSS variables at the top of `style.css`.
- Add a favicon by placing `favicon.ico` in the root.

## GitHub Pages

- Repo name must be `your-username.github.io` for a user site.
- Ensure there's an `index.html` in the root.
- Settings → Pages → set Source to "Deploy from a branch", Branch: `main` (root).

## Custom domain (optional)

- Add your domain in Settings → Pages → Custom domain (e.g., `www.yourname.in`).
- Create a DNS CNAME record for `www` pointing to `your-username.github.io`.
- For apex/zone root (e.g., `yourname.in`), use the A records recommended in GitHub Pages docs.
- After DNS propagates, enable "Enforce HTTPS" in Pages settings.
