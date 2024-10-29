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
- The **Support Vector Regression** model achieved the highest performance with the lowest RMSE and the highest R2 score.
| Model                  | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|------------------------|--------------|---------------|------------|--------------|
| **Random Forest**       | 98.47        | 98.50         | 98.49      | 98.49        |
| **K-Nearest Neighbors** | 95.41        | 95.69         | 95.44      | 95.47        |
| **Gradient Boosting**   | 97.18        | 97.23         | 97.20      | 97.22        |


