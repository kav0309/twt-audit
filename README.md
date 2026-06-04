# 📊 The Whole Truth Foods — Funnel & Media Mix Audit

> An interactive marketing analytics dashboard built as part of an MBA Marketing portfolio. Simulates a full D2C performance audit for The Whole Truth Foods across Meta, Google, and Influencer channels.

**[🔗 View Live Dashboard →](https://kav0309.github.io/twt-audit/)**

---

## What This Is

A single-page interactive dashboard that answers one question:
**"Where should TWT spend its ₹10L/month marketing budget — and why?"**

Built entirely in vanilla HTML/CSS/JS. No frameworks, no backend, no dependencies beyond Chart.js.

---

## Features

### 📈 Channel Performance Analysis
- ROAS and CAC comparison across Meta (2.1×), Google (3.4×), and Influencer (3.8×)
- 6-month ROAS trend chart showing trajectory per channel
- Budget allocation donut chart at current split (50/20/30)

### 🔽 Conversion Funnel
- Full funnel from 1.8M impressions → 2,800 purchases → 784 repeats
- Drop-off % at every stage with gap-vs-benchmark callouts
- Visual width scaling for instant comprehension

### ⚡ What-If Scenario Cards *(new)*
Six pre-built one-click scenarios — click any card to instantly apply it to the budget simulator:
| Scenario | Description |
|---|---|
| 🚀 Double Influencer | Shift 30% Meta → Influencer |
| ✂️ Cut Meta Entirely | Zero Meta, split 50/50 Google + Influencer |
| 🔍 Google-Heavy Mix | 55% Google, lean into search intent |
| ⚖️ Balanced Reallocation | Recommended memo split (25/35/40) |
| 📘 Status Quo (Meta-Heavy) | Baseline 50/20/30 for comparison |
| 🌟 Influencer + Retargeting | 60% Influencer, Meta for retargeting only |

Each card shows ROAS, CAC, Revenue, and Customers vs. baseline — before you even click.

### 🛠️ Funnel Fix Simulator *(new)*
Two independent sliders to model CRO impact **without changing ad spend**:
- **Reduce Cart Abandonment** — current rate 68.2% vs 55% industry benchmark. Slide to see customers & ₹ recovered
- **Improve Repeat Purchase Rate** — current 28%, slide to simulate retention improvement via email/WhatsApp flows

Live outputs: additional customers, additional revenue, effective CAC drop, total monthly revenue.

### 🎯 Budget Reallocation Simulator
Manual sliders for Meta / Google / Influencer with auto-normalisation to 100%. Updates blended ROAS, CAC, customers, and revenue in real time. Syncs with scenario card selection.

### 📋 Creative Brief Recommendations *(new)*
Per-channel ad format briefs grounded in funnel stage:

| Channel | Funnel Stage | Recommended Format |
|---|---|---|
| **Meta** | Retargeting · Mid/Bottom | Ingredient Carousel + Cart Recovery Video |
| **Google** | Search · Bottom Funnel | Responsive Search Ads + Shopping Listings |
| **Influencer** | Awareness + Trust · Top/Mid | Micro-Influencer Honest Review Reel |

Each brief includes: objective, hook/creative direction, CTA, targeting logic, and success KPIs.

### 📝 Strategy Memo
Structured analyst memo covering the problem statement, funnel gaps, and three concrete reallocation recommendations with rationale.

---

## Key Findings (Simulated Model)

| Metric | Current | Recommended Mix |
|---|---|---|
| Blended ROAS | 2.8× | 3.3× |
| Blended CAC | ₹418 | ₹338 |
| Est. Monthly Revenue | ₹28L | ₹33L |
| Biggest Funnel Leak | 68% cart abandonment | Fix before scaling spend |

---

## Tech Stack

```
HTML5 + CSS3 + Vanilla JS
Chart.js 4.4.1 (via CDN)
Google Fonts — DM Serif Display, DM Mono, Epilogue
No build step. Open index.html and it works.
```

---

## How to Run Locally

```bash
git clone https://github.com/kav0309/twt-audit.git
cd twt-audit
open index.html   # or just double-click it
```

No installs. No servers. Just open the file.

---

## Deploy to GitHub Pages

1. Push `index.html` to the `main` branch of your repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Live at `https://kav0309.github.io/twt-audit/` in ~60 seconds

---

## Project Context

This dashboard was built as part of an MBA Marketing elective portfolio. The data is **simulated** — channel metrics, funnel volumes, and ROAS figures are modelled based on publicly available D2C benchmarks for the Indian market (2024–2026).

TWT (The Whole Truth Foods) is a real brand. All analysis represents a student exercise, not official brand data.

---

## Author

**Kav** · MBA Marketing  
[github.com/kav0309](https://github.com/kav0309)

---

*Built with no-BS design principles. Much like TWT's ingredient lists.*
