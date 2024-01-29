

# Bitcoin Price Analysis

#  Overview

This project involves the analysis and visualization of Bitcoin price data. Key objectives include exploring trends over time, identifying patterns, and machine learning using a Random Forest Classifier. 
# Project Description

## Dataset

The dataset(1556 rows × 7 columns) comprises Bitcoin price information, including open, high, low, close values, volume, and market cap, spanning from April 28, 2013, to July 31, 2017.

<img width="275" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/1.png">

Technologies: Tools Used: Azure Blob is used for storage. 

## Exploratory Data Analysis (EDA)

## Technologies Used
The analysis was performed using Python, leveraging the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

## Preprocessing

- Checked for missing values and duplicates.
- Converted the 'Date' column to datetime format.
- Explored and applied relevant transformations, such as log scaling on the 'Close' column.

## Data Visualization

- **Trend Analysis:** Various plots are used to visualize the trends in Bitcoin prices over time, providing insights into the volatility and behavior of the market.
- Reveals a descending trend from 2014 to 2015, followed by a significant and sustained upward trend from 2015 onwards. Periods of increased volatility are observed in 2014 and 2017.
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/2.png">


- **Candlestick Chart:** Provides a detailed visualization of daily price movements, highlighting more positive (green) movements from May 5 to June 2.
  
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/3.png">

- **Feature Engineering and Resampling**
- ### Log Transformation：
  Logarithmic transformation is applied to certain features to normalize the data and reduce skewness.
- ### Resampling:
The data is resampled at different intervals (daily, monthly, quarterly, yearly) to analyze trends at various time scales.
  
<img width="275" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/6.png" style="display:inline-block; margin-right: 20px;">


- **Resampled Mean Price Plots:** Showcase consistent growth, particularly from 2015 onwards. Quarterly analysis indicates a consistent pattern of lower prices in quarter 1, suggesting potential seasonality.

<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/4.png">



## Machine Learning for Price Prediction
- A Random Forest Classifier is chosen for its robustness and ability to handle non-linear data.
- Classification Report：
<img width="275" alt="image" src="https://github.com/Tikii0617/Bitcoin-Price-Analysis/blob/main/IMG/8.png" style="display:inline-block; margin-right: 20px;">

