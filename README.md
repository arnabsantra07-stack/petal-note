# Petal Note — Digital Bouquet starter

A responsive digital bouquet builder built with React + Vite. It lets a sender choose flowers, personalize a letter, preview it, and create a shareable URL.

## Run locally
1. Install Node.js (LTS).
2. In this folder, run `npm install`
3. Run `npm run dev`
4. Open the local URL printed in your terminal.

## Build and deploy
1. Run `npm run build`.
2. Deploy this project to Vercel (or another static host) by importing the Git repository.
3. In Vercel, keep the framework preset as Vite and the build command `npm run build`; output directory `dist`.
4. After deployment, open the live site and create a bouquet. The generated URL includes the bouquet data after `#b=`.

## Important
- This starter does not use a database. Bouquet details are encoded into the share URL, so links work on different devices as long as the link is kept intact.
- The bouquet data is not stored in a central account or dashboard. There is no server-side list of all created bouquets.
- Because the message is in the URL, anyone with the link can read it. Don't include sensitive private information.
- The flower illustrations use emoji-style blooms and CSS animation as a simple starter. You can replace them with custom SVG/PNG floral artwork later.
- Google Fonts are loaded from the internet; system fallbacks are included.
