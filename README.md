# Regression
# California Housing Price Prediction

# Overview
This project focuses on predicting house prices using the California Housing dataset and different machine learning regression algorithms.

# Dataset
The California Housing dataset is loaded using "fetch_california_housing()" from Scikit-learn.

The dataset contains housing-related features such as:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

The target variable is the median house value.

# Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Converted the dataset into a Pandas DataFrame
- Checked the data information and shape
- Checked for missing values
- Detected outliers using the IQR method
- Handled outliers using clipping
- Separated features and target
- Split the data into training and testing sets
- Applied Standard Scaling for models that require scaled features

# Machine Learning Models

The following regression algorithms were implemented:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)

# Model Evaluation

The models were evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

For MSE and MAE, lower values indicate lower prediction errors.
For R² Score, a higher value indicates better performance.

The models were compared based on these evaluation metrics to identify the best and worst-performing models.

# Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Files

- "Regression.ipynb" – Jupyter Notebook containing the complete implementation and analysis.

# Conclusion

This project demonstrates the application of different regression algorithms for house price prediction. The performance of each model was compared using MSE, MAE, and R² Score.
