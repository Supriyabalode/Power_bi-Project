# 📈 Stock Market Analysis

## 📌 Project Overview

This project analyzes historical stock market data of multiple companies to identify price trends, 
trading volume patterns, moving averages, and stock volatility.

The analysis was performed using **Python and Power BI** to transform raw stock data into meaningful insights through data cleaning, 
feature engineering, visualization, and dashboard development.

## 🎯 Objectives

* Analyze historical stock price movements.
* Compare the performance of different companies.
* Identify trends using moving averages.
* Analyze trading volume.
* Measure stock price volatility.
* Create interactive dashboards for data exploration.
* Generate meaningful insights from historical market data.

## 📊 Dataset

The dataset contains approximately **5 years of historical stock market data** for multiple companies.

### Key Columns

* `Date` – Trading date
* `Company` – Company name
* `Open` – Opening price
* `High` – Highest price of the day
* `Low` – Lowest price of the day
* `Close` – Closing price
* `Volume` – Number of shares traded

Additional features were created during analysis, including:

* Moving Average (MA)
* 50-Day Moving Average
* 100-Day Moving Average
* 200-Day Moving Average
* Volatility

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **yFinance**
* **Power BI**
* **Power Query**
* **DAX**
* **Excel**

## 🔄 Project Workflow

```text
Stock Market Data
       ↓
Data Collection
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Power BI Dashboard
       ↓
Insights & Visualization
```

## 🐍 Python Analysis

Python was used for:

* Data collection
* Data cleaning
* Exploratory Data Analysis
* Feature engineering
* Moving average calculation
* Volatility calculation
* Data visualization

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive analysis of stock market data.

### Dashboard Features

* Company-wise stock performance
* Date-based analysis
* Open, High, Low and Close prices
* Trading volume
* Moving average analysis
* Volatility analysis
* Interactive filters and slicers
* Trend visualization

## 💡 Key Insights

The project helps identify:

* Changes in stock prices over time
* Companies with different price-performance patterns
* High and low trading-volume periods
* Short-term and long-term price trends
* Periods of higher or lower volatility
* Relationship between price movement and trading volume

## 📂 Repository Structure

```text
Stock-Market-Analysis/
│
├── Python/
│   ├── data_collection.py
│   ├── data_cleaning.py
│   └── stock_analysis.py
│
├── Dataset/
│   └── stock_data.csv
│
├── PowerBI/
│   └── Stock_Market_Analysis.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Install required Python libraries

```bash
pip install pandas numpy matplotlib seaborn yfinance
```

### 3. Run the Python files

```bash
python stock_analysis.py
```

### 4. Open the Power BI file

Open the `.pbix` file using **Microsoft Power BI Desktop** to explore the interactive dashboard.


