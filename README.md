# OverUnder

AI-powered football predictions and live match signals for iOS.

[App Store](https://apps.apple.com/app/id6760006725) · [Landing Page](https://theaeasoftware.github.io/overunder/overunder.html) · [Privacy](https://theaeasoftware.github.io/overunder/privacy.html) · [Terms](https://theaeasoftware.github.io/overunder/terms.html)

---

## About

OverUnder analyzes hundreds of football matches across 19 leagues every day using a hybrid prediction engine: **53 custom rules** combined with **Claude AI** contextual analysis. Only predictions that pass a 70%+ confidence threshold and survive an additional odds-value filter (≥1.30) reach users — with a per-match post-mortem (xG + match events) used to separate genuine rule errors from bad-luck losses.

### Highlights

- **Daily AI predictions** — 15–25 filtered match calls per day, scored and explained
- **Live signals** — real-time in-match notifications when momentum shifts
- **Transparency dashboard** — system win rate, league-by-league stats, weekly trend chart, monthly heatmap calendar
- **Daily streak** — open the app 7 days in a row to unlock a 24-hour upper-tier experience (queues automatically if a Pro/Elite period is already active)
- **Referral system** — share your code; rewards stack with milestone bonuses (5 / 10 / 25 / 50 invites)
- **6 languages** — English, Türkçe, Deutsch, Français, Italiano, Español
- **Ad-free**, dark mode, push notifications, monthly results calendar

### Subscription tiers

| Plan | Period | Includes |
|---|---|---|
| Amateur | Weekly | Daily predictions, push notifications |
| Professional | Monthly | + Live signals, prediction reasoning |
| **Elite** | Yearly | + Confidence levels — *best value* |

A 2-day free trial is available — no credit card required.

### Leagues covered

Premier League · La Liga · Serie A · Bundesliga · Ligue 1 · Süper Lig · Championship · Eredivisie · Primeira Liga · Jupiler Pro League · Super League Greece · Serie B · 2. Bundesliga · La Liga 2 · TFF 1. Lig · Champions League · Europa League · Conference League · plus more.

---

## This repository

Hosts the public legal & marketing pages served via GitHub Pages.

| Page | File |
|---|---|
| Landing | `overunder.html` |
| Index redirect | `index.html` |
| Privacy Policy | `privacy.html` |
| Terms of Use | `terms.html` |
| Feedback / Support | `feedback.html` |

**Live site:** <https://theaeasoftware.github.io/overunder/>

The iOS application source lives in a separate private repository.

---

## Tech stack (iOS app)

- **Swift 5 / SwiftUI / Combine** — MVVM + Repository pattern
- **Firebase** — Realtime Database, Cloud Messaging, Cloud Functions (Node.js 22)
- **StoreKit 2** — subscription management (iOS 17+)
- **API-Football & Understat** — fixture, statistics, xG, lineup data
- **Anthropic Claude** — predictive reasoning, daily report analysis, weekly calibration

---

## Support

- Email: **support@aeasoftware.com**
- In-app: Settings → Feedback

---

© 2026 AEA Software. All rights reserved.
