# 🦠 COVID-19 Data Analysis & Forecasting with Prophet

This project focuses on analyzing and forecasting the global COVID-19 pandemic trend using real-time data, visualizations, and time series modeling with Facebook Prophet.

## 📊 Dataset

The dataset includes daily COVID-19 statistics by country:
- **Columns**: Province/State, Country/Region, Latitude, Longitude, Date, Confirmed, Deaths, Recovered, Active, WHO Region  
- **Max Date**: 2020-07-27

## 📌 Key Steps

1. **Data Preprocessing**
   - Selected data with the latest available date
   - Grouped data by country
   - Aggregated Confirmed, Deaths, Recovered, and Active cases

2. **Global Analysis**
   - Summed values by date for each metric
   - Identified Top 10 countries with:
     - Most Confirmed Cases
     - Most Recovered Cases
     - Most Deaths
   - Visualized results using graphs

3. **Country-specific Analysis**
   - Created filtered datasets for countries like the **United States**
   - Compared case trends across 3–4 countries

4. **Forecasting with Prophet**
   - Applied Facebook Prophet to forecast **Confirmed Cases**
   - Predicted the trend for the **next 7 months**

## 📈 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `prophet` (formerly `fbprophet`)

## 📊 Sample Visualizations

- Top 10 countries by confirmed/recovered/death cases
- Line graphs comparing countries
- Forecasted curve for the next 7 months

## 📌 Conclusion

This project showcases how time series forecasting can be used to gain insights from public health data, especially in critical global scenarios like pandemics.

---

🔗 **Check out the Notebook & Code in this repository!**

#COVID19 #TimeSeriesAnalysis #Python #DataScience #Forecasting #Prophet #MachineLearning #Visualization #GitHubProject

