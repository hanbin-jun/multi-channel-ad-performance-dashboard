# multi-channel-ad-performance-dashboard

---

## Objectives

- Consolidate and clean raw advertising data from three different platforms
- Calculate key performance indicators (KPIs): CTR, CPC, CVR, CPA, ROAS
- Build a Tableau dashboard to visualize performance by channel, campaign, and creative asset
- Identify underperforming segments and recommend budget reallocation

---

## KPIs Defined

| KPI  | Formula |
|------|---------|
| **CTR (%)** | `(Clicks / Impressions) * 100` |
| **CPC** | `Spend / Clicks` |
| **CVR (%)** | `(Conversions / Clicks) * 100` |
| **CPA** | `Spend / Conversions` |
| **ROAS** | `Revenue / Spend` |

---

## Dashboard Preview

> ![Dashboard Preview](dashboard/screenshots/tableau_dashboard_main.png)

---

## Key Insights

- **Google Ads** had the highest ROAS but also a relatively high CPA
- **Meta Ads** showed high CTR but low conversion performance
- One campaign on the Naver-like platform (Kakao) had high impressions but minimal conversions → Budget reallocation recommended

---

## Tools Used

- **Excel**: KPI Calculation, data transformation
- **Tableau**: Interactive dashboard & data visualization
- *(Optional: Python for automated data prep)*
