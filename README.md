# iOS & iPadOS 26 — Liquid Glass Design System

A complete, single-file HTML reference for Apple's Liquid Glass design language (WWDC 2025).

Every token, typographic scale, color, component, and motion spec — precisely documented.

## Sections

1. **Design Tokens** — corner radii, spacing, durations, blur values
2. **Typography** — all 11 iOS text styles (Large Title → Caption 2)
3. **System Colors** — 12 system colors × light/dark
4. **Semantic Colors** — label, fill, separator, background hierarchy
5. **Materials** — Glass Regular, Clear, Identity (over real aurora gradient)
6. **Navigation** — nav bar, large title, floating tab bar, iPad sidebar
7. **Controls** — buttons (5 sizes, 3 shapes), segmented, toggles, sliders, steppers
8. **Inputs** — text fields (5 states), search, wheel picker, color picker
9. **Feedback** — alerts, bottom sheet, toasts, badges, progress, spinners
10. **Content** — lists, app icons, cards, widgets (3 sizes), Control Center
11. **Motion** — spring curves, 6 interactive animation demos

## Features

- **Dark / Light mode** toggle with `localStorage` persistence
- **Mouse-driven specular highlights** on glass surfaces
- **Sidebar IntersectionObserver** — active link follows scroll
- Full keyboard accessibility, `prefers-reduced-motion` and `prefers-reduced-transparency` support
- Single file, no dependencies, no build step

## Run locally

```bash
python3 -m http.server 8772
# open http://localhost:8772
```

## Built with

- `superpowers:liquid-glass` reference
- `frontend-design` skill
- Apple iOS 26 UI Kit (Figma Community) as visual reference
