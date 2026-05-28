---
doc_id: ASSET-14
title: Licensed Business — Seller + Buyer Action Checklist
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# Licensed Business (Home Care / Healthcare / Childcare / Cannabis / Liquor / Auto / etc.)

## Asset Identity

| Field | Value |
|---|---|
| Asset type | Business operating under a state-issued or federal license (transfer often non-trivial) |
| Primary platform | **FlipWala** |
| Cross-listable to VF? | Rarely (only if heavy digital component AND license is state-portable) |
| Typical price range | $50K–$10M+ |
| Typical multiple | 2.5–5x SDE; license scarcity drives premium (e.g. cannabis dispensary, liquor in restricted markets) |
| EF equivalent | NOT in EF catalog |
| BizBuySell equivalent | Yes |
| Min listing threshold | $50K SDE |
| Operator interview required? | Always |
| Real-estate involvement | Often triggers REQ-008 |
| License-specific compliance | **Always** — surfaced at Stage 1 by jurisdiction routing |

## Common license types

| License type | Issuer | Transfer process |
|---|---|---|
| Home care agency | State health department | License transfer + state survey |
| Childcare / daycare | State licensing dept | Background checks + facility re-inspection |
| Healthcare clinic | State medical board | Provider credentials + facility re-licensing |
| Cannabis dispensary | State + local cannabis regulators | Often non-transferable; structured as M&A of license-holder LLC |
| Liquor (on/off premise) | State ABC + local | State approval + sometimes local hearing |
| Auto repair / dealer | State DMV | License transfer + dealer bond |
| Pharmacy | State board of pharmacy + DEA | Pharmacist-in-charge transfer + DEA registration |
| Real estate brokerage | State RE commission | Broker-of-record transfer |
| Construction / contractor | State CSLB / equivalent | License transfer + bonding |
| Insurance agency | State insurance commission | Producer license transfer |

## What's typically included

- All physical-only-business assets (per asset 12)
- The license itself (or an agreed pathway to license transfer)
- License compliance records (audits, inspections, training)
- Bonded/insured status documentation
- Required staff credentials (e.g. pharmacist-in-charge, qualifying agent for contractors)
- Patient/client/customer records (HIPAA/state-privacy-aware)

## What's typically excluded

- Personal professional credentials of the seller (cannot transfer — buyer needs own qualifying agent)
- Outstanding compliance violations (must be cured before close OR escrowed)
- Pre-existing litigation

---

# 🟢 Seller Actions

## Stage 1 — Application
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register on FlipWala; ID verify | Persona | Seller |
| ☐ | Submit license type + license # + jurisdiction | Form | Seller |
| ☐ | Disclose license transferability (transferable / structured-via-LLC-sale / non-transferable) | License analysis | Seller |
| ☐ | Disclose qualifying-agent / pharmacist-in-charge / RN-of-record requirement | Disclosure | Seller |
| ☐ | Submit 12-month financials + license compliance summary | Financial + compliance | Seller |
| ☐ | Acknowledge sliding commission + license-specific transfer timeline | Listing Agreement | Seller |

## Stage 2 — Vetting & Verification
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Connect QuickBooks + POS + bank | OAuth/Plaid | Seller |
| ☐ | Upload 24 mo financials + tax returns | Files | Seller |
| ☐ | Upload current license document | License copy | Seller |
| ☐ | Upload last 3 years compliance/audit reports | Audits | Seller |
| ☐ | Upload bonds + insurance | Bonds + COIs | Seller |
| ☐ | Upload qualifying-agent / RN / pharmacist-in-charge credentials | Credentials | Seller |
| ☐ | Disclose any compliance violations / cure notices / suspensions in last 5 years | Disclosure | Seller |
| ☐ | Disclose any patient/client complaints / disciplinary actions | Disclosure | Seller |
| ☐ | Disclose data-privacy regime (HIPAA / state PHI / FERPA / etc.) | Compliance memo | Seller |
| ☐ | Disclose all required filings + their cadence | Filing schedule | Seller |
| ☐ | Operator on-site visit | On-site report | OP + Seller |
| ☐ | Receive Verification Score | Dashboard | OP |

## Stage 3 — Listing Build
| ☐ | Approve listing draft + pricing band + publish | Live | Seller |

## Stage 5 — Offer & LOI
| ☐ | Receive/respond; e-sign LOI; 60–120-day exclusivity (depending on license-transfer timeline) | Smart contract | Seller |

## Stage 6 — Due Diligence
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Open data room | Buyer access | Seller |
| ☐ | **Buyer engages licensing authority** for transfer pre-application | Licensing application | Buyer |
| ☐ | **License transferability path determined** (asset transfer / LLC purchase / state pre-approval) | Pathway documented | Buyer's lawyer |
| ☐ | On-site visit + employee interviews | On-site | Buyer |
| ☐ | All physical-business DD from asset 12 | Per asset 12 | Buyer |
| ☐ | **Compliance audit by buyer** — review last 3 years | Compliance memo | Buyer or SP |
| ☐ | **Patient/client records review** under appropriate confidentiality | Sample review | Buyer's compliance SP |
| ☐ | **Background checks** required by licensing authority for buyer + key staff | Background reports | Licensing authority |
| ☐ | 48hr Q&A SLA | Q&A | Seller |

## Stage 7 — Closing & Migration
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | **License transfer / new license issuance** by authority | License issued | Authority |
| ☐ | Sign APA conditioned on license transfer | Smart contract | Both |
| ☐ | Fund escrow (bank escrow typical) | Wire confirmation | Buyer |
| ☐ | All physical handover steps from asset 12 | Per asset 12 | All |
| ☐ | **Patient/client records transfer** with data-privacy-compliant notice | HIPAA-compliant transfer | All |
| ☐ | **DEA registration transfer** if pharmacy/medical | DEA confirmation | Authority |
| ☐ | **Bond / insurance** rebound under buyer's name | Bond/COI | Buyer |
| ☐ | **Required staff credentials** verified for new operating structure | Credentials in place | Buyer |
| ☐ | **Notice to current patients/clients** per state-required disclosure | Notification sent | Buyer |
| ☐ | Confirm handover 100% | Signed | All + OP |

## Stage 8 — Post-close
| ☐ | 90-day transition support — up to 10 hr/week (often required by licensing authority) | Time log | Seller |
| ☐ | Earnout typical (12-month tied to compliance maintenance + revenue) | Earnout dashboard | Seller |
| ☐ | Available for compliance/regulatory questions | Email | Seller |
| ☐ | Leave buyer review | In-platform | Seller |

---

# 🔵 Buyer Actions

## Stage 1 — Application
| ☐ | Register + ID verify; Proof of Funds | Profile | Buyer |
| ☐ | (Required in most cases) Engage industry-specific compliance attorney | SP onboarded | Buyer |
| ☐ | (Required for many licenses) Have your own qualifying-agent/RN-of-record/PIC ready | Credentials ready | Buyer |

## Stage 4 — Reveal & Save
| ☐ | Filter (license type, jurisdiction, SDE, remaining license term); reveal | Reveal | Buyer |

## Stage 5 — Offer & LOI
| ☐ | Submit offer with license-transfer contingency; e-sign LOI; 60–120-day exclusivity | Smart contract | Buyer |

## Stage 6 — Due Diligence
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | All physical-business DD from asset 12 | Per asset 12 | Buyer |
| ☐ | **License transfer process with authority** — pre-application | Licensing application | Buyer |
| ☐ | **Background checks** for self + key staff | Reports submitted | Buyer |
| ☐ | **Compliance audit** — last 3 years of records | Compliance memo | Buyer |
| ☐ | **Industry-specific contracts review** (Medicare/Medicaid for healthcare; supplier agreements for cannabis) | Contracts memo | Buyer's lawyer |
| ☐ | **Bond/insurance applications** ready to bind | Applications | Buyer's broker |
| ☐ | **Local community/zoning approvals** if required | Approval | Buyer |
| ☐ | **License-specific working capital** required | WC analysis | Buyer's CPA |
| ☐ | Renegotiate or proceed | Updated offer | Buyer |

## Stage 7 — Closing & Migration
| ☐ | Receive license transfer / new license | License in hand | Buyer |
| ☐ | Sign APA + fund escrow | Wire confirmation | Buyer |
| ☐ | All physical handover steps from asset 12 | Per asset 12 | Buyer |
| ☐ | Verify DEA / specialty registrations | Registrations live | Buyer |
| ☐ | Verify bond + insurance bound | Bonds + COIs | Buyer |
| ☐ | Verify required staff credentials in place | Credentials filed | Buyer |
| ☐ | Receive patient/client records (data-privacy-compliant) | Records in vault | Buyer |
| ☐ | Sign off on inspection (14–21 days) | Sign-off | Buyer |

## Stage 8 — Post-close
| ☐ | Maintain compliance per license terms | Compliance dashboard | Buyer |
| ☐ | Track earnout milestones | Dashboard | Buyer |
| ☐ | Leave seller review | In-platform | Buyer |

---

## Licensed-business gotchas

| Gotcha | Mitigation |
|---|---|
| **License non-transferable** | Structure as LLC purchase (buyer buys the entity that holds the license); limits to certain license types |
| **Authority delay** | Build 60–120 day window into LOI; some licenses (cannabis, healthcare) take longer |
| **Buyer fails background check** | Deal dies; build refund clause into earnest money |
| **Compliance violations discovered** | Cure pre-close OR escrow hold-back |
| **Patient/client records under HIPAA / state PHI** | Compliant transfer process mandatory |
| **DEA / federal registrations** (pharmacy, medical) | Federal-level approval needed in addition to state |
| **Insurance / bond non-transferability** | Buyer rebinds before close |
| **Qualifying agent / PIC requirement** | Buyer must have credentialed person in place at close |
| **Medicare/Medicaid CHOW (Change of Ownership)** | 60-90 day notice; payment delays |
| **Cannabis: 280E tax exposure** | CPA review of tax position |
| **Liquor: dram shop liability tail** | Insurance review |
| **Lease assignment + license transfer simultaneity** | Coordinate; license sometimes tied to address |
| **Required staff training/certification** for new owner | Plan time |
| **State-specific filings on transfer** | State-specific checklist |

## Operator checks
- License standing (no suspensions, cure notices)
- Compliance audit history
- All physical asset 12 checks
- Staff credentials currency
- Bonds + insurance current

## Real-world consideration

Licensed business deals are the most regulatory-heavy on the platform. The 60–120 day approval window often kills deals that would have closed faster in an unlicensed asset class. The platform's value-add is the Operator + Service Provider directory: surfacing qualified lawyers, compliance consultants, and qualifying agents fast. Without that, sellers and buyers go to specialized brokers — losing the platform's commission.
