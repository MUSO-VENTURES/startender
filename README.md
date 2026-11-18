# STARTENDER Bar Guide

A bartender's field guide that runs in the browser and installs on iPhone and iPad like an app.

- **Allergy check:** ask every guest first. 13 allergens (the 9 major ones plus sulfites, citrus, coconut, celery), guest self-entry, avoid and check-first lists for drinks and dishes, cross-contact steps for the bar
- **Recipes:** 48 classics and modern classics with garnish prep, batch scaling and step check-off
- **Regulars:** their usual and exactly how they take it, interests and talking points, consented photo, guest rating, tailored drink suggestions
- **Group table:** add regulars and walk-ins or pass the device around; picks for each person, one round for the whole table with a zero-proof match, and dishes safe for everyone
- **Food pairing:** drink for their food, or food for their drink, tuned to a regular's taste and allergies
- **DZ menu:** Doppio Zero cocktails, zero-proof, beer and wine with pairings (from the published Walnut Creek drinks menu, Nov 2026)
- **Guest feedback:** hand-to-guest rating screen with quick comments and a results summary
- **Pour test:** free-pour accuracy trainer with spout calibration
- **Add a drink:** checklist builder for house specialties and bartender signatures

## Privacy

Everything you enter (regulars, photos, ratings, feedback) is stored **only in the browser on that device**. Nothing is sent to a server, and nothing about guests is in this repo. Use **Back up data** at the bottom of any page to save a JSON backup, and **Restore backup** to move it to another device.

## Deploy on GitHub Pages

1. Create a repo (for example `startender`) and upload everything in this folder, including `.nojekyll`.
2. Repo **Settings > Pages**: Source **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. Your app lives at `https://<your-user-or-org>.github.io/startender/` a minute later.

## Install on iPhone or iPad

1. Open the Pages URL in **Safari**.
2. Tap **Share > Add to Home Screen**.
3. Launch it from the home screen. It opens full screen and keeps working offline after the first visit.

Home screen apps keep their data. Plain Safari tabs can have site data cleared by iOS after weeks of no use, so install it and back up now and then.

## Updating

Replace `index.html`, then bump `VERSION` in `sw.js` (for example `startender-v2`) so installed copies pick up the change.

Built by MUSO VENTURES.
