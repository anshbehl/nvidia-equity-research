# NVIDIA (NVDA) Equity Research & Valuation

Independent equity research project analyzing NVIDIA's financial performance, competitive position, and valuation using Python.

## Project Overview

This project combines financial statement analysis with Python-based valuation to evaluate NVIDIA's underlying business performance and the assumptions embedded in its current valuation.

The analysis includes:

- Historical revenue, profitability, and free cash flow analysis
- Data Center and business segment analysis
- Five-year discounted cash flow (DCF) valuation
- WACC and terminal growth sensitivity analysis
- Bear, base, and bull valuation scenarios
- Comparable-company analysis
- Investment thesis and key risk analysis

## Valuation Framework

The base-case DCF assumes free cash flow growth gradually normalizes as NVIDIA becomes a larger company.

**Base Case Assumptions**
- Year 1 FCF Growth: 45%
- Year 2 FCF Growth: 32%
- Year 3 FCF Growth: 24%
- Year 4 FCF Growth: 18%
- Year 5 FCF Growth: 14%
- WACC: 10.5%
- Terminal Growth Rate: 4.0%

**Base-Case Implied Value: ~$159 per share**

Scenario analysis is also used to examine how changes in growth, margins, WACC, and terminal growth affect NVIDIA's implied valuation.

## Investment Thesis

NVIDIA remains exceptionally positioned within accelerated computing and AI infrastructure, supported by strong profitability, free cash flow generation, and its competitive position.

However, the analysis suggests that NVIDIA's valuation already incorporates significant expectations for continued AI-driven growth. The primary question is therefore not simply whether NVIDIA is a strong business, but whether future financial performance can justify the expectations reflected in its valuation.

## Tools & Skills

- Python
- pandas
- yfinance
- Financial Statement Analysis
- Discounted Cash Flow (DCF) Valuation
- Comparable Company Analysis
- Sensitivity Analysis
- Equity Research

## Data Sources

Historical financial information was sourced primarily from NVIDIA investor relations and SEC filings. Market data used in the notebook is retrieved through `yfinance`.

Forecasts and valuation assumptions represent independent analyst assumptions for educational purposes and are not investment advice.

## Author

Ansh Behl
