# B&R Exterior Services — AI-Native Digital Ecosystem

**From a WordPress site with no conversion path → a fully autonomous digital operation built, deployed, and iterated in a single session.**

---

## The Arc

| Stage | URL | Status |
|-------|-----|--------|
| Before | [bnrassociatesllc.com](https://bnrassociatesllc.com) | Original WordPress site — no CTA, no pricing, no quote flow |
| New Site | [bnr-power-washing.vercel.app](https://bnr-power-washing-jgpts-projects.vercel.app) | AI-native redesign — quote tool, SEO architecture, conversion-first |
| This Portal | [bnr-seo-report (Vercel)](https://bnr-seo-report.vercel.app) | Client deliverables hub — all reports, deck, map, and pricing |

---

## What's In This Repo

### `index.html` — Client Portal Hub
The entry point. All four deliverables in one nav-accessible dashboard. Shows project phase status, key metrics, and links to every artifact. Designed as a shareable client-facing URL — clean enough to send directly to BNR.

### `bnr-presentation-html.html` — Client Presentation Deck
A 7-slide web-native presentation covering:
- The starting point (SEO 32/100, no conversion path)
- What was built and why
- The AI Quote Tool — how it inverts industry friction
- Design philosophy: beauty and conversion as the same goal
- The SEO gap analysis and opportunity map
- Phase 2 growth path and retainer ROI

### `bnr-pricing-guide.html` — Pricing & Retainer Guide
Market rate comparison (DIY → freelancer → agency → B&R retainer) plus the three tier breakdowns — Foundation ($297), Growth ($597), Dominate ($997) — with ROI snapshot showing break-even at 22 additional jobs/year.

### `bnr-seo-report.html` — SEO Audit Report
Full keyword gap analysis, competitor breakdown (The Woodlands Pressure Washing, Conroe ProWash), Google ranking factors checklist, and prioritized 12-action plan. Baseline: 32/100.

### `outreach-territory-map.html` — Outreach Territory Map
24 Montgomery County zones scored 0–100 by median household income, home age (pre-1995 = higher algae/mildew risk), and home type. Tier A zones (score 90+) are the highest-value prospects for direct outreach campaigns. Built with Mapbox GL.

### `B&R Redesign 2026.md` — Full Project Context
The complete session record — all research, competitive analysis, design decisions, copy rationale, and technical choices documented in one place. The source of truth for this project.

---

## The Innovation: AI Quote Tool

The power washing industry standard: phone calls, 24–72 hour callbacks, friction at every step.

The B&R approach: a homeowner lands on the site, answers 4 questions, and receives an accurate scoped estimate in under 60 seconds — 24/7, no phone tag, no wait.

This isn't a contact form with a delayed response. It's a fully autonomous intake operator that:
- Qualifies the prospect (property type, square footage, services needed, location)
- Generates a realistic estimate range based on actual service pricing
- Captures lead data for follow-up
- Primes the prospect to book before a competitor even returns their call

---

## Design Philosophy

Every visual and structural decision was made against one question: **does this move someone closer to booking?**

- **Navy + gold palette** — signals premium and established trust without alienating residential homeowners
- **IBM Plex type system** — mono for data/labels, serif for authority, sans for readability
- **Information hierarchy** — primary CTA above the fold on every page, quote flow accessible within 2 clicks from anywhere
- **Conversion and aesthetics are the same goal** — a confusing page is an ugly page; a clear page is a beautiful page
- **Mobile-first at 375px** — the majority of local service searches happen on mobile
- **Performance budget** — static Vercel deployment targeting sub-1.5s LCP

---

## How Deployment Works

- **GitHub (GenJess)** — source of truth for all files in this repo
- **Vercel (generativejesse)** — deploy any public GitHub repo to Vercel; accounts don't need to match
- To deploy: Vercel → New Project → Import `GenJess/bnr-seo-report` → Deploy
- Live portal: `bnr-seo-report.vercel.app` (or whatever Vercel assigns)

---

## Built With

- **Perplexity AI** — agentic build, GitHub pushes, and Vercel coordination
- **Mapbox GL JS** — territory outreach map (requires public token)
- **Google Fonts** — Playfair Display + IBM Plex Sans/Mono
- **Vercel** — static hosting + CDN
- **GitHub (GenJess)** — version control and deployment source

---

*B&R Exterior Services — Conroe, TX — May 2026*
