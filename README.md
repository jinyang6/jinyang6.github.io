# jinyang6.github.io

Personal site for Jinyang Jia: https://jinyang6.github.io/

## Core requirement

Clean, short, direct, professional, easy to read.

Keep it easy to edit: one static page, no build step, no JavaScript.

## Editing

- **Theme:** colors and the Newsreader font are in `theme.css` only.
- **Layout and type sizes:** the `<style>` block in `index.html`.
- **Profile icons:** `index.html`, `nav.icons`.
- **Timeline:** `index.html`, `ol.timeline`. Newest first. Project dates are repo creation dates; descriptions are one sentence from each repo. Taoi is a manual entry linked to its Xiaohongshu preview. Education uses degree date ranges and has no description. Copy one `<li>` to add a project.
- **Writing:** `index.html`, `section#writing`.

## Design

Text-first layout in the spirit of [darioamodei.com](https://darioamodei.com/): narrow column, one timeline, and Dario's Newsreader text face.

The palette comes from Taoi's `src/constants/theme.ts`.