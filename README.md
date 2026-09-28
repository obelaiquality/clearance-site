# clearance-site

The marketing website for the game Clearance (game repo: `obelaiquality/clearance`).

## State

Pre-announcement placeholder. The page and `robots.txt` block search indexing until the
Steam "Coming Soon" page and the announcement go live. Do not remove the `noindex` before then.

## Plan

- Release plan and dates: `clearance/Docs/RELEASE_PLAN.md`.
- Website, SEO and AI-search research: `clearance/Docs/research/hit-sweep/10-website-seo-geo.md`.
- Build process: `~/Repos/CLAUDE.md` "Design and website builds" (research, design system and
  build spec by the main model, sections by subagents, screenshot review at desktop and mobile).
- Brand and tokens come from the game: `clearance/Tools/ui/tokens.json`,
  `clearance/Docs/BRAND_BIBLE_v0.md`. No real-world brands.

## Deploy

GitHub Actions publishes `site/` to GitHub Pages on every push to `main`
(`.github/workflows/pages.yml`). The stack (static HTML now) is decided after the research.
