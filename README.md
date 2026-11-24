# Neha — Under the Moon | Lakeside Birthday Website

A single-file, responsive HTML birthday surprise with a photo-based moonlit lake and couple, a cartoon-cardboard warning stamp, and five interactive sections.

## Open it
Double-click `index.html`, or open it in Visual Studio Code and use Live Server.

## What's new in this revision
- Consistent silver-blue moonlight palette across **every** section
- **No rain animations** (the baarish reference remains in the shayari, exactly as requested)
- Cardboard parcel with a stamped message: `childish heart inside, handle with care`
- **Unwrap the surprise** opens an actual birthday-letter dialog; selecting **let me show you** takes Neha into the rest of the site
- Personalized, photorealistic moonlit lakeside image based on your real lake and photos; the couple is shown from behind, her head resting on his shoulder and his arm around her
- Toggle to see your original real-life lake photo
- **Five real photos** across clickable activity cards: inline skating, gym, baarish, pets (black goat), and makeup / festive outfit
- Your actual shared selfie appears in the spontaneous trip section
- Image assets live in the `assets/` folder: upload the whole folder with `index.html`; do not upload HTML alone
- Spontaneous trips cycle through **Dasham Falls, Palna Dam, Ranchi Lake, Netarhat Sunset Point, Puri Beach**, with Google Maps search links
- Exact user-provided Hindi shayari preserved
- Birthday wish popup with a text box, optional on-device saving, confetti, and an explicit Share button

## About the birthday wish
GitHub Pages is static hosting. **It cannot automatically save what someone types to your account.**

By default:
1. Neha can type a wish and click **seal my wish**. This saves it only in **her** browser's local storage when supported.
2. She can click **share my wish**. Her device's share sheet will open (or the wish will be copied), so she chooses what to send and whom to send it to.
3. Nothing is silently collected or transmitted.

### Optional: receive the wish through Formspree
To receive the wish in your own inbox after she explicitly clicks **share my wish**:
1. Create a form at https://formspree.io/ and activate it.
2. Find `const WISH_FORM_ENDPOINT = '';` near the beginning of the JavaScript in `index.html`.
3. Paste your **own** form endpoint URL as the value (e.g. `https://formspree.io/f/your-form-id`).
4. Test it before sharing the site. Submission happens only on the visitor's explicit **share my wish** click.

Do not put API secrets in public GitHub Pages files.

## Birthday and birth year
The date is set to **25 November 2026**, India time. **2003 is not shown anywhere** because her birth year still needs confirmation.

## Host on GitHub Pages
Create a GitHub repository, upload `index.html` **and the `assets` folder**, then use **Settings → Pages → Deploy from a branch → main / (root)**. Since the website is public, avoid adding personal information that should remain private.

## Photo clarity update (24 November 2026)
All eight images in `assets/` have been processed using gentle noise reduction, local contrast, sharpening, and higher-resolution output for sharper high-DPI display. The source subjects and the existing website interactions and text remain unchanged. Motion blur or missing detail in the original photos cannot be completely reconstructed.
