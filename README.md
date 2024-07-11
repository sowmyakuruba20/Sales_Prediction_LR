# Sales Prediction Model
![screenshot](sales.png)
This project aims to develop and evaluate several statistical models for predicting sales. The notebook contains detailed steps for data preprocessing, exploratory data analysis, model building, and evaluation.

## Project Structure

- **Data Cleaning**: Initial steps involve checking for null values to ensure data integrity.
- **Outlier Analysis**: Outlier detection using quantile-based methods and distribution plots to understand data spread.
- **Exploratory Data Analysis (EDA)**: Includes correlation analysis and distribution plots to understand the relationships between different features.
- **Model Building**:
  - **Simple Linear Regression**: A basic model to start the predictive analysis.
  - **Polynomial Regression**: Enhancing the model by considering polynomial features.
  - **Multivariate Regression**: A complex model that uses multiple features for prediction.
- **Model Evaluation**:
  - Evaluation metrics include Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2).
  - Residual analysis to check the distribution of errors.

## Key Findings

- The correlation matrix helps in understanding how different features influence sales.
- Visualizations such as scatter plots are used to represent the relationship between the features and the target variable.
- The models' coefficients provide insights into the contribution of each feature towards sales prediction.

## Usage

To run this notebook:
1. Ensure you have Jupyter Notebook installed.
2. Open the `Sales_Prediction.ipynb` file in Jupyter Notebook.
3. Run the cells sequentially to observe the analysis and results.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-sourced under the MIT License.
