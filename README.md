# Wikipedia Page View Forecasting for AdEase

## Project Overview
AdEase is a digital advertising company leveraging AI to help businesses maximize engagement at minimal cost. Its ad infrastructure relies on three core AI modules – **Design, Dispense, and Decipher** – to deliver effective and economical advertising solutions.  

This project focuses on **analyzing and forecasting Wikipedia page views** to optimize ad placements across regions and languages. The dataset comprises **145,000 Wikipedia pages with daily view counts spanning 550 days**.  

The ultimate goal is to build reliable time series models that anticipate user engagement, enabling AdEase to **strategically position advertisements where they are most impactful**.  

---

## Project Goals
1. **Analyze historical page view patterns** across multiple Wikipedia pages.  
2. **Perform time series preprocessing** to prepare data for forecasting.  
3. **Forecast future page views** to anticipate engagement levels.  
4. **Segment results by language and region** to align with client targeting strategies.  
5. Provide actionable insights to **optimize ad placements** and maximize ROI for clients.  

---

## Work Completed (Ongoing)
- **Data Analysis & Preprocessing**  
  - Explored daily page views for 145,000 Wikipedia pages.  
  - Conducted **stationarity checks** using the Dickey-Fuller test.  
  - Performed **time series decomposition** and **differencing** to remove trends and seasonality.  
  - Used **ACF/PACF analysis** to identify autoregressive and moving average components.  

- **Forecasting Models**  
  - Built and deployed **ARIMA**, **SARIMAX**, and **Facebook Prophet** models.  
  - Generated per-page view forecasts across languages and regions.  
  - Produced insights to guide **ad placement strategies**, targeting high-engagement periods and pages.  

---

## Next Steps
- Incorporate **exogenous factors** such as holidays or major events into models.  
- Enhance forecasting accuracy with **hybrid and ensemble approaches**.  
- Develop an **interactive dashboard** for stakeholders to visualize predicted page views and optimize ad placements in real-time.  

---

## Tools & Libraries
- Python: `pandas`, `numpy`, `statsmodels`, `fbprophet`, `matplotlib`, `seaborn`  
- Time Series Analysis: ARIMA, SARIMAX, Prophet  
- Data Visualization: matplotlib, seaborn  

---

## Status
**Ongoing:** Initial analysis and forecasting models have been implemented. Future iterations will focus on improving accuracy and providing actionable insights for multilingual and regional ad targeting.
