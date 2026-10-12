# Publish and make searchable

1. Upload this project to GitHub (or import it into Vercel).
2. In Vercel, select the Vite framework, build command `npm run build`, output directory `dist`. Deploy.
3. Copy the real published URL. Do not use an example URL as your live link.
4. In `index.html`, add `<link rel="canonical" href="https://YOUR-ACTUAL-DOMAIN/" />` and set `og:url` to your actual domain.
5. In `public/robots.txt`, add `Sitemap: https://YOUR-ACTUAL-DOMAIN/sitemap.xml` after publishing.
6. Create `public/sitemap.xml` containing your actual URL (do not submit a placeholder URL).
7. Redeploy, verify the domain in Google Search Console, submit the sitemap, and request indexing for the homepage.

Google search visibility is not immediate or guaranteed. A custom domain can improve branding but is optional.
