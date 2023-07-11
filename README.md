# Airline recommendation
Summary:

1. We are a consulting company. As a data science analyst, I need to make recommendations on 5 new airlines to acquire.
   Airports (Airport_Codes.csv), Flights (Flights.csv) and Tickets (Tickets.csv) datasets are provided.

2. Data Quality Check
   
2.1 Removed irrelevant data.

2.2 Standardized data format.

2.3 Checked data types.

2.4 Dealt with missing values.
   Defined a function to list sparsity of each variable.
   Made fair business assumptions to fill with valid values.
   Applied sklearn.RandomForestRegressor to fill in missing values.

3. Outliers
   Z-value method. Set threshold. Filter out any outliers with a Z-value larger than threshold.
   Boxplot.

4. Data munging
   Now the 3 datasets are prepared as clean. To gain a big picture of various perspectives we can rely on to make business recommendations, merge 3 datasets. The final data has airline information by origin and destination.

5. EDA
   
5.1 Calculated TOP 10 Busiest routes. Bar chart shows ranking and pie chart shows proportions.
   
5.2 Calculated TOP 10 Profitable routes in terms of profit margin and made visualizations.

6. Recommendations
   Made final recommendations based on priorities/tiers: Traffic, Profit, and Punctuality.
   

   




   
