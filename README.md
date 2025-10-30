# BST_SRLS_WEB_SITE

## Deploy to Netlify

This is a static site (HTML/CSS/JS) ready for Netlify.

Netlify config is provided in `netlify.toml` and publishes the project root.

### Quick deploy options

1) Drag & Drop
- Build not required. Zip or select the project folder (root containing `index.html`).
- Go to Netlify UI → Add new site → Deploy manually → Drag the folder.

2) Connect Git repository
- Push this folder to a Git repo (GitHub/GitLab/Bitbucket).
- In Netlify, New site from Git → pick the repo.
- Build command: leave empty
- Publish directory: `.`

### Notes
- Assets are under `/assets/` and are cached aggressively via headers.
- No redirects are required (single page with hash anchors).
- You can customize headers in `netlify.toml` as needed.
