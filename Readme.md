# Non-Farm Payrolls Forecasting Project

## Overview
This project focuses on forecasting the Non-Farm Payrolls (NFP) in the United States using Linear Regression. NFP is a significant economic indicator that represents the total number of paid U.S. workers of any business, excluding general government employees, private household employees, employees of nonprofit organizations that provide assistance to individuals, and farm employees.
<>
## Objective
The main objective of this project is to apply machine learning techniques to predict changes in the NFP based on historical data. We evaluate the model's performance using metrics such as the Root Mean Squared Error (RMSE) and the directional accuracy of predictions.

## Data
The data used in this project is loaded from an Excel file named `NFP.xlsx`. This dataset includes monthly NFP values which are then processed to create features suitable for time series forecasting.

## Methodology
1. **Data Loading and Transformation**: Data is loaded and transformed to ensure it is in the correct format for analysis.
2. **Feature Engineering**: We compute the first difference of the series to use as features for the regression model, capturing the month-to-month changes in employment.
3. **Data Splitting**: The dataset is split into training and testing sets to evaluate the model's performance.
4. **Model Training**: A Linear Regression model is trained on the historical data.
5. **Prediction and Evaluation**: The model is used to predict NFP changes, and its performance is evaluated using RMSE and the directional ratio.

## Results
The results include visualizations of the original data, its derivative, and the accumulated values over time. Predictions are plotted against actual data to assess the model's accuracy visually. The RMSE and directional accuracy provide quantitative measures of the model's performance.

## Files
- `NFP.ipynb`: Jupyter notebook containing the code and analysis.

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## How to Run
1. Ensure that Python and the necessary libraries are installed.
2. Run the Jupyter notebook `NFP.ipynb` to see the analysis and model performance.

## Conclusion
This project demonstrates the application of linear regression to economic time series data. The model's performance can be improved by exploring more sophisticated algorithms or by tuning the model's hyperparameters.

## Future Work
- Implementing more complex models such as ARIMA or LSTM for better forecasting accuracy.
- Incorporating additional economic indicators to improve the model's predictive power.
- Deploying the model as a web application to provide real-time forecasting.