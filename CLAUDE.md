# CLAUDE.md - FAF Foundation Site

## Project DNA

Static website for the FAF Foundation at foundation.faf.one - stewards of the Foundational AI-context Format open standard.

## Quick Context

- **Type**: Static HTML site (no build system)
- **Stack**: HTML, CSS, vanilla JavaScript
- **Deployment**: Vercel at foundation.faf.one
- **Design System**: fafcli.dev colors (--accent: #00bf63)

## Key Files

- `index.html` - Single-page site with all content
- `project.faf` - AI context file

## Commands

```bash
# Development
open index.html          # Preview locally

# No build required - static site
```

## Design Tokens

```css
--accent: #00bf63        /* Foundation green */
--accent-hover: #00a855
--accent-bright: #00ff88
--bg-primary: #fefcf8
--bg-secondary: #f9f6f1
--dark: #1a1a1a
```

## Content Sections

1. Hero - Foundation tagline and CTAs
2. Mission - Open standard, vendor neutral, community driven
3. Pillars - Speed, Precision, Universality, Openness
4. Resources - SDKs, specs, tools
5. Governance - Rust Foundation model
6. Timeline - FAF milestones
7. Join - Email signup form

## Related Sites

- faf.one - Main FAF site
- fafcli.dev - CLI documentation
- github.com/Wolfe-Jam/faf - Specification repo

## Editing Guidelines

- Maintain fafcli.dev color consistency
- Keep single-file architecture (no external CSS/JS)
- WIP modal for incomplete links
- Logo hover: green checkmark → orange smiley 🧡
