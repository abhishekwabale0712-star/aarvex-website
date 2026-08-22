# AARVEX Website

Static HTML, CSS and vanilla JavaScript website for AARVEX. It is ready for GitHub and Vercel deployment with no build step.

## Run locally

Open the folder in VS Code, open `index.html`, then select **Open with Live Server**. You can also open `index.html` directly in a browser.

## Update business details

All editable contact values are in `js/script.js`, inside `AARVEX_CONFIG`. Replace the placeholder phone and WhatsApp values before launch. The form currently validates locally and shows a success state; replace the submit handler with Formspree, Web3Forms, or an API when enquiry delivery is required.

## Replace visuals and products

The current technical graphics are CSS illustrations. Put optimized `.webp` product or factory photos in `assets/images/`, then add them with meaningful `alt` text and `loading="lazy"`. Product content appears in the `#products` and `#bolt-types` sections of `index.html`.

## Deploy

1. Create a Git repository and push this folder to GitHub.
2. In Vercel, choose **Add New → Project** and import the repository.
3. This is a static site: leave build settings empty and deploy.
4. To connect a custom domain, use **Settings → Domains** in Vercel and apply the DNS records it provides.
