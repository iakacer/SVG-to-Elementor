# SVG to Elementor

A super simple, no-fuss, single file HTML tool to make your SVGs play nice with Elementor. 

## Why does this exist?
Elementor needs SVGs to be "clean" to manipulate them via CSS. If your SVG has hard-coded `width`, `height`, or inline `fill`/`stroke` attributes (which Figma, Illustrator, and Inkscape love to add), Elementor's styling gets overridden. 

This tool strips out the stubborn code and preps it for the web.

## Features
* **Zero Dependencies:** It's just one single `index.html` file. No `npm install`, no servers, no BS. Everything runs locally in your browser.
* **Drag & Drop Magic:** Drop a single `.svg` or drop 50 of them at once in the batch zone.
* **Auto-Cleanup:** Automatically removes bulky metadata (looking at you, Illustrator & Inkscape).
* **Elementor Ready:** * Strips hard-coded `width` & `height`.
    * Preserves or generates the `viewBox` for perfect scaling.
    * Injects `fill="currentColor"` into the root.
    * Nukes inline styles and colors from all child paths.
* **One-Click Export:** Copy the raw code or download the optimized `.svg` files instantly.

Notice: this tool was made with the use of AI.
