---
version: alpha
name: Studio Ma Félicité
description: Parisian event decoration and hosting studio. Wine, candle gold and linen cream, set in Playfair Display and Inter.
colors:
  primary: "#6B1B26"
  secondary: "#C9A96A"
  tertiary: "#7A4E63"
  neutral: "#FDFBF6"
  wine-900: "#3A0D16"
  wine-600: "#7E232D"
  wine-500: "#93303D"
  wine-50: "#F6ECEC"
  gold-600: "#A98A4E"
  gold-400: "#D4B87C"
  gold-300: "#E3CD9F"
  cream-100: "#F8F2E8"
  cream-200: "#EFE3D1"
  cream-300: "#E1D2B7"
  taupe-100: "#DED4C8"
  taupe-200: "#C9BCAC"
  taupe-300: "#B0A190"
  taupe-400: "#8E7F6E"
  taupe-500: "#6E6153"
  ink-500: "#3A342D"
  ink-700: "#242019"
  ink-900: "#14110D"
  error: "#DC2626"
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 4.4rem
    fontWeight: 400
    lineHeight: 1.06
    letterSpacing: -0.02em
  headline:
    fontFamily: Playfair Display
    fontSize: 3.4rem
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: -0.02em
  title-lg:
    fontFamily: Playfair Display
    fontSize: 1.875rem
    fontWeight: 400
    lineHeight: 1.2
  title-md:
    fontFamily: Playfair Display
    fontSize: 1.5rem
    fontWeight: 400
    lineHeight: 1.33
  title-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: 400
    lineHeight: 1.4
  quote:
    fontFamily: Playfair Display
    fontSize: 1.35rem
    fontWeight: 400
    lineHeight: 1.625
  numeral:
    fontFamily: Playfair Display
    fontSize: 1.875rem
    fontWeight: 400
    lineHeight: 1
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: 400
    lineHeight: 1.625
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.625
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.625
  label-kicker:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.28em
  label-button:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0.18em
  label-nav:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0.16em
  label-chip:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0.16em
  label-field:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.16em
rounded:
  xl: 0.75rem
  2xl: 1rem
  tile: 1.5rem
  card: 1.75rem
  panel: 2rem
  full: 9999px
spacing:
  page-gutter-sm: 20px
  page-gutter: 32px
  container-max: 1280px
  container-prose: 768px
  section-y-sm: 96px
  section-y-md: 128px
  section-y-lg: 160px
  heading-stack: 32px
  gallery-gap: 24px
  card-gap: 32px
  nav-height: 96px
  nav-height-solid: 80px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-button}"
    rounded: "{rounded.full}"
    padding: 16px 36px
  button-primary-hover:
    backgroundColor: "{colors.wine-600}"
    textColor: "{colors.neutral}"
  button-gold:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.ink-900}"
    typography: "{typography.label-button}"
    rounded: "{rounded.full}"
    padding: 16px 32px
  button-gold-hover:
    backgroundColor: "{colors.gold-400}"
    textColor: "{colors.ink-900}"
  button-ghost-on-dark:
    textColor: "{colors.neutral}"
    typography: "{typography.label-button}"
    rounded: "{rounded.full}"
    padding: 16px 32px
  link-arrow:
    textColor: "{colors.primary}"
    typography: "{typography.label-button}"
  link-arrow-anniversary:
    textColor: "{colors.tertiary}"
    typography: "{typography.label-button}"
  chip:
    textColor: "{colors.ink-700}"
    typography: "{typography.label-chip}"
    rounded: "{rounded.full}"
    padding: 10px 20px
  chip-selected:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.cream-100}"
  lang-switch-active:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.ink-900}"
    rounded: "{rounded.full}"
    padding: 4px 10px
  badge-numeral:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.numeral}"
    rounded: "{rounded.2xl}"
    padding: 20px 24px
  badge-numeral-anniversary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.neutral}"
  section-kicker:
    textColor: "{colors.wine-500}"
    typography: "{typography.label-kicker}"
  section-kicker-on-dark:
    textColor: "{colors.gold-300}"
    typography: "{typography.label-kicker}"
  section-kicker-legal:
    textColor: "{colors.gold-600}"
    typography: "{typography.label-kicker}"
  section-light:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink-500}"
    typography: "{typography.body-md}"
  section-alt:
    backgroundColor: "{colors.cream-100}"
    textColor: "{colors.ink-500}"
  section-wine:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
  hero:
    backgroundColor: "{colors.wine-900}"
    textColor: "{colors.neutral}"
    typography: "{typography.display}"
  stats-band:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.gold-300}"
    rounded: "{rounded.panel}"
    padding: 56px 48px
  card-service:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink-900}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.card}"
    padding: 32px
  card-form:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink-900}"
    rounded: "{rounded.panel}"
    padding: 48px
  card-glass:
    textColor: "{colors.neutral}"
    rounded: "{rounded.panel}"
    padding: 36px
  card-testimonial:
    textColor: "{colors.cream-100}"
    typography: "{typography.quote}"
    rounded: "{rounded.card}"
    padding: 36px
  gallery-tile:
    textColor: "{colors.neutral}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.tile}"
    padding: 24px
  icon-medallion:
    backgroundColor: "{colors.wine-50}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 48px
  input:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink-900}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xl}"
    padding: 14px 16px
  input-placeholder:
    textColor: "{colors.taupe-300}"
  input-chevron:
    textColor: "{colors.taupe-400}"
    size: 16px
  input-label:
    textColor: "{colors.taupe-500}"
    typography: "{typography.label-field}"
  input-error-text:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.error}"
  nav-solid:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink-900}"
    typography: "{typography.label-nav}"
    height: "{spacing.nav-height-solid}"
  nav-over-hero:
    textColor: "{colors.neutral}"
    typography: "{typography.label-nav}"
    height: "{spacing.nav-height}"
  footer:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.cream-200}"
    typography: "{typography.body-sm}"
  cookie-banner:
    backgroundColor: "{colors.ink-900}"
    textColor: "{colors.cream-100}"
    rounded: "{rounded.2xl}"
    padding: 20px 24px
  back-to-top:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    rounded: "{rounded.full}"
    size: 48px
---

# Design System: Studio Ma Félicité

## Overview

**Creative North Star: "The Candlelit Salon"**

The site is a Parisian reception room at dusk. Deep wine is the wall colour, gold is the candlelight that catches on a few edges, and linen cream is the table everything rests on. Visitors arrive in the dark, warm room (a full-height wine hero with a frosted-glass card), then step into the lit one (cream sections where photography and serif headlines carry the page), and return to wine for the moments that deserve a hush: the stats band and the testimonials.

The voice is composed and ceremonial, not loud. Headlines are set in a regular-weight high-contrast serif with a single italic accent; everything functional is whispered in small, widely tracked uppercase sans. Space is generous (sections breathe at 96 to 160px), corners are soft, and photography of real events is the main decoration. Motion is slow and settling: content rises into place once, images drift on hover, nothing bounces.

This system must never drift toward the pastel wedding template: no blush pink, no script or handwriting fonts, no generic bridal styling. The palette is wine, gold and cream, and the type is Playfair Display and Inter.

**Key Characteristics:**

- Wine and cream alternate as "dark room" and "lit room"; gold is an accent of light, never a field.
- Regular-weight serif headlines with one italic accent phrase each.
- Tiny uppercase labels with very wide tracking (0.14 to 0.28em).
- Pill buttons and chips, generously rounded cards (24 to 32px), no square corners on components.
- Warm, ink-tinted shadows and frosted glass on wine surfaces.
- Real event photography and video in every content block, with a warm gradient placeholder behind each asset.
- Slow ease-out motion on one signature curve, fully disabled under reduced motion.

## Colors

A three-family palette, wine, gold and cream, supported by taupe for borders and metadata and a warm near-black ink for text. Token names map directly to the Tailwind theme in `tailwind.config.js`: `primary` is `wine-700`, `secondary` is `gold-500`, `tertiary` is `mauve-600`, `neutral` is `cream-50`; every other token uses its Tailwind name.

### Primary

- **Salon Wine** (`primary`, Tailwind `wine-700`): The brand colour. Fills the primary button, selected chips, numbered badges, the marquee strip, the stats band, the testimonials section and the back-to-top button. On cream it is also the emphasis text colour: italic headline accents, arrow links, required-field asterisks, text selection.
- **Cellar Wine** (`wine-900`): The darkest room. Hero base colour and the start of the hero gradient (`wine-900` to `primary` to `ink-900`, top-left to bottom-right).
- **Warm Bordeaux** (`wine-600`): Hover state for anything filled with Salon Wine.
- **Garnet** (`wine-500`): Section kickers on cream surfaces only.
- **Wine Wash** (`wine-50`): Tinted fill for icon medallions and the form success panel.

### Secondary

- **Candle Gold** (`secondary`, Tailwind `gold-500`): The call to action on dark surfaces (hero button, cookie "accept"), the active language pill, and small ornaments: the 56px rule under kickers, list dashes, marquee diamonds.
- **Lit Gold** (`gold-400`): Hover state for Candle Gold fills and gold links.
- **Champagne Gilt** (`gold-300`): Gold as text on wine and ink: kickers, italic headline accents, stat numerals, stars, footer link hover, active carousel dot.
- **Antique Brass** (`gold-600`): Kicker on the legal pages only. It sits below 4.5:1 on cream, so keep it to that decorative label and do not extend it to body text.

### Tertiary

- **Dusk Mauve** (`tertiary`, Tailwind `mauve-600`): Category colour for anniversaries. Appears only on the anniversary service card (badge label, numbered badge, arrow link) to distinguish it from weddings, which use Salon Wine.

### Neutral

- **Linen Cream** (`neutral`, Tailwind `cream-50`): Page background, card surfaces, input fill, and the text colour on wine and ink.
- **Ivory Parchment** (`cream-100`): The alternate section background (Services, Contact) and long-form text on dark.
- **Warm Vellum** (`cream-200`): Secondary text on dark surfaces, always at reduced opacity (55 to 85%), and soft blurred background blooms.
- **Sand** (`cream-300`): Start of the image placeholder gradient only.
- **Stone 100 / 200** (`taupe-100`, `taupe-200`): Hairline borders. 100 for card outlines and dividers, 200 for inputs, chips and outlined icon buttons.
- **Stone 300 / 400** (`taupe-300`, `taupe-400`): Input placeholder text and the select chevron; also the end of the placeholder gradient.
- **Stone 500** (`taupe-500`): Metadata: field labels, captions, helper text, list items in service cards.
- **Soft Ink** (`ink-500`): Body paragraphs on cream.
- **Ink** (`ink-700`): Default body colour; chip and outlined-button text.
- **Espresso Ink** (`ink-900`): Headlines on cream, text on gold, and the footer and cookie-banner surface.
- **Error Red** (`error`, Tailwind `red-600`): Form validation messages only; the invalid field border is the lighter Tailwind `red-400`.

The Tailwind config also defines `wine-300`, `mauve-500`, `mauve-700` and a `dustyblue` family that no page uses. They are not part of the system until a design needs them.

### Named Rules

**The Candlelight Rule.** Gold is light, not paint. It fills exactly one kind of thing: the action that matters on a dark surface. On cream, gold is limited to hairlines and dashes, and emphasis is carried by Salon Wine instead.

**The Two Rooms Rule.** Light sections alternate Linen Cream and Ivory Parchment; wine is reserved for the hero, the marquee, the stats band and testimonials; Espresso Ink closes the page. Do not introduce a fourth surface colour.

**The One Category Colour Rule.** Dusk Mauve marks anniversaries and nothing else. A new service category needs its own considered hue, not a reuse of mauve or a tint of wine.

## Typography

**Display Font:** Playfair Display (with Georgia, serif)
**Body Font:** Inter (with system-ui, sans-serif)

**Character:** A high-contrast Parisian serif at regular weight does all the talking; a neutral grotesque does all the labelling. The contrast between large, quiet serif and tiny, wide-tracked uppercase sans is the system's typographic signature.

### Hierarchy

- **Display** (400, 2.75rem mobile rising to 4.4rem at `lg` and 4.9rem at `xl`, line-height 1.06, tracking -0.02em): The hero headline only. One per page.
- **Headline** (400, 2.25rem rising to 3rem at `sm` and 3.4rem at `lg`, line-height 1.1, tracking -0.02em): Section titles. Legal page titles use the same face at 2.25 to 3rem.
- **Title** (400; `title-lg` 1.875rem for service card names, `title-md` 1.5rem for step names, the form title, mobile menu links and legal subheads, `title-sm` 1.25rem for gallery captions and contact details): Serif titles inside components.
- **Quote** (400, 1.125rem rising to 1.35rem at `lg`, line-height 1.625): Testimonial text, upright. The single pull quote in the About copy is 1.125rem italic in Salon Wine.
- **Numeral** (400, 1.875rem, line-height 1): Step and badge numbers. Stat numerals use the same face at 2.25 to 3rem in Champagne Gilt.
- **Body** (400; `body-lg` 1.125rem for the hero lead, `body-md` 15px on mobile and 1rem from `sm`, `body-sm` 0.875rem for descriptions and footer; line-height 1.625): Inter. Keep paragraphs under roughly 65 to 75 characters per line; lead paragraphs are capped at 36rem.
- **Label** (uppercase; `label-kicker` 10 to 11px at 0.28em, `label-nav` 13px/500 at 0.16em, `label-button` 12px/600 at 0.18em, `label-chip` 11px/600 at 0.16em, `label-field` 11px at 0.16em): Kickers, navigation, buttons, chips, field labels and metadata.

The site ships in French, English and Chinese from one template. Playfair Display and Inter carry no CJK glyphs, so Chinese text renders in the system serif and sans fallbacks; layouts must hold with all three copy lengths.

### Named Rules

**The Italic Accent Rule.** A headline may italicise one word or short phrase, coloured Champagne Gilt on dark or Salon Wine on cream. Never italicise a whole headline, and never use bold for emphasis in a serif line.

**The Whispered Label Rule.** Uppercase is for Inter labels at 13px and below, always tracked at 0.14em or wider and never heavier than 600. Serif text is never uppercased.

**The Regular Weight Rule.** Playfair Display is set at 400 everywhere. Size and italics create hierarchy; weight does not.

## Layout

A centred, fixed-maximum container (1280px) with 20px side gutters on mobile and 32px from `sm` (640px). Legal and other long-form pages use a narrower 768px column. Breakpoints are Tailwind's defaults; the structural shift happens at `lg` (1024px), where the navigation expands, two-column sections form, and the testimonial carousel goes from one card to three.

- **Section rhythm:** 96px vertical padding on mobile, 128px from `sm`, 160px from `lg`. The marquee strip is the one tight band (20px).
- **Section header:** kicker with its 56px gold rule, 32px gap, headline, then a 24px gap to an optional lead paragraph. Headers are left-aligned by default; Services centres its header in a 48rem column.
- **Grids:** 12-column splits at `lg` (7/5 in the hero and contact, mirrored), an even two-column About, a three-column gallery (two at `sm`, one on mobile) with 20 to 24px gaps, and a four-column process strip and stats band (two columns below `lg`).
- **Overlap as composition:** elements deliberately break their container: the secondary About photo and the "5+" badge hang off the main image, and each service card's numbered badge straddles the image edge (pulled up 56 to 64px).
- **Media ratios:** gallery tiles 4:3, service card images 16:11, portrait compositions 4:5 and 3:4. All media is `object-cover` over the warm placeholder gradient.
- **Fixed chrome:** header at 80px (96px at `lg`), shrinking to 64px (80px at `lg`) once the page scrolls past 40px; back-to-top button 24px from the bottom-right after 600px of scroll; cookie banner docked bottom-centre at a 768px maximum width.

## Elevation & Depth

A hybrid system. Sections are flat fields of colour and separate by tone (cream to parchment to wine). Within a section, cards lift on soft, warm shadows, and on wine surfaces depth comes from frosted glass instead of shadow.

### Shadow Vocabulary

- **Soft** (`box-shadow: 0 4px 24px -6px rgba(36,32,25,.10)`): Resting state for cards on cream (service cards, form panel) and the solid navigation bar.
- **Lift** (`box-shadow: 0 22px 50px -18px rgba(36,32,25,.30)`): Photography, numbered badges, the stats band, the cookie banner and back-to-top button; also the hover state of soft cards and filled buttons.
- **Glass** (`box-shadow: 0 8px 40px -12px rgba(8,37,28,.45)`): The hero's frosted card only.

### Glass and scrims

- **Frosted glass:** Linen Cream at 7 to 10% opacity with a heavy backdrop blur and a 15 to 20% cream hairline border. Used for the hero card and testimonial cards, and only over wine.
- **Solid navigation:** Linen Cream at 92% with backdrop blur and the Soft shadow.
- **Image scrim:** a bottom-up Espresso Ink gradient (85% to 15% to transparent) under gallery captions, deepening slightly on hover.
- **Atmosphere:** large radial gold glows at 16 to 22% opacity and blurred colour blooms sit behind wine and cream sections. They are background light, never foreground shapes.

### Named Rules

**The Warm Shadow Rule.** Shadows are tinted with ink (36, 32, 25), wide, and pulled in with negative spread. Never use neutral grey or pure black shadows, and never a hard-edged one.

**The Glass on Wine Rule.** Frosted surfaces exist only on dark wine backgrounds. On cream, a card is an opaque Linen Cream surface with a Stone 100 hairline and a Soft shadow.

## Shapes

Everything a visitor can touch is fully rounded; everything that holds content is generously curved. Buttons, chips, the language switch, icon medallions, avatars and carousel dots are pills or circles (`full`). Containers step up in radius with size: inputs 12px (`xl`), badges and banners 16px (`2xl`), gallery tiles 24px (`tile`), service and testimonial cards 28px (`card`), large panels such as the hero glass card, the stats band, the form card and hero-scale photographs 32px (`panel`).

Borders are 1px hairlines: Stone on cream, cream at 12 to 35% opacity on dark. Ornament is linear and fine: a 56px by 1px Candle Gold rule under each kicker, gradient hairlines that fade to transparent at both ends, small gold diamonds between marquee names. Icons are outline-only, 1.5 to 1.8px stroke, round caps and joins, drawn on a 24px grid and inheriting the text colour.

Only full-bleed section bands and hairlines have square edges.

## Components

Refined and ceremonial: components sit quietly at rest and answer a hover with a small lift, a colour warming, or an arrow sliding 4px.

### Buttons

- **Shape:** Full pill (`full`), label in `label-button` (12px, 600, uppercase, 0.18em), often followed by a 16px outline arrow.
- **Primary:** Salon Wine fill with Linen Cream text, 16px by 36px padding. The main action on cream surfaces (form submit).
- **Gold:** Candle Gold fill with Espresso Ink text, 16px by 32px. The main action on dark surfaces (hero, cookie accept at a compact 10px by 20px).
- **Ghost on dark:** Cream hairline (35% opacity) over a 5% cream tint with backdrop blur and Linen Cream text. Secondary action beside a gold button.
- **Hover / Focus:** 300ms. Filled buttons warm one step (wine to Warm Bordeaux, gold to Lit Gold), rise 2px and gain the Lift shadow; the arrow slides 4px right. Ghost buttons brighten fill and border. Disabled buttons drop to 60% opacity.
- **Arrow link:** Text-only action in `label-button` style with a trailing arrow, Salon Wine on cream (Dusk Mauve on the anniversary card), Champagne Gilt on dark. On hover the gap to the arrow widens.
- **Icon buttons:** 36 to 48px circles with a hairline border (carousel arrows, social links, the 44px menu toggle). On hover they fill: wine on cream, cream or gold on dark.

### Chips

- **Style:** Pill with a Stone 200 hairline, transparent fill, Ink text in `label-chip`, 10px by 20px padding.
- **State:** Selected chips fill Salon Wine with cream text and a wine border; hover darkens the border to wine. Used for portfolio filters (single-select tabs) and the "what do you need" options in the form (multi-select checkboxes, with a 2px wine focus ring at 30% opacity).
- **Language switch:** Three small pills inside one hairline pill; the active language fills Candle Gold with Espresso Ink text.

### Cards / Containers

- **Service card:** Linen Cream surface, Stone 100 hairline, 28px radius, Soft shadow. A 16:11 image on top with a frosted cream category pill in its corner, a numbered badge straddling the image edge, then a `title-lg` name, body copy, a dash list in Stone 500 with gold dashes, and an arrow link. On hover the card rises 6px to the Lift shadow and its image scales to 110% over 900ms.
- **Numbered badge:** 16px radius block in Salon Wine (Dusk Mauve for anniversaries) with a serif numeral, optionally a kicker line beneath, 20px by 24px padding, Lift shadow. Also used for the "5+ years" badge and the four process steps.
- **Glass card:** See Elevation. 32px radius in the hero with a gold gradient hairline along its top edge; 28px radius for testimonials, which hold a gold quotation mark, the quote, and a hairline-separated author row with a 48px avatar.
- **Stats band:** 32px radius Salon Wine panel, four centred serif numerals in Champagne Gilt over kicker-style labels, divided by 12% cream hairlines at `lg`.
- **Form panel:** Linen Cream surface, Stone 100 hairline, 32px radius, Soft shadow, padding growing from 28px to 48px.
- **Icon medallion:** 48px circle in Wine Wash with a faint wine hairline and a wine outline icon; on dark, a 36px circle in gold at 20% with a gold hairline.

### Inputs / Fields

- **Style:** Linen Cream fill, Stone 200 hairline, 12px radius, 14px by 16px padding, 15px Espresso Ink text, Stone 300 placeholder. Labels sit above in `label-field` (Stone 500) with a wine asterisk for required fields. Selects hide the native arrow and show a Stone 400 chevron.
- **Focus:** Border turns Salon Wine with a 3px wine ring at 10% opacity; no default outline.
- **Error:** Border turns light red and a 12px Error Red message appears beneath the field.
- **Success:** The form is replaced by a Wine Wash panel (16px radius) with a 56px wine check medallion, a serif title and an underlined reset link.

### Navigation

- **Over the hero:** Transparent, Linen Cream text, 80px tall (96px at `lg`). Wordmark is a 40px cream circle holding the logo mark, the studio name in serif, and a 10px kicker beneath.
- **After 40px of scroll:** 92% Linen Cream with backdrop blur, Soft shadow, Espresso Ink text, 64px tall (80px at `lg`). The change animates over 500ms.
- **Links:** `label-nav`. A 1px underline in the current text colour grows from the left over 350ms on hover and stays on the section in view.
- **Mobile (below `lg`):** A 44px circular menu toggle whose three bars fold into a cross. The menu expands downward as a blurred cream sheet with serif `title-md` links separated by Stone hairlines, and the language switch centred at the bottom with 44px touch targets.
- **Footer:** Espresso Ink surface with Warm Vellum text at 70%, kicker-style column headers at 50% cream, links that turn Champagne Gilt on hover, and an italic serif motto in gold.

### Gallery Tile

A 4:3 image or silent looping video with a 24px radius and the ink scrim. The caption (gold kicker plus `title-sm` name in cream) sits bottom-left with 24px padding, resting 8px low and rising into place on hover while the media scales to 110% over 1100ms. Videos play only while in view and fall back to their poster under reduced motion. Filtering fades tiles in from 14px below.

### Marquee

A Salon Wine strip of venue names in italic serif (Warm Vellum at 55%) separated by Candle Gold diamonds, scrolling left continuously over 38 seconds.

### Motion

- **Signature curve:** `cubic-bezier(.16, 1, .3, 1)`, a long ease-out, used for reveals, the hero entrance, the nav underline and the carousel.
- **Entrance:** Hero elements fade up 24px over 0.8s, staggered by 0.12s. Below the fold, blocks fade up 28px over 0.9s once, the first time they enter the viewport.
- **Hover:** 300ms for colour, shadow and lift; 500ms for card lift and caption movement; 900 to 1100ms for image zoom.
- **Carousel:** Slides move over 0.7s and advance every 6 seconds; dots are 6px bars, the active one widening from 10px to 32px in Champagne Gilt.
- **Reduced motion:** All animation and transition durations collapse, reveals show immediately, autoplay and video playback stop.

## Do's and Don'ts

### Do:

- **Do** keep to wine, gold and cream, with taupe and ink as the only neutrals; follow the Two Rooms Rule when adding a section.
- **Do** use a gold button for the main action on wine or ink surfaces and a wine button on cream; one filled button per view.
- **Do** set every headline in Playfair Display at weight 400 with at most one italic accent phrase.
- **Do** open each section with an uppercase kicker (11px, 0.28em) and its 56px gold rule, then a 32px gap to the headline.
- **Do** make interactive elements pills or circles and give containers a 24 to 32px radius by size.
- **Do** use the Soft and Lift shadows as written, and frosted glass only over wine.
- **Do** lead with real event photography or video in 4:3, 16:11 or portrait ratios, over the warm placeholder gradient.
- **Do** animate on the signature ease-out curve, once on entry, and honour `prefers-reduced-motion`.
- **Do** check every new block in French, English and Chinese; add text through the i18n dictionary in `index.html`.

### Don't:

- **Don't** drift toward a pastel wedding template: no blush pink, no script or handwriting fonts, no generic bridal styling.
- **Don't** use gold as a large fill or as body text on cream; Antique Brass and Candle Gold fall below 4.5:1 there.
- **Don't** uppercase or embolden serif text, or set labels heavier than 600.
- **Don't** use square-cornered buttons, cards, inputs or images.
- **Don't** use grey or black shadows, hard-edged shadows, or glass panels on cream backgrounds.
- **Don't** reuse Dusk Mauve outside the anniversary category, or pull in the unused `dustyblue`, `wine-300` or other dormant palette steps without a reason.
- **Don't** add bouncing, elastic or looping decorative animation; the marquee and the hover zoom are the only continuous motion.
- **Don't** hand-edit `en/index.html`, `zh/index.html` or `css/tailwind.css`; they are build output.
