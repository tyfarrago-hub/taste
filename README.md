# taste

Frontend design skills for Claude Code. A consolidated set of opinionated tools for going from blank file to production-grade interface, with stops along the way to polish, audit, restyle, or rip apart what you've made.

Every skill in here is a single markdown file that teaches Claude Code how to think and act for a specific design task. Drop them into your `~/.claude/skills/` folder and invoke them with `/skill-name` from anywhere.

---

## Install

```bash
git clone https://github.com/tyfarrago/taste.git
cp -r taste/skills/* ~/.claude/skills/
```

Then restart Claude Code. The skills will appear under your `/` menu.

Want only a few? Copy just the folders you care about.

---

## The skills, grouped

### Build something from scratch

| Skill | When to use it |
|---|---|
| `/impeccable` | Production-grade UI from a brief. The default for "design and build this." Handles hierarchy, spacing, accessibility, motion, edge cases. |
| `/website` | Premium narrative landing pages. The skill behind tydra.netlify.app — handles hero, story arc, conversion, second-read moments. |
| `/ui-ux-pro-max` | The mega-skill. 67 styles, 96 palettes, 57 font pairings, 25 chart styles, 13 stacks (React, Next, Vue, Svelte, SwiftUI, Flutter, shadcn, etc). Comes with CSV reference data for every choice. |
| `/huashu-design` | HTML-first prototype and slide framework. Hi-fi mockups, interaction demos, design variant exploration. |
| `/image-to-code` | Translate a screenshot or design reference into working frontend code. |
| `/redesign-existing-projects` | Audit and rebuild an existing site or component, preserving working parts. |

### Plan and shape before coding

| Skill | When to use it |
|---|---|
| `/shape` | Structured discovery interview before writing a single line. Produces a brief that guides implementation. |
| `/brandkit` | Generate or apply a brand system — palette, type, voice, asset rules. |

### Improve what's already there

| Skill | When to use it |
|---|---|
| `/layout` | Fix spacing, rhythm, visual hierarchy, alignment. |
| `/typeset` | Fix fonts, type scale, weight, readability. |
| `/colorize` | Apply strategic color or fix a flat/muddy palette. |
| `/animate` | Add motion, transitions, micro-interactions that improve usability. |
| `/polish` | Final quality pass — alignment, consistency, micro-detail. |
| `/clarify` | Rewrite UX copy, error messages, labels, instructions. |
| `/adapt` | Make it responsive across screens, devices, contexts. |
| `/harden` | Production-readiness — error states, empty states, onboarding, i18n, overflow. |
| `/optimize` | Performance — load time, rendering, bundle size, animation jank. |

### Calibrate the tone

| Skill | When to use it |
|---|---|
| `/bolder` | Amplify a safe or boring design. More personality, more impact. |
| `/quieter` | Tone down a loud or overdesigned UI. Calmer, more refined. |
| `/distill` | Strip to essence. Remove noise, simplify, declutter. |
| `/delight` | Add joy, personality, unexpected moments. |
| `/overdrive` | Push past conventional limits. Ambitious visual effects. |

### Review, critique, audit

| Skill | When to use it |
|---|---|
| `/critique` | UX-perspective review with quantitative scoring, persona testing, anti-pattern detection, actionable feedback. |
| `/audit` | Technical quality check across accessibility, performance, theming, responsive design. Scored report with P0-P3 severity. |

### Pick a design language

These ARE specific design tastes. Use them when you want a defined aesthetic from the jump.

| Skill | The vibe |
|---|---|
| `/design-taste-frontend` | Senior UI/UX engineer — strict component architecture, hardware-accelerated CSS, balanced design engineering. |
| `/high-end-visual-design` | Agency-grade — the fonts, spacing, shadows, and animations that make a site feel expensive. |
| `/emil-design-eng` | Emil Kowalski's philosophy — UI polish, component design, invisible details that make software feel great. |
| `/gpt-taste` | Editorial typography, gapless bento grids, GSAP ScrollTriggers (pinning, stacking, scrubbing), massive section spacing. |
| `/stitch-design-taste` | Google Stitch system — premium, anti-generic, strict typography, perpetual micro-motion. |
| `/minimalist-ui` | Editorial-style — warm monochrome, typographic contrast, flat bento, muted pastels. No gradients, no heavy shadows. |
| `/industrial-brutalist-ui` | Swiss print meets military terminal — rigid grids, extreme type contrast, analog degradation. |
| `/taste-skill` | The base taste framework that informs the others. |

### Image generation as design reference

| Skill | When to use it |
|---|---|
| `/imagegen-frontend-web` | Generate premium, conversion-aware web design references. One image per section. Composition variety enforced. |
| `/imagegen-frontend-mobile` | Same idea for iOS/Android/cross-platform mobile. Phone-mockup framing by default. |

### Meta

| Skill | What it does |
|---|---|
| `/full-output-enforcement` | Overrides default LLM truncation. Forces complete code output, bans placeholders, handles split files cleanly. |

---

## Suggested first moves

Don't try to use all 36 at once. Start here:

1. **`/impeccable`** — give it a brief, watch it build. This is the default.
2. **`/critique`** — point it at what you just made. Get a scored review.
3. **`/polish`** — let it do the final pass before you ship.

That's the whole loop. Brief → build → critique → polish → ship.

Then layer in:
- A taste skill (`/emil-design-eng` or `/high-end-visual-design`) to set the aesthetic up front.
- `/website` when the thing is a landing page specifically.
- A tone calibrator (`/bolder`, `/quieter`, `/distill`) when the first pass is close but off-temperature.

---

## How a skill actually works

Each skill is a folder with a `SKILL.md` file. That file teaches Claude Code one specific design discipline. When you type `/skill-name`, the contents are loaded and Claude follows the instructions for that turn.

You can read any of them yourself. They're not magic — they're just well-written prompts with examples, rules, and references. Edit them, fork them, build your own.

---

## Credits

Most of these started as personal taste rules I kept repeating in conversations. At some point each one earned its own file.

The video and animation skills (HyperFrames, GSAP, Three.js, etc.) live in a separate bundle — this one is intentionally scoped to **frontend design**.

— Ty
