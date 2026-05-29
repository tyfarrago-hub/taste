---
name: cosmic-glass-dashboard
description: Build a dark "cosmic glass" dashboard — aurora-lit background, frosted glassmorphism panels, a per-section tone-tint system, cyan/violet/magenta accents, big tight-tracked headlines, pill buttons with light sweeps. Hands off as a drop-in theme.css + starter.html that you adapt to ANY use case (analytics, CRM, content, ops, fintech). Use when someone wants a premium dark dashboard in this exact visual language.
---

# Cosmic Glass Dashboard

A reusable, brand-agnostic design language for dark dashboards. The look: a deep navy page lit by soft colored auroras, frosted glass panels with gradient hairline borders, and a per-section "tone" tint that colors each card's glow, label dot, status pill, and icon. Big, tightly-tracked headlines; pill buttons with a light-sweep on hover; a fixed glass sidebar.

This skill ships two files you hand off and adapt:
- **`theme.css`** — the entire design system. The ONLY file a recipient needs. Plain CSS, framework-free (works with React, Vue, Svelte, plain HTML, or alongside Tailwind).
- **`starter.html`** — a working reference dashboard (shell + sidebar + hero + KPI row + content grid). Open it to see the language; copy its markup patterns.

## When to use
Any time the goal is a **premium dark dashboard / admin / control-panel UI** and the person likes this specific aesthetic. It is deliberately general: the same kit becomes an analytics console, a CRM, a content pipeline, an ops board, or a fintech dashboard purely by changing copy, nav items, and which tone each section uses.

## When NOT to use
- Light-mode or print-first UIs (this is committedly dark).
- Minimalist/editorial flat looks (use `minimalist-ui` instead — this skill is the opposite: gradients, glow, depth).
- Marketing landing pages (it's an app shell, not a long-scroll site).

## How to deliver it (the handoff)
1. Copy `theme.css` and `starter.html` into the target project (e.g. `public/` or `src/styles/`).
2. Link the stylesheet once: `<link rel="stylesheet" href="theme.css">` (or `import "./theme.css"` in a bundler).
3. Build screens by composing the documented classes. Start by copying blocks out of `starter.html`.

## The 6 rules that keep it on-brand
1. **Every card is a `.glass-panel`.** Never a flat `<div>` with a solid background. The frosted border + top glow is the whole identity.
2. **Every panel/section declares ONE tone** via a `.tone-*` class (`cyan`, `violet`, `purple`, `indigo`, `magenta`, `emerald`, `amber`, `neutral`). The tone auto-tints that card's glow, `.eyebrow` dot, `.status-pill`, and `.icon-bubble` through `color-mix`. Use tone to encode meaning (e.g. emerald = healthy, amber = needs attention, magenta = featured).
3. **Sections open with an `.eyebrow`** (tiny uppercase wide-tracked label with a glowing tone dot), then a heading. This rhythm carries the whole layout.
4. **Headlines are large, weight ~600, tracking very tight** (`-0.05em`), `line-height ~0.94`. Use `.cg-display`. Numbers use tabular figures (already set on `body`) so stat tiles align.
5. **One `.primary-action` per view.** It's the only gradient-filled button; everything else is `.ghost-action` or `.icon-button`. Don't dilute it.
6. **Motion is subtle and uniform.** All transitions use `--cg-ease`. Panels and buttons get a single light-sweep on hover (`.glass-sweep` child for panels; built-in for buttons). Respect `prefers-reduced-motion` (already wired).

## Rebranding (do this first for a new client)
Edit only the `:root` block in `theme.css`:
- **Accents** — `--cg-accent-1/2/3` are raw `R, G, B` triples (so they feed `rgba()` gradients). Replace the cyan/violet/magenta trio with the brand's three colors. This re-skins auroras, buttons, borders, brand orb, and scrollbar in one move.
- **Surface** — `--cg-bg`, `--cg-ink`, `--cg-muted` if the brand needs a warmer/cooler dark.
- **Tones** — the `--tone-*` swatches are the semantic palette for per-section tinting; usually leave as-is.
Then swap brand text in `.brand-lockup`, the nav items, and the avatar initials.

## Component catalog (all in `theme.css`)
| Class | What it is |
|---|---|
| `.glass-panel` (+ `.tone-*`) | The signature frosted card. Add `<span class="glass-sweep"></span>` as first child for the hover sheen. |
| `.cg-shell` / `.cg-sidebar` / `.cg-main` | App layout: fixed 17.5rem glass sidebar + offset main (collapses < 1280px — supply your own mobile nav). |
| `.brand-lockup` / `.brand-orb` | Logo + product name in the sidebar header. |
| `.nav-pill` (`.active`) | Sidebar nav row: `.nav-icon` + `<strong>` title + `<small>` subtitle. |
| `.profile-card` / `.avatar` / `.live-dot` | Bottom-of-sidebar account chip with status dot. |
| `.eyebrow` | Uppercase section kicker with glowing tone dot. |
| `.cg-display` / `.cg-lede` | Hero headline + supporting paragraph. |
| `.status-pill` / `.icon-bubble` | Tone-tinted status chip and rounded icon container. |
| `.primary-action` / `.ghost-action` / `.icon-button` / `.compact` | Button tiers (gradient / glass / square / small). |
| `.search-shell` | Rounded glass search input. |
| `.kpi-grid` / `.kpi-card` | Stat tile row with big tabular numbers. |
| `.metric-cells` / `.metric-cell` | Compact stat group inside a panel. |
| `.panel-head` | Flex header (eyebrow+title on left, action/pill on right). |
| `.dashboard-grid` + `.col-3/4/6/8/12` | 12-column responsive content grid. |
| `.ambient-scene` + `.aurora-a/b/c` + `.holo-grid` | The fixed lit backdrop. Optional but defines the mood. |

## Adapting to a use case (worked patterns)
- **Analytics console** → hero with the headline metric, a `.kpi-grid` row, then `.col-8` chart panel + `.col-4` insights panel. Tone charts by metric health.
- **CRM / pipeline** → nav per stage; main is a `.dashboard-grid` of `.col-3` stage columns, each a `.glass-panel` with a tone and a `.status-pill` count.
- **Content / media** (the original use case) → `.col-8` editor/preview panel + `.col-4` queue; `.kpi-card`s for reach/saves/shares.
- **Ops / monitoring** → tone = severity (emerald/amber/magenta); `.status-pill` for live state; `.metric-cells` for gauges.

## Verify before handoff
Open `starter.html` in a browser. Confirm: auroras glow behind the shell, panels show the frosted gradient border, hovering a panel triggers the light sweep + tone glow, the sidebar nav active state reads clearly, and the one `.primary-action` stands out. If you rebranded, confirm the accent change propagated to buttons, brand orb, and scrollbar.

## Provenance
Distilled from Ty's Code Tavern Content Dashboard (`/reels` view). Generalized: Code Tavern branding, copy, and app-specific components were stripped; tokens were renamed `--ct-*` → `--cg-*` and accents exposed as editable RGB triples so the kit re-skins from one block.
