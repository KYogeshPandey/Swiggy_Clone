# Swiggy Landing Page Clone: Requirements

## Goal
Responsive, static clone of https://www.swiggy.com/ homepage. Visual fidelity only; no functionality.

## Hard Constraints
- HTML5 + CSS3 ONLY. No JavaScript, no frameworks, no CSS libraries, no <script> tags.
- Deliverables: index.html, style.css, assets/ (images + icons), screenshots.
- Do NOT use a full-page screenshot as a background. Every section is real HTML + CSS.
- Use Flexbox and CSS Grid. Use media queries for responsiveness.
- No horizontal scroll, overlap, or cut-off content at any width (320px to 1920px).
- Clean, semantic, well-commented code.

## Folder Structure
project/
├── index.html
├── style.css
├── assets/
│   ├── images/   (hero, service cards, food, instamart, app badges)
│   └── icons/    (logo, social icons, UI icons as .svg)
└── screenshots/  (desktop.png, tablet.png, mobile.png)

## Sections (build in this order)
1. Header: Swiggy logo, "Swiggy Corporate", "Partner with us", "Get the App" button, "Sign in" button (dark/black).
2. Hero: orange background, big heading "Order food & groceries. Discover best restaurants. Swiggy it!", location input, search input, food/grocery illustrations on left and right sides.
3. Service cards (3): Food Delivery, Instamart, Dineout. Image + heading + description + offer text.
4. "Order our best food options": Pizza, Burger, Biryani, Cakes, North Indian, South Indian (circular/rounded image + name).
5. "Shop groceries on Instamart": Fresh Vegetables, Fresh Fruits, Dairy, Munchies, Cold Drinks, Personal Care (rounded-card image + name).
6. Footer: dark background. Company links, Contact/Legal links, "We deliver to" city links (Bangalore, Gurgaon, Hyderabad, Delhi, Mumbai, Pune...), app download badges, social icons, copyright.

## Responsive Behavior
| Breakpoint | Behavior |
|---|---|
| >= 1024px (desktop) | Full nav, hero with side illustrations, 3 cards in a row, 6-column category grid, multi-column footer |
| 768px to 1023px (tablet) | Hero illustrations shrink, cards in 3 narrow columns or 2+1, category grid 3 columns, footer 2-3 columns |
| <= 767px (mobile) | Nav condenses (logo + Sign in; other links stacked or hidden via CSS only), hero illustrations hidden/minimised, search fields stack vertically, cards stack 1 column, categories in 2-3 column grid, footer stacks |

## No-JS Mobile Nav Rule
If a hamburger is wanted, use the CSS-only checkbox hack (<input type="checkbox"> + <label> + :checked sibling selector). Otherwise simply wrap/hide secondary links on mobile.

## Acceptance Checklist
- [ ] Looks like Swiggy at 1440px
- [ ] No horizontal scroll at 320, 375, 768, 1024, 1440px
- [ ] All images have alt text and fixed aspect ratios
- [ ] Zero JavaScript
- [ ] CSS uses variables for colours and fonts
- [ ] Hover states on buttons, links, cards
- [ ] Valid, semantic HTML (header, main, section, footer, nav)