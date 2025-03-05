# Fixed Income Portfolio Valuation and Value at Risk (VaR) Estimation

## Overview
This project implements a **Fixed Income Portfolio Valuation and Risk Assessment** model in Python. It features **bond pricing using discounted cash flows (DCF), portfolio revaluation under interest rate shifts, and Value at Risk (VaR) estimation using historical simulation**. The project provides insights into **fixed income risk management, interest rate sensitivity, and portfolio valuation techniques**.

## Features
✅ **Bond Valuation**: Calculates bond prices using discounted cash flow (DCF) method.
✅ **Portfolio Revaluation**: Adjusts bond prices based on changes in interest rates.
✅ **Historical Simulation for VaR**: Computes **Value at Risk (VaR)** for different time horizons using historical bond price movements.
✅ **Time Scaling for VaR**: Applies the square-root rule for adjusting VaR over different time periods.

## Technologies Used
- **Python** (NumPy)
- **Financial Modeling**
- **Fixed Income Securities Analysis**
- **Risk Management & VaR Calculation**

## Code Structure
- **Bond Class**: Represents individual bonds, computes bond prices using DCF.
- **FixedIncomePortfolio Class**: Manages a collection of bonds and handles revaluation.
- **Value at Risk Calculation**: Estimates portfolio risk using historical simulation.

## Sample Output
```
Initial Portfolio value: 2980.0
Portfolio value after partial revaluation: 2955.3
Portfolio Value at Risk (VaR) for 1 day: -15.2
Portfolio Value at Risk (VaR) for 1 week: -33.9
Portfolio Value at Risk (VaR) for 1 month: -68.1
```

## Future Enhancements
🔹 Implement **Cox-Ingersoll-Ross (CIR) and Vasicek models** for interest rate modeling.
🔹 Extend **Monte Carlo simulation for VaR computation**.
🔹 Integrate **real-time bond market data** using APIs.

## Author
**Satyam**  
📧 satyam@buffalo.edu  
🔗 https://www.linkedin.com/in/sattytough17/

