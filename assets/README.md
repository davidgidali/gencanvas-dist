# Landing-page assets

Drop the brand logo here and it replaces the CSS-gradient placeholder mark in the
page header automatically — no markup or CSS changes needed.

## Logo

- **Filename:** `logo.svg` (preferred) — or change the `url('assets/logo.svg')`
  reference in `../index.html` (the `.logo .mark` rule) to `logo.png`.
- **Shape:** square. The header mark is a 22×22 rounded square and uses
  `background-size: cover`, so a square source fills it exactly. A non-square
  image will be center-cropped.
- **Recommended size:** an SVG (resolution-independent) or a ~512×512 PNG.
- **Background:** the logo sits on top of the gradient fallback, so prefer a
  full-bleed / self-contained mark. Anything transparent will show the
  blue→purple gradient behind it.

Until a file is present, the header shows the gradient mark as a graceful
fallback (pure CSS — no broken-image icon, no 404 noise).
