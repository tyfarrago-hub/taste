---
name: website
description: Build premium, narrative-driven landing pages from scratch or redesign weak ones. Apply the design principles, techniques, and iterative process refined through building tydra.netlify.app — a biotech landing page that went from flat to genuinely good through deliberate iteration. Use when asked to design or redesign a website, landing page, or product page.
---

# Web Design Skill

---

## Tyler's Design Eye — The Most Important Section

This is not about techniques. This is about the underlying standard that drives every single prompt Tyler gives. Internalize this before touching any code.

### The Core Demand: Things Must Feel Real

Tyler's most consistent instinct is physics. When he says something is "off," it's almost always because an element feels pasted on, floating, or disconnected from its environment. When something works, he describes it in physical terms:

> "looks like there's actual physics going on"
> "protrudes in a way that feels connected to the background"
> "punched into the background using shadows"
> "mesh these images with the website"
> "porting from the background elegantly"

**What this means in practice**: Every element needs a relationship to what's around it. An image card doesn't sit on a background — it *emerges* from it. A shadow isn't decoration — it's the element *belonging* to a surface. If you can look at something and think "that was placed there," it's wrong. If it looks like it *grew* there, it's right.

### The Standard: Command Authority

Tyler thinks about websites the way a filmmaker thinks about a shot — it either grabs the viewer or it doesn't. He uses words like:

> "We really got to impact people here. We got to command respect and authority and attention."
> "hook the viewer immediately"
> "make it more impactful, more imperative to the mission"
> "design elevate to respect that"

**What this means in practice**: Passive, informational design is always wrong. Every section should either move the viewer forward emotionally or get cut. If something is just "there," it's taking up space. The bar isn't "does this look okay" — it's "does this demand attention."

### How He Identifies Problems

Tyler names problems precisely and uses specific vocabulary. He doesn't say "this looks bad" — he says:

> "heartbreak" (a visual artifact or gradient break that ruins the composition)
> "slightly sloppy gradient thing"
> "weird and disconnected"
> "kind of bland"
> "really sterile feeling"
> "random boxes coming up"
> "hard color break"
> "pixelation"

**What to listen for**: When Tyler says "sterile" — add warmth, depth, life. When he says "disconnected" — the element needs to integrate with its surroundings. When he says "heartbreak" — there's a specific seam, artifact, or break that needs to be hunted down and fixed. When he says "bland" — the hierarchy is flat; something needs to be elevated dramatically in scale, color, or motion.

### How He Describes What He Wants

His direction is almost always visual and physical, rarely technical:

> "tight, crispy-looking glow animation that travels along the structure"
> "light gradient travel through it"
> "motion gradients that subtly track the outline"
> "seamless connection"
> "flow seamlessly together"
> "top right corner vibe"

**What this means**: Translate his visual description into the most precise technical implementation possible. "Crispy" means hard-edged, high contrast, not blurry. "Travel" means animation with a clear direction and velocity. "Seamless" means gradients that share colors with both surfaces being joined. Don't ask for clarification — make your best interpretation and show it.

### What He Never Does

- **Never passively approves.** If Tyler says "okay" or "good," he's already thinking about what's next. He doesn't dwell on wins.
- **Never accepts "good enough."** The Tydra page went through many revisions on things most designers would have shipped. He noticed the 90px of dead space at the top. He noticed the gradient didn't quite match. He noticed the mobile nav was inconsistent.
- **Never explains the brief twice.** If you missed something, he'll redirect but he won't re-explain the whole vision. Learn from each redirect.

### The Refinement Pattern

Tyler's feedback almost always follows this arc:
1. **Identify the problem** (specific, named, visual): "the gradient thing is sloppy"
2. **Emotional signal** (how wrong it feels): "heartbreak"
3. **Visual direction** (what it should feel like): "should flow seamlessly"
4. **Implicit expectation**: Fix it completely, don't half-fix it

He layers refinements. First pass: get the structure right. Second pass: get the integration right. Third pass: get the motion right. Fourth pass: get the copy right. Each pass adds a layer of quality. Don't try to do all layers at once — respond to what he's focused on.

### How to Anticipate His Next Prompt

Ask yourself before showing anything:
1. Does every element feel like it *belongs* to its surface? (physics)
2. Is there a moment on this page that commands attention? (authority)
3. Is there anything that looks placed, pasted, or disconnected? (integration)
4. Is there any animation that loops without purpose? (motion discipline)
5. Is there dead space that isn't earning its presence? (efficiency)
6. Does the copy sound like a real person or a website? (voice)

If any of these answers are "no" or "I'm not sure" — fix it before showing it. Tyler will find it.

### His Taste in One Sentence

Premium, physical, earned. Every visual choice should feel like it took craft to get right — not because it's complicated, but because the attention to detail is undeniable.

### App & Interaction Design Principles (from Claude Code OS, Apr 2025)

These extend beyond landing pages into product UI, course platforms, and interactive experiences:

1. **Execution > ambition.** A smooth simple animation beats a janky complex one. If it can't run at 60fps, scale back. Only animate `transform` and `opacity`.

2. **Creative tension is the concept.** Tyler blends opposing aesthetics (analog book + retro-digital) by establishing strict rules — serif fonts for the "book world," pixel fonts for the "machine world," never mixing them on the same element. The discipline IS the design.

3. **Kill redundant steps.** If a preview and a destination show the same info, merge them. Shortest path to the experience. Every unnecessary screen is a dropout point.

4. **Design for real behavior.** Tyler's users are non-technical and intimidated. He'll add progressive disclosure (one section at a time), time-gated content reveals (paragraphs appear based on reading time), and manual triggers ("Begin Reading" button) to pace the experience. Walls of text = disengagement.

5. **Functional placement > decorative.** A "Begin Reading" button goes left-aligned because that's where reading starts. Position serves purpose, not symmetry.

6. **Transition seams are bugs.** Every state change must flow. Button fades out → space collapses → content rises in as one continuous motion. No hard cuts, no pops, no jumps.

7. **Feedback must be unmistakable.** Loading dots should be large, glowing, animated. Tyler's users won't interpret subtle cues. Clear > clever. When in doubt, make it bigger.

8. **Pixel-level spatial awareness.** Tyler catches alignment errors immediately. Always verify centering, padding symmetry, and axis alignment before presenting.

### Environmental Design Principles (from Community Chat Redesign, Apr 2026)

These principles emerged from Tyler writing a 3,000-word design brief for a chat section redesign. They reveal how he thinks at the deepest level — not about components, but about places.

9. **Design places, not screens.** Tyler's test: "Does this make a new user feel like they have entered a world, or does it make them feel like they have opened another tab?" Before designing any section, define the place it represents — time of day, light source, materials, atmosphere. Then derive every visual decision from that definition.

10. **Build backgrounds in layers.** Backgrounds are compositing stacks, not single colors. Tyler specified five explicit layers for a background: base color → grain texture → vignette → ambient glow → scanline overlay. Each layer has a named purpose and a specific opacity. This is how depth is built — through accumulation, not a single clever gradient.

11. **Font segregation is information architecture.** Serif font = human speech (names, body text, descriptions). Pixel font = system state (counts, timestamps, status, placeholders). These two fonts never appear on the same text element. The contrast between them IS the brand. This extends to naming: `// SCHOLARS ONLINE` uses double-slash syntax to signal "the system is speaking."

12. **Physical metaphors are specs.** When Tyler says "note card placed on a desk," that implies: slightly lighter than surface, subtle shadow, warm texture, finite size, tangible edges. When he says "stamp applied to a document," that implies: pressed-in appearance, heavy weight, clear imprint. Extract all implicit visual properties from the metaphor and implement every one.

13. **Name things from inside the world.** "Players online" → "SCHOLARS ONLINE." Placeholder text gets `// TYPE YOUR MESSAGE...` with the double-slash. Timestamps become `APR 5 // 14:32`. Every UI label either reinforces the world or breaks it. 50 small naming choices compound into the difference between "an app" and "a place."

14. **Light the scene first.** The background determines everything above it. Tyler specifies backgrounds in extreme detail because the background constrains text contrast, card colors, glow intensity, and animation brightness. Define the implied light source, then derive all foreground colors from it — don't pick them independently.

15. **Emotional states over functional states.** Empty state isn't "No messages" — it's pixel art books with `// NO MESSAGES YET. SAY HELLO.` Loading isn't a spinner — it's Byte thinking with `Loading messages...` in pixel font. Every UI state has an emotional intention. Design the feeling first, then the function.

16. **Controlled asymmetry guides the eye.** Active states use left borders, not full highlights. Ornamental dividers have a diamond at center with lines fading in opposite directions. Tyler uses directional visual weight to create reading paths and hierarchy, not symmetric highlighting.

---

Built from the ground-up process of designing tydra.netlify.app and the Claude Code OS course platform. These aren't generic best practices — they're principles extracted from real before/afters that worked.

---

## The Core Process

Before writing a line of code, answer these four questions:

1. **What is the product?** (What is it, physically or functionally?)
2. **What is the problem it solves?** (What was broken before this existed?)
3. **Who is the buyer?** (Founder? Engineer? Consumer?)
4. **What should the visitor feel by section 3?** (Curiosity? Urgency? Trust?)

The answers determine color palette, motion style, typography, and copy tone. Don't skip this.

---

## Narrative Structure

A landing page is a story with acts. Each section is a beat, not an info dump.

**Act 1 — Hook** (Hero): Establish what this is and make it visually arresting. One sentence max.
**Act 2 — Problem** (Why this matters): Show what was wrong before. Use emotion, not bullet points. The core message should land pre-verbally (symbol, color, scale).
**Act 3 — Proof** (Stats/Material/Science): Ground the claim in something real. Don't be abstract — show the waste pile.
**Act 4 — Solution** (Product): Show what it does, not what it is. Practical copy. No marketing-speak.
**Act 5 — Trust** (People/Credentials): Real faces, real awards. Short.
**Act 6 — Action** (Newsletter/CTA): One ask. Premium framing.

Scroll order is argument order. If the argument doesn't hold, the layout doesn't matter.

---

## Color as Language

Colors aren't aesthetic — they're meaning. Assign roles before assigning hex codes.

| Role | Color | When to Use |
|---|---|---|
| Wrong / Problem | Red / terracotta (`rgba(210,90,65)`) | Strikethrough, problem state, "before" |
| Solution / Brand | Teal (`#25c9b0` or similar) | CTA, payoff, brand mark |
| Premium / Light | Warm ivory (`#f5f0e8`) | Reading sections, contrast from dark |
| Depth / Darkness | Near-black ink (`#0d1117` or warm variant) | Hero, dark sections, footers |
| Natural / Warmth | Amber (`rgba(194,152,98)`) | People, warmth moments |

Build a CSS variable system at the top of every file:
```css
:root {
  --ink: #0e1117;
  --cream: #f5f0e8;
  --cream-dark: #e8e0d0;
  --teal-glow: #25c9b0;
  --terracotta: rgba(210,90,65,1);
}
```
Every color in the design should trace back to a variable. No one-off hex codes.

---

## Typography Hierarchy

Four typefaces, four roles. Don't mix beyond this:

- **Playfair Display** (or equivalent display serif): Brand voice, emotional peaks, hero headline
- **Monospace** (e.g., `font-family: monospace`): Labels, stats, technical precision, section numbers
- **Serif italic**: Quotes, warmth moments, founder voice
- **System sans-serif**: Body copy, readability, UI

**Scale as narrative**: Size isn't just hierarchy — it's emphasis. When a payoff line needs to land, make it absurdly large (92px Playfair in teal on a dark background). Small text whispers. Large text commands. Use the gap between them intentionally.

**Label convention**: Section labels as small mono caps:
```html
<p class="s-label">05 — Why it works</p>
<h2 class="s-title">Six reasons chitin wins.</h2>
```

---

## Motion Principles

**Rule 1: Entrance animations happen once.**
Use `IntersectionObserver` to fire `.reveal` classes when elements enter the viewport. The observer disconnects after firing. No loops.

**Rule 2: Ambient motion is slow and subtle.**
Blobs, shimmer sweeps, floating labels — these loop but at 3–8s duration and low amplitude. They breathe, they don't perform.

**Rule 3: Stagger = pacing = storytelling.**
When multiple elements reveal in sequence, stagger them 0.1–0.2s apart. This makes a list read like dialogue instead of an info dump.

**Rule 4: Motion has meaning.**
- Upward roll (numbers counting up): growth, increase
- Fade-in + translate Y: arrival, emergence
- Scale pulse on completion: satisfaction, confirmation
- Horizontal shimmer: polish, luxury

**Rule 5: When in doubt, remove it.**
The water ripple on the Tydra heading was technically impressive. It was also too much. Remove anything that competes with content for attention.

**Reveal system (base CSS + JS):**
```css
.reveal {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}
.reveal.visible { opacity: 1; transform: none; }
.d1 { transition-delay: 0.1s; }
.d2 { transition-delay: 0.2s; }
.d3 { transition-delay: 0.3s; }
.d4 { transition-delay: 0.4s; }
```
```javascript
const observer = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('visible');
      observer.unobserve(e.target);
    }
  });
}, { threshold: 0.15 });
document.querySelectorAll('.reveal').forEach(el => observer.observe(el));
```

---

## Section Transitions: Physical, Not Visual

**The problem with gradients**: They look designed. Users feel the seam.

**The solution**: Card edges with shadows.

```css
/* Section that casts shadow over the next */
.dark-section {
  border-radius: 0 0 52px 52px;
  box-shadow: 0 40px 80px rgba(0,0,0,0.4), 0 20px 40px rgba(0,0,0,0.3);
  position: relative;
  z-index: 2;
}

/* Section that slides underneath */
.light-section {
  border-radius: 52px 52px 0 0;
  margin-top: -52px;
  position: relative;
  z-index: 1;
}
```

Two curves meet, shadow sells depth. No gradient needed. The visual logic is physical: one card resting on top of another.

Rule: Dark sections flow flat into each other (no treatment). Light sections are separate elevated cards.

---

## Gooey Ambient Blobs (Organic Motion Background)

Use for premium product/biotech positioning. Creates biological/organic visual without being literal.

```html
<!-- Hidden SVG filter -->
<svg style="position:absolute;width:0;height:0">
  <defs>
    <filter id="goo">
      <feGaussianBlur in="SourceGraphic" stdDeviation="40" result="blur"/>
      <feColorMatrix in="blur" mode="matrix"
        values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7" result="goo"/>
    </filter>
  </defs>
</svg>
```

```css
.blobs-container {
  position: absolute; inset: 0;
  filter: url(#goo);
  overflow: hidden;
  pointer-events: none;
}
.blob {
  position: absolute;
  border-radius: 50%;
  mix-blend-mode: hard-light;
  opacity: 0.7;
}
```

Animate blobs with `moveInCircle`, `moveVertical`, `moveHorizontal` keyframes at 15–25s duration. Add one blob that follows the mouse with eased lag for interactivity.

**Important**: If blobs show pixelation at edges, remove the `feColorMatrix` from the filter — use blur only (`feGaussianBlur` alone). The merge effect won't be as strong but edges stay clean.

---

## The Problem Section Pattern

The most effective section in the Tydra page. Works for any product that replaces something broken.

Structure:
1. Large watermark character (×, !, or visual symbol) at 0.07 opacity with layered shadows
2. Lines that name what was broken — with a crossed-out word in terracotta/red
3. A payoff line in display serif at huge scale (80–100px), teal, that pivots to the solution
4. Stagger each line at 1s intervals (not simultaneous)
5. Optionally use scroll-snap to hold the viewport on this section until the full sequence plays

```css
.problem-watermark {
  font-size: clamp(220px, 35vw, 400px);
  opacity: 0.07;
  text-shadow:
    2px 2px 0 rgba(80,30,10,0.6),
    -2px -2px 0 rgba(80,30,10,0.4),
    0 0 180px rgba(20,80,80,0.3);
}
.strike { color: var(--terracotta); text-decoration: line-through; }
.payoff { font-family: 'Playfair Display', serif; font-size: clamp(48px,7vw,92px); color: var(--teal-glow); }
```

---

## Neumorphic Cards (For Stats, Features, Data)

Derives shadow colors from the card's background. Every shadow color is a 15% shift of the base — no arbitrary greys.

```css
.neu-card {
  background: var(--cream);
  border-radius: 24px;
  box-shadow:
    8px 8px 20px #c0b9ae,   /* 15% darker than --cream */
    -8px -8px 20px #ffffff; /* lighter */
  padding: 40px;
}
```

For image backgrounds inside cards: use a gradient overlay that fades from transparent to the card color, so the image melts into the surface rather than hard-clipping.

---

## Image Treatment

**Rule**: Images need gradient exits, not hard borders.

```css
.image-card {
  position: relative;
  overflow: hidden;
}
.image-card::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(to top, var(--ink) 0%, transparent 60%);
}
```

For people photos: crop distracting backgrounds by adjusting `background-size` and `background-position`. Use `background-size: 150–180%` to zoom past headers/UI. Add color-matched border strokes that connect to the rest of the palette.

For hover: micro-zoom at 1.05 scale (`transform: scale(1.05)`) over 0.5s. Subtle.

---

## Copy Principles

- **Plain English over jargon**: "most common natural material after wood" not "high-abundance biopolymer substrate"
- **Short sentences**: 8–12 words. Read aloud. If you run out of breath, shorten it.
- **Practical specifics**: "ships pre-hydrated and drop-in ready. No new tooling required." — this is a real claim, not a feature adjective.
- **One-line emotional beats**: "Not anymore." "Stay ahead of the science." These land because they're short.
- **Labels do the framing**: Small mono labels before headings tell the user what mental shelf to put this on.
- **Footer quote**: Every premium page ends with a philosophical sentence. Earned, not clichéd.
- **Run all public copy through the humanizer skill** before writing to file.

---

## UI/UX Fundamentals (Quick Reference)

### Typography Polish
Tighten letter-spacing on all headings to `-0.02em` to `-0.03em` and drop line-height to `1.1`–`1.2`. This single adjustment makes any large text look professional instantly. Body text stays at normal letter-spacing and `1.5`–`1.6` line-height.

### Icon Sizing
Icons should match the line-height of adjacent text. If the font renders at 24px line-height, the icon is 24px. Oversized icons are the most common amateur tell.

### Button Fundamentals
- **Padding ratio**: horizontal padding = 2× vertical padding (e.g., `12px 24px`)
- **Four required states**: default, hover, active/pressed, disabled. Optionally loading (spinner).
- **Ghost buttons**: no background, just text + optional border. Background appears on hover. Use for secondary CTAs next to a filled primary button.

### Input States
Every input needs: default, focus (brand-color border), error (red border + message below), and optionally warning. Missing states make forms feel broken.

### Shadows Done Right
If the shadow is the first thing you notice, it's too strong. Reduce opacity, increase blur. Cards on same-level backgrounds need subtle shadows; popovers/dropdowns floating above content need stronger ones.

### Dark Mode Rules
- No box-shadows for depth — use lighter card backgrounds than the page bg instead
- Lower border contrast (light borders on dark bg = too harsh)
- Dim chip/badge saturation and brightness; flip text inside them to lighter
- Deep purples, reds, and greens work — don't default to grey/navy

### Semantic Colors
Blue = trust. Red = danger/urgency. Yellow = warning. Green = success. Use color for *purpose*, not decoration. A green chip means "new" or "success" — don't use green just because it looks nice.

### Color Ramp from One Primary
Start with your brand color. Lighten it for backgrounds, darken it for text. This alone gets you halfway to a full color system without picking arbitrary secondary colors.

### Micro Interactions
Every user action needs a visible response. Copy button → confirmation chip slides up. Form submit → success state. Toggle → smooth transition. If the user does something and nothing visibly changes, the UI is broken.

### Image Overlays for Text Readability
Three options, from basic to premium:
1. Full-screen semi-transparent overlay (works but hides image)
2. Linear gradient from transparent → background color (shows image, fades to readable)
3. Progressive blur on top of the gradient (modern, premium feel)

### Responsive Grid Guideline
For structured/repeating content (galleries, blog grids, card layouts): 12 columns desktop, 8 tablet, 4 mobile. Custom/narrative sections don't need to follow a column grid — white space and visual weight matter more than alignment.

---

## What to Reject

These things look impressive in isolation but make pages worse:

- **Water ripple / complex SVG distortion on text**: Too much. Distracts.
- **Perpetual number incrementing**: Animates once on entry, then stops. No infinite ticking.
- **Nav color detection** (swapping light/dark based on section): Creates cognitive dissonance. Pick one nav style and commit.
- **Gradient bridges between sections**: Replace with card edges and shadows.
- **Simultaneous reveals**: Always stagger.
- **Color Matrix on gooey filter if it causes pixelation**: Use blur only.
- **Carousels**: Replace with static full-bleed cards whenever possible.
- **Generic promo CTAs**: Every CTA should be contextual to the section it's in.

---

## Deployment (Netlify via API)

```bash
# Deploy single HTML + images to Netlify without CLI
NETLIFY_TOKEN="your-token"
SITE_ID="your-site-id"

# Create zip, deploy via API
zip -j deploy.zip index.html image1.jpg image2.jpg
curl -X POST "https://api.netlify.com/api/v1/sites/$SITE_ID/deploys" \
  -H "Authorization: Bearer $NETLIFY_TOKEN" \
  -H "Content-Type: application/zip" \
  --data-binary @deploy.zip
```

For HTML-only deploys, use the Netlify Files API to PUT individual files by their SHA:
1. Hash each file
2. POST deploy manifest
3. PUT any files Netlify doesn't already have
4. Deploy auto-publishes when all required files are uploaded

---

## Full Website Build Checklist

Every multi-page site build should hit these in order. Skip what doesn't apply, but check each one.

### Phase 1: Foundation
1. **Discovery** — What is this business? Who visits the site? What should they feel/do?
2. **Design system** — Run UI/UX Pro Max `--design-system` for palette, typography, style
3. **CSS variables** — Colors, shadows, radii, spacing all as custom properties. Zero one-off hex codes.
4. **Typography** — Google Fonts loaded. Heading font, body font, mono font for labels/stats. Max 3 families.
5. **Base styles** — Reset, body, img, a, button defaults. Reveal animation system (`.reveal`, `.d1`-`.d6`).

### Phase 2: Page Structure (index.html)
6. **Nav** — Sticky, scrolled state with shadow/backdrop-blur. Logo + page links + CTA buttons. Hamburger + mobile menu overlay.
7. **Hero** — Headline with accent color span, subtitle, CTA buttons. Optional: stat card with image, floating tag/badge, location badges.
8. **Capabilities / Features** — Icon + title + description cards in 3-column grid.
9. **Product Showcase** — Side-by-side split with center divider for comparing options (e.g., two scanner types). Badge labels, image cards with gradient fade.
10. **Team** — Photo cards with name, role (mono label), credential list. Gradient overlay on photos to melt into card bg.
11. **Testimonials** — Star ratings, italic quote text, avatar initials, author name + meta. 3-column grid. Source attribution line. **Use real reviews only — never fabricate.**
12. **Process / Steps** — Horizontal step flow with numbered icons, connecting lines, arrow indicators. Stacks vertical on mobile.
13. **Locations** — Map embed cards with address, phone, fax, badges (e.g., "X-Ray Available"). Gradient overlay on map bottom edge.
14. **Insurance / Pricing** — Split layout: checklist of accepted plans + visual card with self-pay/alternate options.
15. **FAQ Accordion** — Single-open accordion. Plus icon rotates to X on open. Smooth max-height transition.
16. **Contact** — Dark section with form (name, email, phone, location select, message textarea). Social links. Doubles as footer wrapper.
17. **Footer** — Multi-column inside the dark contact zone: brand + description, page links, location columns. Copyright bar with social icons.
18. **Sticky Mobile CTA** — Fixed bottom bar on mobile only. "Call Now" + "Request Appointment" buttons. Shows after scrolling past hero via IntersectionObserver. Add bottom padding to footer to clear it.

### Phase 3: Subpages
19. **Match the design system exactly** — Same nav, same footer, same CSS variables, same font imports, same reveal system. Every subpage should feel like the same site.
20. **Page hero** — Shorter than home hero. Section label + h1 + subtitle. Optional breadcrumb or back link.
21. **Subpage types** — Technology (scanner specs, image quality), Specialists (full bios, credentials), Patients (prep info, what to expect), Insurance (full plan list, billing info), Contact (standalone form), Physicians/Referrals (referral steps, fax info, capabilities).

### Phase 4: Polish
22. **Copy** — Run every piece of public-facing text through `/humanizer`. No marketing-speak. Short sentences.
23. **Text orphans** — Add `text-wrap: balance` to all headings, subtitles, and short paragraphs. Set `max-width` constraints on body text to prevent single-word line wraps.
24. **Responsive audit** — Check every section at 375px, 768px, 1024px, 1440px. Grid collapses, font size clamps, hidden elements on mobile.
25. **Image treatment** — All images: `object-fit: cover`, gradient fade overlays, proper alt text. Hover: `transform: scale(1.05)` over 0.5s.
26. **Animations** — Stat count-up (fires once, eased cubic, 1.4s duration). Subtle parallax on hero image (desktop only, 20px range). Staggered reveals on all sections.
27. **Accessibility** — ARIA labels on icon-only buttons, form labels, semantic HTML, visible focus states.

---

## Patterns Learned from Extremity MRI Build

### Stat Count-Up Animation
Numbers in hero cards or stat sections should animate from 0 on scroll-in. Use `IntersectionObserver` to trigger, `requestAnimationFrame` for smooth interpolation, cubic ease-out. Fires once. Handle floats (0.4) and suffixes (+) separately.

```javascript
function animateCountUp(el, target, suffix) {
  const duration = 1400;
  const isFloat = String(target).includes('.');
  const start = performance.now();
  function tick(now) {
    const elapsed = now - start;
    const progress = Math.min(elapsed / duration, 1);
    const eased = 1 - Math.pow(1 - progress, 3);
    const current = isFloat ? (eased * target).toFixed(1) : Math.round(eased * target);
    el.textContent = current + suffix;
    if (progress < 1) requestAnimationFrame(tick);
  }
  requestAnimationFrame(tick);
}
```

### FAQ Accordion
Single-open: clicking one closes all others. Animate with `max-height` on the answer wrapper. Plus icon (`+`) rotates 45deg to become `×` on open.

```css
.faq-answer { max-height: 0; overflow: hidden; transition: max-height 0.35s ease; }
.faq-item.open .faq-question svg { transform: rotate(45deg); }
```

### Sticky Mobile CTA
Fixed bottom bar, hidden by default (`transform: translateY(100%)`), shown when hero exits viewport. Use `IntersectionObserver` on hero section — when not intersecting, add `.visible` class.

### Floating Tags Inside Cards
**Gotcha**: If a card has `overflow: hidden` (for image clipping), any element positioned outside the card (`top: -0.75rem`) gets clipped. Position floating tags *inside* the card boundary (`top: 0.75rem; right: 0.75rem; z-index: 2`) so they overlay the image instead.

### Background-Clip Text + Italic Clipping
**Gotcha**: `-webkit-background-clip: text` combined with `font-style: italic` and tight `line-height` clips the edges of italic characters (especially trailing "s", "g", "y"). Fix: add `padding: 0 0.15em` to the accent span with `margin: 0 -0.1em` to compensate, plus `box-decoration-break: clone`.

### Testimonial Cards
Never fabricate reviews. Use placeholder text with `[Paste real Google review here]` if real reviews aren't available. When writing placeholder reviews for client approval, make them sound like real people — casual grammar, specific details, no marketing vocabulary. Each review should highlight a different selling point.

### Multi-Location Handling
- Hero: subtle location badges below CTA buttons with pin icons and divider
- Nav: separate phone CTA buttons per location ("Miami" / "Broward")
- Locations section: side-by-side map embed cards
- Footer: separate columns per location
- Mobile: locations stack vertically, divider hidden

### Phone Number CTAs in Nav
For service businesses, nav CTA buttons should be `tel:` links, not page anchors. Show location name, not the number (cleaner). Style as pill buttons matching the nav aesthetic.

---

## Reference: Tydra

- **Live site**: https://tydra.netlify.app
- **Working file**: `~/Desktop/tydra-v2.html`
- **Palette**: `--ink` (dark), `--cream` (ivory), `--teal-glow` (brand teal), `--terracotta` (problem red)
- **Fonts**: Playfair Display (display), system mono (labels), Georgia (quotes)
- **Sections**: Hero → Chitin explainer → Problem → About/Stats → Product Lines → Applications → Why It Works → Team → Newsletter → Footer

## Reference: Extremity MRI

- **Working dir**: `~/Desktop/extremity-mri/`
- **Palette**: `--ivory: #f5f0eb`, `--blue: #5a8abf`, `--black: #0a0a0a`, `--blue-pale: #dce8f4`
- **Fonts**: Space Grotesk (headings + body), JetBrains Mono (labels/stats)
- **Pages**: index, technology, specialists, patients, insurance, contact, physicians
- **Sections**: Hero (stat card + locations) → Capabilities → Scanners (split) → Team → Testimonials → Steps → Locations → Insurance → FAQ → Contact/Footer
- **Key patterns**: Stat count-up, FAQ accordion, sticky mobile CTA, hero parallax, multi-location nav

---

## Patterns Learned from Indivisible USA Brand Kit Build

### Data Presentation Principles

**1. Always cite and link your sources.**
When claiming benchmarks or industry averages (e.g., "Instagram averages 0.50%"), include a subtle clickable source link near the stat. Small font, low opacity, doesn't distract — but it's there for anyone who wants to verify. Uncited data undermines credibility. Tyler caught this immediately.

**2. Anchor data to a timeframe.**
"397,486 total interactions" means nothing without knowing the window. Always preface time-bound data with the period: "in the last 90 days." Data without a timeframe looks made up.

**3. Guide the viewer through the data.**
Don't just show two numbers side by side. Add a bridging phrase like "This is incredible because" between a stat and its context. The viewer needs to be told *why* a number matters, not just *what* it is. Design the comparison visually — make "Ours" physically larger than the averages so the gap is felt before it's read.

**4. Numbers must add up.**
If you show weekly growth bars totaling 31.9K but the actual follower count is 28K, someone will notice. Always sanity-check that component numbers sum to the stated total. Use net figures, not gross, unless explicitly labeled. Tyler caught a ~4K discrepancy instantly.

**5. Add the unit/context word.**
"Zero to 58,500" — 58,500 what? Always include the noun: "Zero to 58,500 Followers." Don't assume the viewer knows what the number represents.

### Copy Principles (Brand Kit Specific)

**6. Replace jargon with plain language.**
"Share-first behavior" is marketing-speak. "Built-in word of mouth" is something a human would say. If a phrase requires the reader to decode it, rewrite it.

**7. "Community" > "People."**
"What our community is saying" is stronger than "what people are saying." Community implies loyalty, belonging, and repeat engagement — all things a sponsor cares about.

**8. Remove subheadings that over-explain.**
If the header is strong enough ("Zero to 58,500 Followers in Four Months"), the subheading explaining the same thing in more words dilutes impact. Let numbers speak. Cut the crutch.

**9. Provide platform context.**
"We started on Facebook later than Instagram — January 2026" gives the viewer a reason why one platform might have fewer followers. Without context, they'll assume it's underperforming.

### Visual/Design Principles

**10. Prioritize the primary offering through design, not just copy.**
If the 30-Day Placement is your most important sponsorship, it shouldn't be a card the same size as the other three. Make it a full-width hero card with a gold border, a "Most Popular" badge, and stat breakdowns. Design communicates priority faster than words.

**11. Profile photos + clickable handles on platform sections.**
Each platform section should have a small circular profile photo with the @ handle as a clickable link, sitting inline next to the section header. Builds trust — the viewer can verify the account exists and check the numbers themselves.

**12. Legibility over subtlety.**
When comparison numbers are too small or too low-contrast, the entire point of the comparison is lost. If you're showing 0.50% vs 18.3%, make "Ours" physically larger (36px vs 28px) so the gap is *felt* visually. Labels need to be readable — 10px at 0.25 opacity is invisible.

**13. Every section earns its place.**
Tyler cut the growth timeline, the viral posts section, and the "top content by views" panel. If a section doesn't directly contribute to the sale (in a brand kit) or the narrative (on a landing page), remove it. Filler sections make the strong sections weaker by proximity.

### Structural Principles

**14. Move data to where it's relevant.**
The Facebook week-by-week growth chart was originally in a separate "Results" section. Tyler moved it into the Facebook section itself. Data about a platform belongs in that platform's section. Don't create orphan sections for data that has a natural home.

**15. Use bridging labels to guide the eye.**
Between a big stat and its explanation, add a small italic or uppercase label: "This is incredible because." It's a design element and a narrative device — it tells the viewer what mental frame to apply before they read the next piece of information.

---

## Patterns Learned from Barilette Cafe Build

### Scraping & Rebuilding Existing Sites

**1. Wix sites need browser automation, not WebFetch.**
Wix renders client-side. `WebFetch` returns infrastructure JS, not content. Use Chrome browser tools: navigate to the page, `get_page_text` for copy, `javascript_tool` to extract all image URLs from the DOM. Scroll to bottom first to trigger lazy-loaded images.

**2. Extract the color palette from the live site.**
Use `getComputedStyle` on all elements to pull actual rendered colors. Filter out transparent/black/white noise. The two most distinctive non-neutral colors become your primary and secondary. For Barilette: espresso brown (`#513408`) and warm cream (`#FAF9F5`).

**3. Menu images need manual transcription.**
Restaurant menus are often image-based (JPG/PNG of a designed menu). Screenshot them, read the content visually, then rebuild as structured HTML. Tabbed menu sections with dotted-line separators between items look far more professional than reproducing the image.

### Small Business / Cafe Website Patterns

**4. Tabbed menu display is the right move for restaurants.**
Categories as pill-button tabs (Breakfast / Food / Drinks / Coffee), two-column layout within each tab, dotted borders between items, serif font for item names, muted descriptions, prices right-aligned. Feels like a real printed menu, not a website.

**5. Balance your columns.**
If one column has 3 items and the other has 12, move categories between columns until visual weight is roughly equal. The user will immediately notice blank space on one side. Savory (3 items) was too short — moving Healthy Hints underneath it fixed the imbalance.

**6. Don't duplicate images across sections.**
If you use an image as the hero background, don't use the same image in the story section or gallery. Each image should appear exactly once. The user notices immediately.

**7. Local images (avif/jpg from Downloads) over remote Wix URLs.**
When the user provides downloaded images, use local paths (`img1.avif`) instead of remote Wix URLs with resize parameters. Wix URLs with fill/encode params can fail or return wrong content. Local files are reliable and load instantly.

**8. Hero background for cafes/restaurants = the interior shot.**
Not the food, not the logo — the *space*. Show the ambiance: Edison bulbs, rustic shelves, checkered tablecloths, grapevines. The food goes in the gallery. The interior tells the viewer what it *feels like* to be there.

**9. Brown nav bar for warm-toned brands.**
When the brand palette is warm browns/creams, a cream nav bar looks washed out. Switch to a brown nav with cream text and inverted CTA button. Matches the brand better and creates a clean top edge.

**10. Embedded Google Maps for location sections.**
Use the Google Maps embed iframe with the business address. Pair with address, hours, phone, email, and delivery info in a two-column layout (info left, map right). Round the map corners to match the site's border-radius language.

### Image Curation for Photo-Heavy Sites

**11. Plan the full image allocation before writing any HTML.**
When adding 10+ images to a site, map out every placement first: which image goes in which section, and why. Assign each image exactly once. This prevents the scramble of discovering repeats mid-build.

**12. Images must match their section's content.**
A food photo (hummus plate) doesn't belong as the Drinks menu feature — use an actual drink (smoothie). A Breakfast feature should show pastries or morning food. Coffee should show the espresso bar. Match the image to the copy it sits next to, not just the general vibe.

**13. Near-duplicates count as repeats.**
Three photos of the same avocado toast from slightly different angles are one image, not three. Same with two shots of the same interior corner. Curate down to the single strongest shot of each subject. Use the others only if they're well-separated in the layout and serve different purposes.

**14. Don't overuse a design pattern.**
Two photo strips is one too many — it stops being special. One photo strip + one parallax break + an expanded gallery gives enough visual density. Each pattern should appear once unless there's a strong reason to repeat it.

**15. Masonry gallery for large image sets.**
When you have 8+ gallery images, switch from a rigid grid to CSS `columns` masonry. This lets portrait and landscape images coexist without forced aspect ratios. Alternate food and interior shots for rhythm.

### Gallery Grid

**16. Match grid columns to image count.**
3 images = 3 columns. 4 images = 2x2. 6 images = 3x2. Don't force a spanning layout (first item spans 2 rows) unless you have 5+ images with one that's clearly the hero shot. Aspect ratio `4/3` works for most food/interior photography.

### Reference: Barilette

- **Working dir**: `~/Projects/websites/barilette/`
- **Desktop symlink**: `~/Desktop/barilette.html`
- **Palette**: `--espresso: #513408`, `--cream: #FAF9F5`, `--wine: #5a2b1c`, `--parchment: #D4CCC1`
- **Fonts**: Playfair Display (headings), Inter (body)
- **Sections**: Hero (interior bg) → Story (interior photo + highlights) → Photo Strip (5 food images) → Menu (tabbed: Breakfast/Food/Drinks/Coffee, each with feature image) → Parallax Break (interior + quote) → Gallery (9-image masonry) → Visit (info + Google Map) → Footer
- **Key patterns**: Tabbed menu with dotted separators, brown nav bar, local images in `img/` folder, two-column menu layout, photo strip between sections, parallax break with text overlay, masonry gallery with CSS columns
- **Image allocation**: 20 unique images, each used exactly once. Categorized by purpose: interior shots for atmosphere, food shots matched to menu categories, mixed for gallery

---

## Client Proposals and Audits

When building proposals or auditing a client's existing site/presence, follow these rules:

### Verify every factual claim before publishing

If the proposal states something specific about the client's business (review count, response status, photo count, service area wording, page speed), verify it fully before writing it in. Do not check 2 out of 18 reviews and generalize to "no responses." Do not assume a field is empty without looking. One wrong claim kills credibility.

**Process:**
1. Before writing any audit finding, confirm it by actually looking at the source (Google profile, live site, search results)
2. Check ALL instances, not a sample. If there are 18 reviews, scroll through all of them.
3. If you can't fully verify something, use softer language ("some reviews may be missing responses" vs "no responses")
4. Before pushing a proposal live, flag every factual claim and note whether it was verified or assumed. Fix the assumed ones.

### Lesson learned (BT Roofing, March 2026)
Stated "18 reviews with no responses" in the proposal. Bruce actually had responded to some. Only checked the first 2-3 reviews and assumed the rest. Could have damaged Tyler's credibility with the client. Always scroll through everything.
