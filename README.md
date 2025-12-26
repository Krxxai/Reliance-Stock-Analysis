# 📈 Stock Price Trend & Volatility Analysis – Reliance (2023)

## Project Overview
Stock market data is often noisy and difficult to interpret using raw numbers alone.  
This project analyzes **Reliance Industries’ historical stock price data (2023)** to identify **price trends, volatility, and trading behavior** using statistical analysis and data visualization.

The objective is to convert raw financial data into **clear, interpretable insights** that support better decision-making.

 ## Objectives
- Analyze historical stock price trends
- Measure stock volatility using statistical methods
- Identify market correction periods
- Understand the role of moving averages in trend detection
- Present insights through an interactive dashboard

 ## Data Source
- Historical stock price data (Open, High, Low, Close, Volume)
- Data fetched using the `yfinance` Python library (Yahoo Finance)
- Time period: **January 2023 – December 2023**
- Stock: **Reliance Industries (NSE)**

 ## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Yahoo Finance (`yfinance`)
- Power BI

##  Methodology
1. Data Collection
   - Downloaded daily stock price data using `yfinance`

2. Data Cleaning
   - Handled missing values
   - Ensured correct data types

3. Exploratory Data Analysis (EDA)
   - Analyzed stock price movements over time
   - Examined trading volume patterns

4. Feature Engineering
   - Calculated daily returns
   - Computed 20-day moving average
   - Measured volatility using standard deviation of returns

5. Visualization & Dashboard
   - Line charts for price trends
   - Bar charts for trading volume
   - Comparative analysis of price vs moving average
   - Interactive Power BI dashboard for insight presentation

## Key Insights
- Volatility increases during market correction phases, indicating higher risk
- Moving averages reduce short-term noise and reveal long-term price direction
- Volume spikes often coincide with high-volatility periods
- The stock shows recovery after correction phases, indicating trend continuation

## Dashboard Overview
The Power BI dashboard includes:
- KPI cards summarizing price range and volatility
- Stock price trend visualization
- Trading volume analysis
- Price vs 20-day moving average comparison
- Date slicer for dynamic filtering


## Project Structure
├── data/
│   └── reliance_stock.csv
├── notebooks/
│   └── stock_analysis.ipynb
├── dashboard/
│   └── reliance_stock_report.pbix
├── README.md
