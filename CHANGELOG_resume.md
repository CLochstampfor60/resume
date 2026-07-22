# Resume Changelog

All notable changes to Carl Lochstampfor's resume site are documented in this file.

---

## [2.1.0] - 2026-07-22

### Added — Research Content Expansion (extracted from COVA & COVA-X preprints)
- **"Technical Details" accordion** on the COVA and COVA-X research cards (native `<details>`/`<summary>`, no JS), each covering Tools & Frameworks, Methodology Highlights, Notable Results, and a **"My Contributions"** statement written for interview readiness
- **Research Timeline** section visualizing the COVA → COVA-X → ScamLingua progression (Apr 2026, Jun 2026, 2026)
- **Expanded tech tags** on research cards reflecting the actual stack: Qwen 2.5 14B, Ollama, scikit-learn, Hugging Face Transformers, PyTorch, DistilBERT, Longformer, dual-GPU training
- **New "ML Frameworks" skills line**: Hugging Face Transformers, PyTorch, scikit-learn, XGBoost, Longformer/DistilBERT, TF-IDF
- **COVA-X methodology detail**: three-role virtual-kidnapping architecture (67.1% → 46.5% artifact rate), quality-lifecycle pipeline (contamination scan, stage-direction stripping, automated relabeling), 12.7× label-consistency improvement, documented Qwen 2.5 14B capability limits

### Changed
- **JSON-LD `knowsAbout`** expanded with specific technologies discovered in the papers (Multi-Agent LLM Systems, Prompt Engineering, Longformer, DistilBERT, Hugging Face Transformers, PyTorch, XGBoost, scikit-learn, TF-IDF Text Classification, Conversational AI Classification, Smishing Detection, Social Engineering Defense)
- **AI/ML Research skills line** expanded with concrete framework names and Prompt Engineering
- **Certifications:** `Linux+ (In-Progress)` commented out (study paused) — kept in source as an HTML comment for possible later resumption
- **Version bumped to v2.1.0**; visible version string updated

### Preserved (per handoff requirements)
- Content Security Policy (CSP) — no new external resources required; unchanged
- GoatCounter analytics script placement
- Dark mode across all new elements
- Print stylesheet — accordions force-open and chevrons hidden when printing
- Mobile responsiveness (verified at ~380px) and reduced-motion support
- Scroll-reveal (`reveal` class) on the new Research Timeline section

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
