# Key-factors-that-influence-US-Home-Prices-Nationally

## Objective:
This data science project aims to develop a model that explains how various economic factors have impacted home prices in the United States over the last 20 years. This analysis uses the S&P Case-Shiller Home Price Index as a proxy for home prices.

## Preamble:
Case-Shiller Index of US Residential House Prices Data comes from S&P Case-Shiller data and includes national indices and indices for 20 metropolitan regions. These indices are created using a repeat-sales methodology.

## Data Sources:
1. S&P Case-Shiller Home Price Index (CSUSHPISA): Represents home price trends.
2. Federal Funds Rate (FEDFUNDS): Represents interest rates.
3. Unemployment Rate (UNRATE): Measures the percentage of the unemployed labor force.
4. Consumer Price Index (CPIAUCSL): Indicates inflation.
5. Gross Domestic Product (GDP): Represents economic growth.
6. Housing Starts (HOUST): Indicates the number of new residential construction projects.
7. University of Michigan Consumer Sentiment Index (UMCSENT): Measures consumer confidence.

## Methodology:
1.Data Collection: Historical data for the above factors was collected from the Federal Reserve Economic Data (FRED) database and publicly available sources.

2.Data Preprocessing:

      ~Checking and handling missing values.

      ~Adding time-based features (month, quarter, year) to the datasets.
      
      ~Merging the datasets on common date fields to create a comprehensive dataframe.

3.Exploratory Data Analysis (EDA):
      
      ~Visualizing trends and relationships between home prices and economic factors using line plots and scatter plots.
      
      ~Conducting correlation analysis to understand the strength of relationships between features and home prices.

4.Model Building:
      
      ~A linear regression was chosen for its simplicity and interpretability.
      
      ~The data was split into training and testing sets to evaluate model performance.
      
      ~Regularization techniques like Lasso and Ridge regression to handle multicollinearity.

5. Model Evaluation:\n

   ~The model was evaluated using Root Mean Squared Error (RMSE) and R² score.

   ~An RMSE of 8.36 and an R² score of 0.982 indicate excellent model performance, suggesting that the model effectively         captures the relationship between economic factors and home prices.

6.Interpretation - Feature Importance:
      
      ~Feature importance was analyzed to determine the impact of each factor on home prices.
      
      ~Coefficients of the regression model were analsyzed to to determine the impact of each factor on home prices.
      
      ~Interpreting the direction and magnitude of influence of each factor.

## Findings:
1. Interest Rates (FED FUNDS): Significant negative impact on home prices; lower rates generally lead to higher home prices.
2. Unemployment Rate (UNRATE): Negative impact; higher unemployment rates are associated with lower home prices.
3. Inflation (CPIAUCSL): Positive impact; moderate inflation is associated with rising home prices.
4. GDP (GDP): Strong positive impact; economic growth correlates with increasing home prices.
5. Housing Starts (HOUST): Positive impact; more new construction projects correlate with higher home prices.
6. Consumer Sentiment (UMCSENT): Positive impact; higher consumer confidence is associated with rising home prices.

## Conclusion:
This model provides valuable insights into how critical economic factors have influenced home prices in the United States over the last 20 years. These insights can help make informed decisions and predict future trends in the housing market.
