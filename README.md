

# 🗞️ Week 1 Project: News Sentiment & Stock Analysis

This project combines **news sentiment analysis** with **stock market trends** to explore how public sentiment reflected in news headlines correlates with market behavior. It is part of a broader financial data science effort.

---

## 📁 Project Structure

```bash
.
├── .vscode/                  # Editor-specific settings
├── .github/workflows/        # GitHub Actions CI setup
│   └── unittests.yml
├── notebooks/                # Jupyter notebooks for EDA and analysis
├── scripts/                  # Standalone Python scripts
├── src/                      # Core source code (modules, utilities)
├── tests/                    # Unit tests for core modules
├── .gitignore                # Git ignored files and folders
├── README.md                 # Project overview and instructions
├── requirements.txt          # List of Python dependencies
```

---

## 🔍 Project Features

* 📊 **Exploratory Data Analysis (EDA)** of news headlines and sentiment over time.
* 🧠 **Sentiment Analysis** using `nltk` (VADER) and `TextBlob`.
* 🧾 **Stock Price Integration** via `yfinance` and `pynance`.
* 📈 **Technical Indicators** with `TA-Lib`.
* ✅ **Unit testing and CI/CD** with GitHub Actions.

---

## 📦 Requirements

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/doffn/week1-news-sentiment-stock.git
   cd news-stock-analysis
   ```

2. Open and run Jupyter notebooks from the `notebooks/` folder for full analysis.

3. To test the core modules:

   ```bash
   pytest
   ```

---

## ✅ Continuous Integration

This project includes a GitHub Actions workflow in `.github/workflows/unittests.yml` that runs unit tests on every push and pull request to the `main` branch.

---

## 📚 Technologies Used

* Python 3.10
* pandas, numpy
* matplotlib, seaborn
* nltk, TextBlob
* yfinance, pynance
* TA-Lib
* GitHub Actions (CI/CD)

---

## 📈 Potential Applications

* Real-time sentiment-driven trading signals
* News-driven volatility analysis
* Market reaction forecasting
* Portfolio strategy evaluation based on sentiment trends

---

