# Soil-Strength-Prediction-Using-Machine-Learning-Regression-Models

- **Project Focus**: Regression analysis on the "F_CLAY_7_216_TC304" dataset to predict soil test results (su(test) (kPa)).
- **Data Preprocessing**: Handled missing values, dropped unnecessary features, and standardized data.
- **Models Used**: Implemented various regression models, including:
  - **Linear Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Ridge and Lasso Regression**
  - **Decision Tree**
  - **Random Forest Regressors**
  - **Support Vector Regression (SVR)**
  - **Multi-Layer Perceptron (MLP)**
- **Evaluation Metrics**: Calculated Root Mean Squared Error (RMSE) and R-squared (R2) for each model.
- **Visualization**:
  - Correlation heatmap for feature relationships.
  - Line and scatter plots comparing predicted vs. actual values, with a regression line and displayed R2 score.
- **Results**:

| Model                         |    RMSE    |     R²     |
|-------------------------------|------------|------------|
| **Linear Regression**         |   5.024    |   0.680    |
| **K-Nearest Neighbors**       |   4.805    |   0.708    |
| **Ridge Regression**          |   5.024    |   0.680    |
| **Lasso Regression**          |   4.845    |   0.703    |
| **Decision Tree**             |   6.286    |   0.500    |
| **Random Forest Regressor**   |   4.759    |   0.713    |
| **Support Vector Regression** |   4.402    |   0.754    |
| **Multi-Layer Perceptron**    |   5.425    |   0.627    |



