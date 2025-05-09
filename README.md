# What Drives the Price of a Used Car?

# Overview
This project explores a large dataset of used vehicles to determine the key factors influencing car prices. The dataset, originally from Kaggle, has been reduced to around 426,000 entries for faster processing.

The goal is to help a used car dealership better understand consumer preferences and identify which car attributes (such as age, mileage, manufacturer, fuel type, etc.) significantly affect price, thereby enabling optimized inventory, pricing, and marketing strategies.

The project follows the CRISP-DM Framework to ensure a structured approach:

- Business Understanding:**Frame the dealership’s needs into a supervised machine learning problem (regression).

- Data Understanding:** Explore, clean, and visualize the data to identify trends, missing values, and outliers.

- Data Preparation:** Clean and transform the dataset appropriately.

Modeling and Evaluation:** (Future steps if applicable) Develop predictive models to understand key drivers.

The analysis is done using Python in a Jupyter Notebook, leveraging libraries like pandas, NumPy, seaborn, matplotlib, and scikit-learn.

# Key Findings
- Mileage (odometer reading) and vehicle year (age) are major predictors of car price.

- Condition (e.g., excellent, good, like new) has a strong influence on price.

- Manufacturer and model affect consumer perception and therefore pricing.

- Type of vehicle (sedan, SUV, pickup) impacts pricing, with SUVs and pickups generally priced higher than sedans.

- Fuel type and transmission show moderate impact on price.

- Missing or inconsistent values were significant, especially in attributes like VIN, size, and drive type, which required careful handling.

A substantial number of entries had a listed price of $0, indicating likely errors that needed filtering.

# Recommendations

- Prioritize vehicles in excellent or like new condition when sourcing inventory.

- Focus inventory around popular and high-retention models like Ford F-150, Chevy Silverado, and Toyota Camry.

- SUVs and pickups retain higher value and should be emphasized in marketing and inventory strategy.

- Clean and validate data rigorously before pricing decisions, especially fields like mileage and year.

- Consider odometer readings and year as key inputs for predictive pricing tools.

# Project Structure
bash
Copy
Edit
/car_price_analysis/
    ├── README.md
    ├── used_car_price_analysis.ipynb   # Jupyter Notebook with analysis
    └── vehicles.csv                    # Original dataset
- Notebook: All headings, explanations, and visualizations are properly formatted.

- Directories and Files: Organized for clarity and efficient access.

- Unnecessary files: Excluded for simplicity.

# Link to the Analysis
http://localhost:8888/notebooks/Used_Car_features/prompt_II.ipynb?
