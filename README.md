# Market-Sentiment-Task
#  Trader Performance Analysis Based on Bitcoin Market Sentiment

##  Project Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance** using historical trading data from the Hyperliquid platform.  
The goal is to uncover how market psychology influences **profitability, risk-taking behavior, and trading patterns**, and to derive actionable insights for smarter trading strategies.

---

##  Objectives
- Study how different market sentiments affect trader profitability
- Analyze risk behavior through leverage usage
- Identify behavioral patterns during Fear and Greed phases
- Discover hidden insights from top-performing traders
- Provide strategy-oriented recommendations based on sentiment analysis

---

##  Datasets Used

### 1️⃣ Bitcoin Market Sentiment Dataset
- **Columns:**
  - `Date`
  - `Classification` (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
- Represents overall market psychology

### 2️⃣ Historical Trader Data (Hyperliquid)
- **Key Columns:**
  - `account` – Trader identifier
  - `symbol` – Asset traded
  - `execution price`
  - `size`
  - `side` – Buy / Sell
  - `time` – Trade timestamp
  - `closedPnL` – Profit or loss
  - `leverage`

---

##  Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab

---

##  Methodology
1. Loaded and cleaned both datasets
2. Converted date and timestamp columns into datetime format
3. Merged sentiment data with trading data using trade date
4. Performed exploratory data analysis (EDA)
5. Analyzed:
   - Profit & loss by sentiment
   - Win rate by sentiment
   - Leverage usage and risk behavior
   - Buy vs Sell patterns
6. Identified top-performing traders and analyzed their behavior
7. Derived business and strategy insights

---

##  Key Insights
- Traders tend to perform **better during Fear conditions** compared to Greed
- **Leverage usage increases during Greed**, leading to higher losses
- Extreme Greed phases show **higher volatility and downside risk**
- Top traders demonstrate **better leverage control and consistency**
- Market sentiment works best as a **risk management indicator**, not a direct trade signal

---

##  Recommendations
- Reduce leverage exposure during Greed and Extreme Greed phases
- Use sentiment as a position sizing and risk filter
- Avoid emotional overtrading during high-greed market conditions
- Focus on disciplined trading strategies during Fear phases

