# AXXA Agent site

Source of [agent.axxalab.com.br](https://agent.axxalab.com.br), the site of the [AXXA Agent](https://github.com/axxalab/axxa-agent) plugin for Obsidian.

- Plain HTML and CSS in `public/`. No build step, no JavaScript, no third-party fonts, scripts or trackers: every request stays on this domain (see `public/_headers`).
- English at `/`, Portuguese at `/pt/`.
- Hosted on GitHub Pages: every push to `main` publishes `public/` (`.github/workflows/pages.yml`). DNS is on Cloudflare (`agent` CNAME to `axxalab.github.io`, DNS only).
- `wrangler.jsonc` and `public/_headers` are ready for a later move to Cloudflare Workers, which needs a Cloudflare login with Workers permission.
- Screenshots and the demo are real recordings of the plugin; keep it that way.

© 2026 AXXA Lab™
