# PiggySpanx Site Template

This folder contains a simple, responsive parody‑card website built with a single HTML page and Tailwind CSS. The design features a hero banner, collections grid, new release highlights, an About section and a contact form. It’s meant to be a clean starting point for rebuilding your **PiggySpanx** site.

## Customizing Content

- **Replace the placeholder images.** The cards in the “Collections” and “New Releases” sections use placeholder images served from `via.placeholder.com`. Replace the image URLs with your own pictures stored in Wix’s Media Manager or hosted elsewhere. Ensure the URL uses HTTPS.
- **Update the copy.** Edit the headings and descriptions to reflect your actual collections, release dates and brand voice. Feel free to add or remove cards to fit your catalog.
- **Configure the contact form.** The contact form uses [Formspree](https://formspree.io/) for processing. Create a free Formspree form and replace `your-form-id` in the `<form action="https://formspree.io/f/your-form-id">` attribute with your own ID. If you prefer, you can swap the form for Wix’s built‑in contact form widget.

## Deploying the Site

Wix currently **does not support** importing a full site created outside of Wix【670371607197918†L59-L65】. To publish this template and display it on your `piggyspanx.com` domain, you have two options:

### Option 1 – Host externally and embed

1. **Deploy the site to an external host.** Services like Netlify, Vercel or GitHub Pages allow you to drag‑and‑drop a folder to get a secure HTTPS URL. Upload the contents of this folder and note the public URL of your new site.
2. **Embed the site in Wix.** Open your Wix Editor and go to **Add Elements → Embed Code → Popular Embeds**. Choose **Embed a site**【117063018981058†L87-L103】 and click to add it to your page.
3. **Enter your site URL.** Click the embed element, select **Enter Website Address**, paste the HTTPS URL of your deployed site and click **Apply**【117063018981058†L116-L125】.
4. **Adjust dimensions and publish.** Set the iframe’s width and height to `100%` so your site scales properly【117063018981058†L143-L167】, then save and publish your Wix site. Visitors will now see your externally hosted site within your Wix page.

### Option 2 – Recreate in Wix

1. **Start fresh in Wix.** Create a new Wix site using a blank template or a modern theme.
2. **Rebuild the layout.** Add a hero section with a background image, headline, tagline and call‑to‑action button. Create a three‑column **Collections** section, a **New Releases** section, an **About** section and a **Contact** section. Use Wix’s grid and section tools to mirror the layout in `index.html`.
3. **Upload your images.** Use Wix’s Media Manager to upload your product photos and artwork. Replace the placeholders with your own images.
4. **Add store functionality (optional).** If you intend to sell cards directly, install the Wix Stores app to manage products, inventory and checkout.
5. **Use Wix’s form widget for contact.** If you don’t want to use Formspree, drag a **Contact Form** element onto your page and configure the recipient email.
6. **Preview and publish.** Review your new design on desktop and mobile, then hit publish to make it live on your custom domain.

Either approach will give you a far cleaner and more organized site than your current one. Embedding an externally hosted site keeps development flexible, while rebuilding in Wix leverages Wix’s built‑in features for commerce and contact management.