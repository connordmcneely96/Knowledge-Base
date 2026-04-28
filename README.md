# Knowledge-Base

This repository is set up as a static Cloudflare Pages site.

## Files
- `index.html` (entry point used by Cloudflare Pages)
- `vibe-coding-kb-v2 (5).html` (local copy of the page content)
- `_headers` (security headers for Cloudflare Pages)

## Routing behavior
The Cloudflare Pages root route (`/`) redirects directly to:
`https://github.com/connordmcneely96/Knowledge-Base/blob/main/vibe-coding-kb-v2%20(5).html`

## Deploy to Cloudflare Pages
1. Push this repo to GitHub/GitLab.
2. In Cloudflare Dashboard → Workers & Pages → Create application → Pages.
3. Connect your repo.
4. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
5. Deploy.
