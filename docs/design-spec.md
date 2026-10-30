# Design Spec (approximate Swiggy tokens; verify against the live site via DevTools)

## Colours (define as CSS variables)
--swiggy-orange: #FC8019;
--hero-orange: #FF5200;        /* hero background, verify on live site */
--text-dark: #02060C;
--text-grey: #686B78;
--bg-white: #FFFFFF;
--bg-light: #F8F8F8;
--footer-bg: #02060C;
--btn-dark: #000000;
--border: #E9E9EB;

## Typography
- Font: "Proxima Nova" is proprietary. Use Google Font "Nunito Sans" or "Open Sans" with fallback: system-ui, Arial, sans-serif.
- Hero H1: 48-56px desktop (bold/800), ~28-32px mobile, white
- Section titles: 28-32px, bold, dark
- Body/links: 14-16px
- Card headings: ~28px bold; descriptions ~16px grey

## Layout
- Max content width: 1200px, centered, side padding 16px mobile / 24px+ desktop
- Header height ~80px, logo left, links + buttons right
- Hero: full width orange block, centered heading (max ~800px wide), search row below (location input + search input, ~50px tall, white, rounded 12-16px)
- Service cards: 3 columns, gap ~24px, tall cards with image filling the card, rounded corners ~16px, orange offer text
- Category items: circular images ~150px desktop, ~90-100px mobile (food); square rounded images for Instamart
- Footer: dark, 4-5 columns of links, app badges, social row, bottom copyright line

## Components
- Primary dark button: black bg, white text, rounded 14-16px, padding 14px 24px
- Outline/light button: white or transparent with border
- Inputs: white bg, 1px border, rounded, placeholder grey, icon on left (CSS or SVG)
- Cards: hover lift (transform: translateY(-4px) + shadow), transition 0.2s

## Assets Needed
- Swiggy logo (SVG), hero left/right illustrations (veggies, food, etc.)
- 3 service card images
- 6 food images (pizza, burger, biryani, cakes, north indian, south indian)
- 6 instamart images (vegetables, fruits, dairy, munchies, cold drinks, personal care)
- Google Play and App Store badges
- Social icons: Facebook, Instagram, Twitter/X, LinkedIn, Pinterest (SVG)