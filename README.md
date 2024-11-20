# House Price Prediction

## Project Overview
This project focuses on predicting house prices based on various features such as location, size, number of rooms, and more. By leveraging machine learning techniques, the model aims to provide accurate price estimates for houses, aiding real estate stakeholders in making data-driven decisions.

## Features
- **Data Cleaning**:
  - Handled missing values and outliers.
  - Normalized numerical features for consistency.
- **Feature Engineering**:
  - Analyzed and selected important features.
  - Created new features to enhance prediction accuracy.
- **Exploratory Data Analysis (EDA)**:
  - Visualized relationships between features and target prices.
  - Explored correlations and feature distributions.
- **Model Development**:
  - Built multiple regression models, including linear regression and tree-based models.
  - Performed hyperparameter tuning to optimize model performance.
- **Evaluation Metrics**:
  - Evaluated models using R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Dataset
The dataset contains information about houses, including:
- **Numerical Features**: Lot size, house area, number of bedrooms, bathrooms, etc.
- **Categorical Features**: Location, type of house, etc.
- **Target Variable**: House price.

**Dataset Path:** Refer to the `House_Price_Prediction.ipynb` file for dataset details and preprocessing steps.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - XGBoost
- **Notebook Environment**: Jupyter Notebook

## Project Files
- `House_Price_Prediction.ipynb`: Notebook containing data preprocessing, EDA, model training, and evaluation.
- `README.md`: Overview of the project.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/House_Price_Prediction.git

## Results

| Metric                  | Value          |
|-------------------------|----------------|
| **R-squared**           | 0.89           |
| **Mean Absolute Error** | $12,500        |
| **Root Mean Squared Error** | $15,300     |

### Model Insights
- **R-squared** indicates that the model explains 89% of the variance in house prices.
- Low **Mean Absolute Error** and **RMSE** reflect high accuracy in predictions.

