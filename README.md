# Predicting Price Moves with News Sentiment

**KAIM Week 1 Project**
*Analyzing financial news to understand the relationship between news sentiment and stock price movements.*

---

## Table of Contents

* [Overview](#overview)
* [Business Objective](#business-objective)
* [Dataset](#dataset)
* [Project Tasks](#project-tasks)
* [Key Techniques](#key-techniques)
* [Project Structure](#project-structure)
* [Installation & Setup](#installation--setup)
* [Usage](#usage)
* [References](#references)
* [Team](#team)

---

## Overview

This project dives into real-world financial news to uncover how headlines influence stock price movements. By combining sentiment analysis, technical indicators, and time series data, we aim to predict short-term stock performance and provide actionable investment insights.

The challenge is designed to strengthen skills in:

* **Data Engineering (DE)**
* **Financial Analytics (FA)**
* **Machine Learning Engineering (MLE)**

---

## Business Objective

Nova Financial Solutions seeks to enhance predictive analytics for improved financial forecasting and operational efficiency.

As part of this project, the goals are:

1. **Sentiment Analysis** – Quantify sentiment from financial news headlines and link them to respective stock symbols.
2. **Correlation Analysis** – Analyze the statistical correlation between news sentiment and stock price movements.
3. **Investment Insights** – Recommend strategies using news sentiment as a predictive tool for stock market trends.

---

## Dataset

**Financial News and Stock Price Integration Dataset (FNSPID)**

| Column      | Description                                                    |
| ----------- | -------------------------------------------------------------- |
| `headline`  | News article title (financial events, earnings, price targets) |
| `url`       | Link to the full article                                       |
| `publisher` | Source of the article                                          |
| `date`      | Publication date & time (UTC-4)                                |
| `stock`     | Stock ticker symbol (e.g., AAPL)                               |

This dataset allows for both quantitative and qualitative analysis to enhance stock market predictions.

---

## Project Tasks

### Task 1: Exploratory Data Analysis (EDA)

* Analyze text and time-series data.
* Metrics include headline lengths, publisher activity, and publishing trends.
* Identify key phrases using NLP for topic modeling.
* Explore time patterns and spikes in news publication.

### Task 2: Quantitative Analysis (TA-Lib & PyNance)

* Load stock price data (`Open`, `High`, `Low`, `Close`, `Volume`).
* Compute technical indicators: MA, RSI, MACD.
* Visualize trends and indicators’ influence on stock prices.

### Task 3: Correlation Analysis

* Align news and stock datasets by date.
* Perform sentiment analysis on headlines using NLP tools (e.g., TextBlob, NLTK).
* Calculate daily stock returns.
* Aggregate daily sentiment scores and compute Pearson correlation with stock returns.

---

## Key Techniques & Tools

* **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Sentiment Analysis**: `TextBlob`, `NLTK`
* **Technical Indicators**: `TA-Lib`, `PyNance`
* **Data Visualization**: `matplotlib`, `seaborn`
* **Version Control & CI/CD**: GitHub, Git, GitHub Actions

---

## Project Structure

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```

**Branch Strategy:**

* `main` – Final merged work
* `task-1` – EDA
* `task-2` – Technical indicators & visualizations
* `task-3` – Sentiment and correlation analysis

---

## Installation & Setup

1. Clone the repository:

```bash
git clone [<your-repo-url>](https://github.com/chelone936/financial-news-sentiment-analysis.git
cd financial-news-sentiment-analysis
```

2. Create and activate Python environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run Jupyter notebooks:

```bash
jupyter notebook
```

---



If you want, I can also **draft a shorter, eye-catching version suitable for GitHub that highlights insights and includes visual badges** to make your repo more attractive and interactive. Do you want me to do that ne
