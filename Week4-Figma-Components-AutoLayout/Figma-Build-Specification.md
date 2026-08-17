# Week 4 Figma Build Specification

## 1. Foundations
Color variables: Primary #2563EB, Hover #1D4ED8, Surface #FFFFFF, Text #0F172A, Muted #64748B, Border #E2E8F0, Focus #93C5FD.

Spacing: 4 / 8 / 16 / 24 / 32 / 48 px.
Radius: 8 / 12 / 16 px.

## 2. Button/Primary
Create one master component with properties:
- State: Default / Hover / Active / Focus / Disabled
- Has Icon: True / False
- Label: Text

Auto Layout: Horizontal, gap 8px, padding 12px vertical and 16px horizontal, Hug contents.

## 3. Card/Responsive
Structure:
Card → Header → Icon + Title
Card → Body → Description
Card → Footer → Secondary Action + Primary Action

Auto Layout:
- Card: Vertical, padding 24px, gap 16px, Fill Container width, Hug height.
- Header: Horizontal, gap 12px.
- Body: Vertical, gap 8px.
- Footer: Horizontal, gap 8px.

Test short and long titles/descriptions and different button labels.

## 4. Input/Default
Create Default, Focus, Error and Disabled variants.
Use Fill Container for the input field and 48px height.

## 5. Prototype
Connect Default → Hover using While Hovering; Hover → Active using While Pressing; Default → Focus using an interaction representing focus. Disabled should have no interaction.
