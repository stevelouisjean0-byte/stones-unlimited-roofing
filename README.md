# Stones Unlimited — Roofing Services & Custom Builder

Marketing site for Roofing Services Stones Unlimited Builder — Rafael's roofing
contractor and custom home building business in Mt Dora, Florida. 5.0 stars
from 5 Google reviews.

- **Address** 5908 W Jones Ave, Mt Dora, FL 32757
- **Phone** (407) 509-4047
- **Hours** Opens 7 AM Monday (rest of the week not published here — see below)
- **Plus code** P9JR+7M Mt Dora, Florida

## Pages

| File | Contents |
| --- | --- |
| `index.html` | Opener, roofing section detail, tally, two pillars, four service lines, site conduct |
| `roofing.html` | The five stages of a re-roof, repair vs replacement |
| `building.html` | The documented flag-lot build, why builder-and-roofer together matters |
| `reviews.html` | All available reviews verbatim, rating, the one counted topic |
| `contact.html` | Particulars, hours, what helps on the first call, FAQ |

## Design

Identity: **the pitch line.** Roofing is the one trade whose geometry is not
rectilinear, so a single governing diagonal cuts the section edges, the
dividers and the hero — every dark band is clipped along the roof pitch
(`--pitch`), so the page reads as a series of planes rather than stacked
rectangles. Content stacks in `.course` rows, the way a roof is laid.

**Cool only** — asphalt `#191D21` and storm blue `#1F4E7A` on chalk `#F3F5F6`,
with no warm accent anywhere. Type is weight-driven rather than
serif-versus-sans: **Archivo** condensed (`wdth` 84–92, `wght` 700–800,
uppercase) over **IBM Plex Sans**.

Original drawn graphic: a **roofing section detail** on the overview page —
roof deck, underlayment and nine shingle course butts stepping up a true 6:12
slope, with the rise-over-run triangle that defines the pitch. Both the deck
line and the triangle compute to exactly 0.5, so the drawing is dimensionally
correct rather than merely suggestive.

Static HTML, no build step, no JavaScript. Google Fonts is the only external
request.

## Sourcing

This business has only five reviews, so there is very little to work from and
correspondingly no room to pad. Every claim traces back:

| Claim | Source |
| --- | --- |
| 5.0 / 5 reviews | Google profile |
| roof repair ×2 | Google review topic (the only one counted) |
| Re-roof | Nathaly Sevilla's review |
| Roof replacement, landscaping protected, timely and organized | Dax Buell's review |
| Custom build on a flag lot, difficult access, better than expected | Andres Verney's review |
| Owner named Rafael | Andres Verney's review |
| Opens 7 AM Monday | Google profile |

Reviews are quoted verbatim including the missing space in "roof
Replacement.The" — correcting a customer's words would be falsifying them.
None of the three visible reviews carries an owner reply, so none is shown.

No star distribution is displayed: with five reviews Google gives the average
and the total only.

**Hours are deliberately incomplete.** Google shows "Opens 7 AM Mon" with the
rest behind "See more hours". Rather than invent a Tuesday-to-Sunday schedule,
`contact.html` prints Monday and says the rest is not published here. Fill it
in before launch.

## Before launch

- Photography is placeholder stock from Pexels in `assets/img/`. Real job
  photos would help most on `roofing.html` and `building.html` — replace the
  files keeping the filenames; grade and crop are CSS.
- Complete the hours table.
- No licensing or insurance claims appear anywhere by design; the FAQ directs
  callers to ask and verify against the Florida DBPR record.
- Rating and review counts are current as of September 2026.
