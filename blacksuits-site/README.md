# Black Suits — Digital Catalog (demo)

A single-file catalog and booking site for **Black Suits by Biry Elshafaay** (Cairo).
No build step, no dependencies to install: open `index.html` in a browser.

## What it does
- Catalog of suits with prices in EGP and a size picker (EU 48, 50, 52, 54)
- Fabric showcase and the 3-day custom suit service
- Booking flow: occasion, event date, service, fabric, fitting time, name
- Every order or booking opens WhatsApp with the details already written

## Edit the content
Everything lives in the `<script>` at the bottom of `index.html`:

| What | Where |
| --- | --- |
| WhatsApp number | `WHATSAPP_NUMBER` (country code, digits only) |
| Suits, prices, descriptions | `PRODUCTS` array |
| Sizes | `SIZES` array |
| Fabrics | `FABRICS` array |
| Opening hours and address | the contact section and the footer |

Prices and product names are **sample content** until replaced with the real ones.

## Deploy
- **Vercel:** import this repository, framework preset "Other", no build command. Deploy.
- **GitHub Pages:** Settings, Pages, deploy from branch `main`, folder `/ (root)`.
- **Netlify:** drag the folder onto app.netlify.com/drop.

## Notes
- `index.html` includes `noindex` so the demo stays out of Google. Remove that meta tag at launch.
- Logos and signage belong to Black Suits / Biry Fashion.
