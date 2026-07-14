# What Drives the Price of a Used Car?

## Project Overview

This project analyzes a dataset of approximately 426,000 used vehicles from Kaggle to identify the factors that most influence vehicle prices. The goal is to provide actionable recommendations to a used car dealership regarding inventory acquisition and pricing strategies.

The project follows the CRISP-DM methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

---

## Business Problem

Used car dealerships need data-driven insights to determine which vehicle attributes have the greatest impact on resale value.

The objective is to build predictive models that estimate vehicle prices and identify the key drivers influencing those prices.

---

## Dataset

The dataset includes:

- Price
- Year
- Manufacturer
- Model
- Condition
- Cylinders
- Fuel Type
- Odometer
- Transmission
- Drive Type
- Vehicle Type
- Title Status
- Paint Color
- Region

Source:
- Kaggle Used Cars Dataset

---

## Methodology

### Data Cleaning

- Removed duplicates
- Handled missing values
- Removed extreme outliers
- Corrected data types

### Feature Engineering

- Vehicle Age
- Log-transformed Price
- Encoded categorical variables

### Modeling

Models evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regression

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Cross-validation and Grid Search were used for model optimization.

---

## Key Findings

The most important price drivers were:

1. Vehicle Age
2. Odometer Reading
3. Manufacturer
4. Vehicle Condition
5. Vehicle Type
6. Title Status

### Positive Price Drivers

- Newer model years
- Low mileage
- Excellent condition
- Premium brands
- Clean titles

### Negative Price Drivers

- Older vehicles
- High mileage
- Salvage titles
- Poor condition

---

## Business Recommendations

### Inventory Acquisition

Focus on:

- Vehicles under 10 years old
- Low-mileage vehicles
- SUVs and Trucks
- Vehicles with clean titles

### Pricing Strategy

Use:

- Age
- Odometer
- Manufacturer
- Condition

as primary pricing inputs.

---

## Repository Structure

assignment11_1/

│

├── README.md

├── assignment11_1.ipynb

├── data/vehicles.csv

├── requirements.txt

└── images/crisp.png

└── images/kurt.jpeg

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Author

Ravi Kiran Gottumukkala