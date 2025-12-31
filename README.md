# Trader Performance vs Market Sentiment

## Overview
This project analyzes the relationship between **Bitcoin market sentiment** and **trader behavior** using the Fear & Greed Index and historical trading data from Hyperliquid. The goal is to uncover behavioral patterns, evaluate risk-adjusted performance, and derive actionable trading strategies.

The analysis focuses on how sentiment regimes influence position sizing, leverage usage, asset selection, and trade quality.

---

## Project Structure

```
ds_vikash_pandey/
│
├── notebook_1.ipynb # Main analysis notebook
├── csv_files/
│ ├── fear_greed_index.csv
│ └── historical_data.csv
├── outputs/ # Exported charts and visualizations
│ ├── size_vs_pnl_by_sentiment.png
│ ├── daily_pnl_trend_by_sentiment.png
│ ├── strategy_heatmap.png
│ └── correlation_heatmap.png etc...
| 
├── ds_report.pdf # Final summarized insights report
└── README.md
```

---

## Analysis Highlights

- **Behavioral Bias Detection:** Identification of revenge trading and position sizing anomalies.
- **Sentiment Regime Effects:** Clear differences in performance and risk across Fear, Greed, and Neutral markets.
- **Trader Style Clustering:** Four distinct trader archetypes with different risk and performance profiles.
- **Risk-Adjusted Evaluation:** Demonstrates that high absolute PnL does not imply superior trading skill.
- **Asset-Specific Insights:** Certain coins outperform under specific sentiment regimes.
- **Actionable Framework:** A sentiment-aware trading checklist for disciplined execution.

---

## How to Run the Analysis

1. Open `notebook_1.ipynb` using **Jupyter Notebook** or **Google Colab**.
2. Ensure the `csv_files/` directory is in the same root folder.
3. Run the notebook cells sequentially from top to bottom.
4. Generated visual outputs will be saved automatically in the `outputs/` folder.

---

## Key Assumptions

- Leverage is estimated using trade size relative to starting position.
- Sentiment regimes are grouped into Fear, Greed, and Neutral for interpretability.
- Risk-adjusted performance is evaluated using volatility-normalized metrics.

---

## Conclusion

The project demonstrates that **market sentiment is a critical driver of trader behavior and risk outcomes**. Traders who apply disciplined, sentiment-aware strategies and prioritize trade quality over frequency consistently outperform aggressive, emotion-driven approaches.

---

## Author
**Vikash Pandey**
