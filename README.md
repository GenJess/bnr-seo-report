# BNR Associates — AI-Powered Digital Transformation Hub

> **From a static WordPress brochure site to a fully AI-native sales and operations ecosystem — built in a single session.**

---

## The Story

**Before:** [bnrassociatesllc.com](https://bnrassociatesllc.com) — a serviceable but conversion-dead WordPress site. No pricing, no instant quotes, no booking flow. A visitor had to call to find out what anything cost.

**After:** A vertically integrated digital presence where a prospect can land, get an AI-generated quote in under 60 seconds, understand the value proposition, and book — without a single phone call required.

**Live site:** [bnr-power-washing-jgpts-projects.vercel.app](https://bnr-power-washing-jgpts-projects.vercel.app)  
**Live repo:** [github.com/jGPT-Automated/bnr-power-washing](https://github.com/jGPT-Automated/bnr-power-washing)

This repository is the **project intelligence hub** — it houses the SEO audit, competitive analysis, outreach tools, client-facing deliverables, and strategic context that powered the transformation.

---

## What's In This Repo

| File | Purpose |
|------|---------|
| `index.html` | Full SEO audit report — keyword gaps, competitor analysis, on-page recommendations, and a 90-day action plan |
| `bnr-client-portal.html` | Client-facing project portal — deliverable tracker, session notes, and next-step roadmap |
| `outreach-territory-map.html` | Mapbox-powered sales territory map — zones scored by median income × home age × property type to surface highest-value prospects |
| `bnr-pricing-guide.html` | Internal pricing reference guide |
| `bnr-presentation-html.html` | Stakeholder presentation deck |

---

## The Build Philosophy

### Visual Beauty and Information Clarity Are the Same Thing

Every build decision in this project started from one premise: **a confused visitor does not convert.** That means the hierarchy of information — what a prospect sees first, second, and third — is as much a design constraint as color or typography.

The site was built with:
- **Fluid type scales** using `clamp()` — text always readable, never cramped or oversized
- **Nexus design system** — warm neutral surfaces, teal accent reserved strictly for CTAs, zero decorative noise
- **Dark/light mode** — respecting user preference, maintaining contrast on every surface
- **One primary action per view** — no competing CTAs, no ambiguity about what to do next

### Conversion as the North Star

The original site buried friction at every step. The redesign inverts this entirely:

- **Above the fold:** service clarity + trust signals + single CTA
- **AI Quote Tool:** 5 inputs → instant price range → pre-filled booking form. The entire industry asks prospects to wait 24–48 hours for a quote. This site answers in seconds.
- **Social proof placement:** reviews appear adjacent to pricing, not isolated on a separate page
- **Mobile-first:** 60%+ of local service searches happen on mobile. Every touch target, every font size, every layout decision was validated at 375px first.

### The AI Quote Tool — Why It Matters

The quote flow is the highest-leverage feature on the site. It:

1. **Eliminates the #1 drop-off point** — prospects who don't get a price leave and call a competitor
2. **Qualifies leads automatically** — the inputs (sq footage, surface type, stain level) filter out mismatched jobs before a human touches the inquiry
3. **Sets price anchoring** — giving a range upfront means the sales conversation starts from an informed baseline, not from scratch
4. **Feeds the CRM** — every quote submission is a structured lead with job context attached

This is not a chatbot or a gimmick. It is a conversion instrument designed around how local service buyers actually make decisions.

---

## Outreach Territory Intelligence

The `outreach-territory-map.html` scores Montgomery County zones across three signals:

| Signal | Weight | Rationale |
|--------|--------|-----------|
| Median household income | 40% | Higher income = greater willingness to pay for premium exterior cleaning |
| Median home build year | 40% | Older homes accumulate algae, mildew, and oxidation faster — higher service urgency |
| Home type (single-family detached) | 20% | Best fit for pressure washing and soft wash services |

**Tier A zones** (score 85+) like Bentwater/Lake Conroe Shores and Panorama Village represent the highest-density pipeline opportunity for door-to-door and direct mail campaigns.

---

## SEO Audit Highlights

The `index.html` audit covers:

- **Keyword gap analysis** — high-intent terms BNR is invisible for vs. competitors ranking on page 1
- **On-page audit** — title tags, meta descriptions, heading structure, schema markup
- **Competitor breakdown** — what the top 3 local competitors do better and where BNR can outflank them
- **90-day action plan** — prioritized by impact-to-effort ratio, not just SEO theory

---

## Session Architecture

This entire ecosystem was designed and built in a single agentic session:

| Phase | Output |
|-------|--------|
| Discovery | Audited live site, identified conversion gaps, competitive landscape |
| Strategy | SEO keyword map, ICP definition, territory scoring model |
| Design | Nexus design system, dark/light mode, mobile-first layout |
| Build | Full site — hero, services, AI quote tool, reviews, booking flow |
| Intelligence | SEO audit report, client portal, outreach territory map |
| Infrastructure | GitHub repo, Vercel deployment, CI/CD pipeline |

---

## Built With

- **Mapbox GL JS** — territory map visualization
- **Vercel** — hosting and CI/CD
- **GitHub** — version control and project hub
- **Perplexity AI** — agentic design, build, strategy, and deployment

---

## Deploying the Hub

This repo is connected to Vercel. Any push to `main` triggers a redeploy of the SEO audit dashboard at the live URL.

To add the outreach map to its own Vercel deployment:
1. Fork or copy `outreach-territory-map.html`
2. Replace the Mapbox token placeholder with your token from [account.mapbox.com](https://account.mapbox.com/access-tokens/)
3. Connect to Vercel → deploy

---

*BNR Associates LLC — Montgomery County, TX*  
*Exterior cleaning, soft wash, pressure washing, algae & mildew treatment*
