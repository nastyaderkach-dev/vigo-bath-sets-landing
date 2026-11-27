# VIGO · The Complete Bath landing page

Static landing page for VIGO bath sets in one finish (example: The Complete Bath in Matte Black).
Built in the current vigoindustries.com style: black header and footer, condensed uppercase headings, black square buttons, bordered product cards, outlined "save" badge.

## Structure

- `index.html` — the page (responsive, no build step). The set is sold in Matte Black only for now; Matte Brushed Gold and Stainless Steel are shown as "coming soon" with a "Notify me" button.
- `pro/` — VIGO Pro (B2B) mockup: `index.html` trade program page, `cabinet.html` contractor account overview, `project.html` project page; client quote marked "Coming soon" ("With prices / No prices" toggle works).
- `images/` — product and interior photos from vigoindustries.com, VIGO logo.
- `analytics/` — marketing and sales dashboard (snapshot 12.11.2026, data 1 Aug – 11 Nov 2026): `index.html` page, `data.js` data from Shopify, GA4, Google Ads and Meta Ads. No build step; charts use d3 from cdnjs.

## Open locally

Open `index.html` in a browser.

## Before production

- Fonts: the live site uses DIN Condensed and Helvetica Neue LT Pro (licensed). This page uses close Google Fonts (Barlow Condensed, Inter); swap in the site fonts.
- Photos: images are screen captures (up to ~1300 px). Replace with originals from VIGO's library; the hero is the Bathroom category photo — ideally a shot of the exact set.
- Placeholders in square brackets: prices and photos for other finishes, customer photos (UGC rights needed).
- Set price: door at current price, −10% on the shower panel and sink set; promo codes do not apply to sets. Check against MAP.
- Prices as on vigoindustries.com, 06.11.2026 (before BFCM). On 09.11 the Elan Hart Matte Black door was already $919.90: recalculate all set prices after BFCM. "If bought separately" must use current selling prices.
- Finishes (Shopify, 09.11.2026): Montauk sink sets exist only in Matte Black; Ellington comes in Matte Black, Matte Brushed Gold and Stainless Steel (no Chrome). Other finishes need a different sink model from VIGO.
- Confirmed on vigoindustries.com (09.11.2026): 3/8 in. tempered glass on Elan Hart (product page), 1,359 Elan reviews (home page), limited lifetime warranty for residential installations (FAQ), returns within 14 days with a 15% restocking fee (Shipping & Returns).
- Delivery: VIGO is removing the $99 oversized surcharge (decision 09.11.2026). Update Shipping & Returns and the checkout before this page goes live, since the page promises free delivery for doors and panels.
- Still to confirm with VIGO: whether the BFCM "Extra 7% Off" applies to sets.

## Matte Black Collection (collections/matte-black/)

New concept replacing the 3-piece set: a collection page per finish (room tabs: All, Bathroom, Kitchen) with a progressive discount.

- Copy: "One finish. Start to finish." (remodel theme), planned for a January–February launch.
- Discount: highest-priced piece at full price; 2nd piece 3% off, 3rd 7% off, 4th and every next piece 10% off. Pieces under $50 count but aren't discounted. Collection savings don't combine with promo codes.
- Profitability (cost file + 814 site orders, Aug–Nov 2026, BFCM prices): about $3.2 per order (0.7% of revenue) given to customers who already buy several pieces; pays back if 1 in 13–21 orders adds one more piece. Every collection item keeps a positive margin at 10% off (tub doors lowest, ~6%).
- 18 matte black products, prices as on vigoindustries.com 27.11.2026 (BFCM); photos from VIGO's site in `images/p/`.
- Before production: recalculate on January prices; decide on the 10% site codes (TAKE10, VIGOTAKE10, EARLY10) during the launch; Shopify needs a discount function or app for "every next piece costs less"; matte black sinks from VIGO.

## VIGO Pro mockup (pro/)

- Levels, discounts (Pro 10%, Pro Plus 12% from $10,000/yr, Partner by quote), 1-business-day approval and Pro desk contacts are a BASE proposal, to be confirmed by VIGO.
- Names, companies and totals in the account are demo data. Placeholders in square brackets need VIGO input.
- Account features map to Shopify B2B (company profiles, catalogs). VIGO is on Shopify Plus; as of 2026-11-09 its B2B catalogs show -5% but fixed prices equal retail, so the -10% Pro price still needs to be set up.
- Launch scope from Dec 1 (MVP): application, 1-business-day approval, Pro price (10% off the site price, Pro Plus 12%), free delivery. Marked "Coming soon": client quotes, picking a delivery date, Find a VIGO Installer. Net-30 removed.
- Returns follow the site policy (14 days, 15% restocking fee). Free delivery for oversized items depends on VIGO removing the $99 surcharge.
- Elan Hart price is the site price on 2026-11-09 ($919.90); other prices in the account are demo data.
