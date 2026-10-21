# RenPointt Service

A responsive, single-page website for RenPointt Service, a cleaning company serving Stockholm.
The page is built with HTML, CSS, and vanilla JavaScript in `index.html`.

## Features

- English and Swedish language selection, with the choice saved in the browser
- Persistent dark and light themes
- Residential and commercial cleaning service information
- Gallery and About section with illustrative cleaning photos
- Quote forms that open the visitor's email application and prepare a message to `renpointt@gmail.com`
- Responsive navigation, FAQ accordion, image lightbox, and Google Maps embed

## Project files

- `index.html` — page structure, styles, translations, and interactions
- `img/` — RenPointt logo and site icon assets
- `robots.txt` and `sitemap.xml` — search engine crawl and sitemap files

The page loads Google Fonts, map content, and stock photography from external services.
An internet connection is needed to display those resources.

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

## Publish with GitHub Pages

1. Push the project files to the repository's `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Set the deployment source to the `main` branch and the repository root.

The quote forms use `mailto:` and do not submit to a server. Visitors need a configured
email application to send a request.

## Before launch

- Confirm the canonical URL, Open Graph URL, `robots.txt`, and `sitemap.xml` match the
  production domain if it is not `https://www.renpointt.se/`.
- Confirm the address, map location, opening hours, and phone number are correct.
- Replace stock photography with photos of your own team and completed work when available.
