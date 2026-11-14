# 🍔 Fast Food 3D Playground

A goofy little 3D toy: pick a fast food item, spin it, blow it apart, drop it on the table, and take bites out of it. Works on phones and desktop and runs right in the browser, nothing to install.

Made for friends, not for anything serious.

## The menu

| Item | "Brand" |
|---|---|
| $1.50 Hot Dog | Bostco |
| Whooper | Burger Kling |
| Large Stuffed Crust Canadian Pizza | Father Jonathan's |
| Apple Fritter | Countree Style |
| Bagel | Countree Style |
| Wood Oven Bagel | Wood Oven |
| Poutine | St. Lewis Wingz |
| Cereal Milk Latte | Dippin' |

## How to play

- **Drag** to spin, **pinch / scroll** to zoom
- **Tap the food** to take a bite (crumbs fly, phone buzzes)
- **Tap the latte** to stir it
- **⟳ Spin** turns auto-rotate on or off
- **💥 Explode** pulls the layers apart
- **⬇ Drop** drops it on the table
- **♻ Fresh one** gives you a new, unbitten copy

## Put it on GitHub Pages

1. Create a new repo (e.g. `fast-food-3d`).
2. Upload `index.html` and this `README.md`.
3. Go to **Settings → Pages → Branch: `main` / root → Save**.
4. After about a minute it's live at `https://markfourman.github.io/fast-food-3d/`.

## How it's built

- One `index.html` file using [three.js](https://threejs.org/) (r160), loaded from a CDN
- Every food is built in code (no 3D model downloads), so it loads fast on mobile data
- Realistic-ish lighting with surfaces that look shiny, glazed, soft or see-through
- Logos are drawn live on an HTML canvas

## Disclaimer

Parody / fan project. All brand names are deliberately misspelled jokes, and the logos are original designs. Not affiliated with, endorsed by, or connected to any real restaurant or company. Please don't sue a hot dog app.
