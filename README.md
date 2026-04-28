# Knowledge-Base

This repository is set up as a static Cloudflare Pages site.

## Files
- `index.html` (entry point used by Cloudflare Pages)
- `vibe-coding-kb-v2 (5).html` (local copy of the page content)
- `_headers` (security headers for Cloudflare Pages)

## Routing behavior
The Cloudflare Pages root route (`/`) redirects directly to the local file:
`./vibe-coding-kb-v2%20(5).html`

## If GitHub shows a merge conflict in `README.md`
When you see conflict markers like `<<<<<<<`, `=======`, and `>>>>>>>`, keep one clean final block and remove all marker lines.
For this repo, keep these lines in the `## Files` section:
- `vibe-coding-kb-v2 (5).html` (local copy of the page content)
- `_headers` (security headers for Cloudflare Pages)

Then click **Mark as resolved** and complete the merge.

### Which button to click in this exact conflict
Pick **Accept current change** for the conflicted `README.md` block shown in GitHub, then verify the final file still contains:
- `vibe-coding-kb-v2 (5).html` (local copy of the page content)
- `_headers` (security headers for Cloudflare Pages)
- the routing URL to the local HTML file

Do **not** use **Accept both changes** for this block, because it will duplicate lines.

## Deploy to Cloudflare Pages
1. Push this repo to GitHub/GitLab.
2. In Cloudflare Dashboard → Workers & Pages → Create application → Pages.
3. Connect your repo.
4. Build settings:
   - Framework preset: **None**
   - Build command: *(leave empty)*
   - Build output directory: `/`
5. Deploy.
