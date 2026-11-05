# COMMIT-SHEET: Tooele Premium Home Services Demo

1. **Peak**: A high-impact, full-bleed hero section with a bold, type-led value proposition ("Tooele's Gold Standard in Home Comfort") and a background image of a luxury Tooele residence.
2. **Color**: 
   - Primary: OKLCH(0.25 0.05 260) [Midnight Navy]
   - Accent: OKLCH(0.80 0.15 85) [Construction Gold]
   - Tier: Committed.
   - Why: Avoids the "Light Blue/White" generic HVAC reflex. Dark navy signals authority and premium pricing; gold signals quality and "gold standard" service.
   - Background Lightness: L 0.15.
3. **Type**: 
   - Display: 'Outfit' (Geometric Sans)
   - Text: 'Plus Jakarta Sans' (Humanist Sans)
   - Contrast: Geometric + Humanist.
   - Why not Inter: Inter is the AI default; Outfit provides a more architectural, modern feel suited for construction/home services.
4. **Grid break**: The "Trust/Reviews" section will overlap the "Services" section using a negative margin and z-index shift, breaking the vertical stack.
5. **Motion budget**: 
   - Family 1: Soft fade-in-up (opacity 0 -> 1, translate-y 20px -> 0) for section headers.
   - Family 2: Staggered reveal for service cards (80ms interval).
   - Family 3: Subtle scale-up (0.98 -> 1.0) on CTA buttons on hover.
6. **Reflex check**: 
   - (a) First-order: White background, blue accents, generic stock photos of a guy with a wrench.
   - (b) Second-order: "Eco-friendly" green theme, minimalist flat icons, pastel colors.
   - (c) Deviation: High-contrast "Dark Mode" luxury aesthetic. Focuses on *results* (beautiful homes) rather than *tools* (wrenches).
7. **House tells broken**: 
   - No "Eyebrow kickers" above every section; only used once for the "Expertise" section.
   - No "Purple-Blue" gradients; strictly Navy and Gold.
