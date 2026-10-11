# YellowBot Home

A standalone landing page for YellowBot that directs visitors to the Studio.

## Main site
- Landing page: `index.html`
- Studio: https://studio.yellowbot.rohansweb.co.uk/

## Deploy
This repository contains a static website and can be deployed with GitHub Pages or another static host.

### GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select the `main` branch and `/ (root)`, then save.
4. If you want to use a custom domain, enter it in the Pages settings and configure the DNS records GitHub shows.

**Important:** The custom domain `studio.yellowbot.rohansweb.co.uk` is currently intended to point at the YellowBot Studio app. Do not point that same hostname at GitHub Pages if you still want the Render Studio app to load there. Use a separate hostname such as `yellowbot.rohansweb.co.uk` for this landing page, or keep this repository on its GitHub Pages URL and let the buttons link to the Studio.
