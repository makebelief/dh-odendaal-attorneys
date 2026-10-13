# DH Odendaal Attorneys — Independent website concept

## Deployment

This is a static HTML/CSS/JavaScript site. No build tool or dependencies.

1. From this folder, run `python3 -m http.server 8000` for local preview (visit http://localhost:8000).
2. Use Vercel `Other` framework, project root `.` and output directory `.`.
3. For production run `npx vercel --prod`.

## Content

- Business details are drawn from the user-supplied attorneys.co.za screenshots and publicly available directory descriptions.
- Practice established in 2025; founder/director: Dawid Hercules Odendaal.
- Contact number +27 73 235 5558; email dawid@dhoattorneys.com; address 138 Rossini Boulevard, SW 2, Vanderbijlpark, Gauteng, 1911, South Africa.
- WhatsApp uses the listed mobile number; whether the mobile number is WhatsApp-registered has not been independently verified.
- Office exterior image, attorney portrait and logos are user-supplied. Supplied portrait displayed once on Home and once on Our Attorney page.
- The high-resolution 4K logo is a raster enlargement of supplied artwork, not a vector original. Footer logo has a fully transparent background.
- No artificial image generation used.
- Pexels photos are externally hosted; verify all external images and copyrights before official publication.
- The contact form prepares an email draft locally. No server-side submission is configured.
- Search indexing is disabled until the firm approves the demo. Before authorisation, do not represent this as the firm's official website.
- If Vercel uses a different hostname from https://dh-odendaal-attorneys.vercel.app, update meta canonical and sitemap links and structured business data.

## Official handover checks

Confirm correct spelling and contact details, director's biography, published services, location pin, media permissions, Google Maps, POPIA/privacy notice, and domain ownership. Obtain permission before representing this site as official.

## Source references

- https://www.attorneys.co.za/ResultsPage.asp?AreaID=134&LanguageID=-1&RegionID=14&sMode=C
- https://www.findglocal.com/ZA/Vanderbijlpark/1493271-15


## Mobile design consistency update (13 October 2026)
This build retains the same law-firm template used for the other websites:
responsive white navigation, standard mobile menu, image-led homepage, correctly
cropped photographs and **one circular floating WhatsApp icon**.

A screenshot supplied for comparison displayed the address `attorneys.vercel.app`,
which is *not* the domain linked to the DH Odendaal project in the connected
Vercel account. That screenshot's EN/AF toggle and fixed bottom Call/WhatsApp
bar do not exist in this codebase. If those elements still appear after deploying
this release, check the exact hostname and Vercel project being viewed.
