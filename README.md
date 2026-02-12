# Mutual-Fund-Python-Project

# 📊 Mutual Fund Portfolio Analysis & Optimization (Python)

## 🚀 Project Overview

This project focuses on building a **data-driven Mutual Fund Investment Plan** using Python.
Using historical Nifty 50 stock data, we performed portfolio analysis, risk-return evaluation, and optimization techniques to identify:

* 📈 High ROI stocks
* ⚠️ High volatility (risky) stocks
* 📊 Best risk-adjusted performers
* 🏦 Recommended mutual fund portfolio plans

The project applies financial analytics concepts such as **Annualized Returns, Volatility, Sharpe Ratio, and Portfolio Optimization** to simulate real-world investment decision-making.

---

# 🎯 Objective

The primary goal of this project is to:

* Analyze historical stock performance
* Evaluate risk vs return trade-offs
* Identify high-performing and risky stocks
* Construct diversified mutual fund-style portfolios
* Recommend optimized investment strategies for different risk profiles

---

# 📂 Dataset

* Source: Nifty 50 Historical Closing Prices
* Frequency: Daily data
* Assets: 49+ NSE-listed companies

Data was used to compute:

* Daily Returns
* Annualized Returns
* Annualized Volatility
* Sharpe Ratio (Risk-adjusted performance)

---

# ⚙️ Methodology

## 1️⃣ Data Preparation

* Loaded historical closing price data

* Calculated daily percentage returns

* Annualized returns using:

  ```
  Annual Return = (1 + Mean Daily Return)^252 - 1
  ```

* Annualized volatility:

  ```
  Volatility = Std Dev of Daily Returns × √252
  ```

* Assumed Risk-Free Rate = 6%

---

## 2️⃣ Risk-Adjusted Performance (Sharpe Ratio)

```
Sharpe Ratio = (Portfolio Return - Risk Free Rate) / Volatility
```

This metric was used to identify the best investment opportunities.

---

# 📈 Key Insights

## 🏆 Best High ROI Stock

### ✅ BHARTIARTL.NS

* Annual Return ≈ 60%
* Strong Sharpe Ratio ≈ 2.31
* Moderate volatility

➡ Best overall risk-adjusted performer.

---

## 📊 High ROI Stocks

* M&M.NS
* DIVISLAB.NS
* BPCL.NS
* ADANIPORTS.NS

These stocks showed strong annual returns but varying risk levels.

---

## ⚠️ High Volatility / Risky Stocks

* INDUSINDBK.NS (High volatility + negative return)
* ADANIENT.NS (Very high volatility + weak returns)
* ADANIPORTS.NS (High risk but decent returns)

These stocks are suitable only for aggressive investors.

---

# 📊 Risk vs Return Observations

* High return does not always mean good investment.
* Sharpe Ratio is a better decision metric than raw return.
* Some stocks generate strong returns with controlled risk.
* Negative Sharpe stocks reduce portfolio efficiency.

---

# 🏦 Recommended Mutual Fund Plans

## 🟢 Conservative Plan (Low Risk)

| Stock         | Allocation |
| ------------- | ---------- |
| BHARTIARTL    | 40%        |
| DIVISLAB      | 25%        |
| M&M           | 20%        |
| Stable Others | 15%        |

✔ Stable growth
✔ Lower volatility

---

## 🟡 Balanced Plan (Recommended)

| Stock      | Allocation |
| ---------- | ---------- |
| BHARTIARTL | 30%        |
| M&M        | 25%        |
| DIVISLAB   | 20%        |
| BPCL       | 15%        |
| ADANIPORTS | 10%        |

✔ Diversified
✔ Strong risk-adjusted performance
✔ Suitable for 5–7 year investment horizon

---

## 🔴 Aggressive Plan

| Stock                | Allocation |
| -------------------- | ---------- |
| M&M                  | 30%        |
| ADANIPORTS           | 25%        |
| BPCL                 | 20%        |
| ONGC                 | 15%        |
| High-growth volatile | 10%        |

✔ High return potential
⚠ High volatility

---

# 📌 Key Investment Considerations

* Always evaluate Sharpe Ratio, not just returns
* Diversify across sectors
* Avoid stocks with negative risk-adjusted returns
* Rebalance portfolio annually
* Align portfolio with time horizon:

  * <3 years → Conservative
  * 5+ years → Balanced
  * 10+ years → Aggressive

---

# 📊 Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy (Portfolio Optimization)

---

# 🔥 Advanced Features Implemented

* Portfolio Volatility Calculation
* Mean-Variance Optimization
* Monte Carlo Simulation
* Efficient Frontier Visualization
* Sensitivity Analysis

---

# 🎯 Final Conclusion

* 📈 Best High ROI Stock → **BHARTIARTL**
* ⚠ Most Risky → **INDUSINDBK**
* 🏆 Best Risk-Adjusted Performer → **BHARTIARTL**
* 🏦 Recommended Portfolio → **Balanced Diversified Plan**

This project demonstrates practical application of financial analytics, portfolio construction, and investment strategy optimization using Python.

---

# 📌 Future Improvements

* Add Machine Learning-based return prediction
* Implement Dynamic Rebalancing Model
* Integrate Live Market Data API
* Build Interactive Streamlit Dashboard

---

# 💼 Resume Project Summary

> Developed a Python-based Mutual Fund Portfolio Optimization system using historical Nifty 50 data. Applied financial risk-return metrics (Annualized Return, Volatility, Sharpe Ratio), Mean-Variance Optimization, and Monte Carlo simulation to construct diversified investment strategies tailored to different risk profiles.

---

⭐ If you found this project useful, feel free to star the repository!
