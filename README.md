# Adult Dataset Regression: SVR vs Linear Regression

This project compares the performance of **Support Vector Regression (SVR)** and **Linear Regression** models on the **Adult dataset** from the UCI Machine Learning Repository. The goal is to predict whether an individual's income exceeds $50K/yr based on census data, and this analysis focuses on comparing regression techniques.

## Dataset

The dataset used in this project is the Adult dataset from the UCI Machine Learning Repository.

- Dataset Link: [Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- File paths:
  - `/content/adult.data`
  - `/content/adult.names`
  - `/content/adult.test`
  - `/content/old.adult.names`

## Project Structure

- `adult.data`: Contains the raw data used for training and testing.
- `adult.test`: Contains test data for validation.
- `adult.names`: Describes the attributes in the dataset.
- `svr_vs_linear_regression.ipynb`: Jupyter Notebook containing the implementation of both Linear Regression and SVR models, with detailed comparisons.
- `README.md`: This file, describing the project.
  
## Tasks

1. **Data Preprocessing**:
   - Load the dataset, handle missing values, and perform one-hot encoding for categorical features.
   
2. **Linear Regression**:
   - Implemented using Scikit-learn's `LinearRegression`.
   - Evaluated using Mean Squared Error (MSE) and R² Score.

3. **Support Vector Regression (SVR)**:
   - Implemented using Scikit-learn's `SVR`.
   - Compared different kernel functions (e.g., linear, polynomial, and radial basis function).
   - Evaluated using MSE and R² Score.

4. **Comparison**:
   - Compared the performance of both models using the same dataset.

## Results

### Model Performance:

- **Linear Regression**:
  - Mean Squared Error (MSE): `your_lr_mse_value`
  - R² Score: `your_lr_r2_value`

- **SVR (RBF Kernel)**:
  - Mean Squared Error (MSE): `your_svr_mse_value`
  - R² Score: `your_svr_r2_value`

The model with lower MSE and higher R² is considered better for predicting income from the Adult dataset. Based on the comparison, we find that `insert_analysis_here` model performs better for this task.
