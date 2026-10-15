# HAL Stock Price & Behavioural Finance Analysis

### A Quantitative Study of Stock Returns, Trading Volume and Investor Behaviour

This project analyses the stock price movements of **Hindustan Aeronautics Limited (HAL)** using historical market data, daily returns, trading volume and a comparison with the NIFTY 50 index.

The study combines financial data analysis with behavioural finance concepts to examine whether sharp price movements may be associated with company-specific developments, changing investor expectations or potential behavioural biases.

---

## Project Overview

Stock prices are influenced by company fundamentals, market conditions, new information and investor expectations. However, investors may also be influenced by emotions, uncertainty and the behaviour of other market participants.

This project investigates these factors through a case study of HAL, an Indian aerospace and defence company.

The analysis includes:

- Historical closing-price analysis
- Daily stock return calculations
- Identification of the five largest positive and negative daily returns
- Examination of trading volume during large price movements
- Comparison of HAL returns with NIFTY 50 returns
- Analysis of an official HAL announcement concerning the AMCA programme
- Evaluation of possible behavioural and alternative explanations

## Objectives

1. Analyse HAL's daily closing price over the selected period.
2. Calculate daily returns and identify extreme price movements.
3. Examine trading activity during significant price changes.
4. Investigate relevant company announcements.
5. Compare HAL's performance with the broader Indian equity market.
6. Evaluate whether overreaction, underreaction or herding could plausibly explain the observed movements.
7. Distinguish possible behavioural explanations from fundamental and market-related factors.

## Tools and Technologies

- **Microsoft Excel** — data organisation, return calculations, tables and charts
- **NSE historical market data** — stock-price, trading-volume and index information
- **Behavioural Finance** — interpretation of potential investor responses

## Data Sources

### 1. HAL Historical Stock Data

Daily historical data for Hindustan Aeronautics Limited, including closing prices and trading volume.

Source: [NSE India](https://www.nseindia.com/)

### 2. NIFTY 50 Historical Data

Historical index data used to compare HAL's daily returns with broader market movements.

Source: [NSE Historical Index Data](https://www.nseindia.com/reports-indices-historical-index-data)

### 3. Company Announcement

HAL's official clarification concerning media reports about the Advanced Medium Combat Aircraft (AMCA) programme, dated 4 February 2026.

[Read the official HAL announcement](https://nsearchives.nseindia.com/corporate/HAL_04022026161746_Media_Release_04022026.pdf)

## Methodology

### 1. Daily Closing Price

A line chart was prepared to visualise changes in HAL's closing share price over time.

### 2. Daily Returns

Daily returns were calculated using the following formula:

Daily Return (%) = [(Today's Closing Price - Previous Trading Day's Closing Price) / Previous Trading Day's Closing Price] × 100

Positive returns represent price increases, while negative returns represent price decreases.

### 3. Extreme Returns

The five largest positive and five largest negative daily returns were identified to investigate sessions with substantial price movements.

### 4. Trading Volume

Trading volume was examined on selected dates to understand whether large price movements coincided with increased trading activity.

### 5. Market Benchmark Comparison

HAL's daily returns were compared with NIFTY 50 returns over 4–6 February 2026.

This comparison helps assess whether HAL's movements were broadly consistent with the overall market or substantially different.

### 6. Event Analysis

An official HAL announcement concerning the AMCA programme was examined alongside the share-price movements around the announcement date.

The timing of the announcement was considered before evaluating possible market reactions.

## Key Findings

The preliminary comparison for 4–6 February 2026 produced the following results:

| Date | HAL Return | NIFTY 50 Return |
|---|---:|---:|
| 4 February 2026 | -5.67% | +0.19% |
| 5 February 2026 | -4.31% | -0.52% |
| 6 February 2026 | +0.79% | +0.20% |

### Observations

- On 4 February, HAL declined substantially while NIFTY 50 recorded a small positive return.
- On 5 February, HAL's decline was considerably larger than the decline in NIFTY 50.
- On 6 February, HAL recovered more strongly than the broader index.
- These differences suggest that general market movements alone may not explain HAL's price behaviour during this short period.
- Company-specific information, investor expectations, trading activity and other factors may also have contributed.

These observations are descriptive and do not establish the cause of the price movements.

## Behavioural Finance Interpretation

The observed price movements provide an opportunity to evaluate several behavioural finance concepts.

### Overreaction

Investors may respond too strongly to uncertain or negative information, potentially causing a price movement larger than would be justified by subsequent developments.

### Herding Behaviour

Investors may follow the buying or selling decisions of other market participants rather than independently evaluating information.

### Underreaction

Prices may adjust gradually when investors incorporate new information into their expectations over time.

These are possible explanations, not proven conclusions. Price and volume data alone cannot establish that any particular behavioural bias caused the observed movements.

## Alternative Explanations

The analysis also considers explanations beyond behavioural biases:

- Changes in expectations about future revenue, production or programme participation
- Company-specific announcements and developments
- Profit-taking after earlier price increases
- Institutional trading and portfolio adjustments
- Defence-sector developments
- Broader market conditions and liquidity

Considering these alternatives helps avoid attributing every large price movement to investor psychology.

## Limitations

- The comparison with NIFTY 50 covers only three trading sessions.
- Price and volume data do not directly reveal investor motivations.
- Other company announcements or sector developments may have influenced the share price.
- The timing of announcements must be considered before making causal claims.
- The extreme-return table requires date validation against the original exchange data.

The date listed as 1 February 2026 in the preliminary extreme-return table must be verified because it was a Sunday.

## Project Structure

```text
HAL-Stock-Price-and-Behavioural-Finance-Analysis/
│
├── README.md
├── HAL historical data.csv
├── NIFTY 50 historical data.csv
├── Analysis workbook.xlsx
├── charts/
└── report/
