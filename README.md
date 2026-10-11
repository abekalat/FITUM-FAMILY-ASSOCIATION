# Fistum Family Association Website

A responsive bilingual (English/Amharic) static website for the Fitum Family Association.

## Preview locally
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or Safari.
3. Click **አማርኛ / English** to switch languages.

## Before publishing
Edit `index.html` and replace:
- `association@example.com` in the membership form script with the association's real email address.
- The contact placeholders with the official email, phone, and location.
- Sample event details with confirmed dates and locations.
- Sample gallery images with family-approved photos.
- Donation instructions only after the association has approved official payment details.

## Publish free with GitHub Pages
1. Sign in to GitHub or create an account.
2. Create a new public repository, for example `fitum-family-association`.
3. Upload `index.html` (and this README if desired) to the repository's root.
4. Open **Settings → Pages**.
5. Under build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will appear on the Pages settings screen.

Alternative: Netlify Drop can publish a static site by uploading the extracted website folder through Netlify's manual deploy interface.

## Important functional notes
- Navigation is mobile-friendly and collapses into a menu on smaller screens.
- English/Amharic language switching is built in.
- The registration form validates required fields and opens an email draft. It does not store or send data by itself. Change `association@example.com` to the correct recipient before launch.
- This is a static website. To store registrations in a database, accept online payments, or provide a private member portal, connect an appropriate backend or trusted form/payment service.
- External photo links need internet access. Replace with locally owned/approved images if preferred.
