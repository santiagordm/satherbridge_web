# Sather Bridge website: design rules

These rules govern all design work on this repository. They take priority over any generic design skill or default.

## Philosophy
Premium, human-crafted, Apple-inspired. The page must not look like a generic AI-generated template.

## Constraints
1. **Typography first.** One sans-serif family only: Inter (Google Fonts). Never a serif. Strong weight contrast: 800 for headings, 600 for subheadings, 400 for copy. Line height 1.5–1.6.
2. **Anti-AI rule.** No generic dashboard grids, no small colorful boxes holding icons, no border-heavy containers or cards. Separate ideas with generous white space and alternating section backgrounds, not lines.
3. **Palette.** Strictly limited.
   - Light: background #FFFFFF, alternate band #F5F5F7, text #1D1D1F, secondary text #6E6E73, captions/logos #86868B.
   - Dark: background #000000, alternate band #1D1D1F, text #F5F5F7, secondary text #A1A1A6.
   - Accent: #1F4E79 (light) / #8DB4DC (dark), the navy from Santi's CV template. Use only for critical interaction (buttons, links).
   - Body text must meet WCAG AA contrast; #86868B on white does not, so it is for captions and logos only.
4. **Micro-interactions.** Smooth, subtle transitions (ease-in-out, 300ms) on hover. No aggressive color flashes.

## Workflow
- **Pass 1 (vibe discovery):** for redesigns and new sections, present the aesthetic structure and design tokens (color, spacing, type scale) and wait for approval.
- **Pass 2 (critique & code):** self-critique the layout for AI tropes or template defaults, fix them, then write the code.
- Small text or content edits skip Pass 1.

## Content rules
- Copy in English, plain language, no AI buzzwords (leverage, unlock, seamless, journey, landscape, ecosystem, empower, elevate...).
- Never publish confidential client information.
- Never invent or round up metrics.
