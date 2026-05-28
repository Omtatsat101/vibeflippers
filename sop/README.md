---
doc_id: ASSET-00
title: Asset Action Checklists — Index
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# Asset Action Checklists — Index

This is the **most important folder in this suite.** One file per asset type. Each file contains:

- What the asset is + which platform owns it (FW or VF)
- **Seller actions** — full checklist to list, vet, and hand it over
- **Buyer actions** — full checklist to evaluate, offer on, and accept it
- Empire Flippers' equivalent step (so we know we're not skipping verification)
- Required evidence + Operator verification checkpoints
- Escrow/settlement triggers
- Post-close obligations

## How to read these checklists

Every asset checklist follows the same 8-stage structure (mirroring `../02_competitive/01_empire_flippers_model.md`):

| Stage | Seller activity | Buyer activity |
|---|---|---|
| 1. Application | Submit asset for vetting | Register + submit Buyer Application |
| 2. Vetting & Verification | Grant analytics access; provide proof | Pass ID + Proof of Funds |
| 3. Listing build | Approve listing copy + pricing | Browse / save / set alerts |
| 4. Reveal | (none) | Reveal listing (uses 1 of 3 free reveals) |
| 5. Offer & LOI | Accept / counter / reject | Make offer; sign LOI |
| 6. Due Diligence | Provide data room access; answer Q&A | Inspect; ask questions |
| 7. Closing & Migration | Execute handover steps | Fund escrow; receive asset |
| 8. Post-close | Provide transition support | Sign off; pay earnout if structured |

Within each stage, the checklist itself is a literal task list with:
- ☐ checkbox
- Action text
- Required evidence / artifact (where applicable)
- Owner (Seller / Buyer / Operator / Service Provider)

## Asset taxonomy

| # | Asset Type | Primary Platform | Cross-listable? | File |
|---|---|---|---|---|
| 00 | **Master Template** | n/a | n/a | [00_master_template.md](00_master_template.md) |
| 01 | **Shopify e-commerce store** | VF | Yes if has warehouse → FW cross-list | [01_shopify_store.md](01_shopify_store.md) |
| 02 | **SaaS app** | VF | Rarely (only if has physical hardware) | [02_saas_app.md](02_saas_app.md) |
| 03 | **Content website / blog** | VF | No | [03_content_website.md](03_content_website.md) |
| 04 | **Premium / aged domain** | VF | No | [04_domain.md](04_domain.md) |
| 05 | **Social media account** | VF | No | [05_social_media_account.md](05_social_media_account.md) |
| 06 | **Hybrid e-comm + warehouse** | FW (primary) + VF (cross-list digital) | **Always** | [06_hybrid_ecom_warehouse.md](06_hybrid_ecom_warehouse.md) |
| 07 | Newsletter | VF | No | _Pass 2_ |
| 08 | Mobile app (iOS/Android) | VF | Rarely | _Pass 2_ |
| 09 | Brand package (name + logo + social + content) | VF | No | _Pass 2_ |
| 10 | Code repo / template | VF | No | _Pass 2_ |
| 11 | Ad account | VF | No | _Pass 2_ |
| 12 | Physical-only business (laundromat, gym, salon) | FW | No | _Pass 2_ |
| 13 | Franchise (with digital layer) | FW (primary) | Yes | _Pass 2_ |
| 14 | Licensed business (home care, healthcare) | FW | No | _Pass 2_ |

## Cross-cutting requirements every checklist enforces

| Requirement | Applies when | Enforced by |
|---|---|---|
| Seller ID verified | Always | REQ-001 |
| Seller business entity verified | Always | REQ-004 |
| Seller proof of revenue | Always (Stage 2) | REQ-003 |
| Buyer ID verified | Before reveal | REQ-001 |
| Buyer Proof of Funds | Before offer | REQ-003 |
| Buyer Concierge tier auto-routed | At verification | REQ-003 |
| Operator assigned | At Stage 1 approval | REQ-009 |
| KYC/AML over $3K | All deals | MAKE-SCENARIO #4 |
| OFAC screening | All deals | MAKE-SCENARIO #5 |
| Smart contract APA | At Stage 5 | REQ-009 |
| Escrow funded before transfer | Stage 7 | Escrow.com API |
| Inspection period | Post-transfer | 3–7 days |
| Both parties leave reviews | Post-close | Trust score |

## Checklist completeness scoring

When an asset checklist is built, score it against:
- ☐ Has Seller and Buyer sections
- ☐ Covers all 8 stages
- ☐ Every action has owner + evidence
- ☐ Has EF equivalent reference
- ☐ Has Operator checkpoint per stage
- ☐ Specifies escrow trigger
- ☐ Specifies post-close obligations

Aim for 100% on every asset before launch.
