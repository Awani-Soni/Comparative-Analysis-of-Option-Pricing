# Comparative Analysis of European Option Pricing

A Python-based project analyzing and comparing European option pricing using the **Black-Scholes model** and the **Binomial Tree method**.

---

##  Overview

This project implements and compares two fundamental models used in financial engineering for pricing European call and put options:

- **Black-Scholes Closed-Form Formula**
- **Binomial Tree Model**

Both models are explored from mathematical, computational, and empirical perspectives using real-world market data (AAPL options).

---

##  Objectives

- Implement Black-Scholes and Binomial Tree pricing algorithms for European options
- Compare model assumptions and computational characteristics
- Analyze convergence behavior of the Binomial Tree model
- Perform sensitivity analysis on key variables:
  - Volatility (σ)
  - Time to Maturity (T)
  - Risk-Free Interest Rate (r)
  - Strike Price (K)
- Validate pricing outputs using real market data from Yahoo Finance
- Visualize model behavior and pricing deviations

---

## 🛠 Tech Stack

- Python 3.10+
- Libraries:
  - `NumPy`
  - `Pandas`
  - `Matplotlib`
  - `yfinance`

---

##  Visualizations

The notebook includes comprehensive plots:

- ✅ Convergence of Binomial model to Black-Scholes
- ✅ Execution time vs accuracy tradeoff
- ✅ Sensitivity plots for σ, T, r, and K
- ✅ Real vs predicted option prices (Market vs Models)

---


##  Key Takeaways

- The **Binomial Tree model** converges to the **Black-Scholes price** with increasing steps
- Both models show similar sensitivity trends to financial variables
- Real-world prices may diverge from theoretical ones due to implied volatility and market behavior
- Trade-off exists between computational time and pricing accuracy

---

##  Data Source

- Yahoo Finance via `yfinance`
- Example stock used: AAPL (Apple Inc.)

---
##  Skills Demonstrated

- Options Pricing Theory
- Quantitative Finance
- Financial Modeling
- Data Analysis & Visualization
- Python Programming

---

##  Reference

- *Options, Futures, and Other Derivatives* – John C. Hull
