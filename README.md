# CO₂ Emission Prediction using Linear Regression

## Overview
This project predicts CO₂ emissions of vehicles using Linear Regression based on engine and fuel-related features.

## Dataset
- ~1000+ vehicle records
- Features:
  - Engine Size
  - Cylinders
  - Fuel Consumption (City, Highway, Combined)
  - Fuel Type
  - CO₂ Emissions (Target)

## Workflow

### 1. Data Cleaning
- Handled missing values
- Removed irrelevant columns
- Prepared structured dataset for modeling

### 2. Exploratory Data Analysis (EDA)
- Scatter plots between fuel consumption and CO₂ emissions
- Correlation analysis across multiple features
- Identified strong linear relationships (r > 0.85)

### 3. Model Building
- Implemented Linear Regression using Scikit-learn
- Trained multiple models using different feature sets:
  - Fuel Consumption vs CO₂
  - Cylinder Size vs CO₂
  - Fuel Type vs CO₂

### 4. Evaluation
- Evaluated using R² score
- Observed strong predictive performance for fuel-related features

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Insights
- Fuel consumption is the strongest predictor of CO₂ emissions
- Engine size and cylinders also contribute but with lower correlation
- Linear Regression performs well due to strong linear relationships

## Limitations
- No cross-validation applied
- No hyperparameter tuning
- Model not deployed

## Future Improvements
- Add Polynomial Regression for non-linear patterns
- Apply Cross-validation for robust evaluation
- Deploy model using Flask or FastAPI
