# Trader Performance vs Market Sentiment

An end-to-end data analysis project that explores the relationship
between **trader performance** and **market sentiment (Fear & Greed
Index)** to uncover behavioral patterns and design smarter trading
strategies.

------------------------------------------------------------------------

## Project Objective

The goal of this project is to:

-   Analyze how market sentiment influences trader returns
-   Identify hidden behavioral and performance patterns
-   Evaluate whether sentiment can be used as a predictive or
    regime-filtering signal
-   Propose sentiment-driven trading strategies with performance
    comparison

------------------------------------------------------------------------

## Datasets Used

### 1. `historical_data.csv`

Contains historical trading / market performance data with columns such
as: - `date` - `open`, `high`, `low`, `close` - (optional) `returns`
(computed if not present)

### 2. `fear_greed_index.csv`

Contains daily market sentiment data with: - `date` - `value` → Fear &
Greed Index (0--100) - `classification` → Fear / Neutral / Greed

------------------------------------------------------------------------

## Requirements

Install the required Python libraries before running the notebook:

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Python version recommended: **3.8+**

------------------------------------------------------------------------

## How to Run the Notebook

1.  Place the following files in the same directory:
    -   `notebook_1.ipynb`
    -   `historical_data.csv`
    -   `fear_greed_index.csv`
2.  Open the notebook:

``` bash
jupyter notebook notebook_1.ipynb
```

3.  Run all cells sequentially to reproduce:
    -   Data cleaning
    -   Data merging
    -   Visualizations
    -   Correlation and regression analysis
    -   Strategy backtesting

------------------------------------------------------------------------

## Methodology Overview

The analysis follows these main steps:

1.  **Data Cleaning & Preprocessing**
2.  **Data Integration**
3.  **Exploratory Data Analysis (EDA)**
4.  **Modeling & Statistical Analysis**
5.  **Strategy Design & Evaluation**

------------------------------------------------------------------------

##  Key Visualizations Generated

-   Fear & Greed Index over time\
-   Trader returns over time\
-   Scatter plot: Returns vs Sentiment\
-   Correlation heatmap\
-   Boxplot: Returns by sentiment regime\
-   Regression fit: Sentiment vs Returns\
-   Strategy vs Baseline cumulative returns

------------------------------------------------------------------------

## Key Findings

-   Market sentiment strongly affects **risk and volatility**, more than
    average returns
-   Extreme greed is associated with overconfidence and higher
    volatility
-   Fear regimes often provide **contrarian profit opportunities**
-   Best performance typically occurs during **Neutral to Mild Greed**
    regimes

------------------------------------------------------------------------

## Strategy Insights

-   Use sentiment as a regime filter and timing aid
-   Combine sentiment with technical indicators
-   Control leverage during extreme greed

------------------------------------------------------------------------

## Author

**Mrityunjay Sharma**\
Data Science \| Machine Learning \| Quantitative Analysis

------------------------------------------------------------------------

Happy Analyzing 
