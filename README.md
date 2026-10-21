# RenPointt Service

A responsive, single-page website for RenPointt Service, a cleaning company serving Stockholm.
The page is built with HTML, CSS, and vanilla JavaScript in `index.html`.

## Features

- English and Swedish language selection, with the choice saved in the browser
- Persistent dark and light themes
- Residential and commercial cleaning service information
- Gallery and About section with clearly identified illustrative stock photos
- Quote forms that open the visitor's email application and prepare a message to `renpointt@gmail.com`
- Bilingual privacy notice and service details
- Responsive navigation, keyboard-accessible FAQ accordion, and image lightbox
- Local business structured data for search engines

## Project files

- `index.html` — page structure, styles, translations, and interactions
- `privacy.html` and `privacy.css` — bilingual privacy notice
- `img/` — RenPointt logo and site icon assets
- `robots.txt` and `sitemap.xml` — search engine crawl and sitemap files

The page loads Google Fonts and stock photography from external services. The Google
Maps link opens an external map only when selected. An internet connection is needed
to display external resources.

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site to GitHub Pages
whenever changes are pushed to `main`. It can also be started manually from the
repository's **Actions** tab.

The quote and career forms use `mailto:` and do not submit to a server. Visitors need a
configured email application to send a request. The forms limit field lengths and
explain the email handoff before submission.

The Content Security Policy in `index.html` is a meta policy and allows inline scripts
and styles to support the current single-file design. It is not a substitute for
security headers configured by a server or CDN. GitHub Pages does not provide arbitrary
per-site response-header configuration through this repository.

## Before launch

- Confirm the canonical URL, Open Graph URL, `robots.txt`, and `sitemap.xml` match the
  production domain if it is not `https://www.renpointt.se/`.
- Confirm the address, map location, opening hours, and phone number are correct.
- Replace stock photography with permission-cleared photos of your own team and completed work when available.
- Add real customer reviews and links to the verified review profile; do not publish fabricated testimonials.
- Verify the legal business name, organisation number, privacy contact and email-retention practices for the privacy notice.
- Add confirmed pricing, insurance or certification details only after verifying the current information.
- Consider a server-side or managed form provider if you later want enquiries delivered without the visitor's email application; review its privacy and data-processing terms first.
