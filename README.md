#  Corporate Financial Due Diligence & Valuation

> A comprehensive financial analysis project covering corporate governance, IPO evaluation, capital structure, and intrinsic valuation of a listed Indian firm — built using real annual report data and publicly available market information.

---

## Overview

This project performs a **full-stack corporate financial analysis** of a listed Indian company across two fiscal years (FY24 & FY25). It covers four dimensions of analysis: **corporate governance**, **IPO performance**, **financial management**, and **intrinsic valuation** — mirroring the kind of due diligence conducted in investment banking, consulting, and equity research roles.

Built as part of the Financial Management course (**ECON/FIN F315**) at **BITS Pilani, Pilani Campus**.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | All financial modeling, ratio analysis, and valuation |
| Annual Reports (FY24/FY25) | Primary data source |
| NSE / BSE / Screener.in | Market data, IPO data, shareholding patterns |
| Moneycontrol / Trendlyne | Supplementary financial data |

---

## Project Structure

```
finman-due-diligence/
│
├── data/
│   ├── annual_report_fy24.pdf       # Source annual report
│   └── annual_report_fy25.pdf       # Source annual report
│
├── FinmanProject.xlsx               # Master Excel file with all analysis sheets
│   ├── Sheet 1 — Contributors
│   ├── Sheet 2 — Corporate Governance
│   ├── Sheet 3 — IPO Analysis
│   ├── Sheet 4 — CapEx & Working Capital
│   ├── Sheet 5 — Capital Structure
│   └── Sheet 6 — Cost of Capital & Valuation
│
└── README.md
```

---

## Methodology

### Part I — Corporate Governance

Analyzed the governance structure of the firm as reported in its latest annual report:

- **Board composition**: Size, executive vs non-executive split, independent director count
- **CEO Duality**: Whether Chairman and CEO roles are held by the same person and its implications
- **Gender diversity** on the Board of Directors
- **Director profiles**: Age, qualifications, experience of key executive and non-executive directors
- **Auditor assessment**: Credibility, tenure, and commentary on accounting reliability
- **Legal exposure**: Material lawsuits filed against the firm
- **Information asymmetry**: Assessment of potential agency conflicts between board and management

---

### Part II — IPO Analysis

| Metric | Details |
|---|---|
| IPO Date | 15th October 2019 |
| Issue Price | ₹ 60 |
| Listing Price | ₹ 60.35 |
| First-Day Return | 0.5833% (IPO Underpricing) |
| Lead Underwriter | Aryaman Financial Services Ltd. |
| % Oversubscription | 12% |
| Amount Mobilized | ₹ 60 Cr |
| New Issue vs OFS | 30 % New Issue / 70 % OFS |

*(See `FinmanProject.xlsx` Sheet 3 for full data)*

Key questions addressed:
- Did the IPO provide exit routes for PE/VC/Angel investors?
- How was the IPO proceeds utilized?
- Did oversubscription and underpricing positively impact long-term price performance?
- Post-IPO financing: private equity, peer-to-peer lending, institutional financing?

---

### Part III — Financial Management

#### i. Capital Expenditure Analysis
- Identified major investments relative to firm size across FY24 and FY25
- Classified CapEx as: expansion, diversification, replacement, R&D, or intangible assets
- Analyzed growth in total assets, revenues, exports, and key partnerships/JVs

#### ii. Working Capital Trend Analysis
- Tracked working capital components across quarters
- Identified major current assets and liabilities driving working capital requirements
- Assessed how the firm finances its working capital needs

#### iii. Capital Structure Analysis
- Mapped sources of funding over the sample period using quarterly data
- Evaluated alignment between CapEx requirements and funding choices
- Assessed sufficiency of operating cash flows to fund CapEx and obligations

#### iv. Cost of Capital & Intrinsic Valuation

**CAPM Approach:**
```
Ke = Rf + β × (Rm - Rf)

where:
  Rf  = Risk-free rate (10-yr G-Sec yield)
  β   = Levered Beta (from market regression)
  Rm  = Market return (Nifty 500 historical)
```

**WACC:**
```
WACC = Ke × (E/V) + Kd × (1 - Tax Rate) × (D/V)
```

**DCF Valuation:**
- Projected free cash flows based on firm's growth stage
- Applied multi-stage growth model where appropriate (high growth + terminal)
- Compared intrinsic value estimate to current market price

| Metric | Value |
|---|---|
| Risk-Free Rate | 6.9 % |
| Beta | 0.6 |
| Cost of Equity (CAPM) | 15.62% |
| WACC | 10.86847% |
| Intrinsic Value (DCF) | ₹ 3.06 |
| Current Market Price | ~ ₹ 7-9 |

*(Full workings in `FinmanProject.xlsx` Sheet 6)*

---

## 🚀 How to Use

1. Clone or download the repository
2. Open `FinmanProject.xlsx` in Microsoft Excel
3. Navigate through sheets in order — each sheet references the previous
4. All formulas and workings are preserved and visible

---

## 📚 References

- Vishwaraj Sugar Industries Ltd. Annual Reports FY24 & FY25 (via BSE/NSE filings)
- Brealey, Myers & Allen — *Principles of Corporate Finance*
- Damodaran, A. — *Investment Valuation*
- NSE India — [nseindia.com](https://www.nseindia.com)
- BSE India — [bseindia.com](https://www.bseindia.com)
- Screener.in — [screener.in](https://www.screener.in)

---

## 👤 Author

**Shivam Singla**
B.E. Computer Science Engineering, BITS Pilani (2027)
📧 F20230576@pilani.bits-pilani.ac.in
🔗 [LinkedIn](https://www.linkedin.com/in/shivam-singla-043ab53a8/) · [GitHub](https://github.com/shivam-bppc)

---

> *Built for academic purposes as part of ECON/FIN F315 coursework at BITS Pilani. Not financial advice.*
