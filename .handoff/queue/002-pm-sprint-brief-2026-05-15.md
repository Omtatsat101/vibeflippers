---
type: pm-design-brief
priority: high
from: claude
created: 2026-05-15
role-distribution: claude=executor (code pushes only), codex=PM+design+planner
---

# VibeFlippers — 2-Hour Sprint PM Brief (2026-05-15)

## Context
Riket is stepping away for 2h and asked me (Claude) to scale VibeFlippers + FlipWala under your direction as PM/design lead. I push code; you steer.

## Current State (verified 2026-05-15)
- **Site:** vibeflippers.com on GitHub Pages, repo `Omtatsat101/vibeflippers`, head `90f6f8c`
- **Latest shipped:** Stripe live Payment Links wired into `selectPlan()` + `upgradeToPaidBuyer()` (REQ-005, 2026-05-09)
- **Tiers live:** Starter $10 / Pro $49 / Enterprise $199 / Paid Buyer (range $10–$199/mo)
- **Index.html:** 7,576 lines, single-file vanilla HTML/CSS/JS, localStorage persistence
- **Theme:** Purple/dark `#6c3caf` accent on `#0c0a14` background
- **Modules shipped:** Marketplace, Sell, Valuations, Pipeline, Escrow, Domains, AI Agent, Brand-in-a-Box, Hot Deals, Reseller, NFT Ownership, Admin, How It Works, About, Subscriptions, Roadmap voting, Legal (Privacy/Terms)
- **Supabase sync layer:** v3.2 (offline-first, dormant by default)
- **NO contact method:** zero WhatsApp/phone/email contact links visible to buyers — only a DMCA email exists deep in legal
- **NO og:image:** missing from social-share meta tags
- **Bare sitemap:** only homepage URL

## Strategic Positioning Reminder
Per memory: VibeFlippers + FlipWala are positioned as a brand-empire ecosystem, NOT standalone SaaS competitors to Empire Flippers/Flippa. Vibe Sketch is the POD-personalization connector inside this ecosystem (4 distribution channels). Unified Stripe account. International (VibeFlippers) + US (FlipWala) HQ split provides regulatory cushion.

## Questions for You (PM/Design)
Please respond in `responses/002-pm-sprint-brief-2026-05-15.md` with:

1. **Top 3 ship priorities for next 2h?** I can execute any of these without further approval:
   - Contact module (form + email — no WhatsApp number on file)
   - Buyer-trust hardening (escrow walkthrough, verified-seller badges, payment-method explainer)
   - SEO+social: og:image creation, expanded sitemap, JSON-LD Organization/BreadcrumbList, FAQ schema
   - Mobile UX audit + responsive fixes
   - Performance: lazy-load, preconnect, deferred non-critical CSS
   - Roadmap voting analytics (Supabase persist)
   - Reseller storefront flow polish
   - NFT-ownership claim flow polish
   - Admin module live-metric wiring
   - Cross-site referral widget linking to FlipWala/Vibe Sketch

2. **Brand visual direction for og:image?** I can generate an SVG/PNG OG card. Need a one-liner concept: tagline + visual emphasis (e.g., "AI marketplace, purple gradient, listing-card mockup" vs "Hero text + Empire Flippers comparison stat").

3. **Pricing-page split?** Should `/pricing` become a dedicated section or stay inline? (Conversion impact discussion)

4. **Listings: real vs. seeded?** The marketplace shows seed listings. Should we (a) add a clear "demo data" badge, (b) wipe and show empty state with CTA, or (c) leave as-is for trust signaling?

5. **Cross-promotion with FlipWala?** A "Also see FlipWala" widget — placement and copy?

6. **Roadmap voting:** what features should be voteable (currently empty)?

## Constraints
- Single-file HTML — no build system; everything must work without npm
- No invented data (real phone numbers, real testimonials)
- No third-party tracker without explicit approval
- Stripe Payment Links must stay live and intact
- All LLM data flow remains Supabase-only (data sovereignty rule)

## Deliverable Expected From You
A prioritized punch-list ranked by impact/effort. I'll execute and commit. You can do this in <30 min if you skip prose.
