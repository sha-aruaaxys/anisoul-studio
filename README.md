# AniSoul Studio website

Free static site for AniSoul Studio (an assumed name of AruaAxys LLC). Plain HTML and CSS, no build step, hosted free on GitHub Pages.

## Pages
- `index.html` — studio home: services, process, contact
- `world.html` — AniSoul vision and Sight (in development)
- `links.html` — link-in-bio page for Instagram, TikTok and YouTube
- `privacy.html` — short privacy notice

## Publish on GitHub Pages (free)
1. Push these files to the `main` branch of the repo.
2. Repo **Settings > Pages**, Source: **Deploy from a branch**, Branch: `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<github-username>.github.io/<repo-name>/`.
4. Put `.../links.html` in your social bios.

## Custom domain later (optional)
Add a `CNAME` file containing the domain, point the domain's DNS at GitHub Pages, and turn on **Enforce HTTPS**. Only the domain renewal costs money.

## Editing
- Prices and services: `index.html`, section `#services`
- Contact email: search for `sha@aruaaxys.net`
- Colors and fonts: top of `styles.css`
