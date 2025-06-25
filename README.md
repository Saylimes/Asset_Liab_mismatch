# Asset_Liab_mismatch
This project demonstrates how to simulate and stress test cash flows using synthetic data, and then forecast future liquidity conditions using time series models like MA and ARMA.
## Overview-Liquidity risk is the risk that a firm may not meet its short-term financial obligations due to insufficient cash flow. This notebook tackles the problem by:
- Generating **synthetic inflows and outflows**
- Computing **net and cumulative cash flows**
- Applying a **30% stress shock to outflows**
- Performing **time series forecasting** using MA and ARMA models
## Stress Testing Scenario
-**A stress scenario assumes a **30% increase in outflows**, simulating sudden mass withdrawals or liquidity shocks. This tests how resilient the firm is to such financial pressure**
## MA and ARMA forecasting- While stress testing gives a static scenario view, forecasting helps answer:
- Will the firm run out of liquidity in the next few days?
- What trends or shocks are likely in cash flows going forward?
- **AR (AutoRegressive)** captures momentum: If cash flow was high yesterday, it might be high today.
- **MA (Moving Average)** captures shocks or noise in the system.
**- **ARMA** blends both to give a **realistic, statistically robust forecast** of future liquidity.**
  # Output
  -Visualizations showing base vs. stress cumulative cash flow and forecasted values using ARMA 
