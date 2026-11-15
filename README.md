# 🍔 Fast Food 3D Playground

A goofy 3D toy for phones and desktop: pick a fast food item, spin it, blow it apart with real physics, drop it, and take bites out of it. Runs right in the browser, nothing to install.

Made for friends, not for anything serious.

## The menu

|Item|"Brand"|
|-|-|
|$1.50 Hot Dog|Bostco|
|Whooper|Burger Kling|
|Large Stuffed Crust Canadian Pizza|Father Jonathan's|
|Apple Fritter|Countree Style|
|Bagel|Countree Style|
|Wood Oven Bagel|Wood Oven|
|Poutine|St. Lewis Wingz|
|Cereal Milk Latte|Dippin'|
|Chicken Sandwich|Popeyez|
|Sushi Combo|Sanno Sushi|
|Chicken Nuggets|McDougalds|

## How to play

* **Drag** to spin, **pinch / scroll** to zoom
* **Tap the food** to take a bite (crumbs fly, phone buzzes, every 5th bite is a combo)
* **Tap the latte** to stir it
* **⟳ Spin** turns auto-rotate on or off (off by default)
* **💥 Explode** blasts every piece and topping across the table with gravity and bounces. Tap **🧩 Rebuild** to pull it back together. While it's exploded, tap a piece to flick it.
* **⬇ Drop** drops it on the table with a squish
* **♻ Fresh** gives you a new, unbitten copy
* **🔊** top-left mutes the sounds

## Put it on GitHub Pages

1. Create a new repo (e.g. `fast-food-3d`).
2. Upload `index.html` and this `README.md`.
3. Go to **Settings → Pages → Branch: `main` / root → Save**.
4. After about a minute it's live at `https://markfourman.github.io/fast-food-3d/`.

## How it's built

* One `index.html` using [three.js](https://threejs.org/) (r160) from a CDN
* Every food is built in code (no model downloads), so it loads fast on mobile data
* Each item is cached after first build, and the others are built in the background so switching is instant
* A small custom physics loop handles the explosion (gravity, bounces, friction, rebuild)
* Sounds are synthesised in the browser, no audio files

## Disclaimer

Parody / fan project. All brand names are deliberately misspelled jokes and the logos are original designs. Not affiliated with, endorsed by, or connected to any real restaurant or company.

