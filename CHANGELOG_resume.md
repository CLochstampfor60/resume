# CHANGELOG Update Entry

Add this entry to the top of your existing `CHANGELOG_resume.md`:

---

## [2.0.0] - 2026-07-22

### Added — Phase 1: COVA/COVA-X Research Content
- **Featured Research section** with COVA and COVA-X papers (arXiv:2604.11752, arXiv:2606.06879)
- **ScamLingua platform showcase** with links to live site and source repository
- **Mentorship attribution**: Dr. Ayan Roy (CNU), CCI Undergraduate Research Program
- **Research metrics cards** displaying: 10,985 synthetic conversations, 79.71% accuracy, 8 fraud categories, 2 papers under review
- **Updated skills section** with AI/ML research capabilities: LLMs, Synthetic Data Generation, Transformer Fine-Tuning, Dataset Engineering, Ollama/Qwen Local Inference, Trust-Focused Web Engineering
- **Tech tags** for projects showing technology stack at a glance
- **ResearchGate profile link** in social links bar

### Added — Phase 2: UI/UX Upgrades
- **Animated metric counters** with easing animation (counters animate when scrolled into view)
- **Scroll-reveal animations** for all major sections (respects `prefers-reduced-motion`)
- **Interactive research cards** with gradient borders and hover states
- **Metric card shimmer effect** for visual polish
- **Navigation link for Research** section in header

### Changed
- **Executive Summary** updated to reflect AI security research focus and CCI program involvement
- **JSON-LD structured data** expanded with research-related `knowsAbout` entries and updated `jobTitle`
- **SEO meta tags** updated with AI security and research keywords
- **Radar chart** updated to include "AI/ML Research" as a skill category (replacing "Data Ana")
- **Chart color scheme** changed to purple to align with research theme
- **Version bumped to v2.0.0** (major update with new content sections)

### Preserved (per handoff requirements)
- Content Security Policy (CSP) — no new external domains needed
- GoatCounter analytics script placement
- Dark mode toggle functionality
- Mobile responsiveness
- Print stylesheet for PDF export
- Reduced motion support

### Technical Notes
- CSP updated to allow `scamlingua.org` in `img-src` for potential future OG images
- All animations use CSS transitions (no new JS libraries required)
- Counter animations use `requestAnimationFrame` for smooth 60fps rendering
- IntersectionObserver used for scroll-reveal (native browser API, no polyfill needed)

---
