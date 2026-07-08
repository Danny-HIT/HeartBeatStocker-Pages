# Deploying The Public App Pages

These pages give App Store Connect a public Support URL and Privacy Policy URL.

## Recommended Free Option: GitHub Pages

1. In GitHub, create or open the public pages-only repository `Danny-HIT/HeartBeatStocker-Pages`.
2. Go to Settings.
3. Open Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch `main` and folder `/root`.
6. Save.
7. Wait for GitHub Pages to publish.

Expected public URLs:

- Landing page: `https://danny-hit.github.io/HeartBeatStocker-Pages/`
- Support URL: `https://danny-hit.github.io/HeartBeatStocker-Pages/support.html`
- Privacy Policy URL: `https://danny-hit.github.io/HeartBeatStocker-Pages/privacy.html`

Important: GitHub Pages on a free GitHub account needs the Pages repository to be public. Keep the app source repository private and publish only these static support/privacy pages.

## Good Free Alternatives

- Cloudflare Pages: connect a pages-only GitHub repository and set the output directory to the static site folder.
- Netlify: import a pages-only GitHub repository and set the publish directory to the static site folder.

Both options can publish the static HTML pages without a build command.
