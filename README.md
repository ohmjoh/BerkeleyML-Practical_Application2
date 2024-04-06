# Used Car Pricing Analysis

## Overview
This repository contains the code and findings from an analysis conducted to identify the key factors influencing the prices of used cars. The analysis aims to provide actionable insights to used car dealers to fine-tune their inventory and pricing strategies.

## Repository Structure:
- data/: Contains the dataset used for the analysis.
- [prompt_II.ipynb](https://github.com/ohmjoh/BerkeleyML-Practical_Application2/blob/main/prompt_II.ipynb): Jupyter notebooks containing the data preprocessing, exploratory data analysis, and modeling steps.

## Data
The dataset used for this analysis contains information about used cars, including features like manufacturer, model, condition, cylinders, fuel type, odometer reading, title status, transmission type, drive type, car type, paint color, car age, and price.

## Analysis Steps
1. Data Preprocessing
- Handle missing values, outliers, and data cleaning.
- Convert categorical variables into numerical format using label encoding.

2. Exploratory Data Analysis
- Analyze the distribution of the target variable (car prices).
- Explore the relationships between various features and the target variable.

3. Modeling
- Build Ridge and Lasso regression models to predict the prices of used cars.
- Perform hyperparameter tuning using GridSearchCV to identify the optimal alpha values for Ridge and Lasso regression models.

4. Feature Importance
- Identify the most important features influencing the prices of used cars based on the coefficients from the Ridge and Lasso regression models.

5. Findings
- The key findings from the analysis include:
  - Cylinders, odometer reading, fuel type, transmission type, car age, title status, condition, type, drive type, and manufacturer are identified as the most influential factors affecting the prices of used cars.

6. Recommendations
Based on the analysis, the following recommendations are provided to used car dealers:
- Optimize inventory management based on the influential features.
- Implement dynamic pricing strategies reflecting the condition, type, and other factors influencing the price of the vehicle.
- Highlight and promote vehicles with desirable features in marketing and sales efforts.

7. Conclusion
Understanding the key factors influencing the prices of used cars is crucial for used car dealers to make informed decisions related to inventory management, pricing strategies, and marketing. By focusing on the most influential features identified in this analysis, used car dealers can fine-tune their inventory and pricing strategies to maximize profitability and meet the needs of their target customers effectively.

