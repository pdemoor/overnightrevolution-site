# The Overnight Revolution website

Static one-page author website for Cloudflare Pages.

## Replace these files before deploying
- `assets/cover.jpg` — your 1600 × 2560 book cover JPEG
- `assets/peter.jpg` — your author photo

If you do not replace them, the site will show fallback placeholders.

## Deploy on Cloudflare Pages
1. Create a GitHub repo, e.g. `overnightrevolution-site`.
2. Upload all files in this folder.
3. In Cloudflare, choose **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
4. Select the repo.
5. Build settings:
   - Framework preset: None
   - Build command: leave blank
   - Build output directory: `/`
6. Deploy.
7. Add custom domain: `overnightrevolution.com`.

## Store links
Update the hero buttons in `index.html` once Amazon, Google Play, and Apple Books links are live.
