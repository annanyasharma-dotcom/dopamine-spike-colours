# Dopamine Spike Colours

A colour gallery for **Dopamine**, the Tata 1mg design system, by Annanya Sharma.

The site opens on a landing page. **Explore colours** opens a gallery of every palette in the system:

- **Primitives:** 13 colour families (flame coral, cool neutral, vital red and the rest), each step with HEX, RGB, CMYK, HSL and its token name.
- **Semantic tokens:** grouped as in the Figma Semantic collection (Background, Text, Icon, Border). Each token shows the primitive it maps to.
- **Utility:** Health status (`HIH/*`) and business category colours.
- **Type:** the 39 text styles in Figtree (Display, Headings, Label, Body, Caption & Footnote), each shown as a live specimen with copyable CSS, plus the six elevation shadows.
- **Layout:** corner radius (9 steps), stroke width (6) and gap (16) from the Extra collection, each drawn to scale with copyable CSS.

Every palette shows its contrast stats (max contrast, AA text pairs, colour-blind safe pairs) and a contrast grid. You can copy any value, or a palette as CSS or JSON.

## Run it

`index.html` is a single self-contained file with no build step. Open it in a browser, or serve the folder:

```sh
npx serve .
```

To publish with GitHub Pages: **Settings → Pages → Deploy from branch → `main` / root**.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The site: landing page and gallery |
| `tokens/` | Figma variable exports (Primitives, Semantic, Utility, Extra) `extra.tokens.json` (radius, stroke and gap in W3C format) and `typography.css` with the text-size and effect styles |
| `assets/` | Dopamine spike logo, dark-ink and white-ink versions |
