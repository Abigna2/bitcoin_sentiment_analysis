# bitcoin_sentiment_analysis
Given objective: To explore the relationship between trader performance and market 
sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading 
strategies.


This project analyzes the relationship between **Bitcoin market sentiment** and **trader performance metrics** such as **profit/loss, leverage, and trading side (buy/sell)**.

---

## 🧠 Objective

Explore patterns in trader behavior and outcomes based on market sentiment. Specifically, examine:
- 💰 How sentiment affects **profit or loss**
- 📈 Whether sentiment influences **buy/sell direction**
- 🔗 The **correlation** between sentiment strength and trading performance

---

## 📁 Datasets Used

1. **Sentiment Data**: Daily Bitcoin sentiment scores and classification (`positive`, `neutral`, `negative`)
2. **Trader Data**: Historical trades with timestamp, direction, position, and profit/loss info

---

## 🛠️ Steps Performed

1. **Cleaned and parsed timestamps** in both datasets
2. **Filtered** both datasets between `March 2025` and `June 2025`
3. **Merged** them on the `date` column
4. Conducted key analyses:
   - Average profit/loss by sentiment
   - Buy/Sell distribution by sentiment
   - Correlation between sentiment score and PnL

---

## 📊 Key Findings

- ✅ **Profit/Loss Analysis**:
  - Positive sentiment → higher average profit
  - Negative sentiment → average loss

- ✅ **Buy/Sell Behavior**:
  - Balanced buy/sell decisions across sentiment types

- ✅ **Strong Correlation**:
  - Pearson correlation between sentiment score and PnL: **0.99**

---

## 📌 Conclusion

Market sentiment has a strong influence on trading profitability, although not necessarily on direction. This insight can help in developing sentiment-aware trading strategies.

---

## 🧾 How to Run

1. Open `bitcoin_sentiment.ipynb` in Jupyter Notebook
2. Run cells step by step
3. Requires `pandas`, `matplotlib`, and `seaborn`



Abigna Katakam  
*Artificial Intelligence & Data Science Undergraduate*

