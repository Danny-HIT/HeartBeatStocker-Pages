# Deploying The Public App Pages

These pages give App Store Connect a public Support URL and Privacy Policy URL.

## Recommended Free Option: GitHub Pages

1. In GitHub, open `Danny-HIT/HeartBeatStocker`.
2. Go to Settings.
3. Open Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch `main` and folder `/docs`.
6. Save.
7. Wait for GitHub Pages to publish.

Expected public URLs:

- Landing page: `https://danny-hit.github.io/HeartBeatStocker/`
- Support URL: `https://danny-hit.github.io/HeartBeatStocker/support.html`
- Privacy Policy URL: `https://danny-hit.github.io/HeartBeatStocker/privacy.html`

Important: GitHub Pages on a free GitHub account needs the repository to be public. If you want the source repository to remain private, use Cloudflare Pages or Netlify instead.

## Good Free Alternatives

- Cloudflare Pages: connect the GitHub repository and set the output directory to `docs`.
- Netlify: import the GitHub repository and set the publish directory to `docs`.

Both options can publish the static HTML pages without a build command.
