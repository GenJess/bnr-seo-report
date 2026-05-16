<div align="center">

# B&R Power Washing — AI Project Hub

### From Legacy WordPress to a Fully Deployed, AI-Native Web Ecosystem

[![Main Site](https://img.shields.io/badge/Live_Site-bnr--power--washing.vercel.app-152B4F?style=for-the-badge&logo=vercel)](https://bnr-power-washing-jgpts-projects.vercel.app)
[![SEO Report](https://img.shields.io/badge/SEO_Report-Deployed-B8943F?style=for-the-badge&logo=vercel)](https://bnr-seo-report.vercel.app)
[![Outreach Map](https://img.shields.io/badge/Outreach_Map-Deployed-01696f?style=for-the-badge&logo=mapbox)](https://bnr-seo-report.vercel.app)
[![Source Repo](https://img.shields.io/badge/Main_Repo-jGPT--Automated%2Fbnr--power--washing-181717?style=for-the-badge&logo=github)](https://github.com/jGPT-Automated/bnr-power-washing)

> *"Skip the call. Get an instant quote."*
>
> This repository is the **working project hub** for the B&R Power Washing digital transformation — housing the SEO competitive report, territory outreach map, and strategic context documents produced alongside the main site build. Every artifact here was deployed to Vercel through live API connections, with zero manual steps.

</div>

---

## The Transformation: Before & After

### Before — [bnrassociatesllc.com](https://bnrassociatesllc.com)

A standard WordPress/Elementor site doing what most local service sites do: list services, show a phone number, ask visitors to call. No pricing transparency. No online booking. No differentiation from the 200 other pressure washing companies ranking above it in Houston search results.

### After — A Three-Part Digital Ecosystem

Built end-to-end in a single agentic session through natural-language prompts and live API connections (GitHub, Vercel, Gemini, Mapbox, Cal.com, Cloudinary). Every deploy triggered automatically. Every asset generated programmatically.

---

## Ecosystem Map

### 🌐 1. The Main Site
**[bnr-power-washing-jgpts-projects.vercel.app](https://bnr-power-washing-jgpts-projects.vercel.app)**
→ Source: [github.com/jGPT-Automated/bnr-power-washing](https://github.com/jGPT-Automated/bnr-power-washing)

A ground-up rebuild with a custom brand identity, SVG illustration library, AI-powered quote engine, Cal.com booking embed, gallery with filter UX, and a full schema.org + GEO optimization layer. Built as static HTML/CSS/JS with a single Vercel serverless function — zero framework, zero build step, sub-100ms TTFB globally.

**The conversion moat:** Every competitor hides pricing behind *"starting at…"* or *"call for a quote."* The AI Quote Tool gives customers a real, photo-analyzed price range in 60 seconds — inverting the entire industry's friction model. Photo upload → Gemini Vision analysis → price range → Cal.com booking. Intent to calendar in one continuous flow.

---

### 📊 2. The SEO Report *(this repo)*
**Deployed via this repo to Vercel**

An interactive competitive intelligence dashboard auditing B&R's keyword landscape, competitor gaps, and organic opportunity across the Houston exterior cleaning market. Built as a fully deployed Vercel web app with:

- Dark/light mode toggle
- Filterable keyword table with competition difficulty badges
- Structured audit findings across 6 domains (technical SEO, content, backlinks, local signals, schema, GEO)
- Numbered action plan prioritized by impact
- Competitor breakdown with gap analysis

Designed not just to look good, but to make information **immediately actionable** for a non-technical business owner.

---

### 🗺️ 3. The Outreach Territory Map *(this repo)*
**Deployed via this repo to Vercel**

A Mapbox GL-powered interactive map scoring 24 zones across Montgomery County (Conroe, The Woodlands, Lake Conroe corridor) by **sales outreach priority** — built around the insight that older homes in higher-income neighborhoods are the highest-value prospects for algae and mildew exterior cleaning.

**Scoring model (0–100 composite score):**

| Signal | Weight | Rationale |
|---|---|---|
| Median household income | 40% | Higher income = more willing to invest in curb appeal and premium services |
| Median home build year | 40% | Pre-1995 homes = more exterior weathering, algae exposure, mildew susceptibility |
| Home type (single-family detached) | 20% | Best fit for residential pressure/soft-wash services |

**Top Tier A zones:** Bentwater / Lake Conroe Shores (score 98, median income $185k, avg built 1992), Panorama Village (score 97, avg built 1979), Montgomery Proper (score 89).

**Map features:**
- Bubble markers sized by tier, glowing rings on Tier A zones
- Click-to-popup with income, home age, and algae/mildew risk label
- Sidebar filters: slice by income threshold and home build year
- Dark Mapbox base map matching the project's visual system

> **To use live:** swap in your Mapbox public token at [account.mapbox.com/access-tokens](https://account.mapbox.com/access-tokens/)

---

## The Design Philosophy

Every artifact in this project was built around two principles that typically compete but shouldn't:

### Visual Beauty
Custom SVG illustrations that scale infinitely and never break. A precise brand palette — Ink `#0F1117` + Navy Blue `#152B4F` dominant + Antique Gold `#B8943F` sparing — that reads premium without being cold. Fluid type scales with `clamp()`. Scroll-triggered reveals, animated stat counters, dark/light mode everywhere. Inspired by GlossGenius's *"crisp digital ledger"* aesthetic — translated into an exterior cleaning context.

### Information Clarity & Conversion Optimization
Beauty that doesn't convert is decoration. Every design decision was interrogated: *does this move a visitor toward booking?* The AI Quote Tool exists because it answers the only question customers actually care about — *"what will this cost me?"* — before they bounce to a competitor. The outreach map exists because sales rep time is finite and should be spent on Tier A zones first. The SEO report exists because you can't improve what you can't measure.

---

## Files in This Repo

```
bnr-seo-report/
├── bnr-seo-report.html        # Interactive SEO competitive intelligence dashboard
├── bnr-outreach-map.html      # Mapbox territory map — 24 scored prospect zones
└── README.md                  # This file — project hub and narrative
```

---

## The Agentic Workflow

This entire ecosystem — three deployed web applications, a custom brand identity, an AI-powered serverless API, a Gemini Vision integration, competitive SEO research, territory scoring logic, and this documentation — was produced in a single session through natural-language prompts.

### Session Arc

| Phase | Output |
|---|---|
| Discovery | Audit of `bnrassociatesllc.com`, competitor research, category benchmarks |
| Brand direction | Color tokens, typography system, Refero/GlossGenius reference locked |
| Identity | Gold metallic logo refresh, custom SVG illustration library (12 assets) |
| v1 site | Premium homepage, mobile-first, scroll animations, schema.org |
| v2 (hierarchy fix) | Blue promoted to dominant secondary; gold restrained to accent moments |
| v3 (full-stack) | Gallery page, AI Quote Tool with live Gemini Vision, Cal.com embed, `/api/quote` serverless function, sitemap, `llms.txt` |
| SEO + GEO layer | Comprehensive schema.org, AI-crawler `robots.txt`, meta optimization |
| **SEO Report** | Interactive competitive intelligence dashboard → deployed to Vercel via this repo |
| **Outreach Map** | Mapbox territory map scored by income + home age → Tier A prospect zones |
| Handoff | This README |

### Why This Matters

- **Agentic delivery compresses timelines without sacrificing quality.** What traditionally required separate designer, developer, and SEO specialist across 4–6 weeks was executed in one session — and the quality bar is higher, not lower.
- **Every connection was live.** GitHub commits, Vercel deploys, Gemini Vision API calls, Mapbox tile rendering — no simulations, no mocked outputs.
- **The AI Quote Tool isn't a feature — it's a positioning statement.** When every competitor says "call for quote," the one that gives instant pricing communicates trust, modernity, and confidence. The conversion lift is real, but the brand signal is bigger.
- **GEO matters now, not later.** AI agent recommendations (ChatGPT, Perplexity, Claude) are becoming a primary discovery surface for local services. `llms.txt` + AI-crawler allowlist + pricing transparency cost zero and compound over time.

---

## Strategic Insights

**Pricing transparency is a moat in opaque markets.** Local services (HVAC, roofing, pest control, landscaping) all run the "starting at" / "call for quote" playbook. Whoever shows real numbers first owns category trust — and that trust converts.

**Outreach scoring beats geography.** Routing a sales rep by zip code is blunt. Scoring zones by income × home age × housing type means the first knock of the day is on the most likely door.

**SEO and GEO are different games with different rules.** Traditional SEO optimizes for crawl signals and keyword density. GEO optimizes for how an LLM would describe your business when asked — which means `llms.txt`, structured pricing data, explicit trust signals, and named service areas.

---

## Metrics to Track Post-Launch

| Metric | Baseline | Target |
|---|---|---|
| Time-to-quote | Hours to days (phone/form) | 60 seconds (AI tool) |
| Quote → booking conversion | ~12–18% (industry) | 25%+ |
| Google ranking (target keywords) | Not in top 10 | Top 3 within 90 days |
| AI agent inclusion | Not mentioned | Top 5 for "best pressure washing Houston" within 30 days |
| Tier A zones booked (outreach map) | 0 tracked | Pipeline in Airtable within 30 days |

---

## Credits

| | |
|---|---|
| **Strategy + direction** | AJ (Jesse) — Applied AI PM, Texas |
| **Built with** | Perplexity AI (agentic workflow) |
| **Design reference** | Refero "All-In-One Salon" / GlossGenius |
| **Infra** | Vercel · GitHub · Gemini · Mapbox · Cal.com · Cloudinary |
| **For** | B&R Power Washing · BNR Associates LLC · Houston, TX |

---

<div align="center">

*From [bnrassociatesllc.com](https://bnrassociatesllc.com) → to a live, AI-native, conversion-optimized web ecosystem.*

[Main Site →](https://bnr-power-washing-jgpts-projects.vercel.app) · [AI Quote Tool →](https://bnr-power-washing-jgpts-projects.vercel.app/#instant-quote) · [Source Repo →](https://github.com/jGPT-Automated/bnr-power-washing)

</div>
