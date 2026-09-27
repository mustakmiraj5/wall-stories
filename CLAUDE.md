# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

@AGENTS.md

## Commands

```sh
npm run dev     # dev server at http://localhost:3000
npm run build   # production build (also type-checks)
npm run lint    # eslint (flat config: next core-web-vitals + typescript)
```

No test framework is set up yet.

## Stack

- Next.js 16 App Router (`app/`), React 19, TypeScript strict. Path alias `@/*` → repo root.
- Tailwind CSS v4, configured CSS-first: there's no `tailwind.config`. Theme tokens are declared with `@theme` in `app/globals.css`, and PostCSS loads `@tailwindcss/postcss`.
- Page props use Next's global generated types (e.g. `LayoutProps<"/">`), not hand-written prop interfaces.

## Design system

`DESIGN.md` (Google DESIGN.md format: YAML tokens + rationale) is the source of truth for all visual decisions. Wall Stories is a Bangladesh-based storefront selling complete, ready-to-hang gallery walls. Key constraints from it:

- Light-only (no dark mode), warm ivory surfaces, charcoal ink, one earthen accent (`tertiary`).
- Instrument Serif for display/headlines, plus a bilingual sans for UI text.
- No discount-store UI: no sale badges, strikethrough prices, countdowns or star clutter. Listing grids max 3 columns, 1 per row on mobile.

The app is still the create-next-app scaffold: `globals.css` has a dark-mode block and `layout.tsx` loads Geist. Both contradict DESIGN.md and should be replaced with its tokens when UI work starts. Validate edits to DESIGN.md with `npx -y @google/design.md@latest lint DESIGN.md` (the `design-md-planner` skill does this).
