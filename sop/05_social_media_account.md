---
doc_id: ASSET-05
title: Social Media Account — Seller + Buyer Action Checklist
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# Social Media Account

## Asset Identity

| Field | Value |
|---|---|
| Asset type | Social media account on Instagram, TikTok, YouTube, X (Twitter), Facebook, Telegram, LinkedIn, Threads |
| Primary platform | **VibeFlippers** |
| Cross-listable to FW? | No (digital-only) |
| Typical price range | $5–$20K (most listings); $20K–$200K (premium accounts with monetization) |
| Typical valuation | DealBaron benchmark + 30–50% verification premium for our verified-engagement model |
| EF equivalent | Not in EF catalog — they don't sell social accounts |
| DealBaron equivalent | This is their core asset class — see `../flipwala/DEALBARON-COMPETITIVE-INTEL.md` |
| Min listing threshold | None (any verified ownership) |
| Operator interview required? | Required ≥$1K listing or any monetized account |

> ⚠️ **Platform ToS risk:** Most social platforms prohibit account sales in their ToS. Sales happen anyway via "co-management" or full credential transfer. Disclose risk in APA.

## What's typically included

- Account login credentials (username, password)
- Recovery email + phone (transferred to buyer's)
- 2FA reset
- Connected business email forwarded to buyer
- Content history (already on account)
- Audience (already on account)
- Monetization setup if applicable (creator fund, brand deal pipeline, ad accounts)
- Content calendar / SOPs (if managed by team)

## What's typically excluded

- Founder's personal brand presence (account often pivots to new niche)
- Any cross-platform automation tied to founder's other tools
- Direct DMs / private message history (consider deleting before transfer for privacy)

---

# 🟢 Seller Actions (Social Account)

## Stage 1 — Application

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register + ID verification | Persona pass | Seller |
| ☐ | Submit account URL / handle | Handle entered | Seller |
| ☐ | Confirm ownership via DM challenge | Platform-specific challenge passed | Platform |
| ☐ | Disclose platform ToS risk acknowledgment | Risk acknowledged in writing | Seller |
| ☐ | Disclose if account has been previously sold | Disclosure | Seller |
| ☐ | Indicate monetization status | Yes/No + details | Seller |
| ☐ | Acknowledge sliding commission | Listing Agreement | Seller |

**Ownership challenge by platform:**
- **Instagram:** Post a unique platform-supplied phrase to story for 1 hour
- **TikTok:** Bio update with verification token for 1 hour
- **YouTube:** Add platform-supplied UTM/tag to "About" section
- **X:** Pinned tweet or display name update for 1 hour
- **Facebook:** Page admin role for platform's verification account
- **Telegram:** Bot DM verification

## Stage 2 — Vetting & Verification

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Connect Instagram Insights / TikTok Analytics / YouTube Analytics / etc. (read-only) | OAuth | Seller |
| ☐ | Connect Meta Creator Studio / TikTok Creator Center / YouTube Studio | OAuth | Seller |
| ☐ | Provide audience demographics (age, gender, country breakdown) | Analytics export | Seller |
| ☐ | Provide engagement metrics (likes, comments, shares, saves per post — last 30 posts) | Engagement export | Seller |
| ☐ | Provide growth history (followers/month, last 12 months) | Growth chart | Seller |
| ☐ | Disclose acquisition methods (organic, paid, follow-for-follow, bot history) | Disclosure | Seller |
| ☐ | Disclose any monetization revenue (creator fund, brand deals, affiliate, shop) | Revenue statement + payout proofs | Seller |
| ☐ | Disclose any policy strikes / shadowbans / community guideline violations | Strike history (platform-provided) | Seller |
| ☐ | Disclose any past DM/credential leaks | Disclosure | Seller |
| ☐ | Disclose account age (creation date) | Platform-shown date | Seller |
| ☐ | Operator interview (45 min) | Recorded | Seller + Operator |
| ☐ | Receive Verification Score | Dashboard | Operator |

**Operator checks (social-specific — closing the 12 DealBaron gaps):**
- **Engagement rate** — actual ER vs. follower count (flag <1% = likely bot followers)
- **Bot detection** — sample 100 followers; verify they're real accounts
- **Account age** — verify creation date matches claim
- **Geographic audience** — verify alignment with buyer's target geo
- **Niche consistency** — review 50 posts for content alignment with stated niche
- **Monetization verification** — payout statements ↔ bank deposits
- **Comparable sales** — pull similar accounts from DealBaron + internal data

## Stage 3 — Listing Build

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Review listing draft (anonymized handle until reveal) | Draft | Seller |
| ☐ | Approve description | Final copy | Seller |
| ☐ | Approve pricing band (DealBaron benchmark + verification premium) | Pricing acceptance | Seller |
| ☐ | Approve publish | Publish | Seller |

## Stage 5 — Offer & LOI

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Receive offer | Email | Seller |
| ☐ | Review buyer profile | Profile | Seller |
| ☐ | Accept / counter / reject | In-platform | Seller |
| ☐ | E-sign LOI | Smart contract | Seller |
| ☐ | 7-day exclusivity (short — social DD is fast) | Timer | Seller |

## Stage 6 — Due Diligence

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Open data room (analytics exports, payout proofs) | Buyer access | Seller |
| ☐ | Schedule 30-min walkthrough | Calendar | Seller |
| ☐ | Walk buyer through Insights / Studio dashboards | Screenshare | Seller |
| ☐ | Provide read-only access via "Manager" or "Editor" role if platform supports | Access added | Seller |
| ☐ | Answer questions in 48 hr | Q&A | Seller |

## Stage 7 — Closing & Migration

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign APA (with explicit ToS-risk acknowledgment) | Smart contract | Seller |
| ☐ | Wait for escrow funding | Webhook | Operator |
| ☐ | **Reset 2FA** (or temporarily disable for handover) | Confirmed | Seller |
| ☐ | **Change recovery email** to buyer's | Confirmed | Seller |
| ☐ | **Change recovery phone** to buyer's (if platform requires) | Confirmed | Seller |
| ☐ | **Hand over username + password** via secure deal vault (one-time link) | Vault link sent | Seller |
| ☐ | (For YouTube) **Move channel to buyer's brand account** OR transfer manager rights | Channel ownership transferred | Seller |
| ☐ | (For Facebook Page) **Add buyer as admin**; remove self after 7-day hold | Admin role transferred | Seller |
| ☐ | (For Instagram) **Remove all linked Facebook accounts**; buyer re-links theirs | Unlinked confirmed | Seller |
| ☐ | (For TikTok) **Remove all linked accounts**; buyer logs in from new device | Re-login successful | Seller |
| ☐ | **Hand over connected creator/business email** | Email forwarded or transferred | Seller |
| ☐ | **Hand over linked monetization accounts** (Stripe Tap-to-Pay, AdSense, etc.) | Per their TOS | Seller |
| ☐ | (For YouTube) **Mandatory 7-day hold period** before funds release | Hold period enforced | Operator |
| ☐ | Confirm handover 100% | Checklist signed | Seller + Operator |

## Stage 8 — Post-close

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Be available 7 days for any login issue | Email/Slack | Seller |
| ☐ | Do NOT log into account post-handover | (compliance) | Seller |
| ☐ | Leave buyer review | In-platform | Seller |
| ☐ | Receive funds release after platform hold period | Stripe/bank | Seller |

---

# 🔵 Buyer Actions (Social Account)

## Stage 1 — Application

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register + ID verification | Persona pass | Buyer |
| ☐ | Submit Proof of Funds (most social deals are <$25K Standard tier) | Statement | Buyer |
| ☐ | Read & acknowledge platform ToS risk warning | Risk ack | Buyer |
| ☐ | (Optional) Buy paid buyer add-on | Stripe | Buyer |

## Stage 4 — Reveal & Save

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Filter: platform, niche, follower band, engagement rate, monetization | Filter | Buyer |
| ☐ | Reveal listing | Reveal counter | Buyer |
| ☐ | Read Verification Score (engagement %, bot %, age, geo) | Score | Buyer |

## Stage 5 — Offer & LOI

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Submit offer | Offer dialog | Buyer |
| ☐ | E-sign LOI | Smart contract | Buyer |

## Stage 6 — Due Diligence (Social-specific)

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | **Engagement audit** — confirm engagement rate via random-post sampling | ER report | Buyer |
| ☐ | **Bot follower audit** — sample 200 followers; flag fakes | Audit report (HypeAuditor / Modash / FollowerCheck) | Buyer |
| ☐ | **Audience geography audit** — verify alignment with buyer goals | Demographics export | Buyer |
| ☐ | **Niche consistency** — review 50–100 most recent posts | Manual review | Buyer |
| ☐ | **Monetization verification** — payout proofs ↔ bank | Payout reconciliation | Buyer |
| ☐ | **Strike history review** — community guidelines log | Platform export | Buyer |
| ☐ | **Recovery email/phone** — confirm seller can change them at handover | Verification | Buyer |
| ☐ | **Linked accounts** (Meta, Google, TikTok cross-links) — buyer plans for re-link | Plan documented | Buyer |
| ☐ | **Comparable sales** — DealBaron + internal | Comparison | Buyer |
| ☐ | Renegotiate or proceed | Updated offer | Buyer |

## Stage 7 — Closing & Migration

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign APA (with ToS-risk acknowledgment) | Smart contract | Buyer |
| ☐ | Fund escrow | Receipt | Buyer |
| ☐ | Provide receiving recovery email + phone | Submitted | Buyer |
| ☐ | Receive credentials via vault one-time link | Link used | Buyer |
| ☐ | Log in from new device + new IP | Login confirmed | Buyer |
| ☐ | Re-set 2FA on buyer's authenticator | 2FA configured | Buyer |
| ☐ | Verify recovery email + phone changed | Confirmation emails | Buyer |
| ☐ | Verify monetization tools accessible | Dashboard accessible | Buyer |
| ☐ | (For YouTube) Wait through mandatory 7-day hold | Hold period | Buyer |
| ☐ | Sign off on inspection | Sign-off | Buyer |

## Stage 8 — Post-close

| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | 7-day post-handover check — account standing maintained | Status check | Buyer |
| ☐ | Leave seller review | In-platform | Buyer |

---

## Social-account-specific gotchas (DealBaron failure modes to avoid)

| Gotcha | Mitigation |
|---|---|
| **Platform ToS prohibits sales** | Mandatory APA disclosure; account at risk of platform suspension if reported |
| **Account locked after credential change** | Coordinate cutover during low-suspicion window; whitelist buyer's IP if possible |
| **Followers lose interest under new owner** | Buyer plans content continuity; soft niche pivot only after 60 days |
| **Bot followers** | Mandatory bot audit during DD (closing DealBaron gap #1) |
| **Engagement is fake** | Mandatory engagement audit (closing DealBaron gap #3) |
| **Monetization revoked after credential change** | Verify monetization isn't tied to seller's tax info; transfer cleanly |
| **YouTube 7-day hold for ownership transfers** | Built into our settlement timing |
| **Cross-platform login linkages** | List all and unlink before handover |
| **Past strikes hidden** | Mandatory strike-history disclosure; verifiable via platform export |
| **DM history** | Recommend seller wipes before handover for privacy |
| **2FA tied to seller's phone number** | Reset to buyer's phone before credential handoff |
| **Account gets banned post-purchase** | APA states refund if banned within 14 days for pre-existing reason |

## Operator checkpoints (Social-specific)

| Stage | Operator does |
|---|---|
| 1 | Run platform-specific ownership challenge |
| 2 | Bot audit, engagement audit, geo audit, monetization payout reconciliation |
| 3 | Verify pricing band aligns with engagement-verified valuation, not just follower count |
| 7 | Witness 2FA reset, recovery email/phone change, credential handover via vault |
| 7 | Enforce platform hold periods (e.g. YouTube 7 days) |
| 7 | Funds release only after buyer logs in successfully + buyer's hold period passes |
| 8 | 7-day post-close account-standing check |

## DealBaron 12-gap closure tracking (per listing)

| Gap | How we close it |
|---|---|
| 1. No engagement verification | Mandatory ER audit in Stage 2 |
| 2. No account age display | Auto-shown from platform-verified creation date |
| 3. No engagement metrics | ER + likes/comments/saves displayed |
| 4. No geo audience data | Demographics export shown |
| 5. No price history | Listing tracks price changes; shown to buyer |
| 6. No bundle deals | Sellers can group accounts → bundle pricing |
| 7. Junk catch-all categories | Niche tags from a 200+ tag taxonomy |
| 8. No API | Public API + webhook alerts for verified buyers |
| 9. Often-blank seller descriptions | Platform-required minimum 200-char description |
| 10. Self-reported income | Operator-verified payouts ↔ bank |
| 11. Single-asset (social only) | We sell social + everything else |
| 12. No comparable sales | Internal sales data + scraped DealBaron + Sedo + Acquire feed |
