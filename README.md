# jinyang6.github.io

Personal site for Jinyang Jia: https://jinyang6.github.io/

## Core spec

Clean, short, direct, professional, easy to read.

Keep it easy to edit: one static page, no build step, no JavaScript.

## Editing

- **Colors:** `theme.css` only.
- **Layout and type:** the `<style>` block in `index.html`. Text links are always underlined. There are no hover effects; keyboard focus is still visible.
- **Timeline:** `index.html`, `ol.timeline`. Newest first. Project dates are repo creation dates; descriptions are one sentence from each repo. Education uses degree date ranges and has no description. Copy one `<li>` to add a project.
- **Writing:** `index.html`, `section#writing`.
- **Title separator:** use `|` between the name and tagline in metadata.
- **Search metadata:** title, canonical, social tags, and the ProfilePage graph are in `index.html`. `robots.txt` and `sitemap.xml` are at the repo root. Update `lastmod` in the sitemap when the page changes.

## Search

Technical SEO is in place. Ranking still requires work outside the code:

1. Verify the site in [Google Search Console](https://search.google.com/search-console) and submit `https://jinyang6.github.io/sitemap.xml`.
2. Request indexing for the homepage.
3. Link the site from GitHub, LinkedIn, Medium, and SourceForge.
4. Publish more pages and earn links. There is no guaranteed top ranking; Google weighs relevance, authority, and time.
