# Nabita Penmetsa — Academic Homepage

Static site for hosting on GitHub Pages.

## Files

```
index.html          # main page
assets/style.css    # styles
```

## Deploy to GitHub Pages

1. Create a public repo named `<your-github-username>.github.io` (for a user site) or any repo (for a project site).
2. Copy `index.html` and the `assets/` folder into the repo root.
3. Push to `main`.
4. In **Settings → Pages**, set Source = `Deploy from a branch`, Branch = `main`, Folder = `/ (root)`.
5. The site will be live at `https://<your-github-username>.github.io/` within a minute or two.

## Customize

- **Photo**: add `<img src="assets/photo.jpg" alt="Nabita Penmetsa" class="headshot">` inside `.site-header` and style with a `.headshot` rule.
- **CV link**: drop `Nabita_CV.pdf` into `assets/` and add `<a href="assets/Nabita_CV.pdf">CV (PDF)</a>` to the nav.
- **Google Scholar / LinkedIn**: add links in the Contact section.
- **Colors / fonts**: edit the `:root` variables at the top of `style.css`.
