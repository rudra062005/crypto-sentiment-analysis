# Crypto Market Sentiment vs Trader Performance

## 📌 Objective

Analyze how Bitcoin market sentiment (Fear/Greed) affects trader behavior and profitability using historical trading data.

## 📊 Datasets Used

* Bitcoin Fear & Greed Index
* Hyperliquid Trader Data

## ⚙️ Approach

* Cleaned and preprocessed timestamp data
* Merged trader activity with sentiment data based on date
* Analyzed key metrics:

  * Profitability (PnL)
  * Win rate
  * Trade size (risk behavior)
  * Volatility (risk)

## 🔍 Key Insights

* Highest profits occur during Extreme Greed
* Traders deploy more capital during Fear (contrarian strategy)
* Extreme Fear shows highest volatility (high risk)
* Neutral markets are least profitable

## 📈 Strategy Recommendations

* Use trend-following strategies in Extreme Greed
* Use contrarian strategies during Fear
* Avoid trading in Neutral markets
* Apply strict risk control during Extreme Fear

## 🛠️ Tech Stack

* Python
* Pandas
* Matplotlib
* Seaborn
