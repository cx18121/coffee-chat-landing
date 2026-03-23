# Necto — Project Context for Claude

## Project
Single-page landing site for **Necto**, an outreach pipeline tool for finance students that automates lead discovery and cold coffee chat emails. Currently a waitlist landing page; will expand into a full product app.

## Tech Stack
- Single HTML file (`index.html`) with embedded CSS + JS
- Google Fonts: Fraunces (display serif) + DM Sans (body)
- No framework, no build step

## Design Context

### Users
Finance students (juniors/seniors) at target schools — Wharton, Stern, Ross, Georgetown, Notre Dame — recruiting for IB, PE, VC, and AM roles. Time-constrained and competitive. Job to be done: land more coffee chats with less manual effort.

### Brand Personality
**Bold · Modern · Aspirational** — premium consumer product for serious finance students. Confident without arrogance. Modern without gimmicks.

### Emotional Goals
Every visitor should feel: excitement ("this changes my recruiting"), relief ("finally someone built this"), urgency ("I need this now"), and trust ("this looks legit").

### Aesthetic Direction
- **Reference**: Superhuman — soft periwinkle/lavender-to-sky gradient, premium serif headlines, glassmorphism UI cards
- **Palette**: `#7570C0` → `#EBF2FB` gradient hero, `#13101E` dark, white/glass off-hero surfaces
- **Typography**: Fraunces for display + italic emotional emphasis, DM Sans for body
- **Surfaces**: Glassmorphism with `backdrop-filter: blur`, layered shadows, `#F9F9FC` off-hero backgrounds

### Anti-References
- ❌ Generic SaaS template (purple on white, Inter, 3 feature icons)
- ❌ Dark/developer tool aesthetic (no dark mode, no terminal vibes)
- ❌ Corporate/enterprise stiffness
- ❌ Overly playful/consumer brightness (no Robinhood vibes)

### Design Principles
1. **Premium by restraint** — elegance from what's left out; generous whitespace, limited palette
2. **Airy confidence** — periwinkle gradient is the signature; light, soft, never heavy
3. **Real product, not a brochure** — UI mockups should look like a buildable real product
4. **Finance context earns trust** — specific firm names, deal references, school badges over generic copy
5. **Extensible toward a design system** — CSS variables and component patterns should promote cleanly to a full app
