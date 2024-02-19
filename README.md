Car Price Prediction Model
This repository contains a Jupyter notebook (Car_Price_Prediction.ipynb) that implements a car price prediction model. The dataset used for this project is sourced from Kaggle and can be found here.

Contents
1.	Data Cleaning and Preprocessing:<br>
  •	Handling null values and duplicates <br>
  •	Converting 'Mileage' to an integer
  •	Simplifying and cleaning columns like 'Engine volume', 'Doors', and 'Turbo'
  •	Removing outliers
2.	Exploratory Data Analysis (EDA):
  •	Exploring relationships between numerical variables
  •	Visualizing categorical data distribution
  •	Investigating correlations between numerical features
3.	Feature Engineering:
  •	Transforming and encoding categorical variables
  •	Modifying and simplifying 'Drive wheels' and 'Wheel' columns
4.	Baseline Models:
  •	Training and evaluating baseline regression models
  •	Assessing overfitting using train-test split
  •	Implementing Random Forest, Decision Tree, KNN, and XGBoost models
5.	Hyperparameter Tuning:
  •	Utilizing grid search for Random Forest hyperparameter tuning
  •	Improving model accuracy with tuned parameters
6.	Model Evaluation:
  •	Evaluating final Random Forest model on test data
  •	Calculating Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE)
