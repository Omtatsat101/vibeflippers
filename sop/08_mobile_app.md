---
doc_id: ASSET-08
title: Mobile App (iOS/Android) — Seller + Buyer Action Checklist
phase: requirements
site: FlipWala + VibeFlippers
owner: Riket Patel
generated: 2026-05-04
status: draft
evidence_grounded: true
---

# Mobile App (iOS / Android)

## Asset Identity

| Field | Value |
|---|---|
| Asset type | Native or hybrid mobile app on App Store / Google Play |
| Primary platform | **VibeFlippers** |
| Cross-listable to FW? | Rarely (only with hardware/IoT) |
| Typical price range | $10K–$5M+ |
| Typical multiple | 3–6x ARR (subscription apps); 30–48x monthly net (ad-revenue apps); 24–36x monthly revenue (purchase-based) |
| EF equivalent | Apps category |
| Min listing threshold | $1K MRR or $2K monthly ad revenue |
| Operator interview required? | Always |

## What's typically included

- App Store + Google Play listings (developer account transfer or app transfer)
- Source code (full repo)
- Backend API + infrastructure
- Database
- Stripe / IAP / subscription accounts
- Marketing site
- Brand assets (icon, screenshots, video, ASO copy)
- Push notification provider account (OneSignal, Firebase, etc.)
- Analytics (Mixpanel/Amplitude/Firebase/AppsFlyer)
- Ad SDK accounts (AdMob, AppLovin, etc.) if ad-monetized
- Reviews + ratings (transferred via app transfer feature)

## What's typically excluded

- Founder's developer account (unless transferred — Apple/Google specific rules)
- Personal Apple ID for the developer account
- Code signing certificates (regenerate under buyer's developer account)

---

# 🟢 Seller Actions

## Stage 1 — Application
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Register + ID verify | Persona | Seller |
| ☐ | Submit App Store / Play Store URLs | URLs | Seller |
| ☐ | Disclose monetization (subscription / ads / IAP / freemium / paid) | Statement | Seller |
| ☐ | Disclose tech stack (native, RN, Flutter, etc.) | Stack | Seller |
| ☐ | Acknowledge App Store / Play Store ToS for transfer | Acknowledgment | Seller |
| ☐ | Listing Agreement | E-sig | Seller |

## Stage 2 — Vetting & Verification
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Connect App Store Connect (read-only) | OAuth | Seller |
| ☐ | Connect Google Play Console (read-only) | OAuth | Seller |
| ☐ | Connect product analytics (Mixpanel/Amplitude/Firebase) | OAuth | Seller |
| ☐ | Connect Stripe / IAP processor | OAuth | Seller |
| ☐ | Connect ad SDK accounts (if ad-monetized) | OAuth | Seller |
| ☐ | Connect cloud billing | OAuth | Seller |
| ☐ | Upload last 12 mo bank stmts + IAP/Stripe exports | Files | Seller |
| ☐ | Provide install/uninstall data + DAU/MAU + cohort retention | Analytics export | Seller |
| ☐ | Provide ASO performance (keyword rank, CVR) | ASO export | Seller |
| ☐ | Disclose any App Store / Play Store policy strikes | Policy log | Seller |
| ☐ | Disclose code dependencies + open-source licenses | Audit | Seller |
| ☐ | Disclose any pending privacy/data complaints | Disclosure | Seller |
| ☐ | 60-min Operator interview (technical + product) | Recorded | Seller + OP |
| ☐ | Receive Verification Score | Dashboard | OP |

## Stage 3 — Listing Build
| ☐ | Approve listing + pricing band + publish | Live | Seller |

## Stage 5 — Offer & LOI
| ☐ | Receive/respond to offer; e-sign LOI; 21-day exclusivity | Smart contract | Seller |

## Stage 6 — Due Diligence
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Open data room | Buyer access | Seller |
| ☐ | Schedule 90-min technical walkthrough | Calendar | Seller |
| ☐ | Walk codebase, build pipeline, deploy flow | Screenshare | Seller |
| ☐ | Walk App Store Connect + Play Console admin | Screenshare | Seller |
| ☐ | Provide 14-day read-only repo access | GitHub invite | Seller |
| ☐ | Provide TestFlight / Play internal testing access | Tester invite | Seller |
| ☐ | Run buyer's chosen security scan if requested | Scan report | Seller |
| ☐ | 48hr Q&A SLA | Q&A | Seller |

## Stage 7 — Closing & Migration
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | Sign APA | Smart contract | Seller |
| ☐ | **Apple App transfer** — initiate via App Store Connect (must meet Apple's requirements: no IAP changes 90 days prior, etc.) | Transfer initiated | Seller |
| ☐ | **Google Play app transfer** — initiate via Play Console transfer flow | Transfer initiated | Seller |
| ☐ | **Repo ownership transfer** | Repo on buyer's org | Seller |
| ☐ | **Backend infra migration** OR account transfer | Migration confirmed | Seller |
| ☐ | **Database transfer** | Import successful | Seller |
| ☐ | **Push notification provider** ownership change | Provider confirmation | Seller |
| ☐ | **Analytics ownership** transfer | Confirmation | Seller |
| ☐ | **Ad SDK accounts** — buyer creates own accounts; SDK keys swapped at next release | Buyer's accounts ready | Seller |
| ☐ | **Stripe / IAP migration** — IAP cannot be transferred for subs without Apple's process; plan + execute | IAP migrated | Seller |
| ☐ | **Code signing certificates** — buyer regenerates under their dev account | New certs created | Seller |
| ☐ | **First app version under new ownership** uploaded to verify access | Build uploaded | Seller |
| ☐ | Confirm handover 100% | Signed | Seller + OP |

## Stage 8 — Post-close
| ☐ | 60-day transition support — up to 10 hr/week (similar to SaaS) | Time log | Seller |
| ☐ | Earnout typical (12-month, tied to MRR or DAU retention) | Earnout dashboard | Seller |
| ☐ | Available for App Store/Play review responses | Slack | Seller |
| ☐ | Leave buyer review | In-platform | Seller |

---

# 🔵 Buyer Actions

## Stage 1 — Application
| ☐ | Register + ID verify + Proof of Funds; (recommended) hire mobile DD SP | Profile + SP | Buyer |
| ☐ | Have Apple Developer + Google Play developer account ready | Accounts ready | Buyer |

## Stage 4 — Reveal & Save
| ☐ | Filter; reveal; read Verification Score | Score | Buyer |

## Stage 5 — Offer & LOI
| ☐ | Submit offer; e-sign LOI | Smart contract | Buyer |

## Stage 6 — Due Diligence (Mobile-specific)
| ☐ | Action | Evidence | Owner |
|---|---|---|---|
| ☐ | **Code review** — quality, test coverage, signing, build pipeline | Repo review | Buyer (or SP) |
| ☐ | **Privacy review** — App Store / Play privacy labels accuracy | Labels review | Buyer |
| ☐ | **App Store / Play standing** — no policy strikes, no demotions | Policy review | Buyer |
| ☐ | **Install/uninstall trends** | Analytics review | Buyer |
| ☐ | **Cohort retention** — D1/D7/D30 retention curves | Cohort report | Buyer |
| ☐ | **MRR/IAP revenue verification** | Stripe ↔ bank ↔ App Store | Buyer |
| ☐ | **Ad revenue verification** (if applicable) | AdMob ↔ bank | Buyer |
| ☐ | **ASO health** — keyword rankings, CVR, ratings trend | ASO tools (AppFollow, etc.) | Buyer |
| ☐ | **Reviews/ratings** — sample recent reviews; trend | Review export | Buyer |
| ☐ | **Crash rate** — Firebase/Sentry crash analytics | Crash dashboard | Buyer |
| ☐ | **Backend cost vs. revenue** — burn analysis | Cost analysis | Buyer |
| ☐ | **Open-source licenses** | Audit | Buyer |
| ☐ | **GDPR/COPPA compliance** — kids' apps need extra care | Compliance check | Buyer |
| ☐ | Renegotiate or proceed | Updated offer | Buyer |

## Stage 7 — Closing & Migration
| ☐ | Sign APA + fund escrow | Receipt | Buyer |
| ☐ | Accept Apple/Play app transfer in console | Acceptance | Buyer |
| ☐ | Verify app transferred to your account | Console check | Buyer |
| ☐ | Verify repo ownership | git pull | Buyer |
| ☐ | Verify backend deploy works | Smoke test | Buyer |
| ☐ | Verify analytics access | Dashboard | Buyer |
| ☐ | Verify ad SDK swap (next release) | SDK keys updated | Buyer |
| ☐ | Verify IAP / sub continuity | Test transaction | Buyer |
| ☐ | Sign off on inspection (7 days) | Sign-off | Buyer |

## Stage 8 — Post-close
| ☐ | Use seller transition; track earnout; manage App Store/Play relationship | Logged | Buyer |
| ☐ | Leave seller review | In-platform | Buyer |

---

## Mobile-specific gotchas

| Gotcha | Mitigation |
|---|---|
| **Apple's app transfer rules** — no recent rejection, no IAP changes 60d, no version pending review | Confirm eligible at Stage 1 |
| **Google Play transfer waiting period** | Plan timeline accordingly |
| **IAP subscription customers** | Existing subs cannot be transferred between dev accounts; Apple/Google has specific flow; plan disclosure |
| **Push notification provider tied to bundle ID** | Bundle ID stays; just account ownership changes |
| **Ad SDK swap requires app update** | Plan release coinciding with handover |
| **Code signing cert lost** | Buyer must regenerate; old certs invalidated |
| **Sandboxed user data tied to seller's iCloud/Google account** | Disclose if any user data is in seller-owned cloud |
| **App Store screenshots locked to seller's localized account** | Re-upload under buyer's account post-transfer |
| **App-specific passwords / tokens revoke at transfer** | Refresh all keys post-transfer |
| **Kids/health apps** | COPPA/HIPAA compliance pre-close |
| **Game center / Play Games leaderboards tied to bundle** | Survives transfer |

## Operator checks
- App Store / Play standing
- Crash rate baseline
- Revenue reconciliation across IAP + Stripe + ads + bank
- Recent rejection/policy log
- Open issues at >Sev2
