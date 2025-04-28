# Task 3 - Linear Regression

## Objective:
To implement and understand simple and multiple linear regression using a real-world housing dataset.

## Dataset:
- Housing Price Prediction Dataset from Kaggle.
- Features used: `Area`, `BHK`, `Bathroom`, `Parking`.
- Target: `Price`

## Steps:
1. Imported libraries like Pandas, Scikit-learn, Matplotlib, Seaborn.
2. Loaded the dataset (`Housing.csv`).
3. Selected relevant features for regression.
4. Split data into training and testing sets (80%-20% split).
5. Built a Linear Regression model using `sklearn.linear_model`.
6. Evaluated the model using MAE, MSE, and R² score.
7. Plotted the relationship between `Area` and `Price` using a scatter plot.
8. Interpreted the model coefficients.

## Evaluation Metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Plot:
- Scatter plot showing actual vs predicted prices based on Area.

## Requirements:
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## How to Run:
1. Make sure `Housing.csv` is in the same directory.
2. Run the `linear_regression_task3.ipynb` notebook or script.

