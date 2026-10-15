# DevResources Showcase
Static gallery. Data: `showcase.json` → `items[]` with `name, logo, cover, description, link, price, category, tags`.
Add an entry: append an object to `items` (logo e.g. `https://www.google.com/s2/favicons?domain=DOMAIN&sz=128`; cover any image URL, falls back to the logo if it fails), commit, redeploy.
`feed.json`/`feed.js` are copied from the main site (daily-rotating tips feed). Submissions arrive by email (mailto).
