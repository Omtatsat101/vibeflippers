---
doc_id: ASSET-02
title: SaaS App — Seller + Buyer Action Checklist
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# SaaS App

## Asset Identity

| Field | Value |
|---|---|
| Asset type | SaaS application (subscription-based software) |
| Primary platform | **VibeFlippers** |
| Cross-listable to FW? | Rarely — only if hardware/IoT component or licensed-business operator |
| Typical price range | $10K–$2M+ |
| Typical multiple | 3–6x ARR (annual recurring revenue), 24–48x MRR |
| EF equivalent | EF SaaS category |
| Acquire.com equivalent | Most relevant comparable — they're SaaS-focused |
| Min listing threshold | $1K MRR (Standard); $5K MRR (Growth); $20K MRR+ (Premier) |
| Operator interview required? | Yes for all listings ≥$10K |

## What's typically included

- Application source code (full repo)
- Production infrastructure access (AWS/GCP/Azure account or containerized handoff)
- Database (with migration plan)
- Domain(s)
- Customer accounts + subscription data
- Stripe / payment processor account or migration plan
- Documentation (technical + user docs)
- Marketing site
- Pipeline of trial users
- Email list / outreach assets
- Open issues / bug list (transparency)
- Any IP, trademarks, copyrights

## What's typically excluded

- Founder's continued development (unless contracted)
- Personal cloud accounts (must migrate to buyer's account)
- Internal Slack / personal communications
- Unrelated side projects in same repo (must split)
- Pre-existing customer disputes / outstanding refunds

---

# 🟢 Seller Actions (SaaS)

## Stage 1 — Application

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register on VF; complete ID verification | Persona pass | Seller |
| ☐ | Verify business entity | EIN/Companies House | Seller |
| ☐ | Submit app URL + last 12-month MRR/ARR breakdown | Stripe screenshot or SaaS analytics export | Seller |
| ☐ | Indicate tech stack + hosting provider | Form answers | Seller |
| ☐ | Indicate any open-source licensing constraints | License declaration | Seller |
| ☐ | Acknowledge sliding commission | Listing Agreement signed | Seller |
| ☐ | Operator assigned within 48 hours | Email + deal room | Operator |

## Stage 2 — Vetting & Verification

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Connect Stripe (read-only) | OAuth | Seller |
| ☐ | Connect product analytics (Mixpanel / Amplitude / PostHog) | OAuth or read-only key | Seller |
| ☐ | Connect cloud billing console (read-only) | AWS/GCP/Azure billing access | Seller |
| ☐ | Upload last 12 mo bank statements + Stripe exports | PDFs / CSVs | Seller |
| ☐ | Upload customer cohort data (retention curves, churn) | CSV or analytics export | Seller |
| ☐ | Upload tech stack inventory (services, monthly costs, dependencies) | Cost breakdown | Seller |
| ☐ | Disclose monthly burn rate (infra + tools + team) | Cost statement | Seller |
| ☐ | Disclose customer concentration (top 10 % of ARR) | Customer report | Seller |
| ☐ | Disclose any pending lawsuits / IP claims | Written disclosure | Seller |
| ☐ | Disclose code dependencies + licenses (e.g. AGPL risks) | License audit | Seller |
| ☐ | Provide 30-day commit history summary | Git log summary | Seller |
| ☐ | 60-min Operator interview (recorded) | Transcript | Seller + Operator |
| ☐ | Receive Verification Score | Dashboard | Operator |

**Operator checks (SaaS-specific):** MRR retention rate (target >90% gross), churn rate, payment processor age (red flag if Stripe <6 months — indicates dropshipping pivot risk), customer support response health.

## Stage 3 — Listing Build

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Review platform-generated listing | Draft | Seller |
| ☐ | Approve description (anonymized) | Final copy | Seller |
| ☐ | Approve pricing (3–6x ARR band) | Pricing acceptance | Seller |
| ☐ | Choose deal structure preference (cash / earnout / equity rollover) | Structure declared | Seller |
| ☐ | Approve publish | Publish | Seller |

## Stage 5 — Offer & LOI

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Receive offer | Email | Seller |
| ☐ | Review buyer profile + technical depth | Profile review | Seller |
| ☐ | Accept / counter / reject within 72 hours | In-platform | Seller |
| ☐ | E-sign LOI | Smart contract | Seller |
| ☐ | Begin 21-day exclusivity (longer than e-comm because tech DD takes time) | Timer | Seller |

## Stage 6 — Due Diligence

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Open data room | Buyer access | Seller |
| ☐ | Schedule technical walkthrough call | Calendar | Seller |
| ☐ | Walk buyer through codebase (architecture, key modules, deploy pipeline) | Live screenshare | Seller |
| ☐ | Walk through admin panel + customer support tools | Screenshare | Seller |
| ☐ | Walk through onboarding funnel + activation flow | Screenshare | Seller |
| ☐ | Provide read-only repo access (14 days) | GitHub/GitLab invite | Seller |
| ☐ | Provide read-only staging environment | Staging URL + creds | Seller |
| ☐ | Answer all questions in 48 hr SLA | Q&A thread | Seller |
| ☐ | Run buyer's chosen security scan if requested | Scan report | Seller |

## Stage 7 — Closing & Migration

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign final APA | Smart contract | Seller |
| ☐ | Wait for escrow funding | Webhook | Operator monitors |
| ☐ | **Repo transfer** — push code to buyer's GitHub org OR transfer ownership of existing repo | Confirmation email | Seller |
| ☐ | **Domain transfer** — auth code shared | Auth code | Seller |
| ☐ | **Cloud account migration** — either transfer account OR redeploy to buyer's account with white-glove SP help | Migration confirmed | Seller |
| ☐ | **Database transfer** — SQL dump + import OR managed migration | Import successful | Seller |
| ☐ | **Stripe account** — option A: transfer ownership; option B: migrate customers via Stripe Connect / Billing API | Stripe migration confirmed | Seller |
| ☐ | **Customer email notification** — joint announcement (buyer + seller) | Email sent | Seller |
| ☐ | **Domain SSL** — confirm certs valid post-transfer | SSL Labs check | Seller |
| ☐ | **Third-party integrations** — re-auth or transfer (Twilio, SendGrid, Intercom, etc.) | Integration list complete | Seller |
| ☐ | **Documentation handover** — Notion/Confluence/Loom transfer | Docs repo accessible | Seller |
| ☐ | Confirm handover 100% | Checklist signed | Seller + Operator |

## Stage 8 — Post-close

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | 30-day transition support — up to 10 hours/week (more than e-comm because tech) | Time log | Seller |
| ☐ | (Common for SaaS) 6–12 month earnout structure for revenue continuity | Earnout dashboard | Seller |
| ☐ | Available for code questions in shared Slack | Slack history | Seller |
| ☐ | Leave buyer review | In-platform | Seller |
| ☐ | Receive funds release at inspection sign-off | Stripe Connect / bank | Seller |

---

# 🔵 Buyer Actions (SaaS)

## Stage 1 — Application

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register + ID verification | Persona pass | Buyer |
| ☐ | Submit Proof of Funds for SaaS deal range | Bank/wallet/facility statement | Buyer |
| ☐ | Auto-routed to Concierge tier | Tier assignment | Platform |
| ☐ | (Strongly recommended) Hire technical DD Service Provider | SP onboarded | Buyer |

## Stage 4 — Reveal & Save

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Filter listings: SaaS, ARR range, niche, tech stack | Filter results | Buyer |
| ☐ | Save listings | Favorites | Buyer |
| ☐ | Reveal listing | Reveal counter | Buyer |
| ☐ | Read Verification Score | Score breakdown | Buyer |
| ☐ | Set alerts | Saved search | Buyer |

## Stage 5 — Offer & LOI

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Submit offer with deal structure (cash, earnout %, equity rollover %) | Offer dialog | Buyer |
| ☐ | Specify what's included (code only / + customers / + Stripe / + team) | Term sheet | Buyer |
| ☐ | E-sign LOI | Smart contract | Buyer |

## Stage 6 — Due Diligence (SaaS-specific)

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Read all data room docs | Reviewed | Buyer |
| ☐ | **Code review** — architecture, code quality, test coverage, security | Repo access used; code review report from SP | Buyer |
| ☐ | **Tech debt review** — open issues, deprecated dependencies, scaling bottlenecks | Issue tracker review | Buyer |
| ☐ | **Infra cost audit** — verify monthly burn matches claims | Cloud billing console review | Buyer |
| ☐ | **MRR / churn audit** — cohort analysis, gross retention, net revenue retention | Stripe + analytics export reviewed | Buyer |
| ☐ | **Customer concentration** — verify no single account >15% MRR | Customer ARR report | Buyer |
| ☐ | **Pricing analysis** — current pricing vs. competitors; pricing power | Pricing matrix | Buyer |
| ☐ | **Security review** — pen test results, GDPR/SOC2 if applicable | Security audit | Buyer |
| ☐ | **Open-source license review** — check for AGPL / GPL contamination | License audit | Buyer |
| ☐ | **Dependency review** — third-party services + risk of dependency lock-in | Dependency tree review | Buyer |
| ☐ | **Customer support volume** — tickets/month, response time, NPS | Support metrics | Buyer |
| ☐ | **Acquisition channels** — paid vs. organic vs. word-of-mouth | Marketing report | Buyer |
| ☐ | **Trademark / IP check** — USPTO / EUIPO search | IP report | Buyer |
| ☐ | Renegotiate or proceed | Updated offer or proceed | Buyer |

## Stage 7 — Closing & Migration

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign APA | Smart contract | Buyer |
| ☐ | Fund escrow | Receipt | Buyer |
| ☐ | Provide receiving GitHub org / cloud account | Account info | Buyer |
| ☐ | Hire migration SP if needed | SP onboarded | Buyer |
| ☐ | Verify repo transfer | git pull successful | Buyer |
| ☐ | Verify staging deploy works | Staging URL responsive | Buyer |
| ☐ | Verify production deploy works | Customer can log in | Buyer |
| ☐ | Verify database integrity | Row counts match | Buyer |
| ☐ | Verify Stripe / payment continuity | Test transaction | Buyer |
| ☐ | Verify all third-party integrations | Integration tests pass | Buyer |
| ☐ | Send customer notification (joint with seller) | Email sent | Buyer |
| ☐ | Sign off on inspection | Sign-off button | Buyer |

## Stage 8 — Post-close

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Use seller transition support | Logged hours | Buyer |
| ☐ | Confirm earnout milestones (if structured) | Revenue dashboard | Buyer |
| ☐ | Leave seller review | In-platform | Buyer |

---

## SaaS-specific gotchas

| Gotcha | Mitigation |
|---|---|
| **Founder is the product** | Earnout strongly recommended; consultancy contract for transition |
| **Code in personal repo** | Must transfer ownership OR rewrite in fresh org |
| **Cloud account contains other projects** | Force account split before close |
| **Stripe non-transferability** | Stripe Connect onboarding for buyer; customers re-auth payment methods |
| **Customer churn shock from rebrand** | No rebrand for 90 days post-close (clause in APA) |
| **GDPR / data processor contracts** | Buyer must execute new DPAs with subprocessors |
| **Open-source license contamination** | Pre-close audit; license remediation in escrow if found |
| **Single-region hosting + buyer in different region** | Migration plan with downtime window negotiated |
| **Custom domain emails (Google Workspace)** | Workspace tenancy migration is a project itself |
| **Scheduled cron / background jobs** | Document all; buyer's infra must replicate |

## Operator checkpoints (SaaS-specific)

| Stage | Operator does |
|---|---|
| 2 | MRR cohort verification; check Stripe account standing |
| 2 | Verify cloud billing aligns with claimed burn |
| 3 | Confirm pricing reflects ARR multiple band |
| 6 | Stay neutral; ensure 48hr SLA; flag tech DD red flags |
| 7 | Witness repo transfer; confirm test transaction in production |
| 7 | Confirm escrow trigger only after buyer signs off post-inspection |
| 8 | Submit SaaS-specific closing report (test users active, MRR continuity) |
