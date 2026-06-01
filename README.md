# Tesla, Inc. — Financial & Strategic Analysis (FY2019–2023)

**Prepared by:** Teiju Yamaya  
**Institution:** University of Warwick  
**Project type:** Independent equity research & financial analysis  
**Data sources:** Tesla 10-K Annual Reports (FY2019–FY2023), SEC EDGAR; Bloomberg/FactSet consensus estimates

---

## Overview

This project is an analyst-style financial and strategic evaluation of Tesla, Inc. covering five fiscal years (2019–2023). It replicates the format and methodology used by equity research analysts and investment banking associates, including income statement analysis, KPI modelling, segment decomposition, geographic breakdown, competitor benchmarking, and data-driven strategic recommendations.

The deliverables are a structured Excel financial model and a 16-slide PowerPoint presentation.

---

## Repository Contents

```
├── Tesla_Financial_Analysis.xlsx       # Excel financial model (5 sheets)
├── Tesla_Financial_Analysis.pptx       # PowerPoint presentation (16 slides)
└── README.md                           # This file
```

---

## Excel Model — Sheet Guide

| Sheet | Contents |
|---|---|
| **Financials** | Full income statement FY2019–2023 — revenue, gross profit, operating income, net income, all margin % calculated via formula |
| **Segment Analysis** | Automotive, Energy Generation & Storage, Services & Other revenue — absolute ($bn) and % of total |
| **Benchmarking** | Tesla vs. BYD, Toyota, Ford, GM — revenue, gross margin, operating margin, net margin, P/E, EV/EBITDA |
| **KPI Dashboard** | All key metrics in one view — cross-sheet linked to Financials tab, updates automatically |
| **Notes & Formulas** | Colour coding key, formula definitions, data sources, model limitations |

### Colour Coding Convention

| Colour | Meaning |
|---|---|
| **Blue text** | Hardcoded input — safe to change for scenario analysis |
| **Black text** | Formula / calculated output — do not overwrite |
| **Green text** | Cross-sheet link pulling from another tab |

### Key Formulas Used

```
Revenue CAGR       = (End Value / Start Value)^(1/n) - 1      [n = 4 years]
Gross Margin %     = Gross Profit / Revenue
Operating Margin % = Operating Income / Revenue
Net Margin %       = Net Income / Revenue
YoY Growth         = (Current Year - Prior Year) / Prior Year
Segment % Total    = Segment Revenue / Total Revenue
```

---

## PowerPoint Deck — Slide Guide

| Slide | Title | Key Content |
|---|---|---|
| 1 | Cover | Title, author, institution |
| 2 | Executive Summary | 5-year performance headline, key findings, recommendations |
| 3 | Company Overview | Founding, segments, manufacturing footprint, mission |
| 4 | Financial Performance Snapshot | Revenue and net income charts, profitability turning point |
| 5 | Income Statement Detail | Gross profit and operating income charts, cost structure analysis |
| 6 | KPI Analysis | CAGR, operating leverage, FCF, capex, deliveries scorecard |
| 7 | KPI Analysis — Margin Performance | 3-line margin chart, 2022 peak and 2023 compression story |
| 8 | Segment Analysis | Revenue by segment line chart, segment % stacked bar |
| 9 | Geographic Analysis | Revenue by region (US/China/Other), Gigafactory geographic strategy |
| 10 | Competitor Benchmarking | Margin comparison and P/E/EV/EBITDA vs. BYD, Toyota, Ford, GM |
| 11 | Strategic Issues | Margin compression, competition, capex, regulatory risk |
| 12 | Recommendation 1 | Software monetisation — FSD, recurring revenue, margin impact |
| 13 | Recommendation 2 | Scale energy storage — Megapack, grid market, diversification |
| 14 | Recommendation 3 | Cost structure optimisation — battery costs, factory utilisation |
| 15 | Conclusion | Verdict, key risks, strategic priorities for 2024–2026 |

---

## Key Findings

**Financial performance**
- Revenue grew from $24.6bn to $96.8bn between FY2019 and FY2023 — a 34% CAGR
- Tesla turned net profitable in FY2020 for the first time in its history
- Gross margin expanded from 16.7% to 25.9% — driven by Gigafactory scale efficiencies
- Operating margin peaked at 16.8% in FY2022 before falling to 9.2% in FY2023 as Tesla cut prices aggressively to defend volume

**Competitive position**
- Tesla's 25.9% gross margin is 7+ percentage points above the nearest peer (Toyota at 18.5%)
- Tesla trades at 45× EV/EBITDA vs. a legacy OEM average of ~7.5× — the premium prices in software, energy, and autonomy optionality
- BYD outsold Tesla in China every quarter of FY2023, representing the most significant competitive threat in the near term

**Strategic outlook**
- FSD software monetisation is the highest-margin growth lever available with minimal additional capex
- Megapack / Energy Storage is the most underappreciated segment — bookings sold out through 2025
- Battery cost reduction from $110/kWh toward $60/kWh is the clearest path back to 30%+ gross margin

---

## Data Sources & Limitations

**Sources**
- Tesla, Inc. Annual Reports (Form 10-K) — FY2019, FY2020, FY2021, FY2022, FY2023 via SEC EDGAR
- Geographic revenue breakdown from Tesla earnings releases and 10-K geographic segment notes
- Competitor benchmarking figures from company annual reports and Bloomberg/FactSet consensus FY2023

**Limitations**
- All figures rounded to one decimal place ($bn)
- China revenue not separately disclosed by Tesla prior to FY2021 — included within "Other" for FY2019–2020
- Competitor benchmark figures are approximate public estimates and should not be used for investment decisions
- This project is for educational purposes only and does not constitute financial advice

---

## Skills Demonstrated

- Financial statement analysis (income statement, margin analysis)
- KPI modelling and CAGR calculation in Excel
- Segment and geographic revenue decomposition
- Competitor benchmarking using public market data
- Valuation multiples (P/E, EV/EBITDA) — interpretation and peer comparison
- Data visualisation — line charts, bar charts, 100% stacked bar charts in Excel
- Analyst-style presentation design in PowerPoint
- Strategic framework application (issues identification, structured recommendations)

---

*This project was completed as part of an independent finance skills development programme at the University of Warwick. All data is publicly available. No proprietary or non-public information was used.*
