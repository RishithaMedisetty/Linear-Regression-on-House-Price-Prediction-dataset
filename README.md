# Linear-Regression-on-House-Price-Prediction-dataset
# Housing Price Prediction – Linear Regression (Task 3)

This project demonstrates how to build a **Linear Regression** model using the Housing dataset to predict house prices based on features like area, bedrooms, bathrooms, etc.

# 1. Import & Preprocess the Dataset
- Loaded `housing.csv`
- Checked for nulls and handled them
- Encoded categorical variables (like `mainroad`, `furnishingstatus`)
- Standardized numerical columns if needed

# 2. Split into Train/Test Sets
- Used `train_test_split()` to split data into:
  - `X_train`, `X_test`
  - `y_train`, `y_test`  
- Test size: 20%

# 3. Fit Linear Regression Model
- Used `LinearRegression()` from `sklearn.linear_model`
- Trained the model on training data

# 4. Evaluate Model Performance
- Calculated:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score

# 5. Plot the Regression Line
- Visualized predictions vs actual prices using `matplotlib`
- Used `area` as the independent variable for plotting

# Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn

---

# File Structure
