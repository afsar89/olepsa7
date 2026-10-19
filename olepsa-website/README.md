# Olepsa website

Source for [www.olepsa.com](https://www.olepsa.com), the Olepsa web design and development agency site.

It is a static site: plain HTML, CSS and a little JavaScript. There is no build step and nothing to install.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: design, content, enquiry form and structured data |
| `404.html` | Page shown for unknown addresses |
| `robots.txt` | Crawler rules and sitemap location |
| `sitemap.xml` | Page list for search engines |
| `og-image.png` | Image shown when the link is shared (1200 x 630) |
| `favicon.ico`, `favicon.svg` | Browser tab icon |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest` | Phone and app icons |
| `vercel.json` | Security headers and caching for Vercel |

Everything in this repository is public on the website, so keep private files out of it.

## Deploy on Vercel

1. In Vercel choose **Add New > Project** and import this repository.
2. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy. Every commit to the `main` branch then redeploys the site automatically.

## Editing

Open `index.html` on GitHub, press the pencil icon, change the text, and commit. The live site updates within a minute.

## Analytics

Google Analytics 4 is installed in the `<head>` of `index.html` with measurement ID `G-RG04D718N0`. To point it at a different property, replace that ID in the two places it appears.

## Enquiry form

The form posts to FormSubmit, which emails `info@olepsa.com`. The address needs a one-time activation: submit a test enquiry and click the link FormSubmit sends to that inbox.
