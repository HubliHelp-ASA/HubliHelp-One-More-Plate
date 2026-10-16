# images/

This folder is for the site's real photos and the official logo.

The site is intentionally **illustration-led right now** (no fake stock photos, no broken
images), so nothing here is required for the site to look complete. But real, local
photography will make it far more powerful. Drop files here and wire them in as described.

## 1. Official HubliHelp logo  → ✅ added as `hublihelp-logo.jpeg`

The official logo has been placed here and is now used in the **site header** and **footer**.
It is shown **exactly as supplied** — not recoloured, stretched, cropped or given a background
frame (aspect ratio is preserved).

It is also used for the **browser-tab icon (favicon)** via `favicon-32.png` and
`favicon-180.png`, which were auto-generated from the logo.

**To improve it later (optional):** a **transparent PNG or SVG** version at a landscape or
square ratio usually looks best in a header. Drop it here and update the two `<img src="…">`
references in `index.html` (search for `hublihelp-logo`). The `.logo-img` / `.footer-logo`
CSS already preserves proportions, so no other changes are needed.

## 2. Photographs (optional, recommended)

Suggested files. Keep them web-optimised (roughly 1600px wide, JPG, under ~250 KB each).

| File | Subject | Where it would go |
|---|---|---|
| `hero-meal.jpg` | A warm, real-looking Indian meal on a plate | Hero artwork area |
| `story-kitchen.jpg` | Hands preparing or packing food with care | The Human Story section |
| `collection.jpg` | Responsible food collection from a local business | Two Programmes / How It Works |
| `volunteers.jpg` | Hubballi community members / volunteers together | Our Local Commitment |
| `social-card.jpg` | A wide 1200×630 image for link previews | Social sharing (og:image) |

**Photo guidelines (important):**
- Use **authentic, respectful** images. No graphic hunger imagery, no exploitative or
  artificial "charity cliché" photos.
- People should be shown with **dignity** and, ideally, with consent.
- Prefer photos taken in **Hubballi / by the community**.

When you add a photo, place it in the relevant section using an `<img>` with descriptive
`alt` text, for example:
```html
<img src="images/story-kitchen.jpg" alt="Volunteers packing surplus food with care" loading="lazy">
```

## 3. Social sharing image

Social platforms need a raster image (JPG/PNG), not SVG. Add `social-card.jpg`
(1200×630) and, in the `<head>`, uncomment/add:
```html
<meta property="og:image" content="https://YOUR-DOMAIN/images/social-card.jpg">
<meta name="twitter:image" content="https://YOUR-DOMAIN/images/social-card.jpg">
```
