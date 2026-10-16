# One More Plate — An initiative by HubliHelp

A single-page, editorial-quality website for the **One More Plate** food-rescue initiative in
Hubballi, Karnataka.

**Good Food. Less Waste. More Hope.**

---

## What the site does

It explains a clear mission in three ideas:

1. **What we stand for** — good food should nourish people, not become waste.
2. **How we help** — two clearly separated programmes:
   - **Good Food, For Less** — affordable *surplus* food (discounted, for purchase).
   - **A Plate Shared With Love** — a *free* community food-donation programme.
3. **How visitors can help** — participate, partner, volunteer, or spread the message.

The site is deliberately honest: it never claims partnerships, statistics, certifications,
or live features that are not actually in place.

---

## Files

```
one-more-plate/
├── index.html                  # The website
├── css/
│   └── style.css               # Editorial theme (cream / deep green / gold)
├── images/
│   ├── hublihelp-logo.jpeg     # Official HubliHelp logo (header + footer)
│   ├── favicon-32.png          # Browser-tab icon (from the logo)
│   ├── favicon-180.png         # Apple touch icon (from the logo)
│   └── README.md               # Notes on the logo + drop real photos here
├── .nojekyll                   # For GitHub Pages
├── DEPLOY-GITHUB-PAGES.md      # Hosting guide
└── README.md                   # This file
```

---

## Sections

| # | Section | Anchor |
|---|---|---|
| 1 | Hero — headline, mission line, two CTAs | `#top` |
| 2 | The Human Story — why food waste matters | `#story` |
| 3 | Two Ways to Make a Difference (two separate programmes) | `#two-ways` |
| 4 | How It Works — businesses, customers, NGOs, volunteers | `#how-it-works` |
| 5 | Food Safety First — sourcing, handling, storage, collection, distribution | `#food-safety` |
| 6 | Who Can Join — restaurants, bakeries, hotels, caterers, NGOs, volunteers | `#who-can-join` |
| 7 | Get Involved — live Google Form | `#get-involved` |
| 8 | Our Local Commitment — rooted in Hubballi | `#commitment` |
| 9 | Contact + Footer — verified details and status | `#contact` |

---

## Contact (verified)

- **Email:** hublihelp@gmail.com
- **Phone:** +91 98451 00152

---

## The interest form (Google Forms)

The form is already connected — it embeds the live Google Form **"One More Plate.HH"**.

- Short link: <https://forms.gle/RYEuKhJbhb3tQJF1A>
- Edit / view responses: <https://docs.google.com/forms> (sign in with `hublihelp@gmail.com`)
- Email alerts: in the form → **Responses → ⋮ → Get email notifications for new responses**

To swap in a different form later, replace the two URLs in the `#get-involved` section:
- `iframe src="…/viewform?embedded=true"`
- the fallback link `href="…/viewform"`

---

## Brand & assets

- **Logo:** the official HubliHelp logo is used (in the header, footer and browser-tab icon),
  shown exactly as supplied — not recoloured, distorted or given a background frame.
  See `images/README.md` if you later want to swap in a transparent PNG/SVG version.
- **Photography:** the design is illustration-led so there are no fake or broken images.
  Add real, respectful, local photos — see `images/README.md` for the list and guidelines.

---

## Accessibility & quality

- Semantic landmarks, skip-to-content link, keyboard-friendly menus.
- `aria-expanded`, `aria-current`, focus-visible styles.
- Respects **`prefers-reduced-motion`**.
- Mobile-first responsive layout; no horizontal overflow.
- No frameworks, no API keys, no paid services, no recurring subscriptions.

---

## SEO & social

`index.html` includes an accurate page title, meta description, Open Graph and Twitter
tags, and JSON-LD (`Organization`). Two placeholders remain **on purpose** until you have a
live URL:

1. **Canonical URL** — commented out; uncomment and set once published.
2. **Social share image** — add `images/social-card.jpg` (1200×630) and set `og:image`.

---

## Publish it

See **`DEPLOY-GITHUB-PAGES.md`** for free hosting on GitHub Pages (and how to attach your
own domain later).

---

## Important status disclosure (kept on the site)

- One More Plate is an **early-stage HubliHelp initiative**.
- Business / NGO / volunteer participation is currently **by invitation and expression of interest**.
- Live listings, ordering, delivery and payments are **not yet operational**.
- **Donated food is always free** to the person receiving it.
