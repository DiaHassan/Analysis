Portfolio Analysis and Stock Selection Strategies

This repository contains three Python projects each project leverages financial APIs, pandas, and data visualization to analyze and pick stocks based on different methodologies.

---

## **Projects Overview**

### 1. **Equal-Weight Portfolio Construction**
- **Objective**: Build an equal-weight portfolio for the S&P 500.
- **Details**:
  - Retrieved stock data for all S&P 500 companies using a financial API.
  - Created a pandas DataFrame and calculated the number of shares required to build a balanced investment portfolio based on equal weight allocation.
  - Useful for passive investors looking to replicate the S&P 500 index with equal exposure.
  - Exporting into Excel

---

### 2. **Momentum Investing Strategy**
- **Objective**: Identify stocks with strong momentum based on historical returns.
- **Details**:
  - Utilized **1-month, 3-month, 6-month, and 12-month percentiles** to evaluate and rank stocks by momentum.
  - Calculated percentile scores for each time frame to provide a composite momentum score.
  - Aimed at helping investors focus on stocks with the highest momentum trends, instead of just relying on yearly performance.

---

### 3. **Relative Value (RV) Scoring**
- **Objective**: Evaluate and rank stocks based on their relative valuation.
- **Details**:
  - Calculated an **RV Score** for S&P 500 stocks using five key valuation metrics:
    - **P/E Ratio** (Price-to-Earnings)
    - **P/B Ratio** (Price-to-Book)
    - **P/S Ratio** (Price-to-Sales)
    - **EV/EBITDA** (Enterprise Value to EBITDA)
    - **EV/GP** (Enterprise Value to Gross Profit)
  - Normalized metrics into percentile scores and created a composite RV Score for easy comparison.
  - Designed to identify undervalued stocks relative to their peers.


