# ⏳ Crime Dataset - Time Series Analysis Report

This report summarizes the **time series analysis** performed on the Indian Crime dataset.  
The goal is to understand **how crime trends change over time**.

---

## 1. Overall Crime Trend Over Time

- We plotted the **total number of crimes per month/year**.  
- The line chart shows whether crimes are **increasing, decreasing, or stable** over the years.  
- Seasonal or periodic patterns (like spikes during certain months) are visible.

**Insight:**  
This helps answer: *Are crimes rising or falling over time?* and *Are there seasonal patterns?*

---

## 2. Crime Trend by City

- We broke down the time series by **Top Cities**.  
- Each city’s crime count was plotted over time.  
- Some cities show a **steady rise**, while others may show **fluctuations**.

**Insight:**  
This highlights which cities are becoming safer or more dangerous over the years.

---

## 3. Crime Trend by Domain / Category

- We plotted time series for different **crime domains** (e.g., theft, assault, cybercrime).  
- The stacked line/area chart shows **which crime categories dominate in each period**.  
- Certain categories (like cybercrime) may **increase in recent years**, while others (like petty theft) may stay stable.

**Insight:**  
This reveals **shifts in the type of crimes** committed over time.

---

## 4. Seasonality and Monthly Patterns

- We analyzed crimes by **month of the year** to check for **seasonal effects**.  
- A bar or line chart shows if crimes spike in certain months (e.g., festive seasons, summer/winter months).  
- Weekly patterns can also be analyzed (e.g., weekends vs weekdays).

**Insight:**  
This helps understand if **time of year** or **day of week** influences crime rates.

---

## 5. Forecasting (if applied)

- Using models (like ARIMA, Prophet, etc.), we forecasted **future crime trends**.  
- The chart shows both **historical crime counts** and **predicted future counts** with confidence intervals.

**Insight:**  
Forecasts provide an **early warning system** for policymakers and police departments.

---

## ✅ Conclusion

- Crime has **clear temporal patterns** — both long-term trends and short-term seasonality.  
- Some cities and crime categories are **growing faster** than others.  
- Forecasting helps in **strategic planning** for crime prevention.

All time series plots are saved as PNG files in the `./outputs/` folder for reporting and presentations.
