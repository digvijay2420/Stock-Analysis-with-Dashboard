# 📈 Analyzing Historical Stock Data and Building a Dashboard

This project focuses on **analyzing historical stock price data and company revenue** for multiple companies (Tesla, Amazon, AMD, Apple) using **Python, Web Scraping, and Data Visualization**.  
It demonstrates how to extract financial data, clean it, and present insights through an **interactive dashboard**.

---

## 🚀 Project Overview
The stock market is a valuable source of financial insights, but making sense of large datasets requires automation and visualization.  
In this project, we:

- Extracted **historical stock data** using the `yfinance` API.
- Used **web scraping** (`requests` + `BeautifulSoup`) to gather company revenue data.
- Cleaned and transformed the data with `pandas`.
- Built an **interactive dashboard** using `plotly` to compare:
  - **Share Price Trends**  
  - **Quarterly/Annual Revenue**  

This project combines **data engineering, financial data analysis, and visualization** into one workflow.

## 📂 Repository Structure
Stock-Analysis-with-Dashboard/
│── data/
│    └── DATA_SOURCE.md             # Links to Yahoo Finance stock data
│
│── notebooks/
│    └── analysing_stock_prices.ipynb  # Jupyter Notebook with analysis
│
│── requirements.txt                # Dependencies
│── README.md                       # Project overview


---

## 📂 Files in this Repository
- `data` - dtata sources used inside the Jupyter notebook as libraries
- `notebook` → Main Jupyter Notebook with code, analysis, and visualizations.
- `README.md` → Documentation of the project

## 🛠️ Tools & Libraries
- **Python** (data analysis and visualization)
- **pandas** → Data cleaning & manipulation  
- **yfinance** → Extracting historical stock data  
- **requests & BeautifulSoup** → Web scraping revenue data  
- **plotly** → Interactive dashboard plotting  
- **Jupyter Notebook** → Development environment  

---

## 📊 Dashboard Insights
The final dashboard consists of **two main plots**:
1. **Historical Share Price** → Displays stock price trends over time.  
2. **Historical Revenue** → Shows company revenue trends (scraped from financial reports).  

Together, they provide an interactive way to understand the relationship between stock performance and business fundamentals.

---

## 📌 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Stock-Analysis-with-Dashboard.git
   cd Stock-Analysis-with-Dashboard
   pip install -r requirements.txt
   jupyter notebook notebooks/analysing_stock_prices.ipynb
