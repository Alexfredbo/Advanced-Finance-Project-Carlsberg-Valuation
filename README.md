# Carlsberg Valuation
### Hybrid capital and the cost of capital in equity valuation

Academic group project for the Advanced Finance seminar at the University of Copenhagen, autumn 2026.

**Valuation date:** 16 September 2026.

[Read the full report](Carlsberg_Valuation_Final.pdf)

## Overview

How much is Carlsberg worth, and how does the treatment of hybrid capital affect that estimate?

We value Carlsberg using a discounted cash flow model and examine how its EUR 1.8 billion hybrid notes affect financial risk, the cost of capital and ordinary equity value. The analysis combines financial statement analysis, empirical beta estimation and alternative capital structure assumptions.

## Methods

- **Financial analysis and forecasting:** Historical financial statements inform forecasts of revenue, margins, investment and working capital.
- **DCF valuation:** Free cash flow to the firm, WACC estimation and an enterprise-to-equity bridge.
- **Empirical risk estimation:** CAPM beta estimation with robustness checks, shrinkage and leverage adjustments.
- **Valuation cross-checks:** Peer EV/EBITDA and P/E multiples, alongside sensitivity analysis of operating assumptions and the cost of capital.

Python is used for estimation, valuation calculations, tables and figures. This repository presents the report only.

## Key findings

- The two hybrid-capital specifications produce estimated values of **DKK 1,175 and DKK 1,265 per share** — a difference of approximately **8%**.
- The difference arises from how hybrid capital enters the leverage adjustment to equity beta. Hybrid claims are deducted from enterprise value in both specifications.
- Uncertainty about beta and the market risk premium can have a larger valuation effect than hybrid classification.
- Peer multiples imply more conservative values than the DCF model, highlighting the importance of comparing valuation approaches.

## Limitations

The estimates depend on operating forecasts, capital structure assumptions and the discount rate. Approximately 79–80% of enterprise value comes from terminal value, making long-run assumptions particularly important. A constant WACC also simplifies a changing capital structure.

These are academic model estimates, not realised investment returns or investment advice.

## Authors

Alexander Gjerum Fredbo-Nielsen and Emil Kjeldgaard Leth.

The report includes a declaration describing the use of generative AI.
