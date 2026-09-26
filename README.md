# francescapick.com

Plain HTML + CSS. No build step, no JavaScript.

## Files
- `index.html`: main page. Text you'll edit is marked with `EDIT` comments.
- `archive.html` and `archive/`: old blog posts and press links.
- `style.css`: all styling (colors are at the top).
- `images/hero.jpg`: the hero photo (already included).
- `favicon.ico`, `apple-touch-icon.png`, `icon-512.png`: site favicon, generated from a headshot.
- `CNAME`: tells GitHub Pages to serve the site at francescapick.com.

## Before publishing
Everything needed is already in this folder — the hero photo and favicon are
included, and the thesis is linked externally (Google Drive) rather than
hosted as a local file. Just double-check the text edits, then publish.

## Publish on GitHub Pages
1. Create a repository (e.g. `francescapick.com`) and upload all files in this folder.
2. Repository → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Custom domain: `francescapick.com` (already set by the CNAME file). Tick "Enforce HTTPS" once available.
4. At your domain registrar, replace the current Tumblr DNS records with GitHub's:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record for `www`: `<your-github-username>.github.io`
   DNS changes can take a few hours.

## Editing text
Open `index.html` on github.com, click the pencil icon, change the words between
the tags (e.g. between `<p>` and `</p>`), and commit. The site updates within a minute.
