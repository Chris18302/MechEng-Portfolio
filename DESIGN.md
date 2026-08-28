# Design System — Christopher Suarez Engineering Portfolio

## Creative direction: Technical Editorial / Field Notebook

The site should feel like an engineering field notebook refined into a professional publication: warm drafting paper, precise rules, restrained engineering-blue accents, numbered project indexes, dimensional marks, and clean technical typography.

It should not look like a SaaS landing page or a generic developer template. The visual design supports the engineering story rather than competing with it.

## Design principles

1. **Proof before claims.** Project evidence appears immediately after the hero.
2. **Editorial hierarchy.** Use large typography, whitespace, rules, and numbered sections rather than repeated floating cards.
3. **Technical restraint.** Fine lines, grid references, and mono labels provide engineering character without decoration overload.
4. **Field + analysis balance.** Visual language should feel equally appropriate for a mechanical room, a drawing set, and a MATLAB plot.
5. **Scannable for recruiters.** Every section has a clear purpose and short evidence-driven copy.

## Color tokens

- Paper: `#f3efe6`
- Paper raised: `#faf7f0`
- Ink: `#172126`
- Muted ink: `#5b6668`
- Rule: `#c8c6bb`
- Engineering blue: `#245f78`
- Engineering blue dark: `#163e50`
- Brass: `#9a642f`
- Soft blue: `#d9e7eb`

Avoid pure black and pure white for major surfaces.

## Typography

- Display / headings: `Space Grotesk`, with sans-serif fallbacks.
- Body: `IBM Plex Sans`, with sans-serif fallbacks.
- Technical labels / metadata: `IBM Plex Mono`, with monospace fallbacks.

Use external web fonts only as enhancement; the layout must remain usable with fallbacks.

## Geometry

- Main content max width: 1180px.
- Borders: 1px rules; no heavy shadows.
- Radius: 0–4px for controls and project markers.
- Section spacing: large and deliberate.
- Cards only where content genuinely needs containment.

## Components

### Site header
Compact sticky navigation with name, focus area, and anchor links.

### Hero
Large statement of discipline and direction. Include current degree / graduation marker and three compact actions: work, GitHub, LinkedIn.

### Project index
Numbered, full-width rows with project type, title, short proof statement, tools, and link. Avoid six identical rounded cards.

### Experience rail
Three focused entries: Kelvin, Brooklyn Navy Yard, CUNY Building Performance Lab. Each entry states the engineering context and strongest technical contribution.

### Skill matrix
Group skills by Mechanical / Building Systems, Analysis / Simulation, CAD / Documentation, and Field / Project Delivery. No logo wall.

### Build-next strip
Three projects only: commissioning data logger, HVAC load calculation, duct/fan test rig.

### Footer
Minimal contact and confidentiality note.

## Motion
Subtle reveal/hover only. No bounce or elastic effects. Respect `prefers-reduced-motion`.

## Responsive behavior
- Desktop: two-column hero metadata and full project rows.
- Tablet: stack project metadata beneath titles.
- Mobile: single-column layout, horizontal nav becomes compact, buttons remain easy to tap.
