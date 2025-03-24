# Meteorological Data Analysis with Tableau

## Project Overview
This repository contains the Meteorological Data Analysis, completed on December 5th, 2023. The project utilizes Tableau visualizations to analyze a meteorological dataset, exploring relationships between humidity levels, precipitation types, visibility, apparent temperature, and atmospheric pressure across various regions. The objective is to identify patterns and correlations that enhance the understanding of weather phenomena and provide actionable insights for weather-sensitive industries.

## Dataset
The dataset used in this project is sourced from Kaggle:  
[**Meteorological Data**](https://www.kaggle.com/datasets/saurabhsuven/meteorological-data)  

- **Format**: Excel file  
- **Key Variables**:  
  - Humidity (relative scale: 0.26 to 1.0)  
  - Precipitation Types (e.g., rain, snow)  
  - Visibility (kilometers)  
  - Apparent Temperature (°C)  
  - Atmospheric Pressure (millibars)  
- **Temporal Scope**: Hourly data with timestamps, enabling analysis of diurnal and daily patterns.

The dataset was imported into Tableau for visualization and analysis.

## Project Structure
- **Documentation**: The full project report is available in the file `Meteorological Data Analysis Report.pdf`.  
- **Visualizations**: Tableau workbook files containing the visualizations are included.  
- **Dataset**: The raw Excel file from Kaggle is not included due to size constraints but can be downloaded from the link above.

## Key Findings
1. **Humidity vs. Precipitation**:  
   - Higher humidity levels correlate with increased rainfall.  
   - Lower humidity levels are associated with snowfall, contingent on suitable temperatures.  

2. **Visibility vs. Weather Conditions**:  
   - Foggy and windy conditions reduce visibility (e.g., 7.62 km in "Windy and foggy").  
   - Partly cloudy conditions improve visibility (e.g., 389.31 km in "Humid and mostly cloudy").  

3. **Pressure vs. Apparent Temperature**:  
   - Extreme temperature outliers (e.g., 43,076.08°C, -387.78°C) suggest potential data errors or significant weather events.  
   - Pressure peaks between 15–20°C, with lower pressures at extreme temperatures.

4. **Hourly Humidity Fluctuations**:  
   - Humidity increases at night (e.g., 0.59 at 2013-07-29 21:00:00) and decreases during the day (e.g., 0.32 at 2013-07-03 14:00:00).  
   - Peak humidity observed at 0.97 (2013-07-03 02:00:00).  

## Setup Instructions
To replicate or explore the visualizations:
1. **Download the Dataset**: Obtain the Excel file from the Kaggle link provided above.  
2. **Install Tableau**: Use Tableau Public (free) or Tableau Desktop (licensed) to open the workbook files.  
3. **Import Data**: Load the Excel file into Tableau and connect it to the visualizations.  
4. **Explore**: Open the `.twbx` files to interact with the dashboards.

## Managerial Implications
- **Operational Planning**: Adjust schedules in agriculture, construction, or transportation based on precipitation and visibility forecasts.  
- **Inventory Management**: Optimize stock levels for weather-dependent products (e.g., umbrellas, raincoats) using precipitation predictions.

## Conclusion
This project demonstrates the power of Tableau in uncovering meteorological patterns, offering insights valuable for forecasting and decision-making in weather-sensitive sectors. The findings highlight the interplay of humidity, precipitation, visibility, and pressure, providing a foundation for further research and practical applications.

## References
- Sadegh, M., & Alizadeh, A. (2021). *Meteorological Data Analysis Principles*.  
- Voas, J., & Ambler, G. *The relationship between behavior in a stress situation and later separation from flight training with expressed anxiety toward flying*.


