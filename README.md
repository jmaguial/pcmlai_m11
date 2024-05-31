# Overview
This project aims to understand the factors that influence the price of used cars. The analysis follows the industry-standard CRISP-DM methodology and includes data cleaning, visualization, modeling, and interpretation of results. The goal is to provide actionable insights to a fictitious car dealership regarding what consumers value in a used car.

# Data
The dataset includes various features such as:
- price: The price of the car.
- year: The year the car was manufactured.
- manufacturer: The manufacturer of the car.
- model: The model of the car.
- condition: The condition of the car (e.g., new, like new, excellent, good, fair).
- cylinders: The number of cylinders in the car's engine.
- fuel: The type of fuel the car uses (e.g., gas, diesel, hybrid, electric).
- odometer: The odometer reading of the car.
- transmission: The type of transmission (e.g., automatic, manual).
  
# Analysis and Visualizations
## Categorical Variables
1. Manufacturer: Bar plots showing the count of listings per manufacturer and their average prices.
2. Condition: Bar plots showing the distribution of car conditions and their average prices.
3. Fuel Type: Bar plots showing the distribution of fuel types and their average prices.
4. Transmission: Bar plots showing the distribution of transmission types and their average prices.
## Continuous Variables
1. Year: Scatter plot showing the relationship between car year and price.
2. Odometer: Scatter plot showing the relationship between odometer reading and price.

# Modeling
## Multiple Regression Model
- Features used: year, manufacturer, condition, cylinders, fuel, odometer, transmission.
- Preprocessing: One-hot encoding for categorical variables and standardization for continuous variables.
- Model Evaluation: Cross-validation and test set evaluation using Root Mean Squared Error (RMSE).
## Model Performance
- Cross-Validation RMSE (Root Mean Squared Error): Approximately 10556.9
- Test RMSE: Approximately 10633.4
- The test RMSE is very close to the cross-validation RMSE, indicating appropriate fitting of the model.

# Key Findings
1. Manufacturer: Brands like Ferrari, Porsche, Aston-Martin, and Tesla have higher average prices.
2. Condition: Cars in "like new" and "new" conditions fetch the highest prices.
3. Year: Newer cars are more expensive.
4. Odometer: Lower odometer readings correlate with higher prices.

# Recommendations
1. Focus on Newer Models: Stock newer cars to meet consumer demand and achieve higher prices.
2. Maintain Car Condition: Ensure cars are in good or excellent condition to significantly impact selling prices.
3. Monitor Odometer Readings: Highlight cars with lower odometer readings to attract more buyers.

# Next Steps
1. Model Refinement: Explore more complex models and additional features to improve predictive performance and address overfitting.
2. Market Analysis: Conduct further analysis to understand regional price variations and consumer preferences.

By implementing these recommendations, the dealership can better align its inventory with consumer preferences, potentially increasing sales and profitability.
