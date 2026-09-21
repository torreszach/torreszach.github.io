# Zach Torres NFC Contact Card

A lightweight mobile-first digital business card designed for an NFC tag and QR-code destination.

## Publish with GitHub Pages

1. Create a new public GitHub repository (for example `contact`).
2. Upload everything in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. GitHub will provide the live HTTPS URL. Test it on both iPhone and Android.

## Program the NFC tag

Write only the final HTTPS GitHub Pages URL to the NFC tag as a URL/URI record. This lets you change the page or contact details later without rewriting the tag.

Example: `https://YOUR-USERNAME.github.io/contact/`

After testing, optionally lock the NFC tag to prevent accidental rewriting. Locking is permanent, so only do this once the URL is final.

## Updating contact information

Edit both:
- `index.html` for what visitors see.
- `contact.vcf` for what is saved to their contacts.

## Files

- `index.html` — mobile contact page
- `style.css` — responsive light/dark styling
- `contact.vcf` — downloadable contact card
- `assets/zach-torres.jpg` — profile photo

## Optional next steps

Add a custom domain, a QR code to a printed card, analytics, or an embedded profile photo in the vCard.
