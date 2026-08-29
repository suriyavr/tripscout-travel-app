<<<<<<< HEAD
# Trip_Advisor

A responsive, front-end clone of the [Tripadvisor](https://www.tripadvisor.in/) homepage, built with semantic HTML5 and SCSS. The project recreates the hero search experience, interest-based discovery rails, promotional banners, and footer of the live site, and is fully responsive from large desktops down to small phones.
=======
# TripScout

A responsive, front-end travel discovery UI built with semantic HTML5 and CSS. The project recreates a hero search experience, interest-based discovery rails, promotional banners, and footer, and is fully responsive from large desktops down to small phones.
>>>>>>> f436f8856dfb0b5e63bdd9a7e4b4f5014f190d4b

## Preview

| Section | Description |
|---|---|
| Header | Logo, "Plan with AI", Discover / Review / More nav, currency selector, Sign in |
| Hero | "Where to?" heading, category tabs (Search All / Things to Do / Hotels / Restaurants), search bar with "Ask AI" and "Search" |
| Promo carousel | Full-width promo card with image, floating user badge, and CTA button |
| Interest rails | Horizontally-scrolling card rows: Outdoor, Food, Culture, Water |
| Listing sections | Outdoor adventures, business travel, fine dining, and "explore near you" cards with ratings, pricing, and a "next" carousel control |
<<<<<<< HEAD
| Kiva donation banner | Full-bleed image with left-aligned copy and a "Donate now" CTA |
=======
| Donation banner | Full-bleed image with left-aligned copy and a "Donate now" CTA |
>>>>>>> f436f8856dfb0b5e63bdd9a7e4b4f5014f190d4b
| All ages / Iconic places | Family-friendly picks and iconic destination cards |
| Wanderer spotlight | Sponsored video-series promo |
| Traveller's Choice Awards | Full-bleed dark banner with badge, heading, and CTA |
| Footer | Multi-column site links, "Get The App", legal links, currency/region selectors, social icons, and locale disclaimer |

## Tech Stack

- **HTML5** — semantic markup for every section
- **CSS3** — all styling in a single `style.css` file
- **Font Awesome 7** — icons (via CDN)
- No JavaScript framework — this is a static markup + styling exercise

## Project Structure

```
<<<<<<< HEAD
Trip_Advisor/
├── index.html          # Page markup
├── style.css            # All styling
├── Images/             # Local image assets referenced by index.html
=======
tripscout-travel-app/
├── index.html          # Page markup
├── style.css            # All styling
├── Images/             # Local image assets referenced by index.html
│   ├── tripscout-logo.svg   # Header wordmark logo
│   └── tripscout-icon.svg   # Compact square mark for inline badges
>>>>>>> f436f8856dfb0b5e63bdd9a7e4b4f5014f190d4b
└── README.md
```

## Responsive Breakpoints

| Max-width | Target |
|---|---|
| 1440px | Large desktops |
| 1280px | Small laptops |
| 1024px | Tablets |
| 767px | Large phones |
| 480px | Small phones |

## Getting Started

1. Clone or download this repository.
2. Open `index.html` directly in a browser — no server or build step required.
3. Make sure the `Images/` folder sits next to `index.html`, since all images are referenced with relative paths (`./Images/...`).

## Notes

<<<<<<< HEAD
- This is a static UI recreation for learning/demo purposes and is not affiliated with or endorsed by Tripadvisor.
=======
- This is an original static UI project for learning/demo purposes.
>>>>>>> f436f8856dfb0b5e63bdd9a7e4b4f5014f190d4b
- The carousel "next" arrow on the "Explore experiences near Bengaluru" row is styled to match the reference design but is not yet wired to scroll behavior — see open items below.

## Open Items

- [ ] Wire up the carousel arrow buttons to actually scroll their card rows
- [ ] Make the currency/region footer selectors functional dropdowns
- [ ] Replace placeholder `href="#"` links with real destinations
