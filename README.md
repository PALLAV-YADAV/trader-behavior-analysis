# Trader Behavior vs Market Sentiment Analysis

## 📌 Objective
Analyze the relationship between Bitcoin market sentiment (Fear & Greed Index)
and trader performance using historical trading data from Hyperliquid.

The goal is to uncover behavioral patterns and insights that can help design
smarter trading strategies in crypto markets.

---

## 📂 Datasets
- **Fear & Greed Index**
  - Daily market sentiment classification and score (0–100)
- **Hyperliquid Historical Trader Data**
  - Execution-level trade data including PnL, size, fees, and timestamps

---

## 🧠 Methodology
1. Cleaned and standardized both datasets
2. Aligned trades with daily market sentiment using trade date
3. Analyzed performance metrics (PnL, win rate, volatility) across sentiment regimes
4. Studied risk behavior and loss patterns
5. Identified behavioral differences between top and bottom traders

---

## 📊 Key Insights
- Trader profitability varies significantly across sentiment regimes
- Extreme Fear and Extreme Greed are associated with higher PnL volatility
- Aggressive risk-taking during Greed does not guarantee higher win rates
- Consistently profitable traders exhibit disciplined risk management and
  avoid emotionally driven market phases

---

## 📁 Project Structure

trader-behavior-analysis/

├── dataset/

├── notebooks/

├── outputs/

│ ├── charts/

│ └── summary_tables/


---

## ▶️ How to Run
```bash
pip install -r requirements.txt

Open notebooks in order:

01_data_loading_cleaning.ipynb

02_exploratory_analysis.ipynb

03_insights_and_conclusions.ipynb

🛠️ Tools Used
Python

Pandas

Matplotlib

Seaborn

👤 Author
Pallav
