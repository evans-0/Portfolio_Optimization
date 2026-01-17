# NSE Portfolio Optimization: Monte Carlo Simulation 📈

An independent quantitative finance project applying **Modern Portfolio Theory (MPT)** to the National Stock Exchange (NSE) of India. This project was developed as a real-world extension of concepts explored during the **CFI Business Intelligence & Data Analyst (BIDA)** program.

## 🚀 Overview
This tool performs a Monte Carlo simulation of 10,000 random portfolio scenarios to identify the **Efficient Frontier** and the **Maximum Sharpe Ratio** for a basket of high-weight Indian equities.

### 💼 Portfolio Composition
The analysis includes 10 years of historical data for:
* **ITC.NS** (ITC Limited)
* **VBL.NS** (Varun Beverages Limited)
* **TATACONSUM.NS** (Tata Consumer Products Limited)
* **ICICIBANK.NS** (ICICI Bank Limited)
* **HDFCBANK.NS** (HDFC Bank Limited)
* **RELIANCE.NS** (Reliance Industries Limited)
* **HINDUNILVR.NS** (Hindustan Unilever Limited)

## 🛠️ Technical Highlights
* **Risk-Free Rate:** Utilized a realistic **6.6%** (0.066) based on current India 10-Year Government Bond yields.
* **Data Cleaning:** Implemented robust handling for date misalignments and `NaN` values to ensure a consistent 10-year lookback period.
* **Vectorized Calculations:** Used NumPy for efficient matrix multiplication to calculate annualized portfolio returns and volatility.
* **Optimization:** Identified the "Golden Point" where risk-adjusted return is maximized.

## 📊 Key Results
* **Maximum Sharpe Ratio:** **1.17**
* **Optimal Strategy:** The simulation favored a diversified but aggressive allocation toward growth leaders like **VBL** and **Tata Consumer**, balanced by the stability of **Reliance** and the banking sector.


## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, yfinance
* **Format:** Jupyter Notebook (.ipynb)

## 📜 Disclaimer
*This project is for educational and portfolio purposes only. It is not financial advice. Past performance is not indicative of future results.*

## ⚖️ License
This project is licensed under the [MIT License](LICENSE).
