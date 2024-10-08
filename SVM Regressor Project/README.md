# SVM Regressor on California Housing Dataset

## Objective
The aim of this project is to evaluate the performance of Support Vector Regression (SVR) with different kernels on the California Housing dataset. The performance is measured using Mean Squared Error (MSE) and R² score.

## Approach
- **Dataset**: The `California Housing` dataset is fetched from `sklearn.datasets`. It contains information about house prices based on different features like median income, house age, etc.
- **Model**: Used **Support Vector Regression (SVR)** with two different kernels: `linear` and `rbf`.
- **Evaluation**: For each kernel, the model's performance was evaluated using:
  - **Mean Squared Error (MSE)**
  - **R² Score**

## Tools & Libraries
- **Python**
- **NumPy**: For numerical operations.
- **Pandas**: For handling and organizing results.
- **Plotly**: For visualizing the results.
- **Scikit-learn (sklearn)**:
  - `fetch_california_housing`: For loading the California Housing dataset.
  - `train_test_split`: For splitting the dataset into training and testing sets.
  - `StandardScaler`: For feature scaling.
  - `SVR`: For Support Vector Regression.
  - `mean_squared_error` & `r2_score`: For performance evaluation.

## Results
The SVR model's performance with different kernels (`linear` and `rbf`) is compared using both MSE and R² score, and results are visualized using a bar chart.

