# Reviews page + global testimonials template

- `index.html`: standalone preview of the redesigned https://markxmedia.agency/reviews/ page
  (hero → reviews grid with project-type filter → closing CTA). Hero/CTA styles are scoped under `.mxr`.
- `testimonials-section.html`: the **global reusable testimonials section** (styles + markup + script, all scoped under `.mxt`).
  Paste into an Elementor HTML widget / saved global template. Options are `data-*` attributes on `<section class="mxt">`
  (`data-layout="carousel|grid"`, `data-filter`, `data-project`, `data-limit`); reviews live in the JSON block.
  Use `carousel` on service/industry/home pages (with `data-project="SEO"` etc.) and `grid` on the reviews page.
  `index.html` embeds a copy of this block; keep them in sync if you change the template.

## Before publishing
1. All reviews, the 4.9 rating, "15+" clients and "3 countries" are **placeholders**. Replace with real, verifiable numbers
   and real client quotes (the site currently shows differing totals, e.g. 4.8 / 1,500+ vs 4.5 / 1,578; pick one verified figure).
2. Hero CTAs link to `/contact/` and `/services/`; update if your URLs differ.
3. Don't add `aggregateRating` schema for your own business reviews: Google doesn't show rich results for self-served reviews.
4. Add real client photos via the `avatar` field (initials show if empty).
