# AI FRAME/LAB — AI Films & Animation Portfolio

A responsive, static portfolio/blog concept built with plain HTML, CSS and JavaScript. No build tools or paid hosting are required.

## Preview locally
1. Extract this folder.
2. Double-click `index.html` to open it in your browser.
3. Edit `index.html`, `styles.css`, and `script.js` in VS Code.

## Before publishing
- Replace `AI FRAME/LAB` with your preferred brand or name.
- Replace `hello@example.com` in `index.html` with your email address.
- Replace the six illustrative project cards with your real films, stills, reels and links.
- Replace the three starter journal topics with your own articles. The current content is sample copy.
- Add your real domain to a file named `CNAME` (one domain only), for example `www.yourdomain.com`.

## Publish for free with GitHub Pages
1. Sign in at https://github.com and create a **public** repository, e.g. `ai-films-portfolio`.
2. Upload `index.html`, `styles.css`, `script.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the Pages deployment to finish. GitHub will show the free `https://YOUR-USERNAME.github.io/ai-films-portfolio/` URL.

## Connect your GoDaddy domain
1. First add the custom domain in **GitHub repository → Settings → Pages → Custom domain** and save it.
2. At GoDaddy, open **Domain Portfolio → your domain → DNS**.
3. For the root/apex domain, add these four `A` records (Host `@`):
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
4. For `www`, add a `CNAME` record: Host `www`, Points to `YOUR-USERNAME.github.io` (use your actual GitHub username; do not include the repository name).
5. Remove conflicting old `A`/`CNAME` records for the same hosts, but do not delete email-related MX/TXT records.
6. Return to GitHub Pages settings and enable **Enforce HTTPS** once the certificate is ready.

DNS changes can take up to 24 hours. Exact screens can vary by GoDaddy account and DNS setup. Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Important limitations
This is a static website. The contact link opens the visitor's email app; it does not store messages. For a real blog publishing workflow, comments, analytics or a contact form, add a suitable third-party service or a CMS later.
