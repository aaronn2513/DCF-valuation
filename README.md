# 📊 Telstra Group Ltd DCF Valuation

This project contains a discounted cash flow (DCF) valuation model for **Telstra Group Limited (ASX: TLS)**, built in Excel. It estimates the intrinsic share price based on financial assumptions and provides a recommendation based on the comparison to the current market price.

## 🔍 Summary

- **Intrinsic Share Price:** $2.67  
- **Market Price at Valuation Date:** $4.54  
- **Overvaluation Estimate:** ~41%  
- **NPV per Share:** -$1.87  
- **Recommendation:** Sell

## 📁 Files

- `DCF_Valuation.xlsx`: The Excel workbook containing financial data, assumptions, FCFF projections, and valuation calculations.

## 🧮 Key Assumptions and Methodology

- **WACC:** 7.23%  
- **Long-Term Growth Rate:** 2.00%  
- **Dividend Payout Ratio:** 76.27%  
- **Projection Period:** 5 years  
- **Valuation Approach:** Free Cash Flow to Firm (FCFF)

### 📘 Data Sources & Calculation Basis

All financial inputs and assumptions were derived from **Telstra’s past financial statements**, including:

- Balance sheets
- Income statements
- Cash flow statements

These were sourced from:
- Telstra’s Annual Reports (available on the [Telstra Investor Centre](https://www.telstra.com.au/investor))
- Yahoo Finance and other public financial databases

Key metrics like **EBIT**, **NOWC**, **depreciation and amortisation**, **CapEx**, and **net long-term assets** were calculated using multi-year averages and trend analysis from past 5 years of reported data.

WACC was estimated based on:
- Cost of equity via CAPM
- Telstra’s capital structure (debt/equity mix)
- Market risk premium assumptions

Growth assumptions were based on Telstra’s historical performance and industry outlook.


## 📊 Sensitivity Analysis

A two-dimensional sensitivity analysis was conducted to evaluate how changes in **WACC** and **growth rate** impact the intrinsic value. Results show that under nearly all realistic input combinations, the DCF valuation remains below the current market price.


## Disclaimer

This model was developed as part of an academic project to explore intrinsic valuation using financial modeling in Excel. It is not investment advice.
