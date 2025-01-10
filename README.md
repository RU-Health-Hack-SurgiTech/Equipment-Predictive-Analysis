# Won the RU-Health-Hack-2024

# Equipment Demand Prediction

## Overview
This project focuses on predicting the demand for surgical equipment based on historical data from hospitals. By analyzing surgery schedules, equipment requirements, and usage patterns, it provides insights into the quantities of equipment needed, helping optimize hospital resource allocation and reduce the risk of shortages.

## Features
- **Data Cleaning**: Handles missing values, duplicate entries, and ensures consistency in IDs across datasets.
- **Exploratory Data Analysis (EDA)**: Visualizes surgery distributions, daily trends, and average equipment usage statistics.
- **Demand Forecasting**: Implements the SARIMAX model for time series prediction of equipment demand, with metrics such as MAE and MSE for evaluation.
- **Outlier Detection**: Uses the IQR method to identify and filter out demand anomalies.

## Data
The project uses three main datasets:
1. **Surgery Data**: Contains surgery types, dates, and IDs.
2. **Equipment Data**: Lists equipment details, including IDs and types (reusable or disposable).
3. **Preference Card Data**: Maps surgeries to required equipment and quantities.

## Methodology
1. **Data Preprocessing**:
   - Cleaned data for missing values and duplicates.
   - Transformed columns into appropriate formats, such as splitting lists and converting dates.
2. **Exploratory Data Analysis**:
   - Visualized surgery types and trends over time.
   - Calculated average equipment usage and surgery statistics.
3. **Demand Forecasting**:
   - Trained a SARIMAX model on filtered data to predict future equipment demand.
   - Evaluated predictions using error metrics and accuracy percentages.

## Results
  - Identified high-demand equipment types.
  - Provided average monthly surgeries by type.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**: 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Forecasting: `statsmodels`

## Visualizations
- Distribution of surgery types.
- Surgery counts over time.
- Forecasting equipment demand with SARIMAX.
