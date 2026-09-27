# Sivaharsha Sottu — Portfolio Website

A hand-built, multi-page portfolio: deep navy + gold, bold typography, no templates.

## What's inside

| File            | Purpose                                          |
|-----------------|--------------------------------------------------|
| `index.html`    | Home — hero, skills marquee, featured projects   |
| `projects.html` | All projects in detail                           |
| `about.html`   | Bio, education, timeline, skills, interests      |
| `contact.html`  | Email / GitHub / LinkedIn + message form         |
| `styles.css`    | All styling (one shared stylesheet)              |
| `resume.pdf`    | One-page resume, downloadable from the site      |

## Deploy it

### GitHub Pages (free)
1. Create a new **public** repository (e.g. `portfolio`).
2. Upload all files in this folder to the repo root (no subfolder needed).
3. Repo → **Settings** → **Pages** → Source: `Deploy from a branch` → Branch: `main`, folder `/ (root)`.
4. Your site goes live at `https://<your-username>.github.io/portfolio/` in a minute or two.

### Vercel / Netlify (also free)
- Drag and drop this folder at <https://vercel.com/new> or <https://app.netlify.com/drop> — done.
- Or connect the GitHub repo and it auto-deploys on every push.

### Custom domain (optional)
Buy a domain (e.g. `sottu.dev` from any registrar) and point it to your host:
- GitHub Pages: Settings → Pages → Custom domain → follow verification steps.
- Vercel/Netlify: add the domain in project settings, then set the DNS records it shows you.

## Edit it

- **Text content** lives directly in the HTML files — search for the words you want to change.
- **Colors** live at the top of `styles.css` in `:root` (change `--gold`, `--bg`, etc.).
- **LinkedIn URL** — currently `linkedin.com/in/sivaharsha-sottu` (a placeholder guess). Update it in
  all four HTML files once your real profile URL exists.
- **Resume** — replace `resume.pdf` with a new file of the same name.
- **Project links** — point the `GitHub ↗` links at your actual repositories when ready.

## Notes

- Fonts load from Google Fonts (Bricolage Grotesque + Fragment Mono); the site works
  offline too, just with fallback fonts.
- The contact form opens the visitor's email client — no backend or service needed.
