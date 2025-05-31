# 📈 Predicting Price Moves with News Sentiment

This project is part of the **10 Academy Artificial Intelligence Mastery (AIM)** challenge – Week 1. The goal is to analyze financial news headlines and identify correlations between news sentiment and stock price movements using Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and quantitative indicators.

---

## 📌 Business Objective

Nova Financial Solutions aims to improve its predictive analytics using real-time news sentiment. This project explores the relationship between financial news headlines and stock performance, providing actionable insights into how public sentiment influences market behavior.

---

## ✅ Completed Work

- ✅ Dataset Loaded and Cleaned
- ✅ Headline Length and Frequency Analysis
- ✅ Publisher and Stock Symbol Distribution
- ✅ Time-Based Article Trends (daily/hourly)
- ✅ TF-IDF Keyword Extraction
- ✅ Word Cloud for News Topics

---

## 📊 Results and Key Insights

- Most headlines are between **60–120 characters**, showing a tendency toward concise financial communication.
- Top publishers include **Reuters**, **Yahoo Finance**, and **Bloomberg**.
- Stocks like **AAPL**, **TSLA**, and **GOOG** dominate the news mentions.
- News publishing peaks around **midday UTC-4**, aligning with market activity.
- TF-IDF analysis reveals keywords like **earnings**, **target**, and **report** are most common.
- The Word Cloud confirms strong focus on earnings, market movements, and price actions.

---

## 🧠 Tools and Libraries Used

| Category              | Libraries/Tools           |
|----------------------|---------------------------|
| Data Analysis         | pandas, numpy             |
| Visualization         | matplotlib, seaborn       |
| NLP                   | scikit-learn, nltk, wordcloud  |
| Time Series (Upcoming)| TA-Lib, PyNance           |
| Project Management    | Git, GitHub, Jupyter      |

---

## 🔮 Next Steps

- Perform sentiment analysis using TextBlob or VADER
- Collect and align stock price data by date
- Calculate technical indicators (MA, RSI, MACD) using TA-Lib
- Correlate average sentiment scores with daily stock returns
- Generate insights for predictive financial modeling

---

## ▶️ Usage Instructions

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/Becky-Chala/aim-week1-challenge.git
cd aim-week1-challenge

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # On Windows: .venv\Scripts\activate

# Install all dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebooks/eda.ipynb
```

Ensure your dataset (`raw_data.csv`) is placed inside the `data/` directory.

---

## 👥 Contributors

- **Bereket [Becky]** – Data Analyst & Financial Insight Enthusiast  
- **10 Academy AIM Challenge – Week 1 Cohort**

---

## 📌 License

This project is for educational purposes under the 10 Academy AIM program.
