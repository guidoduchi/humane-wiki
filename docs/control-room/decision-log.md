# Decision Log

Status: Working Board
Spoiler Level: Full Canon

This page records important creative and repository decisions so the project does not forget why it changed direction.

## Decision Format

Use this format:

```md
## YYYY-MM-DD — Decision Title

**Decision:** What changed?

**Reason:** Why was this chosen?

**Impact:** What does this affect?

**Follow-up:** What should happen next?
```

## 2026-04-30 — Separate Wiki from Manuscript

**Decision:** The public-facing HUMANE wiki is separate from the manuscript repository.

**Reason:** Canon support, lore, and development notes should not be mixed with chapter prose.

**Impact:** This wiki tracks truth, structure, and development logic. The manuscript repository stores actual book prose.

**Follow-up:** Keep chapter pages focused on purpose and continuity, not full prose.

## 2026-04-30 — Use Docsify for GitHub Pages

**Decision:** The wiki uses Docsify as a lightweight single-page Markdown app.

**Reason:** Docsify keeps the repository Markdown-first and avoids a heavy build pipeline.

**Impact:** GitHub Pages can serve the site directly from `main` root after Pages is enabled.

**Follow-up:** Maintain `_sidebar.md`, `_navbar.md`, `index.html`, `.nojekyll`, and `404.html` carefully.

## 2026-04-30 — Redesign as Control Room

**Decision:** The wiki should feel like a narrative-development control room, not just a file index.

**Reason:** HUMANE needs a place to track canon, pressure, questions, and decisions while developing the book.

**Impact:** Homepage, sidebar, and project pages now prioritize dashboard, open questions, review gates, and workflow.

**Follow-up:** Keep expanding pages around decisions, contradictions, and active development signals.
