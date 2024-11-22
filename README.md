# Description
Delivery orders forecasting project for Bazario, using Seasonal ARIMA to analyze monthly order trends (2016-2023) and predict future demand (2024-2025). Supports strategic inventory planning, supply chain optimization, and peak season readiness.

# Delevery Ordes Forecasting for Bazario

## Project Overview  
This project focuses on analyzing monthly order trends for Bazario from 2016 to 2023 and predicting order demand for the next two years (2024-2025). The objective is to enhance supply chain efficiency, optimize inventory management, and prepare for peak season demands using Seasonal ARIMA modeling.

---

## Objective  
- Analyze historical order trends.  
- Build a forecasting model to predict future order demand.  
- Support strategic decision-making for inventory and logistics planning.  

---

## Dataset  
- **Timeframe:** January 2016 to December 2023.  
- **Frequency:** Monthly order data.  
- **Key Features:** Month, Year, avg Orders per month.  

---

## Tools Used  
- **Python Libraries:** Pandas, NumPy, Statsmodels, Matplotlib, Seaborn.  
- **Model:** Seasonal ARIMA (SARIMA).  

---

## Process  
1. **Data Cleaning & Preprocessing:**  
   - Handled missing values and anomalies.  
   - Converted time-series data into stationary format.  

2. **Exploratory Data Analysis (EDA):**  
   - Identified seasonality, trends, in the data.  
   - Visualized historical order patterns.  

3. **Modeling:**  
   - Applied SARIMA for forecasting based on seasonal patterns.  
   - Tuned hyperparameters using AIC/BIC metrics for optimal performance.  

4. **Validation & Prediction:**  
   - Validated the model using historical data (7-2022-2023).  
   - Forecasted order demand for 2024-2025.  

---

## Recommendations  
1. **Inventory Optimization:** Stock up on high-demand products during peak month (December).  
2. **Staffing Strategy:** Allocate additional resources during forecasted high-demand periods.  
3. **Logistics Efficiency:** Strengthen delivery networks to meet anticipated demand surges.  

---

## Results  
- Forecated the Delivery orders for year 2024 and 2025. File attached.
    
