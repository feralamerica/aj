# The Anand Jon Record (anandjon.info)

A single-page, static, public-interest reference site. No build step, no framework. Just files.

## What's in this folder

- `index.html` — the entire site (all styling and scripts are inline).
- `CNAME` — tells GitHub Pages the custom domain is `anandjon.info`. Leave it as is.
- `404.html` — the "page not found" page.
- `robots.txt` and `sitemap.xml` — basic search-engine files.

## Put it online with GitHub Pages (no coding)

1. Sign in at github.com. Click the **+** (top right), **New repository**. Name it `yourusername.github.io` (use your real username). Set it **Public**. Create.
2. On the repo page, click **uploading an existing file**, then drag in every file from this folder. Click **Commit changes**.
3. Go to **Settings** > **Pages**. Under "Build and deployment," set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
4. Wait about a minute, refresh, and the Pages screen shows **"Your site is live at ..."**. That link is your site.

## Connect the domain anandjon.info

At your domain registrar's DNS settings, add four **A records** for the bare domain pointing to GitHub:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Then in GitHub **Settings > Pages**, put `anandjon.info` in **Custom domain** and save. Once it verifies, tick **Enforce HTTPS**.

## Updating the site later

Edit `index.html` (or re-upload a new copy) and commit. GitHub Pages redeploys automatically within a minute.

## Adding a hero image

Open `index.html` and find the comment that says `HERO IMAGE SLOT`. Follow the instructions there. Use an image you have the rights to, add a caption crediting the source, and avoid the prison-injury photo as the hero.
