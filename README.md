# Bitcoin Price Prediction using Wikipedia Sentiment

## 📌 Overview

Bitcoin prices are strongly influenced by public attention and sentiment.  
Wikipedia, being a publicly edited knowledge source, often reflects these shifts through **edit frequency and editor sentiment**.

This project combines **Bitcoin market data** with **sentiment analysis of Wikipedia revision comments** to predict next-day price movement.


## Highlights

- 18,000+ Wikipedia revisions analyzed  
- Daily aggregation of edit count and sentiment signals  
- Sentiment extracted using a **pre-trained NLP transformer**  
- Rolling time-series feature engineering (2, 7, 60, 365 days)  
- **XGBoost Classifier** trained for price direction prediction  


## Results

- Evaluation Metric: **Precision**
- Final Precision Score: **0.521**

Adding Wikipedia-based sentiment and activity features led to a **measurable improvement over a price-only baseline**, indicating that public attention signals contain **weak but meaningful predictive power** for short-term Bitcoin price movement.


## Tech Stack

- Python  
- Pandas, NumPy  
- HuggingFace Transformers  
- Scikit-learn  
- XGBoost  


## Disclaimer

This project is for educational purposes only and does **not** constitute financial advice.
