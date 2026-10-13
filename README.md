# themadlions.com

The Mad Lions' company site, live at https://themadlions.com (GitHub Pages, branch main, root; CNAME file).

- `index.html` the site, one page, its own CSS and JS; `works.js` only a first paint and fallback.
- `admin/` Studio, the site's admin (sign in with a THEMADLIONS Hub administrator account).
- Films, look, opening picture, shop, enquiries and statistics live in the hub's Supabase project
  (tables site_works, site_settings, site_products, site_leads, site_events; bucket `site`), so changes made
  in Studio show without touching this repository.
- `404.html` sends any old WordPress address to the home page.

The source of truth for the code is `public/site/` in alexisdigipro-hub/themadlions-projects (also served at
hub.themadlions.com/site/ as a preview); copy changes here to publish them.
