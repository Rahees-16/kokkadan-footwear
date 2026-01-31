# Kokkadan Footwear Website

## Project Overview
Static website for Kokkadan Footwear, a family-owned retail shop in Edakkara, Kerala, India. Established in 1975, serving the community for 50+ years.

## Tech Stack
- HTML5, CSS3, JavaScript (vanilla)
- No frameworks - pure static site
- Hosted on GitHub Pages

## Directory Structure
```
kokkadan-footwear/
├── css/
│   └── styles.css       # Main stylesheet with CSS variables
├── js/
│   └── main.js          # Mobile menu, smooth scroll
├── brands_products/              # Brand logos & product images
│   ├── bata.png
│   ├── vkc.png
│   ├── sparx.png
│   ├── paragon.png
│   ├── flite.png
│   ├── walkroo.png
│   ├── skybags.png
│   ├── americanTourister.png
│   ├── aristocrat.png
│   ├── popy.png
│   ├── johns.png
│   ├── kitex.png
│   ├── schoolbag.png
│   ├── ladies_bag.png
│   ├── umberalla.png
│   ├── belts.png
│   └── sports.png
├── index.html           # Home page
├── products.html        # All products page
├── about.html           # About us page
├── contact.html         # Contact page with map
├── CLAUDE.md            # This file
└── README.md            # Project readme
```

## Pages
| Page | Description |
|------|-------------|
| `index.html` | Home page with hero, categories, brands |
| `products.html` | Product showcase (shoes, chappals, bags, school bags, boots, safety shoes) |
| `about.html` | About the business, 50+ years history |
| `contact.html` | Contact info, map, WhatsApp enquiry |

## Key Features
- Responsive design (mobile-first)
- WhatsApp integration for inquiries
- Google Maps integration
- Brand logos showcase (12 brands)
- Simple 4-page navigation

## Color Scheme
- Primary: #6B2D2D (Maroon)
- Secondary: #D4A847 (Gold)
- Background: #F9F6F0 (Cream)

## Brands (with logos)
- **Footwear**: Bata, VKC, Sparx, Paragon, Flite, Walkaroo
- **Bags**: Skybags, American Tourister, Aristocrat
- **Umbrellas**: Popy, Johns
- **Other**: Kitex

## Product Categories
- Shoes
- Chappals & Slippers
- School Bags
- Ladies Bags
- Umbrellas
- Belts
- Sports Goods
- Travel Bags

## Contact Info
- Phone: +91 94473 18825, +91 94478 15783
- Hours: 9:45 AM - 9:30 PM, 7 days a week
- Location: Main Road, Edakkara, Malappuram, Kerala - 679331

## Development Notes
- Product images use Unsplash stock photos
- Brand logos stored locally in `/brands_products/` folder
- WhatsApp links pre-fill inquiry messages

## Commands
```bash
# Serve locally (Python)
python -m http.server 8000

# Or with Node
npx serve .
```

## Live Site
https://rahees-16.github.io/kokkadan-footwear/
