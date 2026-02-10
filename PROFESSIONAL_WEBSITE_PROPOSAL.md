# Proposal: Make the Website Look Highly Professional

## 1) Objective
Transform this personal website into a polished, research-grade professional presence that:
- communicates scientific credibility in under 10 seconds,
- helps recruiters/collaborators find key information quickly,
- presents publications, projects, and media in a consistent and premium format.

---

## 2) Current Snapshot (What to Improve)
The current site already has strong foundational content (home, about, publications), but it can look significantly more professional by improving:
- **Visual hierarchy** (clear hero, typography scale, spacing rhythm),
- **Brand consistency** (color system, iconography, button/link patterns),
- **Navigation clarity** (currently references pages that may not exist yet),
- **Content design** (publication cards, impact metrics, project showcases),
- **Trust signals** (selected highlights, talks, awards, collaborations),
- **Conversion paths** (clear “Contact”, “Download CV”, “Book a call”).

---

## 3) Professional Design Direction

### A. Brand and Visual Identity
- **Tone:** modern academic + industry research lab aesthetic.
- **Color system:**
  - Primary: deep blue (`#0B1F3A`) for trust and technical authority,
  - Accent: electric cyan (`#1CA7EC`) for links and highlights,
  - Neutral palette: light grays for cards/background sections.
- **Typography:**
  - Heading: `Inter` or `IBM Plex Sans` (clean, modern),
  - Body: `Source Sans 3` or `Inter`.
- **Layout style:** generous whitespace, max content width (~1100px), subtle card shadows, crisp section separators.

### B. Information Architecture
Recommended top navigation:
1. **Home**
2. **Research** (projects, themes, impact)
3. **Publications**
4. **Talks & Media**
5. **About**
6. **CV**
7. **Contact**

This reduces ambiguity and makes the site instantly scannable.

### C. Home Page Structure (Professional Template)
1. **Hero section**
   - Professional photo,
   - One-line positioning statement,
   - Two CTAs: “View Publications”, “Download CV”.
2. **Research Focus cards** (3–4 cards)
   - e.g., Tactile Manipulation, Robot Learning, Autonomous Skill Synthesis.
3. **Selected Publications** (top 3)
   - title, venue badge, quick links (paper/code/video).
4. **Selected Projects / Demos**
   - visual thumbnails for credibility.
5. **Industry & Academic Experience strip**
   - NVIDIA, Franka, TUM, etc. (logo row).
6. **Profiles CTA block**
   - links to Google Scholar, ORCID, and LinkedIn.

---

## 4) Content Upgrades Needed

### A. About page
- Add a short **professional narrative** (problem areas + impact),
- Add **timeline layout** for education/experience,
- Add **awards, grants, invited talks** subsection.

### B. Publications page
- Convert to **filterable sections** (journal, conference, thesis),
- Add **tag badges** (tactile, manipulation, learning, planning),
- Add external buttons: PDF / DOI / Code / Video.

### C. New pages to complete professionalism
- `research.md`: flagship themes + outcomes,
- `talks.md`: invited talks/workshops/panels,
- `media.md`: videos, interviews, demos,
- Professional profile links: LinkedIn, Google Scholar, ORCID.

---

## 5) UX Standards to Enforce
- Mobile-first responsive layout.
- Consistent vertical spacing (8px or 4px grid system).
- Link/button states (hover/focus/active) for accessibility.
- Accessible contrast and semantic heading structure.
- Page load performance: optimize images and avoid heavy scripts.

---

## 6) Technical Implementation Plan

### Phase 1 — Foundation (fast, high impact)
- Add a custom stylesheet with design tokens (colors, spacing, typography).
- Implement shared components: hero, card, badge, CTA button styles.
- Clean navigation and remove broken/missing links.

### Phase 2 — Content polish
- Rewrite homepage into modular sections.
- Expand About with timeline and highlights.
- Reformat Publications into a clean, scannable layout.

### Phase 3 — Authority and conversion
- Add research/project pages with visuals.
- Add talks/media pages.
- Add simple analytics + SEO metadata (title/description/open graph).

---

## 7) Proposed Success Criteria
After redesign, the site should satisfy:
- A first-time visitor understands profile + expertise in <10 seconds.
- Publications and projects are discoverable in <2 clicks.
- Visual style is coherent across all pages.
- No dead links in global navigation.
- Lighthouse targets:
  - Performance ≥ 90,
  - Accessibility ≥ 95,
  - Best Practices ≥ 95,
  - SEO ≥ 95.

---

## 8) Suggested Next Actions (Practical)
1. Approve the design direction and navigation structure.
2. Implement style foundation and homepage revamp first.
3. Add missing pages with minimal professional skeleton content.
4. Perform final QA pass (mobile, links, accessibility, metadata).

If desired, this proposal can be translated directly into an implementation checklist and executed page by page in subsequent commits.
