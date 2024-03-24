# GBPUSD-historical-data-Regression-Analysis

The project aims to compare the relationship between the British Pound (GBP) and the US Dollar (USD) by analyzing the historical data of GBP/USD exchange rates. The project makes use of a self-paced approach, where the historical data is collected and analyzed to identify any trends or patterns.

The data is stored in a CSV file and is imported into a Pandas data frame for further processing. The data contains information on the Date, Open, High, Low, Close, Change (Pips), and Change (%) of the GBP/USD exchange rate for a period of 440 days.

The first step in the analysis is to remove the time information from the date column and save the changes. The data is then analyzed to obtain statistical information on the data set, such as the data types, memory usage, and count of non-null values.

The next step is to plot the High, Low, and Mean prices of the GBP/USD exchange rate on a chart. This will help to visualize the changes in the exchange rate over the period of 440 days and identify any trends or patterns.

The analysis indicated a drop in the price of the British Pound in relation to the US Dollar, which can be seen from the plotted chart. The project provides a useful and insightful understanding of the relationship between the British Pound and the US Dollar, and the trends and patterns in their exchange rate over a given period.


# Change in GBPUSD Price Over Time:

The historical data of GBPUSD was analyzed to observe price fluctuations over time.
Utilized Pandas and Matplotlib for data manipulation and visualization.
The Low and High prices were plotted separately as well as together to observe trends.
A linear regression model was built to predict future Low prices based on the date.
The model achieved an R-squared value of 0.738, indicating a moderate-to-good fit.
## Technologies Used:

Python (Pandas, Matplotlib, NumPy)
Seaborn for correlation heatmap
Statsmodels for OLS Regression
## Conclusion:
The analysis provides insights into the GBPUSD price movement over time, aiding in decision-making for trading or investment strategies.
