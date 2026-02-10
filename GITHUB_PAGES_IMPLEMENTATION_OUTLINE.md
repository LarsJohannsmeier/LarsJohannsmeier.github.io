# GitHub Pages Implementation Outline (Professional Redesign)

## Verdict: Is this possible on GitHub Pages?
**Yes — fully possible** for the proposed professional redesign, with one caveat:
- If we want advanced build tooling or unsupported Jekyll plugins, we should use a GitHub Actions build/deploy workflow.
- If we stay within supported Jekyll + static assets, native GitHub Pages hosting is sufficient.

---

## 1) Recommended Approach

### Option A (Simplest, default)
Use GitHub Pages native Jekyll pipeline:
- Markdown content pages (`index.md`, `about.md`, `publications.md`, etc.)
- Shared layout/theme files
- Custom CSS in `assets/css/`
- Optional JavaScript for lightweight filtering/interactions

This is enough for a modern, professional portfolio/research website.

### Option B (If we need more advanced tooling)
Use GitHub Actions to build and deploy:
- Custom Jekyll plugins or non-supported gems
- Asset pipelines (Sass/PostCSS bundling, minification)
- More control over CI quality checks

---

## 2) Compatibility Check by Feature

| Proposed feature | GitHub Pages compatibility | Notes |
|---|---|---|
| Professional typography/colors/spacing via custom CSS | ✅ Yes | Add `assets/css/main.css` and include in layout. |
| Hero, cards, badges, section blocks | ✅ Yes | Implement via HTML/Markdown + CSS utility classes. |
| Navigation menu with clean routes | ✅ Yes | Configure with `_config.yml` and layout templates. |
| Publications grouped by type | ✅ Yes | Can be static sections, collections, or data-driven with YAML. |
| Publication filters/tags | ✅ Yes | Client-side JS filtering is straightforward. |
| SEO metadata / Open Graph | ✅ Yes | Add front matter defaults + layout meta tags. |
| Analytics (e.g., Plausible/GA) | ✅ Yes | Add script include in layout. |
| Lighthouse-friendly performance | ✅ Yes | Keep assets lean and optimize images. |
| Unsupported Jekyll plugin usage | ⚠️ Limited | Needs GitHub Actions build workflow if unsupported by Pages. |

---

## 3) Proposed Repository Structure

```text
.
├── _config.yml
├── _layouts/
│   ├── default.html
│   └── page.html
├── _includes/
│   ├── head.html
│   ├── nav.html
│   └── footer.html
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── publications-filter.js
│   └── img/
├── index.md
├── about.md
├── publications.md
├── research.md
├── talks.md
├── media.md
└── cv.md
```

---

## 4) Implementation Plan (Concrete)

### Phase 1 — Foundation (1 PR)
1. Add `_config.yml` with site metadata, title, description, and nav links.
2. Create base layout (`_layouts/default.html`) with:
   - semantic header/nav/main/footer,
   - responsive container,
   - metadata and social preview tags.
3. Add `assets/css/main.css` with design tokens:
   - color palette,
   - typography scale,
   - spacing system,
   - card/button styles.
4. Migrate existing pages to shared layout front matter.

### Phase 2 — Professional Content Presentation (1–2 PRs)
1. Rebuild home page into sections: hero, focus areas, selected publications, CTA.
2. Upgrade `about.md` into a timeline and highlight format.
3. Rework `publications.md` with structured entries + badges/links.
4. Add missing core pages (`research.md`, `talks.md`, `media.md`).

### Phase 3 — Quality & Credibility Layer (1 PR)
1. Add client-side filtering for publications by category/tag.
2. Optimize images and confirm mobile responsiveness.
3. Add analytics script and verify metadata previews.
4. Validate no broken links and run Lighthouse checks.

---

## 5) Risk & Constraint Notes
- GitHub Pages supports only a fixed set of Jekyll plugins in native mode.
- Heavy JS frameworks are unnecessary for this site and would reduce maintainability.
- The highest ROI comes from content hierarchy + visual consistency, not complex frontend tooling.

---

## 6) Success Gate (Definition of Done)
A redesign should be considered complete when:
1. Navigation and all top-level pages are live and link-clean.
2. Visual style is consistent across all pages.
3. Publications/projects are easy to scan and filter.
4. Mobile layout is stable and readable.
5. Lighthouse targets are met (Perf 90+, Accessibility 95+, Best Practices 95+, SEO 95+).

