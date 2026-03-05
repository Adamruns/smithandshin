# Smith and Shin CPAs, LLC

Website for Smith and Shin CPAs, LLC — my dad's CPA firm in Taylors, SC.

## Background

The original site was hosted on Heroku with a PHP buildpack wrapper around static HTML. I transferred the `smithandshin.com` domain from the previous registrar over to Cloudflare, set up DNS, and migrated the hosting to Cloudflare Pages.

## Hosting

- **Domain registrar:** Cloudflare
- **Hosting:** Cloudflare Pages (auto-deploys from this repo on push to `main`)
- **Build:** None — static HTML served directly with Tailwind CSS via CDN
