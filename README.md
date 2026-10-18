# themadlions.com

The Mad Lions' company site, live at https://themadlions.com (GitHub Pages, branch main, root; CNAME file).

- `index.html` the site, one page, its own CSS and JS; `works.js` only a first paint and fallback.
- `admin/` Studio, the site's admin (sign in with a THEMADLIONS Hub administrator account).
- Films, look, opening picture, shop, enquiries and statistics live in the hub's Supabase project
  (tables site_works, site_settings, site_products, site_leads, site_events; bucket `site`), so changes made
  in Studio show without touching this repository.
- `el/index.html` the same page in Greek; `llms.txt` / `llms-full.txt` the company in plain text for AI assistants;
  `sitemap.xml`. These, the head of both pages and the text between `<!--seo:-->` markers are written by
  `node scripts/site-seo.mjs <this folder> --live` in the hub repo: run it after every copy.
- `404.html` sends any old WordPress address to the home page.

The source of truth for the code is `public/site/` in alexisdigipro-hub/themadlions-projects (also served at
hub.themadlions.com/site/ as a preview); copy changes here to publish them.
