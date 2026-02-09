- Seoul Bike Sharing Demand Prediction

This project focuses on predicting hourly bike rental demand using the Seoul Bike Sharing Dataset. The goal is to understand which factors affect bike usage and to build a machine learning model that can accurately estimate the number of rented bikes.

-Dataset

The dataset contains hourly bike rental data along with weather and temporal features such as:

Temperature, humidity, wind speed, visibility

Solar radiation, rainfall, snowfall

Seasons, holidays, and functioning day indicator

Date and hour information

- What I Did

Performed data preprocessing and cleaning

Converted categorical variables using one-hot encoding

Selected relevant features for modeling

Split the data into training and test sets

Trained and evaluated a Random Forest Regressor

Measured performance using MAE and R² score

- Model Performance

Mean Absolute Error (MAE): ~327

R² Score: ~0.53

These results indicate that the model captures a significant portion of the variability in bike demand, especially considering the non-linear relationships between weather conditions and usage.

-Why Random Forest?

Random Forest was chosen because:

It handles non-linear relationships effectively

It is robust to outliers and feature interactions

It generally performs well without heavy feature scaling

-Technologies Used

Python

Pandas & NumPy

Scikit-learn

Jupyter Notebook

-Project Goal

This project was created to practice end-to-end machine learning workflow, including data preprocessing, feature engineering, model selection, and evaluation, using a real-world dataset.