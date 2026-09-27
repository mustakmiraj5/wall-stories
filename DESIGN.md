---
version: alpha
name: Wall Stories
description: Storefront and design service for a Bangladesh-based brand that sells complete, ready-to-hang gallery walls rather than individual posters.

colors:
  primary: "#211D1A"
  primary-hover: "#3A3430"
  secondary: "#665F58"
  tertiary: "#A64F2B"
  tertiary-hover: "#8C3D23"
  subtle: "#F7E2D4"
  neutral: "#F1ECE3"
  surface: "#F9F6F0"
  on-surface: "#211D1A"
  border: "#DFD8CF"
  error: "#912D2E"
  frame-black: "#151312"
  frame-white: "#F3F2EF"
  frame-oak: "#BD976B"

typography:
  display:
    fontFamily: Instrument Serif
    fontSize: 88px
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: -0.015em
  headline-xl:
    fontFamily: Instrument Serif
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: -0.012em
  headline-lg:
    fontFamily: Instrument Serif
    fontSize: 44px
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: -0.008em
  headline-md:
    fontFamily: Instrument Serif
    fontSize: 32px
    fontWeight: 400
    lineHeight: 1.15
  headline-sm:
    fontFamily: Instrument Serif
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.2
  numeral:
    fontFamily: Instrument Serif
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1
  body-lg:
    fontFamily: Hind Siliguri
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.65
  body-md:
    fontFamily: Hind Siliguri
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Hind Siliguri
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  label-md:
    fontFamily: Hind Siliguri
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Hind Siliguri
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: 0.14em
  price-lg:
    fontFamily: Hind Siliguri
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.2
    fontFeature: "'tnum' 1"
  price-md:
    fontFamily: Hind Siliguri
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.3
    fontFeature: "'tnum' 1"

rounded:
  none: 0px
  sm: 2px
  md: 6px
  lg: 12px
  full: 9999px

spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  xxl: 96px
  gutter: 24px
  margin-mobile: 20px
  margin-tablet: 40px
  margin-desktop: 64px

components:
  page:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
  divider:
    backgroundColor: "{colors.border}"
    height: 1px
  text-meta:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.body-sm}"
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
    height: 52px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.surface}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
    height: 52px
  button-secondary-hover:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
  button-tertiary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
    padding: "{spacing.xs}"
  button-design:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.surface}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
    height: 52px
  button-design-hover:
    backgroundColor: "{colors.tertiary-hover}"
    textColor: "{colors.surface}"
  link-design:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.tertiary}"
    typography: "{typography.label-md}"
  design-band:
    backgroundColor: "{colors.subtle}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-lg}"
    padding: "{spacing.xl}"
  step-active:
    backgroundColor: "{colors.subtle}"
    textColor: "{colors.tertiary-hover}"
    typography: "{typography.label-caps}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  step-idle:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.label-caps}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  nav-link:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-md}"
    padding: "{spacing.sm}"
  bottom-nav:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.label-caps}"
    height: 64px
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
    height: 52px
  input-error:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.error}"
    typography: "{typography.body-sm}"
  select:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
    height: 52px
  filter-chip:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  filter-chip-selected:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.full}"
    padding: "{spacing.sm}"
  tab:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.label-md}"
    padding: "{spacing.md}"
  tab-active:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-md}"
    padding: "{spacing.md}"
  badge:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-caps}"
    rounded: "{rounded.sm}"
    padding: "{spacing.xs}"
  price:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.price-md}"
  price-detail:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.price-lg}"
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: "{spacing.lg}"
  product-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.headline-sm}"
    rounded: "{rounded.md}"
  collection-card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.headline-md}"
    rounded: "{rounded.md}"
  label-plate:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.none}"
    padding: "{spacing.sm}"
  step-numeral:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.numeral}"
  upload-zone:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: "{spacing.xl}"
  modal:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "{spacing.xl}"
  drawer:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    padding: "{spacing.lg}"
    width: 440px
  toast:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "{spacing.md}"
  tooltip:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: "{spacing.sm}"
  swatch-frame-black:
    backgroundColor: "{colors.frame-black}"
    rounded: "{rounded.full}"
    size: 28px
  swatch-frame-white:
    backgroundColor: "{colors.frame-white}"
    rounded: "{rounded.full}"
    size: 28px
  swatch-frame-oak:
    backgroundColor: "{colors.frame-oak}"
    rounded: "{rounded.full}"
    size: 28px
---

# Wall Stories

## Overview

Wall Stories sells a finished wall, not a poster. The customer is buying a composition: five pieces chosen to work together in colour, scale and mood, framed and ready to hang. The interface exists to make that composition legible and desirable, then to get out of the way.

Most people who visit are decorating a specific room: a rented flat in Mirpur, a first home in Chattogram, a café in Banani, a gaming corner. They browse on a phone, often in the evening. They are not design experts. They respond to seeing a whole wall in a real room far more than to a list of print sizes. So the gallery-wall photograph is always the loudest thing on the screen, and the UI is quiet paper and ink around it.

The register is **Editorial Print crossed with Warm Analog**, meaning an interior magazine (*Apartamento*, *Cereal*) printed on lime-washed stock. Large, light serif headlines. A workmanlike bilingual sans for everything a customer taps. Warm ivory paper instead of white. Charcoal ink instead of black. One earthen accent.

**What this system gives up, deliberately:**

- **The discount-store toolkit.** No red sale badges, strikethrough prices, countdown timers, "% OFF" stickers or star-rating clutter on cards. A promotion is a sentence of copy, never a graphic. This will cost some impulse conversion. It buys the "interior studio, not Daraz" positioning, which is the brand's only real moat.
- **Density.** Listing grids top out at three columns. On mobile, gallery walls show one per row, because a five-piece composition shrunk to a 2-up thumbnail stops being a composition.
- **Dark mode.** The product is photographed in daylit rooms on warm walls, and the paper tone is part of how it's framed. The system is light-only.

## Colors

The palette comes from a Bengali wall. The accent is the **terracotta of the Kantajew temple plaques** in Dinajpur. Those plaques are thousands of fired-clay panels composed into one surface, which makes them the region's oldest gallery wall. The neutrals are the **lime-wash and plaster** of an older Dhaka house. The ink is **lamp-black**, the soot of a clay *pradip*.

- **Surface (#F9F6F0):** *Lime-wash.* The page. Warm ivory, never white. Artwork mats and white frames are set a touch cooler than this, so a white frame still reads as an object against the page.
- **Neutral (#F1ECE3):** *Plaster.* One half-step down. Used for cards, the upload zone and filter panels. Most of the interface's structure comes from the gap between Lime-wash and Plaster.
- **Primary / On-surface (#211D1A):** *Lamp-black.* Body text, headings and the primary button fill are the same ink. A primary button is ink on paper, not a brand colour. The hover step (#3A3430) lightens slightly rather than darkening, because there is nowhere darker to go.
- **Secondary (#665F58):** *Ash.* Metadata: piece counts, dimensions, locations, idle tabs, step numerals. Passes AA on both paper tones (5.8:1 on Lime-wash, 5.3:1 on Plaster).
- **Tertiary (#A64F2B):** *Kantajew terracotta.* **It has exactly one job: it marks the Design My Wall service.** It appears on the header CTA, the second hero button, the Design My Wall homepage band, the centre item of the mobile bottom nav, and the active step inside the design flow. It does not appear on Add to Cart, links, prices, badges, icons or borders. Keeping it scarce is how "we'll design it for you" stays findable on every screen. Hover is #8C3D23.
- **Subtle (#F7E2D4):** *Unfired slip.* A pale tint of the terracotta. It is the background of the Design My Wall band and the active step pill, and it is only ever used inside the service.
- **Border (#DFD8CF):** *Plaster seam.* 1px hairlines between rows and around inputs.
- **Error (#912D2E):** *Over-fired brick.* From the same clay family but darker and pushed toward crimson (hue 24° vs the accent's 42°), so it cannot be confused with the accent. It is always paired with an icon and a written message. It is used only in forms, where the accent never appears.
- **Frame colours (#151312 black, #F3F2EF white, #BD976B natural oak):** These are product materials, not UI colours. They are used only for frame-option swatches and the visualiser's frame preview, never for interface chrome.

There is no success green and no warning amber. Confirmations ("Added to cart", "Design saved") appear as a Lamp-black toast with a check icon. The message carries the meaning, so no traffic-light colour is needed.

Every neutral is warm-tinted (OKLCH hue 60–85°, chroma 0.008–0.014). No value in the system has R = G = B. The terracotta ramp bends from hue 55° in the tint to 38° in the hover shade, so it reads as fired clay rather than an HTML colour.

Payment marks (bKash, Nagad, Visa/Mastercard) use the providers' official artwork at their required colours. Those brand colours stay inside the logo and never become tokens.

## Typography

There are two families, split by job.

**Instrument Serif** carries the voice. It is used for display, headlines, section titles, collection names on cards and the large step numerals ("01"). Its high contrast and slightly condensed proportions look like interior-magazine mastheads, and they fit long headlines ("Make your walls say something.") into a narrow left column. **It is used at one weight, 400, only.** Hierarchy between headlines comes from size and space, never from bolding the serif. The italic is allowed for one phrase per headline at most, to carry the emotional word ("say *something*"). SIL OFL. Fallback: `"Instrument Serif", "Cormorant Garamond", Georgia, serif`.

**Hind Siliguri** carries the apparatus. It is used for navigation, buttons, filters, forms, prices, product details and body copy. It was chosen for one hard reason: **it is a Latin + Bengali family**. The taka sign ৳ and any Bangla copy (addresses, delivery notes, a future বাংলা toggle) render in the same face and at the same weight as the English beside them, with no fallback-font seams. It is also quiet enough to disappear next to the serif. Two weights only: 400 and 600. SIL OFL. Fallback: `"Hind Siliguri", "Noto Sans Bengali", "Helvetica Neue", Arial, sans-serif`.

Instrument Serif has no ৳ glyph, so **prices are always set in Hind Siliguri** (`price-md`, `price-lg`, tabular figures), including inside editorial layouts.

The scale is editorial, on a ≈1.333 ratio from 16px body, hand-broken at the top: 24 → 32 → 44 → 64 → 88. Display and headline-xl are desktop sizes and scale fluidly down to 48px and 40px on mobile (`clamp()`). Tracking is optical: slightly negative on the serif at large sizes, +0.01em on button labels, +0.14em on uppercase `label-caps`. Line height runs inversely to size, from 0.98 at display to 1.65 at body-lg.

`label-caps` is the only uppercase style. It is used for piece counts ("5 PIECES"), badges, eyebrows above section titles and the bottom-nav labels. Buttons are never uppercase. They use the title-case product labels as written ("Design My Wall", "Add to Cart").

Body measure is capped at 64ch.

## Layout

**Grid:** 12 columns with 24px gutters. Outer margins are 20px on mobile, 40px on tablet and 64px on desktop. Content max-width is 1440px, and photography may bleed past it to the viewport edge. Breakpoints: 640px (tablet), 1024px (desktop), 1440px (wide).

**Spacing:** strict 8px base, with a 4px half-step inside chips, badges and label plates. Section spacing is 96px on desktop and 64px on mobile. **Section rhythm varies on purpose.** Related sections sit closer: *Shop by Style* follows *Design My Wall* at 48px, not 96px, because both are about choosing a feeling.

**Asymmetric, flush-left.** Headlines and body copy align left. Centred text is not used anywhere, including the hero, empty states and modals. The hero is a 5/7 split: headline and buttons on paper in the left five columns, and the room photograph bleeding off the right edge. On mobile the photograph comes first at full width in 4:5, and the text follows on paper below. **Text is never set over photography**, so there are no scrims or gradient overlays. The only thing that may sit on a photo is a label plate (see Components).

**Product imagery ratios:** room mockups are 4:5. The individual-pieces view is 1:1 on Plaster. Hero and editorial images are 3:2 or full-bleed.

**Grids:**
- Gallery-wall listing: 3 columns desktop, 2 tablet, 1 mobile.
- Shop by Room: an uneven mosaic on desktop (one 6-col tile plus two 3-col tiles per row), becoming a horizontal snap-scroll row on mobile.
- Shop by Style: a horizontal editorial scroller of 4:5 composition tiles with the serif name beneath.
- Inspiration and Customer Walls: masonry, 4 columns wide, 3 desktop, 2 mobile.

**Design My Wall section:** a split with the empty-wall photograph on the left and the same wall with a composition on it on the right, sitting on the Unfired-slip band. Steps 01–04 run in a row beneath, with serif numerals. This is the only full-width tinted band on the homepage.

**Mobile:** the header holds logo, search, cart and menu. A fixed 64px bottom nav holds Home, Shop, **Design** (terracotta icon and label, the accent's job), Inspiration and Cart. The product page keeps Add to Cart in a sticky bottom bar above the nav. Touch targets are at least 44px.

**Prices** use South Asian digit grouping (`Intl.NumberFormat('en-IN')`), ৳ directly before the number with no space: ৳2,990, ৳1,20,000.

## Elevation & Depth

The storefront is flat. Depth comes from paper, not light.

1. **Tonal layering.** Plaster (#F1ECE3) on Lime-wash (#F9F6F0) makes a card a different sheet of paper, not a floating object.
2. **Hairlines.** 1px Plaster-seam (#DFD8CF) rules between filter groups, cart rows and checkout sections. Rules divide, they don't enclose.
3. **Space** for grouping. 8px between related items and 48px between groups.

**One shadow exists, and only for things that are physically above the page:** modals, drawers, dropdowns, toasts and the draggable composition in the visualiser. It is drawn from Lamp-black with light from above: `0 1px 2px rgba(33,29,26,0.08), 0 12px 32px -8px rgba(33,29,26,0.18)`. Cards, product tiles and buttons never have a shadow, at rest or on hover.

The **artwork itself** is the one thing that looks physically real. Framed mockups carry the photographic shadow a frame casts on a wall. That is part of the photograph, not a UI effect.

Modal and drawer scrims are Lamp-black at 40% with no backdrop blur.

## Shapes

Radius follows a hierarchy tied to what an object is:

- **0px: artwork and frames.** A frame is a rectangle. Framed pieces, mockup crops inside the visualiser and label plates are always square-cornered, however rounded their container is.
- **2px: things you press or type into.** Buttons, inputs, selects, badges, toasts and tooltips. The near-square edge echoes a mat board and keeps actions from looking like app chrome.
- **6px: photographs and cards.** Product cards, room tiles, collection tiles and inspiration images. This is the "slightly rounded card" the brand asked for, and it softens the paper edge without turning the grid into bubbles.
- **12px: large surfaces.** Modals, the upload zone and the top corners of mobile drawers.
- **Full: toggles and swatches.** Filter chips, step pills and frame-colour swatches.

**Borders.** Inputs, selects, secondary buttons and idle filter chips use 1px solid Plaster seam (#DFD8CF). The secondary button border is 1px Lamp-black, per the brief's "light background + dark border". On focus, every interactive element shows a 2px Lamp-black outline with a 2px offset. On input-error, the border switches to Over-fired brick. Swatches get a 1px seam ring, plus a 2px Lamp-black ring when selected, so the white-frame swatch is visible on paper. These live in prose because the schema has no `borderColor` sub-token. They are normative.

The upload zone uses a **1.5px dashed** Ash border. It is the only dashed line in the system, and it means "drop something here".

## Components

**Buttons.** There are three levels plus the service variant.
- **Primary** (`button-primary`): Lamp-black fill, Lime-wash text. Used for Add to Cart, Continue to Checkout, Place Order, Save My Design and Order This Wall. One per view.
- **Secondary** (`button-secondary`): Lime-wash fill, 1px Lamp-black border. Used for Shop Gallery Walls, Visualize on My Wall and View collection.
- **Tertiary** (`button-tertiary`): text only, underlined 1px at a 4px offset. Used for Explore →, "I don't have a photo", "Share your wall with us" and Edit.
- **Design** (`button-design`): terracotta fill. **Only for the Design My Wall entry points.** When a hero pairs it with Shop Gallery Walls, Shop is secondary and Design is terracotta. That is the one case where two filled buttons would compete, so Shop steps down.

Every button is 52px tall on mobile and 48px on desktop. Hover is a colour step only (150ms), with no lift, scale or shadow.

**Navigation.** The desktop header is 72px on Lime-wash, with a hairline beneath once scrolled. The logo sits left and the nav links sit beside it in `label-md`. Search, Account and Cart are 20px line icons on the right, followed by the terracotta Design My Wall button. The active link gets a 1px underline, not a colour change.

**Product card** (`product-card`): a 4:5 room mockup of the whole wall, then the collection name in `headline-sm` serif ("Focus"), a `label-caps` line ("5 PIECES · 3 FRAME OPTIONS") in Ash, frame swatches, and the price in `price-md`. "View collection" is a tertiary link. There is no card fill or border, because the photo is the card. On hover (pointer devices only), the image cross-fades to the individual framed pieces laid out on Plaster (400ms). Badges ("New", "Made to order") sit top-left on the image as a label plate. There is never more than one badge per card and never a discount badge.

**Collection card / room tile** (`collection-card`): a full-bleed interior photo at 6px radius with a **label plate** in the lower-left corner. On hover the image scales to 1.03 over 600ms and the plate gains a second line, "Explore →".

**Label plate** (`label-plate`): the system's signature. It is a small square-cornered Lime-wash rectangle styled like a museum wall label, with `body-sm` text and `label-caps` for the secondary line. It is the only permitted way to put text on a photograph. Used for room names, badges, customer credits ("Focus Collection — Sarah, Dhaka") and inspiration captions.

**Price.** `price-md` on cards and `price-lg` on the product page, in Lamp-black with tabular figures. There is no "from" prefix unless sizes change the price, and then it reads "From ৳2,490". There is never a strikethrough.

**Frame swatches.** 28px circles in the three frame materials. The selected one gets a Lamp-black ring. Each has a visible text label beside the group ("Frame: Black"), and a swatch never relies on colour alone.

**Size selector (Small / Medium / Large).** A segmented control of 2px-radius cells with a 1px seam border. The selected cell is filled Lamp-black. The overall wall dimensions for each size appear beneath in Ash ("Medium, 120 × 90 cm overall"), so the customer understands the wall before any single-print size.

**Filters.** On desktop they are a left rail of collapsible groups (Room, Style, Colour, Pieces, Frame, Price) separated by hairlines. On mobile they open as a bottom drawer with a sticky "Show 24 walls" primary button. Applied filters appear as `filter-chip-selected` pills above the grid, each with an ×. Sort is a native `<select>` styled as `select`.

**Tabs** (`tab`, `tab-active`): text-only, with a 2px Lamp-black underline on the active tab. Used on the product page (Details / Dimensions / Installation) and the Inspiration categories (which scroll horizontally on mobile).

**Step indicator** (`step-active`, `step-idle`): a row of pills, "1 Your Wall" through "5 Order". The active step uses Unfired slip with the terracotta shade. Completed steps show a check in Ash, and upcoming steps are idle. On mobile it collapses to "Step 2 of 5 · Your Style" with a thin progress rule.

**Upload zone** (`upload-zone`): a Plaster panel with a 12px radius and a dashed Ash border, holding a `headline-sm` prompt ("Upload a photo of your wall") and a tertiary "I don't have a photo". It accepts drag-drop, tap-to-browse and camera capture on mobile (`accept="image/*" capture="environment"`). While dragging over, the border goes solid Lamp-black. After upload, the photo replaces the panel's contents at its own aspect ratio.

**Visualiser.** A full-screen modal. The customer's wall photo fills the canvas, the composition floats above it with the one system shadow, and a toolbar of icon + label buttons (Move, Scale, Rotate, Frame, Artwork) sits beneath on mobile or to the right on desktop. The primary action is Save My Design, with Add to Cart secondary. Changes to frame or artwork cross-fade in 250ms.

**Modal / Drawer.** Modals are Lime-wash with a 12px radius and the system shadow. Full-screen on mobile. The cart drawer slides from the right on desktop (440px) and from the bottom on mobile. Close is always top-right and Esc closes it.

**Cart and checkout.** Each line item shows a wall thumbnail (never a single print), the collection, pieces, frame, size, a quantity stepper and the price. Rows are separated by hairlines with no cards. Checkout is a single column, 560px max, with sections for Details, Address, Phone, Delivery and Payment separated by rules. Payment is **four equal radio tiles**: bKash, Nagad, Card, Cash on Delivery. Each shows the official logo (or a line icon for COD) and a label. The selected tile gets a 2px Lamp-black border and a filled radio. Phone numbers expect the `+880 1XXX-XXXXXX` format and use `inputmode="tel"`.

**Toast** (`toast`): Lamp-black with Lime-wash text and a check icon, bottom-centre on mobile above the nav and bottom-left on desktop. Auto-dismisses after 4s and includes an action where useful ("View cart").

**Icons.** Use one line set (Phosphor "Light" or Lucide at 1.5px stroke), at 20px in UI and 24px in the bottom nav, in Lamp-black or Ash. Icons label actions. They are never decoration above section headings, and they never sit in tinted squares.

**Motion.**
- Image hover scale: 1.03 over 600ms, `cubic-bezier(0.22, 1, 0.36, 1)`.
- Product image cross-fade: 400ms.
- State changes (hover, selection): 150ms ease-out.
- Drawers and modals: 280ms enter (decelerate) and 200ms exit (accelerate).
- Page transitions: a 200ms opacity cross-fade.
- Scroll reveal: **images only**. They fade in once over 400ms with no translate.

**Text, prices, buttons and navigation never animate in.** Everything is disabled under `prefers-reduced-motion`.

## Do's and Don'ts

- **Do** keep terracotta (`tertiary`) on Design My Wall entry points and inside that flow only. If it appears on Add to Cart, a link or a badge, the service stops being findable.
- **Don't** add a discount badge, a strikethrough price, a countdown or a star rating to a card. Promotions are one line of body copy in Lamp-black.
- **Do** show the complete wall first on every product surface: card, product-page hero, cart thumbnail, order confirmation. Individual prints and their dimensions come second, one tap deeper.
- **Don't** put text on a photograph except inside a square-cornered Lime-wash label plate. No scrims, no gradient overlays, no white text on images.
- **Don't** bold the serif. Instrument Serif is used at 400 only. If a headline needs more presence, give it more size or more space above.
- **Do** set every price, dimension and number in Hind Siliguri with tabular figures, ৳ first with no space, and en-IN grouping. The serif has no taka glyph.
- **Don't** round artwork or frames, even when their container card is rounded. A rounded frame instantly reads as a cheap template.
- **Don't** use pure `#FFFFFF` or `#000000`, including behind product cut-outs. Individual-piece shots go on Plaster.
- **Don't** add a success green or a warning amber. Confirmations are Lamp-black toasts, and errors are Over-fired brick with an icon and a message.
- **Do** keep gallery walls one per row on phones. A five-piece composition at half-width is unreadable, and readability of the whole wall is the product.
- **Don't** centre text blocks or headings, including in the hero, modals and empty states.
- **Don't** fade-up sections on scroll. Only images reveal, once, without movement.
- **Do** render Bangla text and customer-entered addresses in Hind Siliguri at the same size as the English. Never let a system Bengali fallback font appear.
