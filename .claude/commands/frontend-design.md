---
description: Senior UX/UI design pass — add premium feel & depth without adding elements
---

You are acting as a senior UX/UI designer. Run a visual/execution pass on the current page (or the file the user names). This is a **visual pass only** — do not change copy, structure, or facts.

## Hard constraints — do not violate
- Do NOT change any text, copy, headline, subline, positioning, or facts.
- Do NOT invent metrics or claims.
- Do NOT change typefaces unless the user explicitly asks.
- Do NOT add new sections, testimonials, logos, stock images, or icons.
- Keep it a SINGLE static HTML file, no build step, no browser storage, deployable as-is.
- Preserve all existing links and mailtos.
- Keep it calm and uncluttered. If a change adds visual noise, don't make it.

## Create depth and premium feel through (subtlety is mandatory)

1. **Surface & background** — replace pure white with a refined off-white/warm-paper base. Give sections or cards a barely-perceptible layered surface (a second tone a few % different) so the page reads as planes, not one flat sheet. Consider a very faint large-scale radial or linear gradient — almost invisible. Optional ultra-subtle noise/grain texture at low opacity for tactility.

2. **Elevation** — give key blocks soft, low, diffused shadows (large blur, very low opacity, warm-tinted, not pure black) so they sit gently above the surface. Premium = soft and deep, never hard drop-shadows. Use multi-layer shadows for realism.

3. **Borders & detail** — replace flat hairlines with more considered dividers (subtle gradient borders, hairline + faint highlight). Refine border-radius for consistency.

4. **Typography polish** — tighten optical sizing and tracking, `text-wrap: balance` on headlines, improve vertical rhythm and measure. Make big numbers feel intentional and crafted (tabular nums, weight, tracking).

5. **Micro-depth on interaction** — refined hover (gentle lift/shadow on cards & rows), smooth easing, `:focus-visible` rings. Motion stays subtle; respect `prefers-reduced-motion`.

6. **Light & contrast** — gentle contrast between sections so scrolling has rhythm — one section on base tone, the next a hair deeper. Very subtle.

## Also
- Accessible: AA contrast in all states, semantic landmarks, correct heading order.
- Performant: no layout shift, optimized font loading (`font-display: swap`, preconnect).
- Proper meta/OG tags. Inline SVG favicon if not present.
- Invent no claims.

## Reference feel
The quiet, layered depth of a well-made product site (Linear, Vercel, Stripe) — premium through restraint and atmosphere, not decoration.

## After the pass
Push the commit, then reply with a concise summary of what changed (no narration of process).

$ARGUMENTS
