# BDE Gummy — Technical Specification Sheet
Version 1.0 | April 2026 | Build-Ready

## T1 — STACK
- Framework: Next.js 14 (App Router)
- Hosting: Vercel
- Repo: GitHub (clark796-ul/psd)
- CMS: Sanity.io
- Payments: Stripe Billing
- Styling: Tailwind CSS v3 + CSS custom properties
- Animation: GSAP + Framer Motion
- Scroll: Lenis

## T2 — DESIGN TOKENS

### Colors
--color-bg-default: #111111
--color-bg-alternate: #1A1208
--color-bg-pricing: #FAF5EE
--color-bg-dark-band: #0D0D0D
--color-text-primary: #F5F0EB
--color-text-muted: #8A7D72
--color-cta: #8B1A1A
--color-cta-hover: #A82020
--color-accent: #C4873A
--color-trust: #22C55E
--color-border: rgba(245,240,235,0.12)

### Typography
--font-display: Cormorant Garamond, serif
--font-body: Inter, sans-serif
--font-mono: Space Mono, monospace
--text-hero: clamp(4rem, 10vw, 9rem)

## T3 — SECTION MAP
S01 nav | S02 hero | S03 ticker | S04 villain | S05 ingredients
S06 offers | S07 fine-print | S08 lifestyle | S09 testimonials
S10 comparison | S11 scarcity | S12 faq | S13 final-cta | S14 footer | S15 sticky-atc

## T5 — STRIPE PRICE IDs
price_bde_1bottle_sub: $26.25/28days
price_bde_2bottle_sub: $45.00/28days (HERO)
price_bde_3bottle_sub: $67.50/28days
price_bde_5bottle_sub: $105.00/28days (cart upsell)
