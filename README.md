# Summit Web Studio Website

A professional, high-conversion one-page marketing website for a freelance web design business.

## Files

- `index.html` — Website structure and content sections
- `styles.css` — Premium visual styling and responsive layout
- `script.js` — Navigation behavior, scroll reveal, counters, and form validation

## Run Locally

Because this is a static site, you can open `index.html` directly in your browser.

If you want a local server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Customize Before Launch

Update these items in `index.html` to match your business:

- Brand name (`Summit Web Studio`)
- Contact email (`hello@yourstudio.com`)
- Client logos and testimonials
- Portfolio project descriptions and outcomes
- Service details and experience metrics

## Notes

- The contact form validates on the front end and sends submissions to a Google Apps Script web app endpoint.
- Update the `webAppUrl` constant in `script.js` if you deploy a new Apps Script URL.