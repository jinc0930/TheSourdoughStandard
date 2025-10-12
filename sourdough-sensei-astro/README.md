# Sourdough Sensei — Astro Starter

A minimal, fast site to host your sourdough lessons with embedded TikTok/YouTube videos.

## Quick start (local)

```bash
npm i
npm run dev
# open the printed localhost URL
```

## Project scripts

- `npm run dev` — start local dev server with hot reload
- `npm run build` — build static site to `dist/`
- `npm run preview` — preview the built site

## Deploy to Cloudflare Pages

1. Push this folder to a new GitHub repo.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages** and connect your repo.
3. Framework preset should auto-detect **Astro**. If not, set:
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. (Optional) Set an environment variable to pin Node: `NODE_VERSION=20`.

Once the first build finishes, add your custom domain and turn on HTTPS.

## Add your videos

- On **/lessons**, there are example embeds for YouTube and TikTok.
- Replace `VIDEO_ID_HERE` with a real YouTube ID and `TIKTOK_URL_HERE` with a full TikTok URL.
