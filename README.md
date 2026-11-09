# REPARO Mobile Care

Premium black-and-gold, mobile-first static website for REPARO Mobile Care, Vengola, Perumbavoor, Kerala.

## Included
- Responsive landing page and service cards
- Mobile and PC repair/service enquiries
- WhatsApp enquiry form (opens WhatsApp; no server-side storage)
- Click-to-call, email, Instagram and Vengola location search
- Firebase Hosting configuration

## Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase use --add
firebase deploy --only hosting
```

Choose the Firebase project for REPARO when prompted. Set the custom domain `reparoindia.com` in Firebase Hosting and follow its DNS verification instructions. Enable/confirm SSL after DNS verification.

## Important
The current GitHub build contains an SVG/CSS-style shield treatment to avoid missing binary assets. The original supplied PNG logo/emblem/banner are included in the companion ZIP from this conversation and can be added under `assets/` in a subsequent commit. Verify the shop pin and phone/Instagram details before public launch.
