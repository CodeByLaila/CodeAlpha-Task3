Car Price Prediction using Random Forest Regression

Project Overview

This project uses Machine Learning to predict the selling price of used cars based on various features in the car dataset. A Random Forest Regressor is trained to predict car selling prices.

Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Joblib

Google Colab

Project Workflow

Loaded and explored the car dataset.

Checked for missing values and removed duplicate records.

Explored dataset statistics and categorical features.

Converted categorical variables into numerical features using one-hot encoding.

Visualized feature correlations using a correlation heatmap.

Split the data into training and testing sets.

Trained a Random Forest Regression model.

Evaluated model performance using MAE, MSE, RMSE, and R² score.

Visualized feature importance.

Saved the trained model using Joblib.

Model Evaluation

The model was evaluated using the following regression metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Note: Add the actual metric values here after running the notebook.

Feature Importance

A feature importance chart was generated to identify which car attributes contributed most to the model's predictions.

Model Export

The trained model was saved as car_price_prediction_model.pkl using Joblib.

Conclusion

This project demonstrates how Random Forest Regression can be used to predict used-car selling prices, evaluate model performance, explore important features, and save a trained model for future use.
