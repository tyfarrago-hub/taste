# Neumorphic Card System

Apply this design system whenever Tyler asks for cards to look "neu" or "neumorphic".

## Core Principles
- Light source: top-left (negative shadows = light highlight, positive shadows = dark)
- NO flat borders — box-shadows define all edges
- NO high-opacity blacks — tinted shadows only for softness
- Staggered entrance delays (50ms increments) for cascading reveals

## Light Mode Cards (on sand/cream backgrounds `#f4f1ec`)
```css
.card {
  background: #f4f1ec;
  border-radius: 22px;
  border: none;
  box-shadow: 9px 9px 22px #cec8bf, -9px -9px 22px #ffffff;
  transition: transform 0.4s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.4s;
}
.card:hover {
  transform: translateY(-4px) scale(1.01);
  box-shadow: 12px 14px 30px #c4beb5, -9px -9px 22px #ffffff;
}
```

## Dark Mode Cards (on navy backgrounds `#152a4a`)
```css
.card-dark {
  background: rgba(255,255,255,0.04);
  border-radius: 22px;
  border: 1px solid rgba(255,255,255,0.06);
  box-shadow: 8px 8px 24px rgba(0,0,0,0.4), -4px -4px 16px rgba(255,255,255,0.03);
  transition: transform 0.4s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.4s;
}
.card-dark:hover {
  transform: translateY(-4px) scale(1.01);
  box-shadow: 12px 16px 40px rgba(0,0,0,0.5), -4px -4px 16px rgba(255,255,255,0.04);
}
```

## Inset Fields (form inputs on light bg)
```css
.field-inset {
  background: #f4f1ec;
  border: none;
  border-radius: 16px;
  box-shadow: inset 4px 4px 10px #cec8bf, inset -4px -4px 10px #ffffff;
}
.field-inset:focus {
  box-shadow: inset 4px 4px 10px #c4beb5, inset -4px -4px 10px #ffffff, 0 0 0 2px rgba(94,184,162,0.3);
}
```

## Icon Badges (small neumorphic containers)
```css
.icon-badge {
  background: #f4f1ec;
  border-radius: 14px;
  box-shadow: 5px 5px 12px #cec8bf, -5px -5px 12px #ffffff;
}
```

## Typography
- Headings: semi-bold (600), letter-spacing -0.02em
- Body: medium (500) or regular (400)
- Timing function: cubic-bezier(0.34, 1.56, 0.64, 1) for bouncy hover
- Hover: translateY(-4px) scale(1.01-1.02)

## Key Rule
Always match the shadow tint to the background color. On `#f4f1ec`, dark shadow is `#cec8bf` (14% darker), light shadow is `#ffffff`. On navy, dark shadow is deep black with low opacity, light shadow is white with very low opacity (0.03-0.04).
