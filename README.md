

# 1) README.md (SkillLeo — Logo & Brand Package)

````markdown
# SkillLeo — Logo & Brand Package

**Status:** Delivered (vector master + exports)  
**Author:** Professional graphic designer (commissioned by the client)  
**Purpose:** Repository of brand master files and export assets for SkillLeo — a sleek, modern, premium logo and visual identity designed for web, product, and print usage.

---

## Overview
This repository stores the SkillLeo logo and core branding assets. The logo was professionally designed by a contracted graphic designer and supplied to the client as a complete brand package. These assets are intended for use across product UI, marketing, pitch decks, social media, favicon, and print collateral.

> ⚠️ Note: The master Adobe Illustrator file (`.ai`) is the authoritative source. Exports (SVG, PNG, EPS, PDF) are derived from the master. Confirm license/usage rights with the designer if you plan to redistribute or resell assets.

---

## What’s included
Typical files inside this package (file names may vary):
- `SkillLeo-master.ai` — Adobe Illustrator master (vector, layers intact).
- `SkillLeo-logo.svg` — Clean vector SVG for the web (scalable).
- `SkillLeo-logo-outline.svg` — Outline/stroke-only variant (if provided).
- `SkillLeo-logo.png` — High-res PNG (transparent background).
- `SkillLeo-logo-@2x.png`, `SkillLeo-logo-@3x.png` — Retina ready exports.
- `SkillLeo-favicon.ico` / `favicon-32.png` / `favicon-16.png` — Favicon sizes.
- `SkillLeo-bw.png` / `SkillLeo-white.png` — Monochrome and reversed variants.
- `SkillLeo-vertical.png` / `SkillLeo-horizontal.png` — Layout variations.
- `brand-colors.md` or `brand-guidelines.pdf` — Palette, spacing, DOs & DON’Ts.
- `typography.md` — Recommended fonts and web fallbacks.
- `assets/source/` — any additional source files (EPS, PDF).
- `README.md` — this file.

> If you received a single zip (`Logo-SkillLeo.zip`), expand it to reveal these assets.

---

## Brand description & visual intent
SkillLeo’s logo was crafted to be:
- **Sleek & modern:** minimal geometric forms with premium spacing.
- **Simple & iconic:** recognisable at small sizes (favicon) and strong as a wordmark.
- **Professional & premium:** restrained color palette and clear typographic hierarchy suitable for enterprise and consumer-facing products.
- **Flexible:** variants for light/dark backgrounds, print, and social profiles.

The design reflects the designer's creative decisions. As the client, you commissioned this work; the designer executed it with professional craft.

---

## Color palette (example)
Use the provided palette file or copy these tokens to CSS variables. Replace with exact hex codes from `brand-colors.md`.

```css
:root {
  --skillleo-primary: #0B6AF6; /* Example: primary blue */
  --skillleo-accent: #FF7A59;  /* Example: accent / CTA */
  --skillleo-neutral-900: #0B1C2D;
  --skillleo-neutral-100: #FFFFFF;
}
````

---

## Typography

Designer provides recommended fonts and sizes. Typical pattern:

* **Display / Headline:** \[Primary Typeface] — e.g., "Inter / Poppins / Montserrat" (use provided license fonts or web equivalents).
* **Body:** System or web safe fallback (e.g., `system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial`).
* **Fallback:** If the primary font is paid, use `font-family` fallbacks in CSS.

---

## Usage guidelines (DOs & DON’Ts)

**DO**

* Preserve clearspace (use the spacing token specified — usually x = height of logo mark).
* Use vector (SVG) for web, and high-res PNG/EPS for print.
* Use monochrome variants when color contrast is required.

**DON’T**

* Stretch or distort the logo.
* Change proportions, rotate or recolor outside approved palette.
* Apply drop-shadows or effects that alter legibility at small sizes.

---

## Export & integration recommendations

### Web

* Use **SVG** for inline logos or `<img src="SkillLeo-logo.svg">`.
* Provide PNG fallbacks for legacy email clients.
* Add accessible `alt` text: `alt="SkillLeo logo"`.
* Favicons: include `favicon-16.png`, `favicon-32.png` and an `favicon.ico`.

### CSS token suggestion

```css
.logo { height: 40px; width: auto; }
.header .logo { height: 32px; }
```

### Social & profile avatars

* Square crop 400×400 px for social profiles; include centered mark-only variant for avatar clarity.

### Print

* Use vector EPS/PDF/AI with CMYK color profiles. Export bleed and crop marks when required by printers.

---

## File naming & versioning

Use semantic names and versioning:

* `SkillLeo-logo_v1.ai`
* `SkillLeo-logo_v1.1.svg`
* `SkillLeo-favicon_v1.ico`

Commit changes to versioned branches when updating the brand assets.

---

## Legal & licensing

* This repo holds assets provided by the contracted designer. Confirm licensing:

  * Who holds copyright?
  * Are there restrictions on resale, resale with modification, or sublicensing?
* Typical arrangement:

  * Client owns final logo for use in the product and marketing.
  * Designer may retain moral or portfolio rights; check contract.

Place license text in `LICENSE` if required.

---

## How to open & edit the .ai master file

* Adobe Illustrator (recommended) — preserves layers, artboards, typography.
* Alternatives: Affinity Designer (partial), Inkscape (SVG export only), or export to EPS/PDF if Illustrator is unavailable.
* For web edits, export to SVG from Illustrator and open in a text editor for minor tweaks.

---

## Practical checklist for developers

1. Copy `SkillLeo-logo.svg` into `assets/images/` and reference in header/nav.
2. Add favicon files to the root and include:

   ```html
   <link rel="icon" href="/favicon-32.png" sizes="32x32" />
   ```
3. Use CSS variables for brand colors and ensure accessibility contrast.
4. Replace placeholder fonts with licensed web fonts or good fallbacks.

---

## Attribution & credits

* **Designer:** \[Designer Name] (credit as provided by designer). Include designer contact if provided.
* **Client:** This repo owner — client who commissioned the design.

Add a `CREDITS.md` if you need to list the designer, design agency, and version history.

---

## Modifications & requested changes

If you would like the designer to adjust colors, spacing, or provide additional exports:

* Contact the designer with exact requirements (file name, export size, color hex).
* Keep a changelog: `CHANGELOG.md`.

---

## Frequently asked questions

**Q:** Can I edit the logo?
**A:** Yes, using Illustrator. Confirm licensing & retain design integrity.

**Q:** Which file should I use on the web?
**A:** `SkillLeo-logo.svg` for scalability; `png` for email.

**Q:** Who owns the logo?
**A:** Ownership depends on the contract between client and designer. Verify the agreement.

---

## Changelog

* `v1.0` — Initial delivery with `.ai`, `.svg`, `.png`, favicon and guidelines.

---

## Contact

For asset requests, corrections, or licensing info contact the designer or the client project manager (contact details to be stored outside this repo).

---

