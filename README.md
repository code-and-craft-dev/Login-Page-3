# Imperial Emerald & Champagne Gold — Auth Portal (`Login-page-3`)

A single-file, responsive Login & Register portal (`index.html`) styled with a quiet-luxury **Alabaster, Imperial Emerald, and Champagne Gold** palette.

## Features & Design Highlights
- **Champagne Gold Frame & Porcelain Card**: A `1.5px` metallic gold gradient border surrounding an alabaster/porcelain card with a crisp inner highlight.
- **Imperial Emerald Diagonal Curtains**: Dual skewed emerald and porcelain panels (`0.95s` spring sweep) paired with staggered `0.58s` form and welcome-text transitions.
- **Editorial Typography**: `Playfair Display` (with italic accents on welcome headings) paired with `Plus Jakarta Sans`.
- **Refined Form UX**:
  - Floating labels using `:not(:placeholder-shown)` so invalid input text never overlaps its label.
  - Eye / eye-off password visibility toggle with `aria-pressed` state.
  - Pill toast notifications on form submission.
- **Accessibility & Responsiveness**:
  - Syncs `inert` and `aria-hidden` when switching between Sign In and Register.
  - Clear `:focus-visible` outlines and `@media (prefers-reduced-motion: reduce)` support.
  - Adaptive mobile layout (`<= 720px`) with a top emerald-gold accent bar.

## Usage
- **Full version:** Open `index.html` in any modern browser.
- **Minimal version:** Open `minimal/index.html` for a stripped-down variant without field icons, password toggles, stagger blur, or toast notifications.
