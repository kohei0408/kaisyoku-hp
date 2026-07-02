# GitHub and Vercel publish notes

This folder is ready to deploy as a static site with GitHub + Vercel.

## Before publishing

1. Replace `hello@your-domain.example` in `index.html` with your real contact address.
2. Replace `your-domain.example` in `robots.txt` and `sitemap.xml` with your real domain after Vercel assigns or you connect it.

## Recommended flow

1. Create a GitHub repository.
2. Push this folder to the repository root.
3. Import the repository into Vercel.
4. Use the default static deployment settings.
5. Add your production domain in Vercel, then update `robots.txt` and `sitemap.xml`.

## Optional CLI flow

1. Install the Vercel CLI:
   `npm install -g vercel`
2. Sign in:
   `vercel login`
3. Move into this folder:
   `cd C:\Users\zawa0\Documents\Codex\2026-07-02\hp\outputs\kaiseki_lp_site`
4. Deploy:
   `vercel`
5. Promote to production:
   `vercel --prod`

## Google indexing

After deployment, add the site to Google Search Console and submit:

`https://your-domain.example/sitemap.xml`
