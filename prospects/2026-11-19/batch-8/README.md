# AI Skills World — Gaya Restaurant Concepts (19 Nov 2026)

Five independent, unsolicited concept demos are included. Each restaurant folder contains `index.html` and `prospect.json`; the root `index.html` links to all five demos.

Each page is mobile-responsive and includes SEO metadata, `noindex,nofollow`, keyboard focus states, a skip link, map directions, click-to-call/SMS only where a public phone was verified, and a client-side copy-enquiry action. No visitor data is stored or transmitted. No WhatsApp number was independently verified, so WhatsApp CTAs are not enabled. No order, payment or reservation workflow is enabled.

All menu references are public listing/review mentions, not owner-approved menus. Confirm all business details and obtain owner approval before publication. The demos are not official restaurant websites and do not imply affiliation.

## Netlify deployment
No build command is required. The connected Netlify integration can inspect projects but does not expose a file-upload or deploy-start action, so no live URL is claimed.

**One combined Netlify site** (landing page plus five demo paths):
- Import: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8
- Base directory: `prospects/2026-11-19/batch-8`
- Build command: leave blank
- Publish directory: `.`

**Separate Netlify site per restaurant:** use the matching import path below; for each, leave build command blank and publish directory `.`.
- pgr-dhaba-restaurant-sikahar: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8%2Fpgr-dhaba-restaurant-sikahar
- bheli-restaurant-mast-alipur: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8%2Fbheli-restaurant-mast-alipur
- tandoor-mahal-manpur: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8%2Ftandoor-mahal-manpur
- shrawan-fast-food-guraru: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8%2Fshrawan-fast-food-guraru
- kitam-kittu-hot-food-guraru: https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmymindest%2Faiskillsworld&create_from_path=prospects%2F2026-11-19%2Fbatch-8%2Fkitam-kittu-hot-food-guraru
