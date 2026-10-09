# Life Launch Coach — Android setup guide

This is a static website starter: HTML + CSS + JavaScript. It does not need a paid framework or database to preview.

## Files included
- `index.html` — homepage
- `mind-soul.html` — mindset and wellbeing education
- `career-wealth.html` — career and business skills
- `heritage.html` — Meitei heritage, traditions and belief systems
- `products.html` — ₹149 starter product and ₹199/₹499 guidance offer display
- `community.html` — registration interest form demo
- `contact.html` — contact page
- `privacy.html` — starter privacy and terms text
- `assets/css/style.css` — responsive visual design
- `assets/js/app.js` — language switch, mobile menu and form demo

## Important: configure before public launch
1. Open `assets/js/app.js` and find `const phone=window.LLC_WHATSAPP_NUMBER||'91XXXXXXXXXX'`.
2. Replace `91XXXXXXXXXX` with your WhatsApp number, digits only, including country code. Example format: `919876543210` (example only; do not use this unless it is your number).
3. Search every HTML file for `91XXXXXXXXXX` and replace the WhatsApp floating-button link too.
4. In `products.html`, set the actual launch offer start and end dates. The offer should run for exactly seven calendar days; don't claim it ends on a date until the date is decided.
5. Replace demo product/contact details with the exact content you can deliver.
6. Add your real payment checkout URLs only after setting up a provider. No payment processor is connected in this starter.
7. Test every page and link on your phone before announcing the site.

## Android-friendly GitHub upload
1. Open GitHub in your mobile browser and sign in.
2. Open your repository: `Life-Launch-Coach-`.
3. If you want to preserve your existing work, first open the repository and download a backup or create a new branch before replacing any files.
4. Upload the files/folders from this project. GitHub mobile file upload can be awkward for folders; if needed, use GitHub's web interface from Chrome with Desktop site enabled, or upload files one at a time.
5. Commit changes only after checking the file names and contents.
6. For free hosting, use GitHub Pages: repository Settings → Pages → deploy from the `main` branch and `/ (root)`, then Save. The public URL will appear in the Pages settings after deployment.

## Current limits
- The registration form is a demo and opens WhatsApp only after you configure the number. It does not save submissions to a database.
- Checkout/payment is not connected.
- No user login, private dashboard or booking system exists yet.
- Meiteilon translation is a starter translation for key homepage text; some page-specific content remains in English and needs review by a fluent speaker.
- External Google Fonts need internet access; fallback fonts are included.

## Responsible presentation
Health pages are educational only. Do not promise diagnosis, cure, guaranteed spiritual protection, guaranteed income or guaranteed destiny outcomes. Explain exact package inclusions, real offer dates, refund terms and any fees before taking payment.
