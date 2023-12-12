# AML_3104_Final_Project

California Housing Price Prediction
This repository contains a Jupyter notebook for predicting California housing prices using regression models. The dataset is loaded from the California Housing dataset provided by scikit-learn. The following steps are performed in the notebook:

# 1. Data Preprocessing and Exploration
Handling missing values
Identifying and removing outliers using Z-Score
Normalizing numerical features using StandardScaler
Exploring data distributions, correlations, and patterns
# 2. Feature Engineering
Creating a new feature: Rooms per Household
Log transformation for skewed features
Standardizing numerical features
# 3. Exploratory Data Analysis (EDA)
Plotting distributions for numerical features
Visualizing correlations using a heatmap
Identifying patterns using scatter plots
# 4. Model Training and Evaluation
Splitting the dataset into training and testing sets
Training regression models (Linear Regression, Decision Tree Regressor)
Evaluating models using Mean Squared Error (MSE)
# 5. Hyperparameter Tuning
Performing grid search for hyperparameter tuning
Identifying the best parameters for each regression model
# 6. Model Saving and Prediction
Saving the trained Decision Tree Regressor model using pickle
Creating a Panel UI to input features and make predictions
Usage
Install the required libraries:
pandas numpy seaborn matplotlib plotly-express scikit-learn panel
Run the Jupyter notebook to perform data analysis, train models, and created a Panel UI for predictions.

Open the generated Panel UI in your browser to input features and get predictions for California housing prices.

Note: The dataset used in this project is the California Housing dataset from scikit-learn. Ensure that you have the required libraries installed before running the notebook.
