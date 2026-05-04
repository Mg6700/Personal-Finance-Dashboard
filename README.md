# Personal Finance Analytics: Spending & Savings Optimization

**Tools:** Power BI, Excel, DAX  
**Domain:** Personal Finance | Behavioral Analytics | Savings Optimization  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes personal financial data across 4 years (2018–2021) to answer one core question: *Am I spending and saving according to what I earn?* The dashboard tracks income sources, expense categories, and savings instruments to surface behavioral patterns and deliver actionable optimization recommendations.

---

## Dashboard Preview

<img width="1441" height="796" alt="image" src="https://github.com/user-attachments/assets/a0e29afd-e187-4da9-ba99-1e4276744474" />

---

## Dataset

| Field | Description |
|---|---|
| Period | Jan 2018 – Jan 2021 (monthly granularity) |
| Income Sources | Salary + Source 2 (secondary income) |
| Expense Categories | House Rent, Groceries & Food, EMIs, Health, Leisure, Shopping |
| Savings Instruments | Mutual Funds, Emergency Fund, Fixed Deposit, Liquid Cash |

**Scale:** ₹1.51M total income | ₹3.02M total transactions tracked | 4 years of monthly data

---

## Key Metrics (All-Time)

| Metric | Value |
|---|---|
| Total Income | ₹1,507,500 |
| Expense % | 78% |
| Savings % | 22% |
| Net Worth Generated | ₹3,25,500 |
| Total Expenses | ₹11,82,000 |
| Total Savings | ₹3,25,500 |

---

## Dashboard Features

- **Year filter** (2018–2021) and **Month filter** (Jan–Dec) for time-period analysis
- **Income vs Expense vs Savings % trend chart** — monthly MoM comparison across all 4 years
- **Savings Target line** — tracks whether savings rate meets the 25–30% ideal benchmark
- **Where do I spend?** — horizontal bar chart showing expense category breakdown
- **Where do I save?** — horizontal bar chart showing savings instrument breakdown
- **Detailed Statement table** — year-wise breakdown of every income, savings, and expense line item

---

## Detailed Financials

### Income Breakdown
| Year | Salary | Source 2 | Total |
|---|---|---|---|
| 2018 | ₹3,80,000 | ₹12,000 | ₹3,92,000 |
| 2019 | ₹4,20,000 | ₹45,000 | ₹4,65,000 |
| 2020 | ₹5,33,000 | ₹60,000 | ₹5,93,000 |
| 2021 | ₹51,500 | ₹6,000 | ₹57,500 |
| **Total** | **₹13,84,500** | **₹1,23,000** | **₹15,07,500** |

### Expense Breakdown
| Category | % of Total Spend | All-Time Amount |
|---|---|---|
| House Rent | 40.44% | ₹4,78,000 |
| Groceries & Food | 24.20% | ₹2,86,000 |
| EMIs | 21.40% | ₹2,53,000 |
| Health | 6.18% | ₹73,000 |
| Leisure | 4.10% | ₹48,500 |
| Shopping | 3.68% | ₹43,500 |

### Savings Breakdown
| Instrument | % of Total Savings | All-Time Amount |
|---|---|---|
| Mutual Funds | 71.58% | ₹2,33,000 |
| Emergency Fund | 14.44% | ₹47,000 |
| Fixed Deposit | 13.67% | ₹44,500 |
| Liquid Cash | 0.31% | ₹1,000 |

---

## Key Findings

**1. Expense rate (78%) consistently exceeds the ideal savings threshold**
The savings rate hovers at 22% — below the recommended 25–30% benchmark. The trend chart shows savings rate never sustainably crosses the target line across the 4-year period.

**2. House Rent dominates expenses at 40.44%**
Rent is a fixed, non-negotiable cost consuming nearly half of all spending. This single category caps the maximum achievable savings rate, making it the primary constraint on financial flexibility.

**3. Groceries + EMIs together account for ~45% of expenses**
These two categories combined represent essential, largely unavoidable spending — leaving very limited discretionary room for optimization.

**4. 71% of savings concentrated in Mutual Funds**
While Mutual Funds are a reasonable investment vehicle, 71% concentration indicates low diversification. Emergency Fund (14.44%) and Fixed Deposits (13.67%) together represent only ~28% of savings — below recommended levels for liquidity cushion.

**5. 2020 shows a significant savings dip**
Expenses spiked to ₹4,94,000 in 2020 (vs ₹3,56,000 in 2019) while income grew to ₹5,93,000 — the expense growth rate outpaced income growth, causing savings to drop from ₹1,09,000 to ₹99,000.

**6. Income growth is unstable**
Salary grew from ₹3.8L (2018) to ₹5.33L (2020) — a 40% increase over 2 years — but the savings rate barely improved, indicating lifestyle inflation absorbed most of the income gains.

---

## Recommendations

| Recommendation | Rationale |
|---|---|
| Target savings rate of 28–30% | Current 22% leaves insufficient buffer for emergencies and wealth building |
| Reduce Mutual Fund concentration to 50–55% | Diversify into FD and liquid instruments for better risk balance |
| Track EMI-to-income ratio monthly | EMIs at 21.4% of expenses is high — monitor to prevent further growth |
| Set a monthly Leisure + Shopping cap | Combined 7.78% — small absolute but controllable discretionary category |
| Build Emergency Fund to 6 months of expenses | Current ₹47,000 is insufficient relative to monthly expense run rate |

---

## Technical Highlights

- Built fully interactive Power BI report with year and month slicers
- Used DAX measures for dynamic savings rate, expense %, and MoM change calculations
- Designed savings target benchmark line using a constant DAX measure
- Combined line and bar charts for multi-metric trend visualization
- Detailed Statement matrix built using Power BI table visual with conditional formatting

---

## How to Use

1. Clone or download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Use the **Year** and **Month** slicers to filter to specific time periods
4. The trend chart updates dynamically — compare savings rate against the target line
5. Drill into the Detailed Statement table for exact rupee-level breakdowns

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
