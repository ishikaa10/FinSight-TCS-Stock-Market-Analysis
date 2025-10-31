# FinSight-TCS-Stock-Market-Analysis

FinSight is a comprehensive **financial time-series analysis** project built using Python to explore **TCS (Tata Consultancy Services)** stock market trends, volatility, momentum indicators, and price behavior from 2020 onwards, to extract meaningful insights for data-driven investment understanding.

---

## Project Objectives
- Analyze historical price movements of TCS  
- Identify long-term trends and seasonal patterns  
- Evaluate volatility, daily returns, and price stability  
- Visualize candlestick charts, moving averages & momentum signals  
- Extract actionable insights for financial understanding  

---

## Data Source
- The dataset is sourced from Yahoo Finance using the yfinance API.

- ### Dataset Description:
    The analysis uses two datasets:
  
1. **TCS_Original_Raw_Data.csv**  
   - Raw historical stock data  
   - Columns: Date, Open, High, Low, Close, Adj Close, Volume  

2. **TCS_Adjusted_Stock_Analysis_1.csv**  
   - Cleaned/adjusted dataset for analysis  
   - Used for trend and volatility modeling  

---

## Setup & Requirements
- **Python environment** (e.g., Jupyter Notebook)
- **Pandas** – data manipulation & cleaning  
- **NumPy** – numerical computations  
- **Matplotlib & Seaborn** – visualizations  
- **mplfinance** – candlestick charts  
- **yfinance** - data source  

---

## 📊 Key Analysis Performed

### 1. Data Cleaning & Preprocessing
- Handling missing values  
- Fixing column types  
- Removing duplicates  
- Extracting date-based features  

### 2. Exploratory Data Analysis (EDA)
- Line charts of historical closing prices  
- Price distributions  
- Yearly & monthly performance comparisons  
- Correlation heatmap  

### 3. Trend & Momentum Analysis
- 50-day & 200-day moving averages  
- Trend interpretation  
- Momentum shift detection  

### 4. Volatility Analysis
- Daily returns  
- Rolling volatility  
- Return distribution charts  

### 5. Candlestick Visualization
- Candlestick chart using mplfinance  
- Short-term trend interpretation  

---

## Summary

- TCS stock shows **steady long-term growth** with identifiable seasonal patterns.  
- Technical indicators reveal **momentum shifts** and possible reversal zones.  
- Volatility analysis shows **moderate day-to-day fluctuations** with overall stability.  
- Monthly and yearly performance breakdowns provide **investment benchmarks**.  

---

## Key Insights

- Clear long-term **uptrend** with periodic corrections.  
- **Moving averages** effectively capture trend reversals and momentum changes.  
- **Daily returns** highlight market-driven volatility spikes.  
- **Candlestick patterns** reveal intraday strength and weakness.  
- Correlation analysis captures relationships between price components and returns.  

---

## Skills Demonstrated
- Time-Series Analysis  
- Financial Data Analytics  
- Trend & Momentum Modeling  
- Python for Data Analysis  
- Data Cleaning & Preprocessing  
- Insight Communication  
- Visualization & Interpretation  

---

## Usage
- Clone or download the project repository.
- Ensure all Python libraries are installed.
- Run the Jupyter notebooks:
    TCS_Stock_Analysis.ipynb is the main analysis notebook.
- Results and insights are embedded as markdown and visualizations within notebooks.
- CSV files output:
    TCS_Original_Raw_Data.csv: Raw unprocessed data.
    TCS_Adjusted_Stock_Analysis.csv: Cleaned and enriched data with computed indicators

---

## Future Work
- Incorporate sentiment analysis from news or social media.
- Build predictive models based on technical indicators.
- Expand to multi-stock portfolio analysis.
- Automate alerts based on indicator signals.

---

## Project Structure
FinSight/
│
├── TCS_Stock_Analysis.ipynb
├── TCS_Original_Raw_Data.csv
├── TCS_Adjusted_Stock_Analysis_1.csv
└── README.md
