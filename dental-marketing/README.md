# Dental Marketing page redesign

Redesign of https://markxmedia.agency/industries/dental-marketing/ (Industry post type).

- `index.html` is a standalone preview. For Elementor, paste the block between
  `BEGIN mxd page styles` / `END` into Custom CSS (or an HTML widget) and the block
  between `BEGIN mxd page content` / `END` into an HTML widget. All styles are scoped under `.mxd`.
- `assets/dental-hero.webp` (2400w) and `assets/dental-hero-1400.webp` are the
  Real-ESRGAN 4x upscaled hero image, resized for the web. `dental-hero-4x.jpg` is the full 3492×2180 master.
  Upload them to the Media Library and update the `src`/`srcset` URLs.
- Before publishing: add a clinic interior photo (`assets/dental-clinic.jpg` slot) and replace the
  bracketed testimonial placeholders with real client quotes.
