# Bitcoin Price Analysis

#  Overview

This project involves the analysis and visualization of Bitcoin price data. Key objectives include exploring trends over time, identifying patterns, and gaining insights into the behavior of Bitcoin prices.

## Dataset

The dataset(1556 rows × 7 columns) comprises Bitcoin price information, including open, high, low, close values, volume, and market cap, spanning from April 28, 2013, to July 31, 2017.
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/1.png">

## Preprocessing

- Checked for missing values and duplicates.
- Converted the 'Date' column to datetime format.
- Explored and applied relevant transformations, such as log scaling on the 'Close' column.

## Data Analysis

- **Time Series Plot:** Reveals a descending trend from 2014 to 2015, followed by a significant and sustained upward trend from 2015 onwards. Periods of increased volatility are observed in 2014 and 2017.
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/2.png">


- **Candlestick Chart:** Provides a detailed visualization of daily price movements, highlighting more positive (green) movements from May 5 to June 2.
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/3.png">
- **Handling Object Data:**
   - Set the 'Date' column as the index of the DataFrame.
   - Explored and visualized the 'Close' column.
   - Applied log scaling to the 'Close' column for better visualization.
<img width="375" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/4.png">


- **Resampled Mean Price Plots:** Showcase consistent growth, particularly from 2015 onwards. Quarterly analysis indicates a consistent pattern of lower prices in quarter 1, suggesting potential seasonality.
<img width="275" alt="image" src="https://github.com/Tikii0617/BIT-ANALYSIS/blob/main/IMG/6.png" style="display:inline-block; margin-right: 20px;">


## Technologies Used
The analysis was performed using Python, leveraging the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly


## Data Visualizations

Utilized various visualizations, including time series plots, candlestick charts, and resampled mean price plots, to effectively communicate trends and patterns in the Bitcoin price data.


## Insights

In conclusion, the analysis revealed significant trends in Bitcoin prices. The overall trend showcased a descending pattern from 2014 to 2015, followed by a substantial and sustained upward trend from 2015 onwards. Periods of increased volatility in 2014 and 2017 were also identified. The quarterly analysis indicated a consistent pattern of lower prices in quarter 1, suggesting potential seasonality. It is crucial to consider these trends for making informed decisions in Bitcoin investments or related analyses.

