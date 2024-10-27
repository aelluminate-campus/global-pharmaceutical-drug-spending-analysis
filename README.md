# Global Pharmaceutical Drug Spending Analysis

This project aims to analyze global trends in pharmaceutical drug spending, focusing on variations over time and across different countries. By investigating these trends, we can gain insights into the economic impact of drug expenditures and assess the factors driving pharmaceutical costs.

## Dataset Description

The dataset chosen for this project comes from DataHub.io (https://datahub.io/core/pharmaceutical-drug-spending) detailing pharmaceutical drug spending data across multiple countries and years. It includes metrics such as country, year, total drug spending, and spending per capita, providing a comprehensive view of global drug expenditure trends.

## Summary of Findings

Our analysis reveals significant variations in pharmaceutical spending across countries, with notable trends showing steady increases in spending per capita over recent years. Countries with higher healthcare investments exhibit correspondingly high drug expenditures, suggesting a potential correlation between healthcare spending and pharmaceutical costs.

## Data Preprocessing

To prepare the dataset for analysis, several preprocessing steps were taken:

Missing Values: Handled missing values by either imputing or omitting incomplete data entries.

Data Transformation: Converted currency values and unified formats where necessary.

Normalization: Adjusted spending data to account for inflation and standardize values across different years.

## Exploratory Data Analysis

### Visualization

![image](https://github.com/user-attachments/assets/d574dd00-a1ff-40a3-86ad-378d6e5ac7f0)
  The image show all the countries who use global trends in pharmaceutical drugs. as the chart shown the norway and korea has the most used pharmaceutical drugs in all the location
  then the least is the russia.
![image](https://github.com/user-attachments/assets/b04c327d-c919-4a79-bfcc-dac2cc87e40a)
  The used flag codes in the shown locations is B then the second ne is D then the least is P
![image](https://github.com/user-attachments/assets/f76b12e6-90b0-4893-9cd9-05d69002f03d)
  The distribution is unimodal and slightly right-skewed, indicating that most countries have a per capita healthcare expenditure clustered around a central value (around 15), with a few countries having significantly higher expenditures.
  The curve suggests a possible concentration of countries with similar economic situations or healthcare systems.
![image](https://github.com/user-attachments/assets/db24bc25-ffe0-405a-95d3-24ea3566418f)
  The peak around $0.8 (likely in tens of thousands of USD) suggests many countries in the dataset have that per capita GDP level. This influences the types of drugs and pricing strategies that are viable in those markets.
  Market Potential: Higher per capita GDP often (but not always) translates to greater potential for expensive, innovative therapies.
![image](https://github.com/user-attachments/assets/74af22de-5adb-408e-a27d-c1b3dcb4887d)
  If representing company size, there are many smaller pharmaceutical companies and a few very large ones.
  If representing market size, many countries have relatively smaller pharmaceutical markets, while a few have significantly larger markets.
![image](https://github.com/user-attachments/assets/1bbc7ce4-5c6e-40c1-ac4e-89f8a43cf8ad)
   This highlights the concentrated nature of the healthcare market. Pharmaceutical companies often focus on these high-spending areas to maximize revenue. However, it also underscores potential opportunities in lower-spending regions, especially       with targeted therapies or innovative access programs.
   
## Model Development

A time-series forecasting model was developed to predict future drug spending based on historical data. We experimented with models such as ARIMA and Prophet to capture temporal patterns and seasonality in drug spending trends.
## Model Evaluation
Model evaluation was conducted using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Our final model demonstrated high accuracy in predicting spending trends, especially for countries with stable, increasing patterns of expenditure.
## Conclusion

This project highlights the rising global trend in pharmaceutical drug spending and identifies key factors influencing these costs. Insights from this analysis can inform policymakers in designing budget allocations and cost-management strategies in healthcare.
## Documentation
  ![image](https://github.com/user-attachments/assets/3cd627d9-89c5-41b1-9229-a898369b2bb7)