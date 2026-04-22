# 📊 Trading Behavior vs Market Sentiment Analysis

## 📌 Overview

This project analyzes how trader performance and behavior change based on market sentiment (Fear vs Greed).

---

## ⚙️ Setup

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib
   ```
3. Run the notebook:

   ```bash
   jupyter notebook analysis.ipynb
   ```

---

## 📂 Data

* Fear & Greed Index dataset
* Historical trader data

---

## 🧠 Methodology

* Converted timestamps (including Unix format) to daily dates
* Aggregated trader data (PnL, trade size, frequency)
* Merged with sentiment data
* Created metrics:

  * Daily PnL
  * Win rate
  * Trade frequency
  * Position size
  * Leverage proxy

---

## 📊 Key Insights

1. Trader performance (PnL) differs between Fear and Greed periods
2. Traders adjust trade frequency based on sentiment
3. Larger position sizes are observed during Greed phases

---

## 🎯 Strategy Recommendations

1. During Fear periods, reduce position size and avoid overtrading
2. During Greed periods, increase exposure cautiously with strict risk management

---

## ⚠️ Limitations

* Limited overlapping dates between datasets
* Predictive modeling was not feasible due to small sample size

---

## 📈 Outputs

Charts included:

* PnL comparison
* Trade frequency
* Position size

---

