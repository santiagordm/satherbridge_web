# Sather Bridge website: design rules

These rules govern all design work on this repository. They take priority over any generic design skill or default.

## Philosophy
Premium, human-crafted, Apple-inspired. The page must not look like a generic AI-generated template.

## Constraints
1. **Typography first.** One sans-serif family only: Inter (Google Fonts). Never a serif. Strong weight contrast: 800 for headings, 600 for subheadings, 400 for copy. Line height 1.5–1.6.
2. **Anti-AI rule.** No generic dashboard grids, no small colorful boxes holding icons, no border-heavy containers or cards. Separate ideas with generous white space and alternating section backgrounds, not lines.
3. **Palette.** Strictly limited.
   - Light: background #FFFFFF, alternate band #FAFAF7 (warm off-white from the slide template), text #1D1D1F, secondary text #6E6E73, captions/logos #86868B.
   - Light only: the site does not switch to a dark theme, whatever the visitor's system setting. The contact band and footer use #1D1D1F with text #F5F5F7 / #A1A1A6.
   - Accent: #1C786F (contrast 5.3:1 on white), the green from Santi's slide template. Use only for critical interaction (buttons, links).
   - Body text must meet WCAG AA contrast; #86868B on white does not, so it is for captions and logos only.
4. **Micro-interactions.** Smooth, subtle transitions (ease-in-out, 300ms) on hover. No aggressive color flashes.
5. **Motion.** One idea only: things appear in order when you reach them (How I work line draws itself; engagement numbers and case highlights appear in sequence). Once, 300–900ms, ease-in-out. Content is fully visible without JavaScript or with reduced motion. No count-ups, no cursor effects, nothing that needs hover.

## Workflow
- **Pass 1 (vibe discovery):** for redesigns and new sections, present the aesthetic structure and design tokens (color, spacing, type scale) and wait for approval.
- **Pass 2 (critique & code):** self-critique the layout for AI tropes or template defaults, fix them, then write the code.
- Small text or content edits skip Pass 1.

## Content rules
- Copy in English, plain language, no AI buzzwords (leverage, unlock, seamless, journey, landscape, ecosystem, empower, elevate...).
- Never publish confidential client information.
- Never invent or round up metrics.
