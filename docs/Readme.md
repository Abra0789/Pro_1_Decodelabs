# Brew & Bean — Project 1: Static Webpage Design

DecodeLabs Frontend Development Industrial Training (Batch 2026)

A 4-page static website for a fictional coffee shop, built with plain HTML5 and CSS3 — no frameworks, no JavaScript.

## Pages

- `index.html` — Home (hero, Popular Picks, Our Story)
- `about.html` — About (How We Started, What We Stand For)
- `menu.html` — Menu (Drinks, Pastries & Bakes)
- `contact.html` — Contact (info, map, message form)

## Structure

```
Pro_1/
├── index.html
├── about.html
├── menu.html
├── contact.html
├── css/
│   └── style.css
└── images/
    ├── cappuccino.jpg
    ├── Cold Brew.jpg
    ├── latte.jpg
    ├── croissant.jpg
    ├── Blueberry Muffin.jpg
    ├── Chocolate Chip Cookie.jpg
    ├── Our Story.jpg
    ├── Hero.jpg
    └── barista.jpg
```

> The `images/` folder needs the actual photo files added locally (exact filenames above) before Git will have anything to track in that folder — an empty folder isn't picked up by Git on its own.

## Build notes

- One shared stylesheet, `css/style.css` — BEM naming, no ID selectors, no inline styles.
- CSS Grid for page-level layout, Flexbox for components.
- Semantic landmarks (`header`, `main`, `footer`), one `<h1>` per page, no skipped heading levels.
- Accessible: alt text on every image, labelled form fields, visible focus states, `prefers-reduced-motion` respected.

## Viewing locally

Just open `index.html` in a browser — no build step, no server, no dependencies.
