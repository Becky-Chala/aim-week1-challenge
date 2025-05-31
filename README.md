```markdown
# 📈 Week 1: Predicting Price Moves with News Sentiment

This project is part of the 10 Academy Artificial Intelligence Mastery (AIM) challenge. The goal is to analyze financial news data and identify correlations between **news sentiment** and **stock price movements** through Exploratory Data Analysis (EDA), NLP, and quantitative indicators.

---

## 📌 Business Objective

Nova Financial Solutions aims to improve its predictive analytics using real-time news sentiment. This project explores the relationship between financial news headlines and stock performance, providing actionable insights into how public sentiment influences market behavior.

---

## 📂 Project Structure

```

10AIM-Week1/
├── data/
│   └── raw\_data.csv                 # Financial news dataset
├── notebooks/
│   └── eda.ipynb                    # Exploratory Data Analysis notebook
├── scripts/
│   └── helpers.py                   # Reusable functions (optional)
├── src/
│   └── **init**.py                  # Placeholder for modular code
├── tests/
│   └── test\_helpers.py              # Unit tests (optional)
├── .github/
│   └── workflows/unittests.yml     # GitHub Actions CI (optional)
├── .gitignore
├── README.md
├── requirements.txt

````

---

## ✅ Completed Work

- [x] Dataset Loaded and Cleaned
- [x] Headline Length and Frequency Analysis
- [x] Publisher and Stock Symbol Distribution
- [x] Time-Based Article Trends (daily/hourly)
- [x] TF-IDF Keyword Extraction
- [x] Word Cloud for News Topics

---

## 🧠 Tools and Libraries Used

| Category              | Libraries/Tools           |
|----------------------|---------------------------|
| Data Analysis         | pandas, numpy             |
| Visualization         | matplotlib, seaborn       |
| NLP                   | sklearn, nltk, wordcloud  |
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

## 🗂️ Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/your-username/10AIM-week1.git
cd 10AIM-week1
````

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # or .venv\\Scripts\\activate on Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch the notebook:

```bash
jupyter notebook notebooks/eda.ipynb
```

---

## 👥 Contributors

* **Bereket \[Becky]** – Data Analyst & Financial Insight Enthusiast
* 10 Academy AI Mastery Challenge – Week 1 Cohort

---

## 📌 License

This project is for educational purposes under the 10 Academy AIM program.

````

---

## 📄 `requirements.txt`

Make sure this file includes:
```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
wordcloud
nltk
jupyter
````
---

## 💡 GitHub Repo Description (Use This on GitHub)

> "A financial news analytics project exploring how headline sentiment influences stock price movements. Includes EDA, text analysis, and technical indicator planning as part of the 10 Academy AIM challenge."


