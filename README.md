```markdown
# 📈 AIM Week 1 Challenge – News Sentiment & Stock Price Correlation

This project explores the relationship between financial news sentiment and short-term stock market movements. It is divided into three progressive tasks involving data cleaning, sentiment analysis, and correlation evaluation.

---

## 📂 Project Structure

```

aim-week1-challenge/
│
├── data/
│   ├── raw\_analyst\_ratings.csv        
│   ├── AAPL\_historical\_data.csv       
│   ├── ...                              
│
├── notebooks/
│   └── AIM\_Week1\_Challenge.ipynb     
│
├── README.md                           
└── requirements.txt                      

````

---

## ✅ Tasks Overview

### 🔹 Task 1: Exploratory Data Analysis
- Loaded and cleaned the `raw_analyst_ratings.csv` file.
- Extracted relevant fields: `date`, `headline`, and `stock`.
- Explored stock frequency and headline trends over time using visualizations.

### 🔹 Task 2: Sentiment Analysis
- Applied **TextBlob** to compute sentiment polarity for each headline.
- Grouped by stock and date to calculate average daily sentiment.
- Visualized sentiment trends to identify impactful news periods.

### 🔹 Task 3: Sentiment vs. Stock Price Correlation
- Loaded historical stock price data (AAPL, AMZN, TSLA, etc.).
- Computed daily returns from adjusted close prices.
- Merged with sentiment data on date and stock.
- Calculated Pearson correlation coefficients and visualized results.

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/Becky-Chala/aim-week1-challenge.git
cd aim-week1-challenge
````

2. Create a virtual environment (optional but recommended):

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Open the notebook:

```bash
jupyter notebook notebooks/AIM_Week1_Challenge.ipynb
```

2. Run the notebook cells step-by-step.
3. Ensure the stock and sentiment data are in the correct `data/` folder.

---

## 📊 Example Output

* Correlation scores table showing the relationship between news sentiment and stock return per company.
* Visual scatter plots of sentiment vs. return.

---

## 📌 Key Tools Used

* `pandas`, `numpy` – Data manipulation
* `TextBlob` – Sentiment analysis
* `matplotlib`, `seaborn` – Data visualization
* `scipy` – Pearson correlation calculation

---

## 📈 Results

* Weak-to-moderate correlations between sentiment and returns were observed.
* Sentiment appears to be one of several influencing factors in stock performance.
* Recommendation: combine with other indicators for better prediction.

---


## 🙋‍♂️ Author

**Bereket Chala**
GitHub: [@Becky-Chala](https://github.com/Becky-Chala)

---
