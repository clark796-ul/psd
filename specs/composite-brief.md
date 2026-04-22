# BDE Gummy — Composite Page Brief
**For use with Google Stitch, v0.dev, Figma, or Bolt.new**

---

## VISUAL INSPIRATION SOURCES
- **Reference 1:** Grüns x OLIPOP — `/references/ref-1-gruns-olipop/`
- **Reference 2:** Khloud Protein Popcorn — `/references/ref-2-khloud/`

---

## PAGE INTENT
Build a **mobile-first** single-page landing page for **BDE Gummy**.
- Dark background (`#111111`) as default
- Cream section (`#FAF5EE`) for pricing only
- **Burgundy** (`#8B1A1A`) as the sole CTA color
- Amber (`#C4873A`) as accent/mono font color
- Forest green (`#22C55E`) for trust/guarantee only

---

## SECTION MAP (scroll order, top to bottom)

### S01 — NAV
- Transparent → dark on scroll
- Logo left | Links center | “Get BDE” pill button right (burgundy)

### S02 — HERO
*Borrow structure from: Grüns x OLIPOP hero*
- Trust line top: `90,000+ customers · 4.8 · Sells out every run`
- Giant serif display text: `Pre-` + rotating word (CONFIDENCE / STRENGTH / DATE / GYM / MEETING / SCHOOL RUN / EVERYTHING)
- Subhead: *“We do not have to simply want to get better.”*
- Burgundy pill CTA: `Get BDE Now`
- Guarantee line below CTA: `28-day full-performance guarantee or full refund`
- Product image right side: amber bottle + 3 watermelon gummies

### S03 — TRUST TICKER
*Borrow structure from: Khloud trust line*
- Dark band (`#1A1A1A`), 44px height
- Scrolling marquee: `Non-GMO ❖ CGMP Certified ❖ World Farms Third-Party Tested ❖ Vegan ❖ Gluten-Free ❖ No Artificial Colors ❖ 60 Gummies Per Bottle`

### S04 — VILLAIN SECTION
- Background: `#1A1208` (dark warm)
- Headline: *“Everyone else is loud. You don’t have to be.”*
- Body: Position against synthetic pre-workouts, beta-alanine tingles, neon labels
- No CTA here — this is a mood/positioning section only

### S05 — INGREDIENT GRID
*Borrow structure from: Khloud’s 2×2 benefit icon cards*
- 4-col desktop / 2-col mobile grid
- NO icons — typographic treatment only
- Each card: Ingredient name (ALL CAPS) | Dosage in amber mono | Benefit in one line
- 8 ingredients: Watermelon Extract, Beet Root, Sea Moss, Maca Root, Pumpkin Seed Oil, Amino Acid Complex, Vitamin D, Vitamin E

### S06 — PRICING TABLE
*Borrow subscription toggle from: Khloud pricing module*
*Borrow card layout from: Grüns x OLIPOP bundle selector*
- Background: `#FAF5EE` (CREAM — full section inversion)
- 3 cards: 1 Bottle | **2 Bottles (HERO — burgundy border)** | 3 Bottles
- Subscribe pre-selected with thick border active state
- Each card: MSRP struck | Selling price large | Per-day in amber mono | Savings badge green | Benefits checklist | Full-width burgundy CTA
- Under all cards: guarantee strip + certification pills

### S07 — FINE PRINT BAND
- Dark band background
- Brand-voice irreverent long-form copy styled like legal text
- Recaptures attention before social proof

### S08 — LIFESTYLE / IDENTITY SECTION
- Dark background
- Before/After identity framing: who you are without BDE vs. with BDE
- Real-life moments: backyard, kitchen, conference table, mirror before a date

### S09 — TESTIMONIALS
*Borrow UGC mosaic from: Khloud’s photo grid*
*Borrow video carousel from: Grüns x OLIPOP UGC video cards*
- Section header: `90,000+ customers. Real people. Real life.`
- Scarcity subline (amber): `Sold out in 3 of 4 markets. US stock available now.`
- 5 vertical 9:16 video cards with name, location, tag badge, quote

### S10 — COMPARISON TABLE
- Dark warm background
- BDE Gummy vs. Typical Pre-Workout — ingredient superiority grid
- BDE wins every row

### S11 — SCARCITY SECTION
- Dark band
- Real sellout history: US, CA, UK, FR since 2020
- Countdown or inventory signal

### S12 — FAQ ACCORDION
*Borrow + style from: Khloud FAQ*
- 7 items, burgundy left border on open state
- Questions in priority objection order

### S13 — FINAL CTA
- Dark band
- Last purchase opportunity before footer
- Burgundy full-width pill CTA

### S14 — FOOTER
- Deep dark background (`#0D0D0D`)
- FDA disclaimer full text
- Links: Privacy | Terms | Refund Policy | Contact

### S15 — STICKY MOBILE ATC BAR
- Mobile only, fixed bottom
- 72px height
- Thumbnail | Name + Subscribe & Save | `Get BDE` burgundy pill

---

## STITCH PROMPT (paste this exactly)

```
Create a mobile-first landing page for BDE Gummy, a functional energy gummy supplement.

Use the uploaded Grüns x OLIPOP screenshots for the hero layout, bundle pricing card structure, and UGC video carousel style.

Use the uploaded Khloud screenshots for the 2x2 ingredient icon grid, subscription toggle module, UGC photo mosaic, and review rating breakdown.

Color system:
- Default background: #111111 (near-black)
- Alternate section: #1A1208 (dark warm brown)
- Pricing section: #FAF5EE (cream) — full inversion
- Primary CTA color: #8B1A1A (burgundy) — used only for buttons
- Accent/dosage text: #C4873A (amber)
- Trust/guarantee: #22C55E (forest green)
- Body text on dark: #F5F0EB (warm off-white)

Typography:
- Display headlines: Cormorant Garamond serif, large, tight tracking
- Body and UI: Inter sans-serif
- Dosage numbers: Space Mono monospace in amber

The tone is: confident, grounded, premium. NOT loud or gym-bro. The brand name is BDE Gummy. The tagline is: “We do not have to simply want to get better.”

Build all 15 sections listed in the composite brief. Start with the mobile layout.
```
