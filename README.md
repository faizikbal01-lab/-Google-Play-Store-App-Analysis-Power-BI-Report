# -Google-Play-Store-App-Analysis-Power-BI-Report

An interactive styled in the Power BI aesthetic, visualizing key market insights from the Google Play Store dataset. Built as an EDA assessment project covering **10,841 apps across 33 categories** — with 8 charts, a live top-apps leaderboard, and embedded category filter controls.

> **No Power BI license needed** — runs entirely in the browser as a self-contained HTML file.

---

##  Dashboard KPIs

| Metric | Value |
|---|---|
| Total Apps Analyzed | **10,841** |
| Unique Categories | **33** |
| Average App Rating | **4.17 / 5.0** |
| Free Apps Share | **92.1%** |
| Paid Apps Share | **7.9%** |
| Avg Reviews — Free Apps | **444K** |
| Avg Reviews — Paid Apps | **28K** |
| Peak Update Year | **2018** |

---

##  File Structure

```
Google_Play_Store_App_Analysis___Power_BI_Report
│
└── Single self-contained HTML file
    ├── Dark-theme dashboard UI (CSS)
    ├── Sticky header + filter bar (All / Free / Paid / 4★+)
    ├── 5 KPI metric cards
    ├── 8 interactive Chart.js visualizations
    ├── Top 10 Apps leaderboard table
    └── 3 insight callout cards
```

---

##  Charts & Visuals Included

| # | Chart | Question Tag | Key Insight |
|---|---|---|---|
| 1 | Average Rating by Category (Top 12) | MEDIUM Q2 | Events (4.44) & Education (4.39) lead |
| 2 | Free vs Paid Apps — Donut | BASIC Q4 | 92.1% free dominance |
| 3 | Top 10 Categories by Total Installs | MEDIUM Q10 | GAME (35.2B) & COMMUNICATION (28.7B) top |
| 4 | Content Rating Distribution — Donut | BASIC Q5 | 81.8% target "Everyone" |
| 5 | App Size Distribution — Histogram | BASIC Q3 | 20–50 MB is the most common range |
| 6 | App Update Trend (2010–2018) — Line | ADVANCED Q2 | Rapid growth from 45 → 3,200 updates |
| 7 | Rating Distribution — Bar | BASIC Q7 | Strong clustering in 4.0–4.5 range |
| 8 | Avg Rating by Install Volume Bins — Line | ADVANCED Q3 | More installs → marginally higher ratings (3.82 → 4.28) |

###  Top 10 Apps Leaderboard

| App | Category | Rating | Installs | Reviews |
|---|---|---|---|---|
| Clash of Clans | GAME | 4.6 | 100M+ | 44.9M |
| Instagram | SOCIAL | 4.5 | 1B+ | 66.6M |
| Google Photos | PHOTOGRAPHY | 4.5 | 1B+ | 9.5M |
| WhatsApp Messenger | COMMUNICATION | 4.4 | 1B+ | 69.1M |
| Google Maps | MAPS | 4.3 | 1B+ | 15.5M |
| YouTube | VIDEO | 4.3 | 1B+ | 32.3M |
| Gmail | COMMUNICATION | 4.3 | 1B+ | 14.7M |
| Facebook | SOCIAL | 4.1 | 1B+ | 78.2M |
| Google Play Games | GAME | 4.1 | 1B+ | 24.5M |
| Google Play Books | BOOKS | 3.9 | 1B+ | 9.8M |

---

##  Tech Stack

| Tool | Purpose |
|---|---|
| HTML5 + CSS3 | Dashboard layout & dark theme |
| Chart.js 4.4.1 | All 8 interactive charts |
| Google Fonts (Sora + JetBrains Mono) | Typography |
| Vanilla JavaScript | Filter logic & dynamic table rendering |

> No backend, no frameworks, no build step — opens directly in any modern browser.

---

##  Key Insights

**Free apps dominate engagement** — Free apps receive approximately **15× more reviews** than paid apps (444K vs 28K average), confirming that lower barrier to entry drives far higher user interaction and feedback volume.

**GAME & COMMUNICATION lead installs by a wide margin** — GAME category apps account for 35.2 billion installs and COMMUNICATION 28.7 billion — more than double the next category. Apps targeting these verticals should prioritize virality, social features, and performance optimization.

**App size sweet spot is 10–50 MB** — The most popular apps cluster in the 20–50 MB range. Apps exceeding 100 MB show reduced install rates, pointing to a size-performance trade-off that developers should actively optimize.

**Ratings cluster in the 4.0–4.5 band** — The distribution is left-skewed with the vast majority of apps rated between 4.0 and 4.5, meaning the real competition for visibility happens within a narrow quality band.

**More installs correlate with better ratings** — Average ratings rise steadily from 3.82 for apps with fewer than 1K installs to 4.28 for apps with over 100M installs, suggesting that scale and quality reinforce each other over time.

**Events & Education top the rating charts** — Despite lower install volumes, these categories have the highest average ratings (4.44 and 4.39), indicating deeply satisfied niche audiences with strong monetization potential.

---

##  Recommendations

1. **Launch free, then monetize via in-app purchases** — The 15× review gap between free and paid apps makes free launch the only viable strategy for building organic ranking and social proof quickly.

2. **Target GAME or COMMUNICATION for maximum reach** — These two categories collectively account for over 63 billion installs. Adjacent apps (casual games, utility tools with messaging) can directly tap into existing high-intent audiences.

3. **Keep app size under 50 MB** — The histogram clearly shows size friction beyond 50 MB. Use on-demand asset delivery, modular features, or progressive loading to stay within the install sweet spot.

4. **Aim for a 4.2+ rating as your baseline target** — With most apps clustering between 4.0–4.5, breaking above 4.2 is the minimum threshold to differentiate. Fast response to 1-star reviews and prompt bug fixes are the most reliable levers.

5. **Schedule major updates in January and Q3 (July)** — The update trend shows consistent seasonality around these windows. Aligning feature releases with peak update periods maximises visibility and search ranking freshness.

6. **Consider Events or Education for premium/subscription pricing** — High satisfaction ratings in niche categories signal engaged, loyal audiences who are more willing to pay. These verticals are under-monetised relative to their satisfaction levels.

7. **Design for the "Everyone" content rating from the start** — With 81.8% of apps targeting all ages, keeping your content universally accessible removes algorithmic filters and maximises your addressable audience with no added development cost.

8. **Invest in early user acquisition to seed ratings** — The install-vs-rating line chart shows a clear upward trend. Even modest paid acquisition in the early stages can create a rating flywheel effect that compounds organically.

---


## Author

**Mohd Faiz**
- **Role:** Business and Data Analyst
- **GitHub:** [https://github.com/faizikbal01-lab](https://github.com/your-username)

