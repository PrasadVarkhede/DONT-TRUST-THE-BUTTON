---
name: Arcade Mischief
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#32394b'
  surface-container-lowest: '#070e1e'
  surface-container-low: '#141b2c'
  surface-container: '#181f30'
  surface-container-high: '#232a3b'
  surface-container-highest: '#2e3447'
  on-surface: '#dbe2fa'
  on-surface-variant: '#d1c5ac'
  inverse-surface: '#dbe2fa'
  inverse-on-surface: '#293042'
  outline: '#9a9078'
  outline-variant: '#4e4633'
  surface-tint: '#efc110'
  primary: '#fff0cf'
  on-primary: '#3c2f00'
  primary-container: '#ffd027'
  on-primary-container: '#705900'
  inverse-primary: '#735c00'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#ffeded'
  on-tertiary: '#680019'
  tertiary-container: '#ffc7c8'
  on-tertiary-container: '#b70d35'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe087'
  primary-fixed-dim: '#efc110'
  on-primary-fixed: '#231a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffdada'
  tertiary-fixed-dim: '#ffb3b5'
  on-tertiary-fixed: '#40000c'
  on-tertiary-fixed-variant: '#920027'
  background: '#0c1324'
  on-background: '#dbe2fa'
  surface-variant: '#2e3447'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
  body-lg:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-badge:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  code-metric:
    fontFamily: Space Mono
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels the chaotic energy of 90s coin-op cabinets, bootleg puzzle electronics, and Saturday-morning cartoon villainy. The brand personality is unapologetically mischievous, subversive, tactile, and high-stakes humorous. It addresses casual to hardcore puzzle gamers seeking tactile satisfaction, sharp reactive visual gags, and psychological trickery.

The visual direction marries neo-brutalist tactile physical UI with classic arcade cabinet vernacular:
- **Chunky Arcade Brutalism:** Thick dark framing, offset mechanical drop shadows, and high-contrast layered die-cut panels.
- **Micro-Toy Affordance:** Buttons beg to be pressed (or avoided) with squashed physical states, extruded edges, and warning tape framing.
- **Expressive Game Meta:** Interfaces react with character—googly-eyed mascots, flickering neon hazard accents, and exaggerated visual states when traps spring.

## Colors

The palette establishes an arcade cabinet environment: deep cavernous midnight tones overlaid with vibrant, dangerous physical hardware components.

### Palette Roles
- **Primary (`#FFD027` Arcade Yellow):** The primary attractor. Used for the titular button, key rewards, active toggles, and high-visibility interaction triggers. Pairs with `#FFE066` for inner bevel highlights.
- **Secondary (`#00F0FF` Electric Cyan):** Logic, timer pulses, scan lines, tech readout accents, and interactive secondary pathways.
- **Tertiary (`#FF4B63` Hot Hazard Coral):** Trap warnings, self-destruct mechanisms, penalty alerts, and panic states.
- **Neutral Surface (`#FDF6E2` Warm Parchment):** The physical faceplate color for dialogs, cards, and modal popups, providing tactile contrast against the dark midnight chassis.
- **Chassis Base (`#0B0F19` & `#131A2B` Midnight Navy):** The overarching backdrop of the machine, keeping attention locked on the illuminated playfield.
- **Structural Stroke (`#141923` to `#1E2638` Dark Charcoal):** The bold boundary color for borders, hard shadows, and typography on cream panels.

### Contrast Application
- On **cream surfaces (`#FDF6E2`)**, all text and icons must use `#141923` or `#1E2638` for maximum comic-book legibility.
- On **dark chassis surfaces (`#0B0F19`)**, text defaults to crisp off-white (`#F8FAFC`) or neon electric cyan (`#00F0FF`).

## Typography

The typography pairs mechanical retro computing with loud, punchy arcade character:

- **Headlines (`Space Grotesk`):** Heavyweight geometric grotesk with eccentric ink traps and bold contours. Used in uppercase or dynamic headline capitalization for titles, stage numbers, challenge names, and punchlines.
- **Body & Counters (`Space Mono`):** Monospaced precision for timers, countdowns, warning logs, scores, and instructional dialogue, evoking terminal screens and retro circuit test equipment.
- **Badges & Microcopy (`Space Grotesk`):** Capitalized, tightened tracking for arcade callouts, high-stakes warnings, and inventory badges.

## Layout & Spacing

The layout is built around a responsive arcade bezel structure. Content behaves like physical game cartridges, cabinet panels, or dynamic LCD sub-displays nested inside the chassis.

- **Mobile (< 768px):** A single-column interface anchored by bottom control banks and top status readouts. Margin is set to `1rem` to maximize playable interaction space.
- **Tablet / Desktop (≥ 768px):** Fixed-ratio playboards centered horizontally within a deep navy frame, flanked by faux diagnostic panels, coin-op slots, and side dials. Maximum game board canvas is clamped to `960px`.
- **Rhythm & Grid:** A baseline 8px module governs spacing. Padding inside interactive tactile controls uses generous vertical breathing room (`space-md` to `space-lg`) to facilitate quick, chaotic touch input without accidental miss-clicks.

## Elevation & Depth

Visual depth avoids realistic lighting gradients or soft ambient blurs. Instead, elevation is rendered through **mechanical neo-brutalist extrusion**:

- **Hard-Edge Drop Shadows:** Elements utilize pure solid-color offsets (typically `#141923` or `#0B0F19`) at a strict 45-degree or direct 90-degree downward angle.
  - Floating Panels: `4px 4px 0px 0px #141923`
  - Big Play Buttons: `0px 6px 0px 0px #141923` resting state, reducing to `0px 1px 0px 0px` on active press.
- **Physical Extrusion Depths:** Interactive items appear mechanically raised. The default resting state displays an extruded bottom rim; the `:active` state translates the element downward (`translate-y-[4px]`) to simulate bottoming out a mechanical arcade switch.
- **Borders as Chassis Seams:** All interactive components and containers sport consistent `3px` or `4px` solid `#1E2638` borders, creating physical boundaries reminiscent of injection-molded plastic and stamped metal.

## Shapes

Shapes feature rounded corners (`0.5rem` base, `1rem` for major modal panels) combined with rigid internal structures. This balances the welcoming, cartoonish look of a classic toy with the industrial stability of an arcade game board.

- **Badges & Hazard Pills:** Full pill radiuses (`rounded-full`) provide a visual foil to the blocky game boards.
- **Mascot & Googly Elements:** Perfectly circular components with misaligned pupil offsets (`rounded-full`) convey comedic paranoia and mischief.

## Components

### Buttons
- **The Main Trap Button:** Rendered in `#FFD027` with a 4px solid `#141923` border and an extruded 6px `#141923` drop shadow. Includes an internal subtle top highlight stripe (`#FFE066`). On press, translates 4px down and reduces shadow to 2px. Often embellished with googly eye accents or warning tape decals.
- **Secondary Controls:** Electric Cyan (`#00F0FF`) or Parchment (`#FDF6E2`) with 3px `#141923` borders and 3px offset drop shadows.

### Cards & Faceplates
- Built with rich cream (`#FDF6E2`) backgrounds, 3px solid `#1E2638` border, and 5px 5px solid dark offset shadows. Internal compartments or header ribbons are dipped in midnight navy (`#131A2B`) with Space Grotesk white or cyan text.

### Badges & Micro-Tags
- Pill or chamfered tags featuring 2px borders, contrasting solid fill (`#FF4B63` danger coral or `#00F0FF` cyan), with Space Grotesk uppercase text tracking. Used for labels such as "DANGER", "DO NOT TOUCH", or "STAGE 04".

### Form Controls (Inputs, Checkboxes, Radios)
- **Checkboxes & Radios:** Chunky square tiles with 3px `#141923` borders. Check states fill with vibrant `#00F0FF` or `#FFD027` containing thick comic-style marks.
- **Input Fields:** Crisp parchment surface inset into the midnight navy chassis with an inverted inset look (`border: 3px solid #141923`), styled with `Space Mono` typography.

### Arcade Dials & Timers
- High-contrast LED-style display modules with midnight navy backgrounds, electric cyan monospaced numerals (`Space Mono`), and subtle grid line overlays simulating vintage segmented CRT monitors.