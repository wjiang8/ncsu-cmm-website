# CMM Group Website

Static website for the Computational Mechanics and Materials (CMM) research group,
Department of Nuclear Engineering, NC State University.

## Deploy on GitHub Pages (5 minutes)

1. Create a new **public** repository on GitHub (e.g. `cmm-website`,
   or `<username>.github.io` for a root-level URL).
2. Upload every file in this folder to the repository
   (drag-and-drop works: repo page → "uploading an existing file").
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**,
   choose `main` branch, `/ (root)` folder, and Save.
4. Your site goes live at `https://<username>.github.io/cmm-website/`
   within a minute or two.

## Editing content

Every page is plain HTML — edit directly on GitHub (pencil icon) and commit;
the site redeploys automatically.

- `index.html` — homepage (hero, research cards, news, openings panel)
- `research.html` — research area descriptions
- `people.html` — team profiles (replace [Student Name] placeholders;
  add photos to an `img/` folder and swap the `.photo` divs for
  `<img src="img/name.jpg" alt="Portrait of ..." width="140">`)
- `publications.html` — replace placeholder entries with real papers
- `openings.html`, `contact.html` — fill in email/office details
- `style.css` — all styling; colors are CSS variables at the top

## Custom domain (optional)

Buy a domain, add it under Settings → Pages → Custom domain, and set the
DNS records GitHub shows you.
