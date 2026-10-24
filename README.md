# Satark — Diva

The website for Diva, Satark's cold plasma straw treatment drum. It is built for desktop screens.

It is a static page with inline CSS and JS: no framework, no build step, and no outside requests at runtime. GitHub Pages serves it directly from this `gh-pages` branch.

## Run it locally

```bash
python -m http.server 8080
```

Then open http://localhost:8080. Opening `index.html` directly from disk also works.

## What is on the page

1. **Hero:** a full-screen stage with six chapters on the left rail (DIVA, PLASMA, INSIDE, HARVEST, FIELD, ORIGIN). Each chapter moves the camera over the drum, which is drawn in the page, and swaps the headline and paragraph.
2. **About Diva**
3. **Inside the drum:** scrolling takes the drum apart and labels every part.
4. **How it works:** collect, treat, return, with the harvester drawing.
5. **Benefits**
6. **Why it matters:** the burning problem in numbers.
7. **Team**
8. **Field partners**
9. **Contact**

A sticky bar appears once the hero has scrolled away. The MENU button opens a panel with every section.

## Files

```
index.html                       the page
assets/fonts/inter-s-400.woff2   Inter Regular, subset (body text)
assets/fonts/inter-s-700.woff2   Inter Bold, subset (headings)
assets/fonts/chakra-s-700.woff2  Chakra Petch Bold, subset (labels)
assets/img/harvester.webp        harvester drawing
.nojekyll                        tells GitHub Pages to serve the files as they are
```

The drum drawing is illustrative, based on the product render. It is not an engineering drawing.
