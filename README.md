
# The Sporting Ledger — Free Static Site

This is a simple, static site you can publish **for free** with GitHub Pages or Netlify.

## Publish on GitHub Pages (free)
1) Create a GitHub account and a **public** repo named `the-sporting-ledger` (any name is fine).
2) Upload all files from this folder (keep the structure).
3) Go to **Settings → Pages → Source** → choose **Deploy from a branch**, then **Branch: main / root** → Save.
4) Your site appears at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## Publish on Netlify (free)
1) Visit https://app.netlify.com/drop
2) Drag this folder in → Netlify gives you a live URL instantly.

## Edit content
- Home: `index.html`
- Article page: `posts/brighton-model.html` (copy this file to create new posts)
- Styles: `styles.css`
- Images & interactive HTML: `/assets`

## Add a new post
1) Duplicate `posts/brighton-model.html` → rename (e.g., `posts/tactics-momentum.html`).
2) Edit the new file’s `<title>` and `<h1>`, paste your content.
3) Link to it from `index.html` (add a new block under “Latest article”).

## Custom domain
- GitHub Pages: **Settings → Pages → Custom domain**
- Netlify: **Domain settings → Add custom domain**

