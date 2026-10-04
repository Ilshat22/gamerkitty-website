# Gamer Kitty — One Minute Formula Landing Page

Static landing page built for GitHub Pages / Netlify / Vercel.

## Run locally
Open `index.html` directly, or serve the folder with any static server.

## Before publishing
1. Replace every Gumroad checkout URL with the permanent product checkout URL.
2. Review and publish final 90-Day Monetization Guarantee terms. The current modal is intentionally marked as a draft.
3. The Starter Pack modal is connected to the EmailOctopus inline form tagged `Starter Pack Lead`. After deployment, update the Starter Pack links inside EmailOctopus emails to the final public PDF/page URL.
4. Compress images to WebP/AVIF for production performance.
5. Add analytics/pixel only after deciding your privacy/cookie setup.

## Deploy on GitHub Pages
Upload the folder to a repository, then enable Pages from the repository settings and deploy from the main branch/root.


V5 launch notes:
- All paid CTAs use https://gamerkittyyy.gumroad.com/l/1minutemoney
- Starter Pack PDF is bundled in `assets/`.
- Starter Pack signup uses EmailOctopus form `fa0e1b04-c038-11f1-b83d-8795b2d6c401`, configured to apply the `Starter Pack Lead` tag.
- The PDF is delivered by the EmailOctopus automation. After deployment, point the delivery-email CTA to the final public PDF/page URL.
- Guarantee and Privacy modals are launch drafts and should be reviewed/finalized before publishing.


## V6.1
- Improved EmailOctopus signup readability on the dark modal by placing the embedded form on a light, high-contrast surface.
- Public Starter Pack asset remains at `assets/Gamer-Kitty-Viral-Short-Form-Starter-Pack.pdf`.
