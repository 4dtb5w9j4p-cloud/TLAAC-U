# TLAAC — The Legal Advisory Aid Camp (Static Site)

This package contains a ready-to-publish static website for **TLAAC**.

## Files
- index.html
- about.html
- team.html
- research.html
- contact.html
- styles.css
- logo.svg

## How to publish

### Option A — GitHub Pages (recommended for static sites)
1. Create a new GitHub repository (public).
2. Upload all files (drag-and-drop or push via git).
3. In the repository, go to Settings → Pages.
4. Under "Build and deployment" choose "Deploy from a branch".
5. Select the `main` branch (or `master`) and the root folder `/`.
6. Save — your site will be available at `https://<your-username>.github.io/<repo>/`.
7. To use **TLAAC.com**, add the domain in Pages settings and update your domain's DNS (A or CNAME record) as instructed by GitHub.

### Option B — Netlify (easy, supports drag-and-drop & custom domains)
1. Sign up at netlify.com.
2. On the dashboard choose "Add new site" → "Deploy manually" → drag-and-drop the ZIP or folder.
3. Once deployed, go to Domain settings → Add custom domain → enter `TLAAC.com`.
4. Update your domain's DNS records to point to Netlify (they will provide the DNS targets).

### Notes about the domain (TLAAC.com)
I cannot connect the domain or upload files to your hosting without access to your registrar/hosting account.
To point `TLAAC.com` to this site you will need to:
- Own the domain and be able to edit DNS records OR
- Give a developer access to your hosting control panel.

If you want, I can provide exact DNS records and step-by-step instructions for whichever host or registrar you use.

