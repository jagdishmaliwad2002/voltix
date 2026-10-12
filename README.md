# Voltix – Tech For A Brighter You

A modern, responsive e-commerce homepage for an electronics store, built with plain HTML, CSS and JavaScript. No frameworks or build tools needed.

**Created by Jagdish Maliwad**

---

## Preview

Open `index.html` in any modern browser. Everything, including the product images, is embedded in that single file.

## Features

- **Hero slider** with three auto-rotating messages and clickable dots
- **Shop by Category** tiles: Laptops, iPhone, Android, Foldables, Desktops, Cases
- **Featured Collections** and promotional banners
- **Trending Now** grid with 12 products, star ratings and prices
- **Add to Cart** with a live cart counter and toast notification
- **Wishlist hearts** that toggle on each product
- **Sticky header** with blur effect and scroll shadow
- **Scroll reveal** animations and smooth hover effects
- **Newsletter** signup form and full footer with app download links
- **Responsive** layout for desktop, tablet and mobile
- Respects the `prefers-reduced-motion` accessibility setting

## Project Structure

```
.
├── index.html   # Complete site (HTML + CSS + JS + embedded images)
└── README.md    # This file
```

## Getting Started

1. Download `index.html`.
2. Double-click it to open in your browser.

To serve it locally instead:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customization

| What to change | Where |
| --- | --- |
| Colors | CSS variables in `:root` (`--blue`, `--dark`, `--ink`) |
| Font | Google Fonts `<link>` in `<head>` (currently Inter) |
| Hero slide text | `sl` array in the script at the bottom of `index.html` |
| Products, names, prices | `.prod` blocks inside the "Trending Now" section |
| Images | Replace the `src` of any `<img>` with a file path or URL |

> Product names, ratings and prices are placeholders. Replace them with your real data.

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, custom properties, transitions)
- Vanilla JavaScript (IntersectionObserver, DOM events)
- Google Fonts (Inter)

## Notes

- The Add to Cart, wishlist and newsletter features are front-end only. Connect them to a backend or cart service for a live store.
- Product images are embedded as base64 for portability, which makes the file larger. For production, move them to separate optimized image files.
- Brand names and product images belong to their respective owners and are used here for demonstration purposes only.

## Author

**Jagdish Maliwad**

## License

Free to use and modify for personal and learning projects. Please keep the author credit.
