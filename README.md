# M.S Mozahid Islam Tasin — Portfolio

A static, single-page portfolio built with plain HTML5 and CSS3 (no JavaScript, no frameworks). Ready to deploy on GitHub Pages.

## Structure

```
index.html
style.css
assets/
  profile.jpg                 (included)
  project-autocad.jpg         (add your own)
  project-greenhouse.jpg      (add your own)
  project-surveillance-car.jpg (add your own)
README.md
```

## Deploy to GitHub Pages

1. Create a new GitHub repository and push these files to the root (or to a `docs/` folder).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set the source branch (e.g. `main`) and folder (`/root` or `/docs`).
4. Save — GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`.

Because `index.html` sits at the root and everything is relative (`style.css`, `assets/...`), no configuration changes are needed.

## Customize

- **Project images**: drop matching JPGs into `assets/` using the filenames above. Until you do, each project card shows a themed color placeholder instead of a broken image.
- **Contact details**: open `index.html`, find the Contact section (`id="contact"`), and replace the placeholder email/Facebook/LinkedIn/GitHub links with your real ones.
- **Colors/fonts**: all design tokens (colors, spacing, fonts) are defined once at the top of `style.css` under `:root` — change them there to restyle the whole site.

## Notes

- No JavaScript is used anywhere; the mobile nav menu uses a pure-CSS checkbox toggle.
- Layout is responsive down to small mobile screens via CSS media queries.
