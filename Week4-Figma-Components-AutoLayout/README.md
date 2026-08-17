# Week 4 — Figma Components & Auto Layout

## Responsive UI Component Library

This repository contains the Week 4 design-system documentation and supporting assets for a responsive component library in Figma.

### Required Tasks
1. Create reusable master UI components inside Figma.
2. Apply Auto Layout so components adapt to varying content lengths.
3. Build interactive variants for hover, active and focus states.
4. Assemble responsive card templates using component instances.
5. Document spacing variables and design tokens.

### Recommended Figma structure
```
Week 4 — Component Library
├── Foundations
│   ├── Colors
│   ├── Spacing
│   ├── Radius
│   └── Typography
├── Components
│   ├── Buttons
│   ├── Inputs
│   └── Cards
├── Variants
└── Responsive Examples
```

### Components

**Button/Primary**
- Auto Layout: Horizontal
- Padding: 12px vertical / 16px horizontal
- Gap: 8px
- Width/Height: Hug contents
- Radius: 8px
- Variants: Default, Hover, Active, Focus, Disabled

**Card/Responsive**
- Auto Layout: Vertical
- Padding: 24px
- Gap: 16px
- Width: Fill container
- Height: Hug contents
- Radius: 16px
- Nested Header, Body and Footer

**Input/Default**
- Auto Layout: Horizontal
- Padding: 12px / 16px
- Gap: 8px
- Width: Fill container
- Height: 48px
- Variants: Default, Focus, Error, Disabled

### Submission
Create the actual components, Auto Layout settings, variants, instances and prototype interactions in Figma. Upload this documentation and token file to GitHub, add the Figma link to this README, then submit your repository URL in the internship portal.
