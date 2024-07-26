# Key-factors-that-influence-US-Home-Prices-Nationally\n\n

Objective:\n
This data science project aims to develop a model that explains how various economic factors have impacted home prices in the United States over the last 20 years. This analysis uses the S&P Case-Shiller Home Price Index as a proxy for home prices.

Preamble:\n
Case-Shiller Index of US Residential House Prices Data comes from S&P Case-Shiller data and includes national indices and indices for 20 metropolitan regions. These indices are created using a repeat-sales methodology.

Data Sources:\n
1. S&P Case-Shiller Home Price Index (CSUSHPISA): Represents home price trends.\n
2. Federal Funds Rate (FEDFUNDS): Represents interest rates.\n
3. Unemployment Rate (UNRATE): Measures the percentage of the unemployed labor force.\n
4. Consumer Price Index (CPIAUCSL): Indicates inflation.\n
5. Gross Domestic Product (GDP): Represents economic growth.\n
6. Housing Starts (HOUST): Indicates the number of new residential construction projects.\n
7. University of Michigan Consumer Sentiment Index (UMCSENT): Measures consumer confidence.\n

Methodology:\n
1.Data Collection: Historical data for the above factors was collected from the Federal Reserve Economic Data (FRED) database and publicly available sources.\n
2.Data Preprocessing:\n
      ~Checking and handling missing values.\n
      ~Adding time-based features (month, quarter, year) to the datasets.\n
      ~Merging the datasets on common date fields to create a comprehensive dataframe.\n
3.Exploratory Data Analysis (EDA):\n
      ~Visualizing trends and relationships between home prices and economic factors using line plots and scatter plots.\n
      ~Conducting correlation analysis to understand the strength of relationships between features and home prices.\n
4.Model Building:\n
      ~A linear regression was chosen for its simplicity and interpretability.\n
      ~The data was split into training and testing sets to evaluate model performance.\n
      ~Regularization techniques like Lasso and Ridge regression to handle multicollinearity.\n
5. Model Evaluation:\n
      ~The model was evaluated using Root Mean Squared Error (RMSE) and R² score.\n
      ~An RMSE of 8.36 and an R² score of 0.982 indicate excellent model performance, suggesting that the model effectively         captures the relationship between economic factors and home prices.\n
6.Interpretation - Feature Importance:\n
      ~Feature importance was analyzed to determine the impact of each factor on home prices.\n
      ~Coefficients of the regression model were analsyzed to to determine the impact of each factor on home prices.\n
      ~Interpreting the direction and magnitude of influence of each factor.\n

Findings:\n
1. Interest Rates (FED FUNDS): Significant negative impact on home prices; lower rates generally lead to higher home prices.\n
2. Unemployment Rate (UNRATE): Negative impact; higher unemployment rates are associated with lower home prices.\n
3. Inflation (CPIAUCSL): Positive impact; moderate inflation is associated with rising home prices.\n
4. GDP (GDP): Strong positive impact; economic growth correlates with increasing home prices.\n
5. Housing Starts (HOUST): Positive impact; more new construction projects correlate with higher home prices.\n
6. Consumer Sentiment (UMCSENT): Positive impact; higher consumer confidence is associated with rising home prices.\n

Conclusion:\n
This model provides valuable insights into how critical economic factors have influenced home prices in the United States over the last 20 years. These insights can help make informed decisions and predict future trends in the housing market.
