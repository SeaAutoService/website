# Sea Auto Service / Sea Auto Servicio (Static Website)

## What this is
A fast, responsive, bilingual (EN/ES) one-page website for Sea Auto Service / Sea Auto Servicio.

## Key features
- Tailwind CSS (CDN) clean branded styling
- Click-to-call phone links: +1 (561) 847-1169
- Language auto-detect redirect at /index.html
- One-page smooth scrolling sections
- Google Maps embed for service area
- SEO meta tags + JSON-LD schema (Google Business friendly)

## Structure
- /index.html (auto-redirect)
- /en/index.html (English one-page site)
- /es/index.html (Spanish one-page site)
- /assets/images/logo-en.png, logo-es.png
- /assets/js/main.js

## Deploy
Upload the contents of this folder to any static host. Keep the structure as-is.


## Canonical URLs (OceanDeep)
This build uses canonical URLs set to https://seaautoservice.com/... (best practice for SEO). If your OceanDeep deployment uses a temporary OceanDeep URL (before your custom domain), update BASE_URL in /en/index.html and /es/index.html (search for `link rel="canonical"`) to match your live domain.
