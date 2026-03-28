# 📊 Trader Performance vs Market Sentiment Analysis

## 🎯 Objective
The objective of this project is to analyze how market sentiment (Fear vs Greed) impacts trader behavior and performance using Hyperliquid trading data.

---

## 📂 Dataset
- Bitcoin Market Sentiment (Fear/Greed Index)
- Historical Trader Data (Hyperliquid)

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handled missing values and duplicates
- Converted timestamps to datetime format
- Aligned both datasets on daily level

### 2. Feature Engineering
- Daily PnL per trader
- Win rate (profit vs loss trades)
- Trade frequency
- Position size (used as proxy for risk)
- Long/Short ratio

### 3. Analysis
- Compared performance across Fear vs Greed
- Studied behavioral changes in trading patterns
- Segmented traders into:
  - High vs Low risk
  - Frequent vs Infrequent
  - Winners vs Losers

---

## 📊 Key Insights

- Trader performance varies with market sentiment, with lower profitability observed during Fear periods.
- Traders take larger positions during Greed, indicating increased risk appetite.
- Trade frequency increases during Greed, suggesting overtrading behavior.
- High-risk traders experience higher volatility, especially during Fear periods.

---

## 💡 Strategy Recommendations

### 1. Risk Reduction During Fear
- Reduce position sizes
- Avoid aggressive trades
- Focus on high-confidence setups

### 2. Control Overtrading During Greed
- Limit number of trades per day
- Avoid impulsive decisions
- Maintain discipline in execution

### 3. Adaptive Risk Strategy
- Adjust position size based on sentiment
- High-risk traders should dynamically manage exposure

---

## ⚠️ Note
Leverage data was not available in the dataset. Therefore, **position size (USD)** was used as a proxy for trader risk.

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Run the notebook:
   jupyter notebook analysis.ipynb

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Conclusion
Market sentiment significantly influences trader behavior and performance. By adapting trading strategies based on sentiment, traders can improve consistency and manage risk more effectively.