---
doc_id: ASSET-10
title: Code Repo / Template — Seller + Buyer Action Checklist
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# Code Repository / Template

## Asset Identity

| Field | Value |
|---|---|
| Asset type | Reusable codebase, boilerplate, theme, component library, no-code template, AI prompt library |
| Primary platform | **VibeFlippers** ("Vibe Code Broker" subtype is core to VF identity) |
| Cross-listable to FW? | No |
| Typical price range | $50–$50K (rare to exceed) |
| Typical valuation | License sales × multiple (12–24 months) OR flat sale + handover |
| EF equivalent | NOT in EF catalog |
| Min listing threshold | None — accept any well-documented codebase |
| Operator interview required? | ≥$5K listing |

## What's typically included

- Source code (full repo)
- Documentation
- Demo / live preview
- Brand assets (if template includes branding)
- License agreement template
- (Optional) existing customer/license-holder list
- (Optional) Stripe / Gumroad / Lemon Squeezy account or migration

## What's typically excluded

- Founder's continued maintenance (unless contracted)
- Personal repos containing the code (must split out)
- Open-source code remains under original license (MIT etc.) — only the original-author copyright transfers
- Customer support beyond transition

---

# 🟢 Seller Actions

## Stage 1 — Application
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register + ID verify | Persona | Seller |
| ☐ | Submit repo URL or zip | URL/file | Seller |
| ☐ | Disclose license model (MIT / proprietary / dual / commercial-only) | License doc | Seller |
| ☐ | Disclose tech stack + dependencies | Dep list | Seller |
| ☐ | Disclose existing license-holders / sales history | Sales log | Seller |
| ☐ | (Optional) Vibe Code Broker subtype declaration | Subtype | Seller |
| ☐ | Listing Agreement | E-sig | Seller |

## Stage 2 — Vetting & Verification
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Provide read-only repo access | GitHub invite | Seller |
| ☐ | Connect Gumroad / Stripe / Lemon Squeezy if applicable | OAuth | Seller |
| ☐ | Upload last 12 mo bank/processor exports for sales reconciliation | Files | Seller |
| ☐ | Provide LICENSE.md + commercial-use clarification | LICENSE | Seller |
| ☐ | Provide README + setup docs | Docs reviewed | Seller |
| ☐ | Disclose all open-source dependencies + their licenses (esp. AGPL/GPL contamination risk) | License audit | Seller |
| ☐ | Disclose any AI-generated code components | Disclosure | Seller |
| ☐ | Provide demo/preview link | Live demo | Seller |
| ☐ | (≥$5K) 30-min Operator interview | Recorded | Seller + OP |

## Stage 3 — Listing Build
| ☐ | Approve listing draft + pricing + publish | Live | Seller |

## Stage 5 — Offer & LOI
| ☐ | Receive/respond; e-sign LOI; 7-day exclusivity | Smart contract | Seller |

## Stage 6 — Due Diligence
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Open data room | Buyer access | Seller |
| ☐ | 14-day buyer repo access | Invite | Seller |
| ☐ | Walkthrough call if requested (45 min) | Screenshare | Seller |
| ☐ | 48hr Q&A SLA | Q&A | Seller |

## Stage 7 — Closing & Migration
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign APA (with explicit IP assignment + license-holder rights handling) | Smart contract | Seller |
| ☐ | Wait for escrow funding | Webhook | OP |
| ☐ | **Repo ownership transfer** to buyer's GitHub/GitLab org | Confirmation | Seller |
| ☐ | **Documentation transfer** | Docs in buyer's space | Seller |
| ☐ | **Demo site** transfer (domain per asset 04 if applicable) | Demo on buyer infra | Seller |
| ☐ | **Sales account transfer** (Gumroad, Stripe Connect) OR list export | Transfer/export complete | Seller |
| ☐ | **Existing license-holder list** delivered (if commercial license) | List in vault | Seller |
| ☐ | **Customer notification** (joint announcement) | Email sent | Seller |
| ☐ | Confirm handover 100% | Signed | Seller + OP |

## Stage 8 — Post-close
| ☐ | 14-day transition support for any setup questions | Email | Seller |
| ☐ | Cease publicly representing as the maintainer (per APA non-compete) | Compliance | Seller |
| ☐ | Leave buyer review | In-platform | Seller |

---

# 🔵 Buyer Actions

## Stage 1 — Application
| ☐ | Register + ID verify + Proof of Funds | Profile | Buyer |

## Stage 4 — Reveal & Save
| ☐ | Filter (stack, license type, sales history); reveal; read Verification Score | Score | Buyer |

## Stage 5 — Offer & LOI
| ☐ | Submit offer (often BIN); e-sign LOI | Smart contract | Buyer |

## Stage 6 — Due Diligence
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | **Code review** — quality, structure, test coverage, dependencies | Repo review | Buyer (or SP) |
| ☐ | **Open-source license audit** — confirm no GPL/AGPL contamination unless permitted | License audit (Snyk Open Source / FOSSA) | Buyer |
| ☐ | **Documentation completeness** | Docs review | Buyer |
| ☐ | **Setup test** — clone repo, follow docs, get to working state | Setup successful | Buyer |
| ☐ | **AI-generated code rights** | Disclosure validated | Buyer |
| ☐ | **Sales history reconciliation** | Stripe ↔ bank | Buyer |
| ☐ | **Existing license-holder rights** (e.g. perpetual license terms) | Rights review | Buyer |
| ☐ | **Trademark on the template name** | TM check | Buyer |
| ☐ | Renegotiate or proceed | Updated offer | Buyer |

## Stage 7 — Closing & Migration
| ☐ | Sign APA + fund escrow | Receipt | Buyer |
| ☐ | Provide receiving repo org | Org info | Buyer |
| ☐ | Verify repo ownership | git pull from new home | Buyer |
| ☐ | Verify documentation accessible | Docs accessible | Buyer |
| ☐ | Verify demo site if applicable | Demo loads | Buyer |
| ☐ | Verify sales account / list received | Account access | Buyer |
| ☐ | Setup test under your control | Local clone works | Buyer |
| ☐ | Sign off on inspection (5 days) | Sign-off | Buyer |

## Stage 8 — Post-close
| ☐ | Honor existing license-holder rights per APA | Compliance | Buyer |
| ☐ | Leave seller review | In-platform | Buyer |

---

## Code/template-specific gotchas

| Gotcha | Mitigation |
|---|---|
| **AGPL/GPL contamination** | License audit; remediation in escrow if found |
| **Existing license-holders' rights** (e.g. they bought a perpetual license) | Buyer must honor or buy out; APA clause mandatory |
| **Code in personal repo with other projects** | Must extract to clean repo before close |
| **Dependencies with restrictive commercial licenses** | Identify in DD; replace if needed |
| **Trademark on template name** | TM check; possible rebrand |
| **Fonts/icons with non-commercial license** | Replace before close OR buyer buys commercial license |
| **AI-generated code commercial rights** | Verify per AI tool's TOS |
| **Existing customer support obligations** | Disclose support load; cap in APA |
| **Free tier vs. paid tier feature gating** | Document gating logic; transfer payment processing |

## Operator checks
- License audit on dependencies (Snyk/FOSSA)
- Setup test from cold-clone
- Sales reconciliation (if commercial)
- TM scan
- Documentation completeness check
